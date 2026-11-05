---
title: "BoundingBox2D"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

De as‑gealigneerde begrenzingsbox voor Vector2


## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| NULL | De null-bounding box |
| INFINITE | De oneindige bounding box |

## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(minimum, maximum) | Initialiseer een eindige bounding box met gegeven minimum- en maximumhoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| minimum | Vector2 | De minimumhoek |
| maximum | Vector2 | De maximumhoek |

 **Result:**



---


### getExtent{#getExtent}

| Naam | Beschrijving |
| --- | --- |
| getExtent() | Haalt de omvang van de bounding box op. De waarde van de eigenschap is BoundingBoxExtent integer‑constante. |

 **Result:**



---


### getMinimum{#getMinimum}

| Naam | Beschrijving |
| --- | --- |
| getMinimum() | De minimumhoek van de bounding box |

 **Result:**



---


### getMaximum{#getMaximum}

| Naam | Beschrijving |
| --- | --- |
| getMaximum() | De maximale hoek van de begrenzingsvak |

 **Result:**



---


### merge{#merge}

| Naam | Beschrijving |
| --- | --- |
| merge(pt) | Voegt de nieuwe doos toe aan de huidige begrenzingsvak. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Naam | Beschrijving |
| --- | --- |
| merge(bb) | Voegt de nieuwe doos toe aan de huidige begrenzingsvak. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Haalt de stringrepresentatie van de begrenzingsvak op. |

 **Result:**
String


---



