---
title: "BoundingBox2D"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Die achsenparallel ausgerichtete Begrenzungsbox für Vector2


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
| minimum | Vector2 | Der minimale Eckpunkt |
| maximum | Vector2 | Der maximale Eckpunkt |

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
| toString() | Ermittelt die Zeichenkettenrepräsentation der Begrenzungsbox. |

 **Result:**
String


---



