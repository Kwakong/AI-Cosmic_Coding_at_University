# Food Detection System
### @flyoutOnly true
### @hideIteration false
### @explicitHints true


# Last Task 

## Food Detection System

Give the Agent 3 items. Make sure it detects the correct items in the correct slots. If the Agent has 3 food items it should shout out "food!".

### ~ Hint 

Use construction ``||if||`` -> ``||Agent||`` -> ``||item slot ID||`` -> say "Food!"


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
github:kwakong/ai-cosmic_coding_at_university
```
