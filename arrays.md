# Arrays
--- 
### För att lagra ordnade samlingar finns det en speciell datastruktur som kallas `array`

#### Exempel
Detta är ett mycket bekvämt sätt att lagra många saker på samma ställe och inte skapa separata variabler för element

```
const bilar = ["Audi", "BMW", "Hyundai", "Honda"];
```
Istället för att skriva så här

```
const bil1 = "Audi";
const bil2 = "BMW";
const bil3 = "Hyundai";
const bil4 = "Honda";
```
Varje element som placeras i array får ett lämpligt nummer, räknat från 0

---

Det finns ett sätt att skriva element till en array som ser bra ut

```
const bilar = [
    "Audi", 
    "BMW", 
    "Hyundai", 
    "Honda"
];
```
Element kan läggas till i array efter deklarationen
```
const bilar = [];
bilar[0] = "Audi";
bilar[1] = "BMW";
bilar[2] = "Hyundai";
bilar[3] = "Honda";
```
Man kan hämta ett element från array genom att hänvisa till indexposition 

```
const bilar = ["Audi", "BMW", "Hyundai", "Honda"];
let bil = blar[2] // Hyundai, eftersom nedräkningen börjar från 
```