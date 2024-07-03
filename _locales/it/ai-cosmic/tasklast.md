# Bonus Task
### @flyoutOnly true
### @hideIteration true
### @explicitHints false

``` ghost
    for (let index = 0; index < 1; index++) {
        agent.move(FORWARD, 1)
    }
```
```template
   //     
```

## Sistema di rilevamento degli alimenti

Dai all'agente 3 oggetti. Assicurati che rilevi gli elementi corretti negli slot corretti. Se l'agente ha 3 prodotti alimentari, dovrebbe gridare "cibo!".

### ~ Suggerimento 

Usa costruzione ``||se||`` -> ``||Agente||`` -> ``||ID slot articolo||`` -> dire "Cibo!".


``` blocks
if (agent.getItemDetail(1) == POISONOUS_POTATO) {
    if (agent.getItemDetail(2) == COOKED_CHICKEN) {
        if (agent.getItemDetail(3) == SWEET_BERRIES) {
            player.say("Food!")
        }
    }
}
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
