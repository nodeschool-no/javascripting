---

# ITERERE GJENNOM ARRAYER

I denne oppgaven skal vi bruke en **for løkke** til å lese og endre en liste av verdier i en array.

Å lese verdier fra en array kan gjøres med et heltall.

Hvert innslag i en array identifiseres med et nummer, fra og med `0`.

Så i denne arrayen er `hei` identifisert ved nummeret `1`:

```js
var hilsinger = ['hallo', 'hei', 'god morgen'];
```

Verdien kan nås slik som dette:

```js
hilsinger[1];
```

Så på innsiden av en **for løkke** ville vi brukt `i` varibelen inni hakeparantesen instedefor å bruke et tall.

## Oppgaven:

Lag en fil som heter `looping-through-arrays.js`.

Definer en variabel `pets` som refererer til denne arrayen:

```js
['cat', 'dog', 'rat'];
```

Lag en for løkke som endrer hver eneste string i den arrayen til flertall.

Du vil måtte bruke et uttrykk som dette på inni for løkken:

```js
pets[i] = pets[i] + 's';
```

Etter den for løkken, bruk `console.log()` for å skrive ut `pets` arrayen til skjermen.

Se om programmet ditt er riktig ved å kjøre denne kommandoen:

`javascripting verify looping-through-arrays.js`

---
