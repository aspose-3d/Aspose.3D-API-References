---
title: "BoundingBox2D"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

La bounding box allineata agli assi per Vector2


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
| minimum | Vector2 | L'angolo minimo |
| maximum | Vector2 | L'angolo massimo |

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


### merge{#merge}

| Nome | Descrizione |
| --- | --- |
| merge(pt) | Unisce la nuova box alla bounding box corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Nome | Descrizione |
| --- | --- |
| merge(bb) | Unisce la nuova box alla bounding box corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Ottiene la rappresentazione stringa della bounding box. |

 **Result:**
String


---



