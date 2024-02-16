# Task #1
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

##  Clear the Path

Looks like there are some blocks in your path. Use your Agent to break those blocks.

###  ~ Hint 

Use ``||loops:loops||`` to speed up the process. 



``` blocks
    agent.destroy(FORWARD)
    agent.move(FORWARD, 1)
```
``` blocks
for (let index = 0; index < 1; index++) {
}
```
``` package
github:kwakong/ai-cosmic_coding_at_university
```
