Kod liste unutar *li* se treba ubaciti link ili nešto jer se inače ne prikazuje


Button
- ako taknem funckiju *border* odma nestane mogućnost klika


Stavljanje elemenata kontenjera na float kolapsira kontenjer: fixevi:
https://stackoverflow.com/questions/218760/how-do-you-keep-parents-of-floated-elements-from-collapsingInp


Ne treba nam id za input jer imamo samo jedan.
Moramo staviti i border style i border width inače izgleda više ko 3d


Maknuti dok pritisnemo search bar da ima border

```css
  input:focus {
            outline: none;
            
        }

```