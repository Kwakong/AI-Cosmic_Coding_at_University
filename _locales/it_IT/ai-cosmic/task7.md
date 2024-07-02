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

## Costruisci un ponte

Con l'aiuto del tuo agente, costruisci un ponte per attraversare l'acqua. Non dimenticare di dare all'agente i blocchi necessari!

### ~ Suggerimento 

Non esiste un modo specifico per eseguire questa attività. Prova a usare ``||cicli||``.
Crea un ponte e parla con il capitano Anna.



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
Questo è usato SOLO per distruggere il
blocco posizionato erroneamente o per cambiare il modo di camminare dell'agente
```
``` blocks
agent.turn(LEFT_TURN)
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
