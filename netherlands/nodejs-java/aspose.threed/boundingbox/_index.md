---
title: "BoundingBox"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

De as‑gealigneerde begrenzingsbox


## Properties

| Naam | Beschrijving |
| --- | --- |
| NULL | De null begrenzingsvak |
| INFINITE | De oneindige begrenzingsvak |

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
| constructor_overload(minimum, maximum) | Initialiseer een eindige begrenzingsvak met de opgegeven minimum- en maximumhoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| minimum | Vector3 | De minimumhoek |
| maximum | Vector3 | De maximumhoek |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Initialiseer een eindige begrenzingsvak met de opgegeven minimum- en maximumhoek |

 **Result:**



---


### getExtent{#getExtent}

| Naam | Beschrijving |
| --- | --- |
| getExtent() | Haalt de omvang van de begrenzingsvak op. De waarde van de eigenschap is de gehele constante BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Naam | Beschrijving |
| --- | --- |
| getMinimum() | De minimumhoek van de begrenzingsvak |

 **Result:**



---


### getMaximum{#getMaximum}

| Naam | Beschrijving |
| --- | --- |
| getMaximum() | De maximumhoek van de begrenzingsvak |

 **Result:**



---


### getSize{#getSize}

| Naam | Beschrijving |
| --- | --- |
| getSize() | De grootte van het begrenzingsvak |

 **Result:**



---


### getCenter{#getCenter}

| Naam | Beschrijving |
| --- | --- |
| getCenter() | Het midden van het begrenzingsvak. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Naam | Beschrijving |
| --- | --- |
| fromGeometry(geometry) | Construeer een begrenzingsvak vanuit de gegeven geometrie |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| geometr | Geometrie | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Haalt de tekenreeksrepresentatie van de begrenzingsvak op. |

 **Result:**
String


---


### hashCode{#hashCode}

| Naam | Beschrijving |
| --- | --- |
| hashCode() | Retourneert de hashcode voor deze instantie |

 **Result:**
Number


---


### equals{#equals}

| Naam | Beschrijving |
| --- | --- |
| equals(obj) | Bepaalt of twee objecten gelijk zijn |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



