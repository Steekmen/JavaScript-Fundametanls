# Loops 
--- 
### Ibland måste man göra samma sak många gånger, `loops` hjälper till med det

## `for` Loop
#### Skrivas det så här, exempel

```
for (let i = 0; i < 10; i++) { // visar 0, 1, 2...
    alert(i)
}
```
##### Kållar närmare på strukturen av tre faser `for` loop

> `let i = 0;` **Start**, utförs en gång när loop börjas
> `i < 10;` **Villkoret**, kontrolleras varje gång före en ny upprepning av loop
> `i++;` **Steg**, utförs efter kodblocket, lägger till 1 talet
 
## `while` Loop 
##### Skrivas det så här

```
while (villkoret) {
// kodblock
// kallas också för 'kodkroppen'
}
```
##### Kodblocket utförs så länge villkoret är sant

#### Exempel
```
let i = 0
while (i < 10) {
    alert(i);
    i++;
}
```