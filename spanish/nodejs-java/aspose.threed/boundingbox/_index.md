---
title: "BoundingBox"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

El cuadro delimitador alineado a los ejes


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
| minimum | Vector3 | La esquina mínima |
| maximum | Vector3 | La esquina máxima |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Inicializa una caja delimitadora finita con la esquina mínima y máxima dadas |

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


### getSize{#getSize}

| Nombre | Descripción |
| --- | --- |
| getSize() | El tamaño del cuadro delimitador |

 **Result:**



---


### getCenter{#getCenter}

| Nombre | Descripción |
| --- | --- |
| getCenter() | El centro del cuadro delimitador. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Nombre | Descripción |
| --- | --- |
| fromGeometry(geometry) | Construir un cuadro delimitador a partir de la geometría dada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| geometría | Geometría | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Obtiene la representación en cadena del cuadro delimitador. |

 **Result:**
Cadena


---


### hashCode{#hashCode}

| Nombre | Descripción |
| --- | --- |
| hashCode() | Devuelve el código hash para esta instancia |

 **Result:**
Número


---


### equals{#equals}

| Nombre | Descripción |
| --- | --- |
| equals(obj) | Determina si dos objetos son iguales |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| ob | Objeto | null |

 **Result:**
boolean


---



