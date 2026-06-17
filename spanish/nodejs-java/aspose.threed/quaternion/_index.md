---
title: "Cuaternión"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

El cuaternión se usa normalmente para realizar rotaciones en gráficos por computadora.


## Propiedades

| Nombre | Descripción |
| --- | --- |
| w | El componente w. |
| x | El componente x. |
| y | El componente y. |
| z | El componente z. |
| IDENTITY | El cuaternión de identidad. |

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
| constructor_overload(w, x, y, z) | Inicializa una nueva instancia de la clase Quaternion. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| w | Número | componente w del cuaternión |
| x | Número | componente x del cuaternión |
| y | Número | componente y del cuaternión |
| z | Número | componente z del cuaternión |

 **Result:**



---


### getLength{#getLength}

| Nombre | Descripción |
| --- | --- |
| getLength() | Obtiene la longitud del cuaternión |

 **Result:**



---


### equals{#equals}

| Nombre | Descripción |
| --- | --- |
| equals(obj) | Comprueba si dos cuaterniones son iguales |

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
| hashCode() | Obtiene el código hash de Quaternion |

 **Result:**
Número


---


### conjugate{#conjugate}

| Nombre | Descripción |
| --- | --- |
| conjugate() | Devuelve un cuaternión conjugado del cuaternión actual |

 **Result:**
Cuaternión


---


### inverse{#inverse}

| Nombre | Descripción |
| --- | --- |
| inverse() | Devuelve un cuaternión inverso del cuaternión actual |

 **Result:**
Cuaternión


---


### dot{#dot}

| Nombre | Descripción |
| --- | --- |
| dot(q) | Producto de puntos |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| q | Cuaternión | El cuaternión |

 **Result:**
Número


---


### eulerAngles{#eulerAngles}

| Nombre | Descripción |
| --- | --- |
| eulerAngles() | Convierte el cuaternión a una rotación representada por ángulos de Euler. Todos los componentes están en radianes |

 **Result:**
Vector3


---


### normalize{#normalize}

| Nombre | Descripción |
| --- | --- |
| normalize() | Normaliza el cuaternión |

 **Result:**
Cuaternión


---


### concat{#concat}

| Nombre | Descripción |
| --- | --- |
| concat(rhs) | Concatenar dos cuaterniones |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rh | Cuaternión | null |

 **Result:**
Cuaternión


---


### fromAngleAxis{#fromAngleAxis}

| Nombre | Descripción |
| --- | --- |
| fromAngleAxis(a, axis) | Crea un cuaternión alrededor del eje dado y lo rota en sentido horario |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| a | Número | Rotación en sentido horario en radianes |
| eje | Vector3 | Eje |

 **Result:**
Cuaternión


---


### fromRotation{#fromRotation}

| Nombre | Descripción |
| --- | --- |
| fromRotation(orig, dest) | Crea un cuaternión que rota de la dirección original a la dirección de destino |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| orig | Vector3 | Dirección original |
| dest | Vector3 | Dirección de destino |

 **Result:**
Cuaternión


---


### fromEulerAngle{#fromEulerAngle}

| Nombre | Descripción |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Crea un cuaternión a partir del ángulo de Euler dado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| pitch | Número | Ángulo de cabeceo en radianes |
| guiñada | Número | Guiñada en radianes |
| giro | Número | Giro en radianes |

 **Result:**
Cuaternión


---


### fromEulerAngle{#fromEulerAngle}

| Nombre | Descripción |
| --- | --- |
| fromEulerAngle(eulerAngle) | Crea un cuaternión a partir del ángulo de Euler dado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| eulerAngle | Vector3 | Ángulo de Euler en radianes |

 **Result:**
Cuaternión


---


### toMatrix{#toMatrix}

| Nombre | Descripción |
| --- | --- |
| toMatrix() | Convierte la rotación presentada por el cuaternión a una matriz de transformación. |

 **Result:**
Matrix4


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Obtiene la representación del cuaternión en una cadena |

 **Result:**
Cadena


---


### interpolate{#interpolate}

| Nombre | Descripción |
| --- | --- |
| interpolate(t, from, to) | Rellena este cuaternión con el valor interpolado entre los argumentos de cuaternión dados para un t entre from y to. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| t | Número | El coeficiente a interpolar. |
| de | Cuaternión | Cuaternión de origen. |
| a | Cuaternión | Cuaternión de destino. |

 **Result:**
Cuaternión


---



