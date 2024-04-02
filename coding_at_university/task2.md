# Task #2
### @flyoutOnly true
### @hideIteration false
### @explicitHints false

``` ghost
    for (let index = 0; index < 1; index++) {
        agent.move(FORWARD, 1)
    }
```
```template
   //     
```

## Fix the Speaker

You have to fix the speaker. Use the three found blocks to make your Agent put them in the right places.
If something goes wrong, try again using a different route. If you put up a block incorrectly, you can also destroy it with an Agent.

### ~ Hint 

Remember that this task does not have one specific path to choose from. Choose the path that suits you! 


```typescript-valid
Solution to put the first block on the left
```
``` blocks
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 3)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.setSlot(1)
agent.place(FORWARD)
```
```
```
```typescript-valid
Solution to put the second block in the middle
```
``` blocks
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.setSlot(1)
agent.place(FORWARD)
```
```
```
```typescript-valid
Solution to put the third block on the right
```
``` blocks
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 1)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 1)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.setSlot(1)
agent.place(FORWARD)
```
```
```
```typescript-valid
This is ONLY used to destroy wrong placed block
```
``` blocks
agent.destroy(FORWARD)
```
```package
github:kwakong/ai-cosmic_coding_at_university
```
