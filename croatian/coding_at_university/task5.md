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

## Skupite hranu i stavite je u Chef AI robota

Provedite agenta kroz labirint. Skupite svu hranu koju možete pronaći i stavite je u Chef AI robota. Koristite naredbe ``||agent:destroy||`` i ``||agent:collectAll||`` za prikupljanje pojedinačnih stavki.
Ako blok predmeti nestanu s tla, upotrijebite gumb pored Chef AI robota.

### ~ Savjet 1

U ovom zadatku morate sakupiti 8 namirnica. U prvoj rundi morate sakupiti: ``||Luk||``, ``||Grožđe||``, ``||Kobasica||``, ``||Čokolada||``. U sljedećem krugu morat ćete skupiti: ``||Meat||``, ``||Peas|``, ``||Tomato||``, ``||Garlic||``. Ako pogriješite, slobodno kliknite gumb "poništi poziciju agenta" koji se nalazi blizu Chef AI Robota.

### ~ Savjet 2
Nakon što nabavite sve namirnice nakon zadane runde, desnom tipkom miša kliknite agenta kako biste preuzetu hranu prenijeli Chef AI robotu tako što ćete također kliknuti desnom tipkom miša na njega. Sretno!


```typescript-valid
Rješenje prve runde za skupljanje 4 predmeta
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
Rješenje druge runde za prikupljanje 4 predmeta
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
