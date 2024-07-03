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

## Popravite zvučnik

Moraš popraviti zvučnik. Iskoristi tri pronađena bloka kako bi ih tvoj agent stavio na prava mjesta.
Ako nešto pođe po zlu, pokušajte ponovno drugom rutom. Ako pogrešno postavite blok, također ga možete uništiti pomoću agenta

### ~ Savjet 

Zapamtite da ovaj zadatak nema jedan određeni put za odabir. Odaberite put koji vama odgovara!


```typescript-valid
Rješenje za postavljanje prvog bloka s lijeve strane
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
Rješenje za stavljanje drugog bloka u sredinu
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
Rješenje za postavljanje trećeg bloka s desne strane
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
Ovo se SAMO koristi za uništavanje pogrešno postavljenog bloka
```
``` blocks
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
