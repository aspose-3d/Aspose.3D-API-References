---
title: BoundingBox2D
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Die achsenorientierte Begrenzungsbox für Vector2


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
| minimum | Vector2 | Der minimale Eckpunkt |
| Maximum | Vector2 | Der maximale Eckpunkt |

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


### merge{#merge}

| Name | Beschreibung |
| --- | --- |
| merge(pt) | Fügt die neue Box in die aktuelle Begrenzungsbox ein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Name | Beschreibung |
| --- | --- |
| merge(bb) | Fügt die neue Box in die aktuelle Begrenzungsbox ein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt die Zeichenkettenrepräsentation der Begrenzungsbox zurück. |

 **Result:**
String


---



