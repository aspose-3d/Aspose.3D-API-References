---
title: "TransformBuilder"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

El TransformBuilder se usa para construir la matriz de transformación mediante una cadena de transformaciones.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(initial, order) | Construye un TransformBuilder con la matriz de transformación inicial y el orden de composición especificado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| initia | Matrix4 | null |
| orden | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(order) | Construye un TransformBuilder con la matriz de transformación de identidad inicial y el orden de composición especificado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| orden | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Nombre | Descripción |
| --- | --- |
| getMatrix() | Obtiene o establece el valor de la matriz actual. |

 **Result:**



---


### setMatrix{#setMatrix}

| Nombre | Descripción |
| --- | --- |
| setMatrix(value) | Obtiene o establece el valor de la matriz actual. |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Nombre | Descripción |
| --- | --- |
| getComposeOrder() | Obtiene o establece el orden de composición de la cadena. El valor de la propiedad es la constante entera ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Nombre | Descripción |
| --- | --- |
| setComposeOrder(value) | Obtiene o establece el orden de composición de la cadena. El valor de la propiedad es la constante entera ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Nombre | Descripción |
| --- | --- |
| compose(m) | Añadir o anteponer el argumento a la matriz interna. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Nombre | Descripción |
| --- | --- |
| append(m) | Añade la nueva matriz de transformación a la cadena de transformaciones. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Nombre | Descripción |
| --- | --- |
| prepend(m) | Anteponer la nueva matriz de transformación a la cadena de transformaciones. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Nombre | Descripción |
| --- | --- |
| rearrange(newX, newY, newZ) | Reorganizar la disposición del eje. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| newX | Eje | Eje |
| newY | Eje | Eje |
| newZ | Eje | Eje |

 **Result:**



---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| escala(s) | Encadenar una matriz de transformación de escala con un componente escalado por s |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Número | null |

 **Result:**



---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| scale(x, y, z) | Encadenar una matriz de transformación de escala |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Número | null |
|  | Número | null |
|  | Número | null |

 **Result:**



---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| escala(s) | Encadenar una transformación de escala |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nombre | Descripción |
| --- | --- |
| rotateDegree(angle, axis) | Encadenar una transformación de rotación en grados |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Número | El ángulo a rotar en grados |
| eje | Vector3 | El eje a rotar |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nombre | Descripción |
| --- | --- |
| rotateRadian(angle, axis) | Encadenar una transformación de rotación en radianes |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Número | El ángulo a rotar en radianes |
| eje | Vector3 | El eje a rotar |

 **Result:**



---


### rotate{#rotate}

| Nombre | Descripción |
| --- | --- |
| rotate(q) | Encadenar una rotación mediante un cuaternión |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Cuaternión | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Nombre | Descripción |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Encadenar una rotación mediante ángulos de Euler en grados |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| deg | Número | null |
| deg | Número | null |
| deg | Número | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nombre | Descripción |
| --- | --- |
| rotateEulerRadian(x, y, z) | Encadenar una rotación mediante ángulos de Euler en radianes |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Número | null |
|  | Número | null |
|  | Número | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nombre | Descripción |
| --- | --- |
| rotateEulerRadian(r) | Encadenar una rotación mediante ángulos de Euler en radianes |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Nombre | Descripción |
| --- | --- |
| translate(tx, ty, tz) | Encadenar una transformación de traslación |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| t | Número | null |
| t | Número | null |
| t | Número | null |

 **Result:**



---


### translate{#translate}

| Nombre | Descripción |
| --- | --- |
| translate(v) | Encadenar una transformación de traslación |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Nombre | Descripción |
| --- | --- |
| reset() | Restablecer la transformación a la matriz identidad |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nombre | Descripción |
| --- | --- |
| rotateDegree(rot, order) | Agregar rotación con el orden especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rot | Vector3 | Rotación en grados |
| orden | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nombre | Descripción |
| --- | --- |
| rotateRadian(rot, order) | Agregar rotación con el orden especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rot | Vector3 | Rotación en radianes |
| orden | RotationOrder | RotationOrder |

 **Result:**



---



