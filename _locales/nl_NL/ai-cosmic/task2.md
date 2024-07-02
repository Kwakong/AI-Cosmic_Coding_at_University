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

## Repareer de spreker

Je moet de luidspreker repareren. Gebruik de drie gevonden blokken om je Agent ze op de juiste plek te laten zetten.
Als er iets fout gaat, probeer het dan opnieuw via een andere route. Als je een blok verkeerd plaatst, kun je het ook vernietigen met een Agent.

### ~ Hint 

Onthoud dat deze opdracht niet één specifiek pad heeft om uit te kiezen. Kies het pad dat bij je past!


```typescript-valid
Oplossing om het eerste blok links te plaatsen
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
Oplossing om het tweede blok in het midden te plaatsen
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
Oplossing om het derde blok rechts te plaatsen
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
Dit wordt ALLEEN gebruikt om verkeerd geplaatste blokken te vernietigen
```
``` blocks
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
