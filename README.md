### @explicitHints false

## Introduksjon @unplugged
Her vil du lære å kode kule toner. 

Målet er å spille Twinkle twinkle little star !


## Steg 1: Lage en funksjon som skal inneholde toner for første og siste vers.
Vi begynner med første vers og siste vers.
Trykk på ``|| Advanced: Avansert ||`` fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

Klikk på ``|| Functions: Lag en funksjon ||`` og klikk inni feltet som det står [ gjørNoe].
Skriv inn [Begynnelse/Slutt]. (her kan du kalle den det du vil. men gi den et navn som forteller hva denne inneholder.
 )

 ```blocks  
function BegynnelseSlutt () {        
}     
```
## Steg 2: Lage en funksjon som skal inneholde toner for refrenget.
Så tar vi refrenget.
Trykk på ``|| Advanced: Avansert ||`` fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

Klikk på ``|| Functions: Lag en funksjon ||`` og klikk inni feltet som det står [ gjørNoe ].
Skriv inn [ Refreng ]. (her kan du kalle den det du vil. men gi den et navn som forteller hva denne inneholder.
 )

 ```blocks  
function BegynnelseSlutt () {       
}
function Refreng () {
}    
```
## Steg 3: Definer tone og takt i 1 og siste vers
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Functions: Begynnelse/Slutt ||``.
Sett tone og takt til ``|| Music: spill tone ( Midtre C ) i ( 1 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
}     
```
## Steg 4:  Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre C ) i ( 1 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
}     
```
## Steg 5: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
}    
```
## Steg 6: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
}     
```
## Steg 7: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre A ) i ( 1 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
}    
```
## Steg 8: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre A ) i ( 1 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
}     
```
## Steg 9: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 2 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
}     
```
## Steg 10: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre F ) i ( 1 taktslag ) ||``.

 ```blocks  
function BegynnelseSlutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
}     
```
## Steg 11: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre F ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))  
}
```
## Steg 12: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre E ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))  
}
```
## Steg 13: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre E ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
}
```
## Steg 14: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre D ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
}
```
## Steg 15: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre D ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
}
```
## Steg 16: Definer tone og takt
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre C ) i ( 2 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
```
## Steg 17: Definer tone og takt i refrenget
Trykk på ``|| Advanced: Avansert||``. Klikk på ``||Functions: Funksjoner ||`` fra blokkmenyen. klikk og dra inn ``|| Functions: Refreng ||``.


```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}

function Refreng () {
  
  
}

```
## Steg 18: Definer tone og takt i refrenget
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne inni ``|| Functions: Refreng ||``..
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
}
```
## Steg 19: Definer tone og takt i refrenget
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre G ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
}
```
## Steg 20: Definer tone og takt i refrenget
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre F ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
}
```
## Steg 21: Definer tone og takt i refrenget
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre F ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
}
```
## Steg 22: Definer tone og takt i refrenget
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre E ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
}
```
## Steg 23: Definer tone og takt i refrenget
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre E ) i ( 1 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
}
```
## Steg 24: Definer tone og takt i refrenget
Trykk på ``||Music: Musikk||`` fra blokkmenyen. klikk og dra deretter inn ``||Music: Spill tone ( Midtre C ) i (1 taktslag) ||`` og sett denne under forrige blokk.
Sett tone og takt til ``|| Music: spill tone ( Midtre D ) i ( 2 taktslag ) ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Double))
}

```
## Steg 26: sette opp rekkefølge på vers og refreng
Trykk på ``|| Advanced: Avansert||`` fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

