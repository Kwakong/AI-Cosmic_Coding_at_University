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

## Materiālu apkopošana

Pārvietojiet aģentu cauri labirintam un savāciet visas nepieciešamās detaļas! Lai paņemtu priekšmetu, izmantojiet komandu ``|||agent.destroy||``. Pēc tam, kad jūsu robots ir savācis vajadzīgos priekšmetus, aprunājieties ar ``||profesora asistentu||``.

### ~ Padoms 

Lai savāktu visas nepieciešamās detaļas, brīvi izveidojiet savu robota ceļu. Ja atkal parunāsieties ar profesoru Artūru, varēsiet atjaunot savu uzdevumu un uz zemes atkal atraisīt priekšmetus. 


```typescript-valid
Ceļš vienumam “glowstone_dust”
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
Ceļš vienumam “iron_ingot”
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
Ceļš vienumam “stick”
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
