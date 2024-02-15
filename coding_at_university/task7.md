# Build a Bridge
### @flyoutOnly true
### @hideIteration false
### @explicitHints true


# Task #7

## Build a Bridge

With the help of your Agent, build a bridge to get across water. Don't forget to give the Agent the necessary blocks!

### ~ Hint 

There is no specific way to accomplish this task. Try using ``||loops||``.
Create a bridge and talk to Captain Anna.


``` blocks
agent.setSlot(1)
agent.setSlot(GRASS)
agent.move(FORWARD, 3)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
```
``` blocks
for (let index = 0; index < 1; index++) {
```
```
```
```typescript-valid
This is ONLY used to destroy wrong
placed block or to change way of Agent walk
```
``` blocks
agent.turn(LEFT_TURN)
agent.destroy(FORWARD)
```
```package
github:kwakong/ai-cosmic_coding_at_university
```
