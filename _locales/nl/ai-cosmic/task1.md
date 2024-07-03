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

##  Maak het pad vrij

Het lijkt erop dat er een aantal blokken op je pad staan. Gebruik je Agent om die blokken te breken.


###  ~ Hint 

Gebruik ``|loops:loops|`` om het proces te versnellen. 



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
