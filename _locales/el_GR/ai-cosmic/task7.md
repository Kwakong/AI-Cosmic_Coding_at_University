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

## Κατασκευάστε μια γέφυρα

Με τη βοήθεια του πράκτορά σας, κατασκευάστε μια γέφυρα για να περάσετε το νερό. Μην ξεχάσετε να δώσετε στον Πράκτορα τα απαραίτητα τουβλάκια!

### ~ Υπόδειξη 

Δεν υπάρχει συγκεκριμένος τρόπος για την εκτέλεση αυτής της εργασίας. Δοκίμασε να χρησιμοποιήσεις τη μέθοδο ``||Loops||``.
Δημιουργήστε μια γέφυρα και μιλήστε με την καπετάνισσα Άννα.



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
Αυτό χρησιμοποιείται ΜΟΝΟ για να καταστρέψει λάθος τοποθετημένο μπλοκ ή για να αλλάξετε τον τρόπο με τον οποίο περπατάει ο πράκτορας.
```
``` blocks
agent.turn(LEFT_TURN)
agent.destroy(FORWARD)
```
```package
github:Mikey-S1/ai-cosmic_coding_at_university
```
