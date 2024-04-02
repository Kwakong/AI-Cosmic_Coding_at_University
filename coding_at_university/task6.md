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

## WiFi Password

Vending machine is covering the WiFi password and professor cannot remember it. Code the Agent to remove the vending machine, so that WiFi password can be revealed.

### ~ Hint 

Use Agent to remove vending machine, by ``||agent:attack forward||`` action


``` blocks
agent.move(FORWARD, 2)
agent.attack(FORWARD)
```
```package
github:kwakong/ai-cosmic_coding_at_university
```
