---
title: BoundingBox
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

Die achsenorientierte Begrenzungsbox


## Properties

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
| constructor_overload(minimum, maximum) | Initialisieren Sie eine endliche Begrenzungsbox mit gegebenen minimalen und maximalen Eckpunkten |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| minimum | Vector3 | Der minimale Eckpunkt |
| Maximum | Vector3 | Der maximale Eckpunkt |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| Konstruktor_Überladung2(minX, minY, minZ, maxX, maxY, maxZ) | Initialisieren Sie eine endliche Begrenzungsbox mit gegebenen minimalen und maximalen Eckpunkten |

 **Result:**



---


### getExtent{#getExtent}

| Name | Beschreibung |
| --- | --- |
| getExtent() | Liefert den Umfang des Begrenzungsrahmens. Der Wert der Eigenschaft ist die Ganzzahlkonstante BoundingBoxExtent. |

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
| getSize() | Die Größe der BoundingBox |

 **Result:**



---


### getCenter{#getCenter}

| Name | Beschreibung |
| --- | --- |
| getCenter() | Der Mittelpunkt der BoundingBox. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Name | Beschreibung |
| --- | --- |
| fromGeometry(geometry) | Erstelle eine BoundingBox aus gegebener Geometrie |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Geometrie | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt die Zeichenkettenrepräsentation der Begrenzungsbox zurück. |

 **Result:**
String


---


### hashCode{#hashCode}

| Name | Beschreibung |
| --- | --- |
| hashCode() | Gibt den Hashcode für diese Instanz zurück |

 **Result:**
Number


---


### equals{#equals}

| Name | Beschreibung |
| --- | --- |
| equals(obj) | Bestimmt, ob zwei Objekte gleich sind |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



