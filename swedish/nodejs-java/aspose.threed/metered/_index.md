---
title: "Metered"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/metered/
---
## Metered class

Tillhandahåller metoder för att ställa in mätad nyckel.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av den här klassen. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Namn | Beskrivning |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Ställer in den mätade offentliga och privata nyckeln. Om du köper en mätt licens, bör detta API anropas när applikationen startas; normalt är detta tillräckligt. Men om uppladdning av konsumtionsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | Sträng | offentlig nyckel |
| privateKey | Sträng | privat nyckel |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Namn | Beskrivning |
| --- | --- |
| getConsumptionQuantity() | Hämtar förbrukningsfilens storlek |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Namn | Beskrivning |
| --- | --- |
| getConsumptionCredit() | Hämtar förbrukningskredit |

 **Result:**
BigDecimal


---



