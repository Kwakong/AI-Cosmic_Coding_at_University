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

## Ripara l'altoparlante

Devi riparare l'altoparlante. Usa i tre blocchi trovati per fare in modo che il tuo agente li metta nei posti giusti.
Se qualcosa va storto, riprova utilizzando un percorso diverso. Se metti un blocco in modo errato, puoi anche distruggerlo con un agente.

### ~ Suggerimento 

Tieni presente che questa attività non ha un percorso specifico tra cui scegliere. Scegli il percorso che fa per te!


```typescript-valid
Soluzione per mettere il primo blocco a sinistra
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
Soluzione per mettere il secondo blocco al centro
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
Soluzione per mettere il terzo blocco a destra
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
Questo viene utilizzato SOLO per distruggere il blocco posizionato in modo errato
```
``` blocks
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
