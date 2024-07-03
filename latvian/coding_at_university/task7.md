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

## Uzcelt tiltu

Ar aģenta palīdzību uzbūvē tiltu, lai pārceltos pāri ūdenim. Neaizmirstiet nodot aģentam nepieciešamos blokus!

### ~ Padoms 

Šim uzdevumam nav konkrēta veida, kā to paveikt. Izmēģiniet izmantot ``||cilpas||``.
Izveidojiet tiltu un aprunājieties ar kapteini Annu.



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
Tas tiek izmantots tikai, lai iznīcinātu nepareizu
novietoto bloku vai lai mainītu aģenta pastaigas veidu.
```
``` blocks
agent.turn(LEFT_TURN)
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
