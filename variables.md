# Variables
---
### Variabler är ett minnet område som kan ges ett namn för lagring av data
Så här deklareras variabeln

```
const 'namn'
let 'namn' 
var 'namn' 
'bara namn'
```
#### Exempel

```
let a = 15;
let b = 10;
let c = a + 99;
```
```
var a = 38;
var b = 3;
var c = a + b;
```
```
a = 10;
b = 22;
c = a + b;
```

### När ska 'var' och 'let' användas?
> Deklarationen `var` används inte längre nuförtiden, ofta används `const` och `let`
> 'Var' används för att läsas av äldre webbläsare och tillämpades på gamla websidor
### När ska 'const' användas?
> Om du vill att ett givet värde inte ska ändras använder du `const`
> Om du vill tillåta att värdet i en variabel ändras använder du `let`

```
const num1 = 501;
const num2 = 39;
let num3  = num1 + num2;
```
Här representerar `const` ett område med ett tydligt värde och `let` kan variera