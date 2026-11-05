---
title: "BoundingBox"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

Die achsenparallel ausgerichtete Begrenzungsbox


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| NULL | Die Null-Begrenzungsbox |
| INFINITE | Die unendliche Begrenzungsbox |

## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(minimum, maximum) | Initialisiert eine endliche Begrenzungsbox mit angegebenem minimalen und maximalen Eckpunkt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| minimum | Vector3 | Der minimale Eckpunkt |
| maximum | Vector3 | Der maximale Eckpunkt |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Initialisiert eine endliche Begrenzungsbox mit angegebenem minimalen und maximalen Eckpunkt |

 **Result:**



---


### getExtent{#getExtent}

| Name | Beschreibung |
| --- | --- |
| getExtent() | Ermittelt die Ausdehnung der Begrenzungsbox. Der Wert der Eigenschaft ist die Ganzzahlkonstante BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Name | Beschreibung |
| --- | --- |
| getMinimum() | Der minimale Eckpunkt der Begrenzungsbox |

 **Result:**



---


### getMaximum{#getMaximum}

| Name | Beschreibung |
| --- | --- |
| getMaximum() | Der maximale Eckpunkt der Begrenzungsbox |

 **Result:**



---


### getSize{#getSize}

| Name | Beschreibung |
| --- | --- |
| getSize() | Die Größe der Begrenzungsbox |

 **Result:**



---


### getCenter{#getCenter}

| Name | Beschreibung |
| --- | --- |
| getCenter() | Der Mittelpunkt der Begrenzungsbox. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Name | Beschreibung |
| --- | --- |
| fromGeometry(geometry) | Erstelle eine Begrenzungsbox aus gegebener Geometrie |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| geometr | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Ermittelt die Zeichenkettenrepräsentation der Begrenzungsbox. |

 **Result:**
String


---


### hashCode{#hashCode}

| Name | Beschreibung |
| --- | --- |
| hashCode() | Gibt den Hashcode für diese Instanz zurück |

 **Result:**
Zahl


---


### equals{#equals}

| Name | Beschreibung |
| --- | --- |
| equals(obj) | Bestimmt, ob zwei Objekte gleich sind |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| ob | Objekt | null |

 **Result:**
boolean


---



