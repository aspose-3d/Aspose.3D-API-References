---
title: "BoundingBox2D"
second_title: "Aspose.3D per Node.js via Java API Reference"
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
| constructor_overload(minimum, maximum) | Inizializza un bounding box finito con gli angoli minimo e massimo specificati |

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
| merge(pt) | Unisce il nuovo box al bounding box corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Nome | Descrizione |
| --- | --- |
| merge(bb) | Unisce il nuovo box al bounding box corrente. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Restituisce la rappresentazione stringa del riquadro di delimitazione. |

 **Result:**
Stringa


---



