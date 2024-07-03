# Task #5
### @flyoutOnly true
### @hideIteration false
### @explicitHints false

``` ghost
    for (let index = 0; index < 1; index++) {
        agent.move(FORWARD, 1)
        agent.destroy(FORWARD)
        agent.collectAll()
        agent.turn(RIGHT_TURN)
    }
```
```template
   //     
```

## Raccogli il cibo e mettilo nel robot Chef AI

Guida l'agente attraverso il labirinto. Raccogli tutto il cibo che riesci a trovare e mettilo nel robot Chef AI. Utilizzare il comando ``||agente:distruggere||`` e ``||agente:collectAll||`` per raccogliere singoli elementi. 
Se gli oggetti bloccati scompaiono dal terreno, usa il pulsante accanto a Chef AI Robot.

### ~ Suggerimento 1

In questo compito devi raccogliere 8 alimenti. Al primo round devi raccogliere: ``||Cipolla||``, ``||Uva||``, ``||Salsiccia||``, ``||Cioccolato||``. Nel prossimo round dovrai raccogliere: ``||Carne||``, ``||Piselli|``, ``||Pomodoro||``, ``||Aglio||``. Se commetti un errore, sentiti libero di fare clic sul pulsante "ripristina posizione agente" posizionato vicino a Chef AI Robot.

### ~ Suggerimento 2
Una volta ottenuti tutti gli alimenti dopo un determinato round, fai clic con il pulsante destro del mouse sull'agente per trasferire il cibo acquisito al robot Chef AI facendo clic con il pulsante destro del mouse su di esso. Buona Fortuna!


```typescript-valid
Soluzione del primo round per la raccolta di 4 oggetti
```
``` blocks
agent.move(FORWARD, 2)
agent.destroy(FORWARD)
agent.collectAll()
agent.move(FORWARD, 1)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.destroy(FORWARD)
agent.collectAll()
agent.move(FORWARD, 1)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.destroy(LEFT)
agent.collectAll()
agent.move(BACK, 6)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.destroy(FORWARD)
agent.collectAll()
```
```
```
```typescript-valid
Soluzione del secondo round per la raccolta di 4 oggetti
```
``` blocks
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 3)
agent.destroy(LEFT)
agent.collectAll()
agent.move(FORWARD, 4)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.destroy(LEFT)
agent.collectAll()
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.destroy(FORWARD)
agent.collectAll()
agent.move(BACK, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.destroy(FORWARD)
agent.collectAll()
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
