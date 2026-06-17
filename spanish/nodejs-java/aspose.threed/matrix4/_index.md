---
title: "Matrix4"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

Implementación de matriz 4x4.


## Propiedades

| Nombre | Descripción |
| --- | --- |
| m00 | El m00. |
| m01 | El m01. |
| m02 | El m02. |
| m03 | El m03. |
| m10 | El m10. |
| m11 | El m11. |
| m12 | El m12. |
| m13 | El m13. |
| m20 | El m20. |
| m21 | El m21. |
| m22 | El m22. |
| m23 | El m23. |
| m30 | El m30. |
| m31 | El m31. |
| m32 | El m32. |
| m33 | El m33. |

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
| constructor_overload(r0, r1, r2, r3) | Construye la matriz a partir de 4 filas. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Inicializa una nueva instancia de la estructura Matrix4. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| m00 | Número | M00. |
| m01 | Número | M01. |
| m02 | Número | M02. |
| m03 | Número | M03. |
| m10 | Número | M10. |
| m11 | Número | M11. |
| m12 | Número | M12. |
| m13 | Número | M13. |
| m20 | Número | M20. |
| m21 | Número | M21. |
| m22 | Número | M22. |
| m23 | Número | M23. |
| m30 | Número | M30. |
| m31 | Número | M31. |
| m32 | Número | M32. |
| m33 | Número | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nombre | Descripción |
| --- | --- |
| constructor_overload3(m) | Construye Matrix4 a partir de una instancia de FMatrix4. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nombre | Descripción |
| --- | --- |
| constructor_overload4(m) | Inicializa una nueva instancia de la estructura Matrix4. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Nombre | Descripción |
| --- | --- |
| getIdentity() | Obtiene la matriz identidad. La identidad. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Nombre | Descripción |
| --- | --- |
| getDeterminant() | Obtiene el determinante de la matriz. El determinante. |

 **Result:**



---


### concatenate{#concatenate}

| Nombre | Descripción |
| --- | --- |
| concatenate(m2) | Concatena las dos matrices |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| Nombre | Descripción |
| --- | --- |
| transpose() | Transpone esta instancia. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Nombre | Descripción |
| --- | --- |
| normalize() | Normaliza esta instancia. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Nombre | Descripción |
| --- | --- |
| inverse() | Invierte esta instancia. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Nombre | Descripción |
| --- | --- |
| setTRS(translation, rotation, scale) | Inicializa la matriz con traducción/rotación/escala |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| traducción | Vector3 | Traducción. |
| rotación | Vector3 | Ángulos de Euler para rotación, los campos están en grados. |
| escala | Vector3 | Escala. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Nombre | Descripción |
| --- | --- |
| toArray() | Convierte la matriz a un arreglo. |

 **Result:**
Number[]


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Devuelve un java.lang.String que representa el actual Matrix4. |

 **Result:**
Cadena


---


### translate{#translate}

| Nombre | Descripción |
| --- | --- |
| translate(t) | Crea una matriz que traduce a lo largo del eje x, el eje y y el eje z |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| t | Vector3 | Desplazamiento de traducción |

 **Result:**
Matrix4


---


### translate{#translate}

| Nombre | Descripción |
| --- | --- |
| translate(tx, ty, tz) | Crea una matriz que traduce a lo largo del eje x, el eje y y el eje z |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| tx | Número | Desplazamiento de coordenada X |
| ty | Número | Desplazamiento de la coordenada Y |
| tz | Número | Desplazamiento de la coordenada Z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| escala(s) | Crea una matriz que escala a lo largo del eje x, el eje y y el eje z. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| s | Vector3 | Las fábricas de escalado se aplican al eje x, al eje y y al eje z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| escala(s) | Crea una matriz que escala a lo largo del eje x, el eje y y el eje z. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| s | Número | Las fábricas de escalado se aplican a todos los ejes |

 **Result:**
Matrix4


---


### scale{#scale}

| Nombre | Descripción |
| --- | --- |
| scale(sx, sy, sz) | Crea una matriz que escala a lo largo del eje x, el eje y y el eje z. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| sx | Número | Las fábricas de escalado se aplican al eje x |
| sy | Número | Las fábricas de escalado se aplican al eje y |
| sz | Número | Las fábricas de escalado se aplican al eje z |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nombre | Descripción |
| --- | --- |
| rotateFromEuler(eul) | Crea una matriz de rotación a partir del ángulo de Euler |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| eul | Vector3 | Rotación en radianes |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nombre | Descripción |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Crea una matriz de rotación a partir del ángulo de Euler |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rx | Número | Rotación en el eje x en radianes |
| ry | Número | Rotación en el eje y en radianes |
| rz | Número | Rotación en el eje z en radianes |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nombre | Descripción |
| --- | --- |
| rotate(angle, axis) | Crear una matriz de rotación mediante el ángulo de rotación y el eje |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| ángulo | Número | Ángulo de rotación en radianes |
| eje | Vector3 | Eje de rotación |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nombre | Descripción |
| --- | --- |
| rotate(q) | Crear una matriz de rotación a partir de un cuaternión |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| q | Cuaternión | Cuaternión de rotación |

 **Result:**
Matrix4


---



