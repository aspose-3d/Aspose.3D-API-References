---
title: "Matrix4"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4-matrisimplementation.


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| m00 | m00‑värdet. |
| m01 | m01‑värdet. |
| m02 | m02‑värdet. |
| m03 | m03‑värdet. |
| m10 | m10‑värdet. |
| m11 | m11‑värdet. |
| m12 | Den m12. |
| m13 | Den m13. |
| m20 | Den m20. |
| m21 | Den m21. |
| m22 | Den m22. |
| m23 | Den m23. |
| m30 | Den m30. |
| m31 | Den m31. |
| m32 | Den m32. |
| m33 | Den m33. |

## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(r0, r1, r2, r3) | Skapar en matris från 4 rader. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initierar en ny instans av Matrix4-strukturen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| m00 | Nummer | M00. |
| m01 | Nummer | M01. |
| m02 | Nummer | M02. |
| m03 | Nummer | M03. |
| m10 | Nummer | M10. |
| m11 | Nummer | M11. |
| m12 | Nummer | M12. |
| m13 | Nummer | M13. |
| m20 | Nummer | M20. |
| m21 | Nummer | M21. |
| m22 | Nummer | M22. |
| m23 | Nummer | M23. |
| m30 | Nummer | M30. |
| m31 | Nummer | M31. |
| m32 | Nummer | M32. |
| m33 | Nummer | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload3(m) | Skapa Matrix4 från en FMatrix4-instans |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload4(m) | Initierar en ny instans av Matrix4-strukturen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Namn | Beskrivning |
| --- | --- |
| getIdentity() | Hämtar identitetsmatrisen. Identiteten. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Namn | Beskrivning |
| --- | --- |
| getDeterminant() | Hämtar determinanten för matrisen. Determinanten. |

 **Result:**



---


### concatenate{#concatenate}

| Namn | Beskrivning |
| --- | --- |
| concatenate(m2) | Konkatenar de två matriserna |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| Namn | Beskrivning |
| --- | --- |
| transpose() | Transponerar den här instansen. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Namn | Beskrivning |
| --- | --- |
| normalize() | Normaliserar detta objekt. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Namn | Beskrivning |
| --- | --- |
| inverse() | Inverterar detta objekt. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Namn | Beskrivning |
| --- | --- |
| setTRS(translation, rotation, scale) | Initierar matrisen med translation/rotation/scale |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| translation | Vector3 | Translation. |
| rotation | Vector3 | Eulervinklar för rotation, fälten är i grader. |
| scale | Vector3 | Scale. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Namn | Beskrivning |
| --- | --- |
| toArray() | Konverterar matris till array. |

 **Result:**
Number[]


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Returnerar en java.lang.String som representerar den aktuella Matrix4. |

 **Result:**
Sträng


---


### translate{#translate}

| Namn | Beskrivning |
| --- | --- |
| translate(t) | Skapar en matris som translaterar längs x-axeln, y-axeln och z-axeln |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| t | Vector3 | Translateringsoffset |

 **Result:**
Matrix4


---


### translate{#translate}

| Namn | Beskrivning |
| --- | --- |
| translate(tx, ty, tz) | Skapar en matris som translaterar längs x-axeln, y-axeln och z-axeln |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| tx | Nummer | X-koordinatförskjutning |
| ty | Nummer | Y-koordinatens förskjutning |
| tz | Nummer | Z-koordinatens förskjutning |

 **Result:**
Matrix4


---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| skala(r) | Skapar en matris som skalar längs x-axeln, y-axeln och z-axeln. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| s | Vector3 | Skalningsfabriker gäller för x-axeln, y-axeln och z-axeln |

 **Result:**
Matrix4


---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| skala(r) | Skapar en matris som skalar längs x-axeln, y-axeln och z-axeln. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| s | Nummer | Skalningsfabriker gäller för alla axlar |

 **Result:**
Matrix4


---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| scale(sx, sy, sz) | Skapar en matris som skalar längs x-axeln, y-axeln och z-axeln. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| sx | Nummer | Skalningsfabriker gäller för x-axeln |
| sy | Nummer | Skalningsfabriker gäller för y-axeln |
| sz | Nummer | Skalningsfabriker gäller för z-axeln |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Namn | Beskrivning |
| --- | --- |
| rotateFromEuler(eul) | Skapa en rotationsmatris från Euler-vinkel |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| eul | Vector3 | Rotation i radian |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Namn | Beskrivning |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Skapa en rotationsmatris från Euler-vinkel |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rx | Nummer | Rotation i x-axeln i radian |
| ry | Nummer | Rotation i y-axeln i radian |
| rz | Nummer | Rotation kring z-axeln i radian |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Namn | Beskrivning |
| --- | --- |
| rotate(angle, axis) | Skapa en rotationsmatris med rotationsvinkel och axel |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | Nummer | Rotationsvinkel i radian |
| axel | Vector3 | Rotationsaxel |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Namn | Beskrivning |
| --- | --- |
| rotate(q) | Skapa en rotationsmatris från en kvaternion |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| q | Kvaternion | Rotationskvaternion |

 **Result:**
Matrix4


---



