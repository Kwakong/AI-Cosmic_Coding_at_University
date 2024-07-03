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

## Skaļruņalabošana

Jums ir jāsalabo skaļrunis. Izmantojiet trīs atrastos blokus, lai liktu savam aģentam tos novietot pareizajās vietās.
Ja kaut kas neizdodas, mēģiniet vēlreiz, izmantojot citu maršrutu. Ja kļūdaini novietojat kādu bloku, varat to arī iznīcināt ar aģentu.

### ~ Padoms 

Atcerieties, ka šim uzdevumam nav viena konkrēta ceļa, no kura izvēlēties. Izvēlieties sev piemērotāko ceļu!


```typescript-valid
Risinājums, kā ievietot pirmo bloku kreisajā pusē
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
Risinājums, kā ievietot pirmo bloku kreisajā pusē
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
Risinājums, lai trešo bloku novietotu pa labi
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
To izmanto TIKAI, lai iznīcinātu nepareizi novietotu bloku.
```
``` blocks
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
