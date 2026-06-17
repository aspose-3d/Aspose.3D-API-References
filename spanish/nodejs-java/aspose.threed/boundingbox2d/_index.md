---
title: "BoundingBox2D"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

El cuadro delimitador alineado a los ejes para Vector2


## Propiedades

| Nombre | Descripción |
| --- | --- |
| NULL | La caja delimitadora nula |
| INFINITE | La caja delimitadora infinita |

## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(minimum, maximum) | Inicializa una caja delimitadora finita con la esquina mínima y máxima dadas |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| minimum | Vector2 | La esquina mínima |
| maximum | Vector2 | La esquina máxima |

 **Result:**



---


### getExtent{#getExtent}

| Nombre | Descripción |
| --- | --- |
| getExtent() | Obtiene la extensión de la caja delimitadora. El valor de la propiedad es la constante entera BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Nombre | Descripción |
| --- | --- |
| getMinimum() | La esquina mínima de la caja delimitadora |

 **Result:**



---


### getMaximum{#getMaximum}

| Nombre | Descripción |
| --- | --- |
| getMaximum() | La esquina máxima de la caja delimitadora |

 **Result:**



---


### merge{#merge}

| Nombre | Descripción |
| --- | --- |
| merge(pt) | Fusiona la nueva caja en la caja delimitadora actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Nombre | Descripción |
| --- | --- |
| merge(bb) | Fusiona la nueva caja en la caja delimitadora actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Obtiene la representación en cadena del cuadro delimitador. |

 **Result:**
Cadena


---