Klikk på og dra inn ``|| Functions: BegynnelseSlutt ||`` 2 ganger og sett disse inni ``basic: gjenta for alltid ||`` blokken.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Double))
}
basic.forever(function () {
    begynnelseslutt()
    begynnelseslutt()
})
```
## Steg 26: sette opp rekkefølge på vers og refreng
Trykk på ``||Loops: Løkker||`` fra blokkmenyen. klikk og dra deretter inn ``||Loops: gjenta (4) ganger ||`` og sett denne inni ``|| basic:  ved start ||`` og i mellom ``|| Functions: kjør BegynnelseSlutt ||`` blokkene.
Sett verdi til ``|| Loops: gjenta (2) ganger ||``.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Double))
}
basic.forever(function () {
    begynnelseslutt()
    for (let index = 0; index < 2; index++) {
    
    }
     begynnelseslutt()
})
```
## Steg 27: sette opp rekkefølge på vers og refreng
Trykk på ``|| Advanced: Avansert||`` fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

Klikk på og dra inn ``|| Functions: Refreng ||`` og sett denne inni ``||Loops: gjenta (2) ganger ||`` blokken.

```blocks
function begynnelseslutt () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(440, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Double))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Whole))
    music.playTone(262, music.beat(BeatFraction.Double))
}
function Refreng () {
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(392, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(349, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(330, music.beat(BeatFraction.Whole))
    music.playTone(294, music.beat(BeatFraction.Double))
}
basic.forever(function () {
    begynnelseslutt()
    for (let index = 0; index < 2; index++) {
    Refreng()
    }
    begynnelseslutt()
})
```
## Steg 28: Laste ned på microbiten

Hvis du har en @boardname@ tilkoblet, trykk ``|last ned|``!
Prøv nå også endre farge og hvilken LED som skal lyse for så å trykke ``|last ned|`` igjen.
For hver endring vi gjør i koden må det lastes ned på nytt til @boardname@. Dersom du ikke har en @boardname@ tilkoblet, må du gjøre de neste stegene også.

## Steg 29: Koble til micro:biten
For å kunne laste ned koden din til micro:biten med et klikk må du først få MakeCode til å skjønne at alle filer skal lastes ned direkte til den.
Det krever bare noen få, enkle steg.

## Steg 30: Prikkene ved siden av Last Ned-knappen

Start med å sjekke at micro:biten du skal bruke er koblet til PCen. Når den er koblet til, klikker du på de tre prikkene ved siden av ``|last ned|``-knappen

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect1.jpg)

## Steg 31: Connect-menyen @unplugged
Når du klikker på de tre prikkene dukker det oppe en liten meny. Dersom det står "Koble Fra" eller "Disconnect" på den øverste linjen, trenger du ikke å gjøre mer.
Da kjenner PCen og MakeCode igjen micro:biten fra tidligere, og du kan klikke ved siden av menyen og laste ned koden din ved å klikke på den store ``|last ned|``-knappen.

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect2b.jpg)


## Steg 32: Dersom MakeCode ikke kjenner micro:biten fra før
Dersom MakeCode ikke kjenner micro:biten fra før vil det stå "Connect device" eller "Koble til" på den øverste linjen.
Klikk i så fall på den øverste linjen i menyen.

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect2.jpg)


## Steg 33: Veiledningsvindu

Når du klikker på den øverste linjen dukker det opp et par veiledningsvinduer som tar deg gjennom tilkoblingsprosessen. De to første kan du bare trykke "Next" eller "Fortsett" på:

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect3.jpg)

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect4.jpg)


## Steg 34: Velg micro:biten

Etter at du har klikket "Next" to ganger dukker det opp en liste over tilgjengelige micro:biter. Det skal bare være én micro:bit på lista.
Klikk først på navnet til micro:biten så det blir merket med blått, og så på "Koble til".

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect5.jpg)

## Steg 35: Ferdig!

I det siste veiledningsvinduet klikker du på "Done" eller "Ferdig" om det står på norsk.
Etter det kan du laste ned kode direkte til micro:biten ved å klikke på den store, lilla ``|last ned|``-knappen nederst til venstre på skjermen i MakeCode:

![Connect](https://raw.githubusercontent.com/InspiriaSCC/Superbit/master/static/Connect6.jpg)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
