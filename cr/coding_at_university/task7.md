# Task #7
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

## Izgradite most

Uz pomoć svog agenta, izgradite most za prelazak preko vode. Ne zaboravite Agentu dati potrebne blokove!

### ~ Savjet 

Ne postoji poseban način da se izvrši ovaj zadatak. Pokušajte koristiti ``||petlje||``.
Napravite most i razgovarajte s kapetanicom Annom.


``` blocks
agent.setSlot(1)
agent.setSlot(GRASS)
agent.move(FORWARD, 3)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
agent.place(DOWN)
agent.move(FORWARD, 1)
```
```
```
```typescript-valid
Ovo se koristi SAMO za uništavanje pogrešnog
postavljen blok ili promijeniti način hoda agenta
```
``` blocks
agent.turn(LEFT_TURN)
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
