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

## Voedseldetectiesysteem

 Geef de Agent 3 voorwerpen. Zorg ervoor dat hij de juiste voorwerpen in de juiste vakjes detecteert. Als de Agent 3 items heeft moet hij "food!" roepen.

### ~ Hint 

Gebruik de constructie ``||if||`` -> ``||Agent||`` -> ``|item slot ID||`` -> zeg "Food!".


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
