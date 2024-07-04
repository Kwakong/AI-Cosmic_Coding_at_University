# Task #7
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

## Een brug bouwen

Bouw met de hulp van je Agent een brug om het water over te steken. Vergeet niet om de Agent de benodigde blokken te geven!

### ~ Hint 

Er is geen specifieke manier om deze taak uit te voeren. Probeer ``||loops||`` te gebruiken.
Maak een brug en praat met kapitein Anna.


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
```
```
```typescript-valid
Dit wordt ALLEEN gebruikt om verkeerd geplaatste
geplaatst blok te vernietigen of om de manier van Agent lopen te veranderen
```
``` blocks
agent.turn(LEFT_TURN)
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
