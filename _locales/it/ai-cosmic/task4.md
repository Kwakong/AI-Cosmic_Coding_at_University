# Task #4
### @flyoutOnly true
### @hideIteration false
### @explicitHints false

``` ghost
    for (let index = 0; index < 1; index++) {
        agent.move(FORWARD, 1)
        agent.destroy(FORWARD)
        agent.collectAll()
    }
```
```template
   //     
```

## Raccogli i materiali

Guida l'agente attraverso il labirinto e raccogli tutte le parti necessarie! Per prendere un oggetto, usa il comando ``||agente.distruggere||``. Dopo che il tuo robot ha raccolto gli oggetti necessari, parla con ``||Assistente Professore||``.

### ~ Suggerimento 

Sentiti libero di creare il tuo percorso del robot per raccogliere tutte le parti necessarie. Se parli di nuovo con il Professor Artur, puoi azzerare il tuo compito e generare di nuovo oggetti a terra. 


```typescript-valid
Percorso per l'elemento "glowstone_dust"
```
``` blocks
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.destroy(FORWARD)
agent.collectAll()
```
```
```
```typescript-valid
Percorso per l'elemento "iron_ingot"
```
``` blocks
agent.move(FORWARD, 5)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 4)
agent.destroy(FORWARD)
agent.collectAll()
```
```
```
```typescript-valid
Percorso per l'elemento "stick"
```
``` blocks
agent.move(FORWARD, 3)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 3)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.destroy(FORWARD)
agent.collectAll()
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
