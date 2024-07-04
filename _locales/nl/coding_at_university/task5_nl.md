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

## Verzamel voedsel en plaats het in de Chef AI Robot

Navigeer de Agent door het doolhof. Verzamel al het voedsel dat je kunt vinden en plaats het in de Chef AI Robot. Gebruik de commando's ``||agent:destroy||`` en ``||agent:collectAll||`` om individuele voorwerpen te verzamelen.
Als er voorwerpen van de grond verdwijnen, gebruik dan de knop naast de Chef AI Robot.

### ~ Hint 1

In deze opdracht moet je 8 voedingsmiddelen verzamelen. In de eerste ronde moet je verzamelen: ``||Ui||``, ``||Druiven||``, ``||Worst||``, ``||Chocolade||``. In de volgende ronde moet je verzamelen: ``||Vlees||``, ``||Peras||``, ``||Tomaat||``, ``||knoflook||``. Als je een fout maakt, klik dan op de "reset Agent positie" knop die vlakbij de Chef AI Robot staat.

### ~ Hint 2
Als je na een bepaalde ronde alle voedsel hebt verkregen, klik je met de rechtermuisknop op de Agent om het verkregen voedsel over te dragen aan de Chef AI Robot door er ook met de rechtermuisknop op te klikken. Veel succes!


```typescript-valid
Eerste ronde oplossing voor het verzamelen van 4 items
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
Tweede ronde oplossing voor het verzamelen van 4 items
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
