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

## Sustav detekcije hrane

Dajte agentu 3 predmeta. Provjerite otkriva li ispravne stavke u ispravnim utorima. Ako Agent ima 3 prehrambena artikla, trebao bi viknuti "hrana!".

### ~ Savjet 

Koristite konstrukciju ``||if||`` -> ``||Agent||`` -> ``||item slot ID||`` -> recite "Hrana!".


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
