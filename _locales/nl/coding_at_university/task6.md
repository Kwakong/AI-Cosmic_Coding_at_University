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

## WiFi-wachtwoord

De automaat verbergt het WiFi-wachtwoord en de professor kan het niet onthouden. Codeer de agent om de automaat te verwijderen, zodat het WiFi-wachtwoord kan worden onthuld.

### ~ Hint 

Gebruik Agent om automaat te verwijderen, door ``||agent:attack forward||`` actie.


``` blocks
agent.move(FORWARD, 2)
agent.attack(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
