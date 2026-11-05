---
title: "Metered"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/metered/
---
## Metered class

Biedt methoden om een gemeten sleutel in te stellen.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuwe instantie van deze klasse. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Naam | Beschrijving |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Stelt de gemeten publieke en private sleutel in. Als u een gemeten licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal is dit voldoende. Echter, als het steeds mislukt om verbruiksgegevens te uploaden en de 24 uur overschrijdt, wordt de licentie op evaluatiestatus gezet. Om zo'n geval te voorkomen, dient u regelmatig de licentiestatus te controleren; als deze op evaluatiestatus staat, roept u deze API opnieuw aan. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| publicKey | String | publieke sleutel |
| privateKey | String | privésleutel |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Naam | Beschrijving |
| --- | --- |
| getConsumptionQuantity() | Haalt de bestandsgrootte van het verbruik op |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Naam | Beschrijving |
| --- | --- |
| getConsumptionCredit() | Haalt het verbruikscrediet op |

 **Result:**
BigDecimal


---



