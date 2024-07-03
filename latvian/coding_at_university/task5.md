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

## Savāc pārtiku un ievieto to šefpavāra mākslīgā intelekta robotā.

Pārvietojiet aģentu pa labirintu. Savāciet visu atrodamo pārtiku un ievietojiet to šefpavāra mākslīgā intelekta robotā. Izmantojiet komandas ```|agent:destroy|||`` un ```|agent:collectAll||``, lai savāktu atsevišķus priekšmetus. Ja bloka priekšmeti pazūd no zemes, izmantojiet pogu blakus šefpavāra AI robotam.

### ~ Padoms 1

Šajā uzdevumā ir jāsavāc 8 pārtikas produkti. Pirmajā kārtā jums ir jāsavāc: ``||Šokolāde||``, ``|Sīpoli|``, ``|Vīnogas|``, ``|Desa|``, ``|Šokolāde|``. Nākamajā kārtā jums būs jāsavāc: ``|Gaļa||``, ``|Zirņi|``, 
``|Tomāti||``, ``|Kiploki|``. Ja esat kļūdījies, noklikšķiniet uz pogas “Atiestatīt aģenta pozīciju”, kas atrodas pie šefpavāra AI robots.

### ~ Padoms 2
Kad pēc attiecīgās kārtas esat ieguvis visus pārtikas produktus, noklikšķiniet uz aģenta ar peles labo pogu, lai pārnestu iegūto pārtiku uz šefpavāra mākslīgā intelekta robotu, arī uz tā uzklikšķinot ar peles labo pogu. Veiksmi!


```typescript-valid
Pirmās kārtas risinājums 4 priekšmetu vākšanai
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
Otrās kārtas risinājums 4 priekšmetu vākšanai
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
