# Bonus Task
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

## Σύστημα ανίχνευσης τροφίμων

Δώστε στον πράκτορα 3 αντικείμενα. Βεβαιωθείτε ότι ανιχνεύει τα σωστά αντικείμενα στις σωστές θέσεις. Εάν ο Πράκτορας έχει 3 αντικείμενα τροφίμων θα πρέπει να φωνάξει «φαγητό!».

### ~ Υπόδειξη 

Χρησιμοποιήστε την κατασκευή ``||αν|||`` -> ``||Πράκτορας||`` -> ``|| αναγνωριστικό υποδοχής στοιχείου ||`` -> πείτε «Φαγητό!».


``` blocks
if (agent.getItemDetail(1) == POISONOUS_POTATO) {
    if (agent.getItemDetail(2) == COOKED_CHICKEN) {
        if (agent.getItemDetail(3) == SWEET_BERRIES) {
            player.say("Food!")
        }
    }
}
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
