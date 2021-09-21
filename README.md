### @explicitHints false

## Introduksjon @unplugged
Her vil du lære å kode kule toner. 

Målet er å spille Twinkle twinkle little star !


## Steg 1: Lage en funksjon som skal inneholde toner for begynelse og slutt vers.
Vi begynner med 1 vers og siste vers.
Trykk på [ Avansert ] fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

Klikk på ``|| Functions: Lag en funksjon ||`` og klikk inni feltet som det står [ gjørNoe].
Skriv inn [Begynnelse/Slutt]. (her kan du kalle den det du vil. men lurt å gi et navn så du vet hva denne inneholder.
 )

 ```blocks  
function BegynnelseSlutt () {        
}     
```
## Steg 2: Lage en funksjon som skal inneholde toner for refrenget.
Så tar vi refrenget.
Trykk på [ Avansert ] fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

Klikk på ``|| Functions: Lag en funksjon ||`` og klikk inni feltet som det står [ gjørNoe ].
Skriv inn [ Refreng ]. (her kan du kalle den det du vil. men lurt å gi et navn så du vet hva denne inneholder.
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
Trykk på [ Avansert ]. Klikk på ``||Functions: Funksjoner ||`` fra blokkmenyen. klikk og dra inn ``|| Functions: Refreng ||``.


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
Trykk på [ Avansert ] fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

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
Trykk på [ Avansert ] fra blokkmenyen. Trykk deretter på ``|| Functions: Funksjoner ||``.

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
## Steg 28: Leste ned på microbiten

hvis du har en @boardname@ tilkoblet, trykk ``|last ned|``!
Prøv nå også endre farge og hvilken LED som skal lyse for så å trykke ``|last ned|`` igjen.
For hver endring vi gjør i koden må det lastes ned på nytt til @boardname@.
