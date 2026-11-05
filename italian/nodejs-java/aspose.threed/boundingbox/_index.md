---
title: "BoundingBox"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

La bounding box allineata agli assi


## Proprietà

| Nome | Descrizione |
| --- | --- |
| NULL | Il bounding box nullo |
| INFINITE | Il bounding box infinito |

## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(minimum, maximum) | Inizializza un bounding box finito con gli angoli minimo e massimo forniti |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| minimum | Vector3 | L'angolo minimo |
| maximum | Vector3 | L'angolo massimo |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Inizializza un bounding box finito con gli angoli minimo e massimo forniti |

 **Result:**



---


### getExtent{#getExtent}

| Nome | Descrizione |
| --- | --- |
| getExtent() | Restituisce l'estensione del bounding box. Il valore della proprietà è la costante intera BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Nome | Descrizione |
| --- | --- |
| getMinimum() | L'angolo minimo del bounding box |

 **Result:**



---


### getMaximum{#getMaximum}

| Nome | Descrizione |
| --- | --- |
| getMaximum() | L'angolo massimo del bounding box |

 **Result:**



---


### getSize{#getSize}

| Nome | Descrizione |
| --- | --- |
| getSize() | La dimensione del bounding box |

 **Result:**



---


### getCenter{#getCenter}

| Nome | Descrizione |
| --- | --- |
| getCenter() | Il centro del bounding box. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Nome | Descrizione |
| --- | --- |
| fromGeometry(geometry) | Costruisci un bounding box dalla geometria fornita |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| geometr | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Ottiene la rappresentazione stringa della bounding box. |

 **Result:**
String


---


### hashCode{#hashCode}

| Nome | Descrizione |
| --- | --- |
| hashCode() | Restituisce il codice hash per questa istanza |

 **Result:**
Numero


---


### equals{#equals}

| Nome | Descrizione |
| --- | --- |
| equals(obj) | Determina se due oggetti sono uguali |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



