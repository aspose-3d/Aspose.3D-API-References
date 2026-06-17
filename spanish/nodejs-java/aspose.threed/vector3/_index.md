---
title: "Vector3"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Un vector con tres componentes.


## Propiedades

| Nombre | Descripción |
| --- | --- |
| x | El componente x. |
| y | El componente y. |
| z | El componente z. |
| ORIGIN | Obtiene la posición de origen. El origen. |
| UNIT_SCALE | Obtiene el vector de escala de unidad. |
| X_AXIS | Obtiene el eje X. El eje X. |
| Y_AXIS | Obtiene el eje Y. El eje Y. |
| Z_AXIS | Obtiene el eje Z. El eje Z. |

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
| constructor_overload(x, y, z) | Inicializa una nueva instancia de la estructura Vector3. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| x | Número | La coordenada x. |
| y | Número | La coordenada y. |
| z | Número | La coordenada z. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(vec) | Inicializa una nueva instancia de la estructura Vector3. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| vec | FVector3 | La coordenada x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nombre | Descripción |
| --- | --- |
| constructor_overload3(v) | Inicializa una nueva instancia de la estructura Vector3. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| v | Número | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nombre | Descripción |
| --- | --- |
| constructor_overload4(vec4) | Inicializa una nueva instancia de la estructura Vector3. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Nombre | Descripción |
| --- | --- |
| getLength2() | Obtiene el cuadrado de la longitud. La longitud2. |

 **Result:**



---


### getLength{#getLength}

| Nombre | Descripción |
| --- | --- |
| getLength() | Obtiene la longitud de este vector. La longitud. |

 **Result:**



---


### equals{#equals}

| Nombre | Descripción |
| --- | --- |
| equals(obj) | Comprueba si dos vector3 son iguales |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| obj | Objeto | El objeto para comprobar la igualdad. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Nombre | Descripción |
| --- | --- |
| hashCode() | Obtiene el código hash de Vector3 |

 **Result:**
Número


---


### dot{#dot}

| Nombre | Descripción |
| --- | --- |
| dot(rhs) | Obtiene el producto punto de dos vectores |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rhs | Vector3 | Valor del lado derecho. |

 **Result:**
Número


---


### normalize{#normalize}

| Nombre | Descripción |
| --- | --- |
| normalize() | Normaliza esta instancia. |

 **Result:**
Vector3


---


### sin{#sin}

| Nombre | Descripción |
| --- | --- |
| sin() | Calcula el seno en cada componente |

 **Result:**
Vector3


---


### cos{#cos}

| Nombre | Descripción |
| --- | --- |
| cos() | Calcula el coseno en cada componente |

 **Result:**
Vector3


---


### cross{#cross}

| Nombre | Descripción |
| --- | --- |
| cross(rhs) | Producto cruz de dos vectores |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rhs | Vector3 | Valor del lado derecho. |

 **Result:**
Vector3


---


### set{#set}

| Nombre | Descripción |
| --- | --- |
| set(newX, newY, newZ) | Establece los componentes x/y/z en una sola llamada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| newX | Número | El componente x. |
| newY | Número | El componente y. |
| newZ | Número | El componente z. |

 **Result:**
Vector3


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Devuelve un java.lang.String que representa el Vector3 actual. |

 **Result:**
Cadena


---


### angleBetween{#angleBetween}

| Nombre | Descripción |
| --- | --- |
| angleBetween(dir, up) | Calcula el ángulo interno entre dos direcciones. Dos direcciones pueden ser vectores no normalizados. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| dir | Vector3 | El vector de dirección con el que comparar. |
| up | Vector3 | El vector up del plano compartido de las dos direcciones. |

 **Result:**
Número


---


### angleBetween{#angleBetween}

| Nombre | Descripción |
| --- | --- |
| angleBetween(dir) | Calcula el ángulo interno entre dos direcciones. Dos direcciones pueden ser vectores no normalizados. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| dir | Vector3 | El vector de dirección con el que comparar. |

 **Result:**
Número


---


### compareTo{#compareTo}

| Nombre | Descripción |
| --- | --- |
| compareTo(other) | Compara el vector actual con otra instancia. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Número


---



