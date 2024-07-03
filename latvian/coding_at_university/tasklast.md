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

## Pārtikas noteikšanas sistēma

Dodiet aģentam 3 priekšmetus. Pārliecinieties, ka tas nosaka pareizos priekšmetus pareizajos slotos. Ja aģentam ir 3 pārtikas produkti, tam ir jāsarkst “pārtika!”.

### ~ Padoms 

Izmantot konstrukciju ``||Ja|||`` -> ``||Aģents||`` -> ``||priekšmeta slota ID|||`` -> pateikt “Pārtika!”.


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
