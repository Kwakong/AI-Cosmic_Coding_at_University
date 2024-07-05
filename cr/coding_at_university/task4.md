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

## Prikupite materijale

Provedite agenta kroz labirint i sakupite sve potrebne dijelove! Da biste uzeli predmet, koristite naredbu ``||agent.destroy||``. Nakon što vaš robot prikupi potrebne predmete, razgovarajte s ``||Professor Assistant||``.

### ~ Savjet 

Slobodno napravite vlastitu robotsku stazu kako biste skupili sve potrebne dijelove. Ako ponovno razgovarate s profesorom Arturom, možete poništiti svoj zadatak i ponovno stvoriti predmete na zemlji. 


```typescript-valid
Put za stavku "glowstone_dust".
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
Put za stavku "iron_ingot".
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
Put za stavku "stick".
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
