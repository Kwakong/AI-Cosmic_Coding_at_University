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

## Fix the Intercom

You have to fix the intercom. Use the concrete you have found to make your Agent match them to the corresponding colour.

### ~ Hint 

If something is wrong you can always use button **"reset"** positioned on middle of room, to reset task and start again.
Remember to select the slot that the Agent must use to place the block.


```typescript-valid
Solution to put red concrete
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
Solution to put yellow concrete
```
``` blocks
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.setSlot(2)
agent.place(FORWARD)
```
```
```
```typescript-valid
Solution to put lime concrete
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
agent.setSlot(3)
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
