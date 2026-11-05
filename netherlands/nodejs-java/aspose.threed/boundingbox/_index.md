---
title: "BoundingBox"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

De as‑gealigneerde begrenzingsbox


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
| minimum | Vector3 | De minimumhoek |
| maximum | Vector3 | De maximumhoek |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Initialiseer een eindige bounding box met gegeven minimum- en maximumhoek |

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


### getSize{#getSize}

| Naam | Beschrijving |
| --- | --- |
| getSize() | De grootte van de begrenzingsdoos |

 **Result:**



---


### getCenter{#getCenter}

| Naam | Beschrijving |
| --- | --- |
| getCenter() | Het midden van de begrenzingsdoos. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Naam | Beschrijving |
| --- | --- |
| fromGeometry(geometry) | Construeer een begrenzingsdoos vanuit de gegeven geometrie |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| geometrie | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Haalt de stringrepresentatie van de begrenzingsvak op. |

 **Result:**
String


---


### hashCode{#hashCode}

| Naam | Beschrijving |
| --- | --- |
| hashCode() | Retourneert de hashcode voor deze instantie |

 **Result:**
Nummer


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



