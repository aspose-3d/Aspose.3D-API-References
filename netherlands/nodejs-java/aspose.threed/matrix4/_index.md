---
title: "Matrix4"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

Implementatie van een 4x4-matrix.


## Properties

| Naam | Beschrijving |
| --- | --- |
| m00 | De m00. |
| m01 | De m01. |
| m02 | De m02. |
| m03 | De m03. |
| m10 | De m10. |
| m11 | De m11. |
| m12 | De m12. |
| m13 | De m13. |
| m20 | De m20. |
| m21 | De m21. |
| m22 | De m22. |
| m23 | De m23. |
| m30 | De m30. |
| m31 | De m31. |
| m32 | De m32. |
| m33 | De m33. |

## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(r0, r1, r2, r3) | Construeert matrix uit 4 rijen. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initialiseert een nieuw exemplaar van de Matrix4-structuur. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| m00 | Number | M00. |
| m01 | Number | M01. |
| m02 | Number | M02. |
| m03 | Number | M03. |
| m10 | Number | M10. |
| m11 | Number | M11. |
| m12 | Number | M12. |
| m13 | Number | M13. |
| m20 | Number | M20. |
| m21 | Number | M21. |
| m22 | Number | M22. |
| m23 | Number | M23. |
| m30 | Number | M30. |
| m31 | Number | M31. |
| m32 | Number | M32. |
| m33 | Number | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload3(m) | Construeer Matrix4 vanuit een FMatrix4-exemplaar. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload4(m) | Initialiseert een nieuw exemplaar van de Matrix4-structuur. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Naam | Beschrijving |
| --- | --- |
| getIdentity() | Haalt de identiteitsmatrix op. De identiteit. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Naam | Beschrijving |
| --- | --- |
| getDeterminant() | Haalt de determinant van de matrix op. De determinant. |

 **Result:**



---


### concatenate{#concatenate}

| Naam | Beschrijving |
| --- | --- |
| concatenate(m2) | Concateneert de twee matrices. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| Naam | Beschrijving |
| --- | --- |
| transpose() | Transponeert deze instantie. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Naam | Beschrijving |
| --- | --- |
| normalize() | Normaliseert deze instantie. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Naam | Beschrijving |
| --- | --- |
| inverse() | Inverseert deze instantie. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Naam | Beschrijving |
| --- | --- |
| setTRS(translation, rotation, scale) | Initialiseert de matrix met translatie/rotatie/schaal |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| translatie | Vector3 | Translatie. |
| rotatie | Vector3 | Eulerhoeken voor rotatie, velden zijn in graden. |
| schaal | Vector3 | Schaal. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Naam | Beschrijving |
| --- | --- |
| toArray() | Converteert matrix naar array. |

 **Result:**
Number[]


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Retourneert een java.lang.String die de huidige Matrix4 vertegenwoordigt. |

 **Result:**
String


---


### translate{#translate}

| Naam | Beschrijving |
| --- | --- |
| translate(t) | Creëert een matrix die langs de x-as, de y-as en de z-as verplaatst. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| t | Vector3 | Vertaalverschuiving |

 **Result:**
Matrix4


---


### translate{#translate}

| Naam | Beschrijving |
| --- | --- |
| translate(tx, ty, tz) | Creëert een matrix die langs de x-as, de y-as en de z-as verplaatst. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| tx | Number | X-coördinaatverschuiving |
| ty | Number | Y-coördinaat offset |
| tz | Number | Z-coördinaat offset |

 **Result:**
Matrix4


---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(s) | Maakt een matrix die schaalt langs de x-as, de y-as en de z-as. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| s | Vector3 | Scaling factories is van toepassing op de x-as, de y-as en de z-as |

 **Result:**
Matrix4


---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(s) | Maakt een matrix die schaalt langs de x-as, de y-as en de z-as. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| s | Number | Scaling factories is van toepassing op alle assen |

 **Result:**
Matrix4


---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(sx, sy, sz) | Maakt een matrix die schaalt langs de x-as, de y-as en de z-as. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| sx | Number | Scaling factories is van toepassing op de x-as |
| sy | Number | Scaling factories is van toepassing op de y-as |
| sz | Number | Scaling factories is van toepassing op de z-as |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Naam | Beschrijving |
| --- | --- |
| rotateFromEuler(eul) | Maak een rotatiematrix van een Euler-hoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eul | Vector3 | Rotatie in radialen |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Naam | Beschrijving |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Maak een rotatiematrix van een Euler-hoek |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rx | Number | Rotatie in x-as in radialen |
| ry | Number | Rotatie in y-as in radialen |
| rz | Number | Rotatie in z-as in radialen |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Naam | Beschrijving |
| --- | --- |
| rotate(angle, axis) | Maak een rotatiematrix aan met rotatiehoek en as |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| hoek | Number | Rotatiehoek in radialen |
| as | Vector3 | Rotatieas |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Naam | Beschrijving |
| --- | --- |
| rotate(q) | Maak een rotatiematrix aan vanuit een quaternion |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| q | Quaternion | Rotatiequaternion |

 **Result:**
Matrix4


---



