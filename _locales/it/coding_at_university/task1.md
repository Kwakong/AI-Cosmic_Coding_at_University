# Task #1
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

##  Cancella il percorso

Sembra che ci siano alcuni blocchi sul tuo percorso. Usa il tuo agente per rompere questi blocchi.

###  ~ Suggerimento 

Usa ``||cicli:cicli||`` per velocizzare il processo.



``` blocks
    agent.destroy(FORWARD)
    agent.move(FORWARD, 1)
```
``` blocks
for (let index = 0; index < 1; index++) {
}
```
``` package
github:Mikey-S1/ai-cosmic_coding_at_university
```
