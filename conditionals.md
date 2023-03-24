# Conditionals
---
### Ibland måste vi göra olika saker beroende på vilkor
## `if` instruktion

Instruktionen ```if(...)``` beräknar villkoret inom parentes och utför kodblocket om resultatet är sant

#### Exempel
```
if (condition) {
    // Kodblock som utförs om villkoret är sant.
}
```

## `else` block

`if`instruktion kan innehålla ett valfritt `else` block. Den utförs när villkoret är falskt

#### Exempel
```
let day = promt('Hur många dagar i veckan')

if (day == 7) {
    alert('Sant');
} else {
    alert('Fel svar')
}
```

## `else if` block
Lägger till nya villkor om de första villkoren inte stämmer

#### Exempel
```
let age = promt('Hur gammal är du')

if (age < 18) {
    alert('Du är ung')
} else if (age > 60) {
    alert('Du är gammal')
} else (age > 18) {
    alert('Du är vuxen')
}
```