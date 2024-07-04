# Task #6
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

## Password WiFi

Il distributore automatico copre la password WiFi e il professore non riesce a ricordarla. Programma l'agente per rimuovere il distributore automatico, in modo che la password WiFi possa essere rivelata.

### ~ Suggerimento 

Usa l'agente per rimuovere il distributore automatico, tramite l’azione ``||agente:attacco in avanti||``.


``` blocks
agent.move(FORWARD, 2)
agent.attack(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
