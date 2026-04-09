---
title: Matrix4
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4-Matrix-Implementierung.


## Properties

| Name | Beschreibung |
| --- | --- |
| m00 | Das m00. |
| m01 | Das m01. |
| m02 | Das m02. |
| m03 | Das m03. |
| m10 | Das m10. |
| m11 | Das m11. |
| m12 | Das m12. |
| m13 | Das m13. |
| m20 | Das m20. |
| m21 | Das m21. |
| m22 | Das m22. |
| m23 | Das m23. |
| m30 | Das m30. |
| m31 | Das m31. |
| m32 | Das m32. |
| m33 | Das m33. |

## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(r0, r1, r2, r3) | Konstruiert die Matrix aus 4 Zeilen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initialisiert eine neue Instanz der Matrix4‑Struktur. |

 **Parameters:**

| Name | Typ | Beschreibung |
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

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(m) | Erstellt Matrix4 aus einer FMatrix4‑Instanz |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Name | Beschreibung |
| --- | --- |
| constructor_overload4(m) | Initialisiert eine neue Instanz der Matrix4‑Struktur. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Name | Beschreibung |
| --- | --- |
| getIdentity() | Gibt die Einheitsmatrix zurück. Die Einheitsmatrix. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Name | Beschreibung |
| --- | --- |
| getDeterminant() | Gibt die Determinante der Matrix zurück. Die Determinante. |

 **Result:**



---


### concatenate{#concatenate}

| Name | Beschreibung |
| --- | --- |
| concatenate(m2) | Verkettet die beiden Matrizen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| Name | Beschreibung |
| --- | --- |
| transpose() | Transponiert diese Instanz. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Name | Beschreibung |
| --- | --- |
| normalize() | Normalisiert diese Instanz. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Name | Beschreibung |
| --- | --- |
| inverse() | Invertiert diese Instanz. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Name | Beschreibung |
| --- | --- |
| setTRS(translation, rotation, scale) | Initialisiert die Matrix mit Translation/Rotation/Skalierung |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Übersetzung | Vector3 | Übersetzung. |
| Rotation | Vector3 | Euler-Winkel für die Rotation, die Felder sind in Grad. |
| Skalierung | Vector3 | Skalierung. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Name | Beschreibung |
| --- | --- |
| toArray() | Konvertiert die Matrix in ein Array. |

 **Result:**
Number[]


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Gibt einen java.lang.String zurück, der die aktuelle Matrix4 darstellt. |

 **Result:**
String


---


### translate{#translate}

| Name | Beschreibung |
| --- | --- |
| translate(t) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse übersetzt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| t | Vector3 | Versetze Offset |

 **Result:**
Matrix4


---


### translate{#translate}

| Name | Beschreibung |
| --- | --- |
| translate(tx, ty, tz) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse übersetzt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| tx | Number | X-Koordinaten-Offset |
| ty | Number | Y-Koordinaten-Offset |
| tz | Number | Z-Koordinaten-Offset |

 **Result:**
Matrix4


---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(s) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| s | Vector3 | Skalierungsfaktoren gelten für die X-Achse, die Y-Achse und die Z-Achse |

 **Result:**
Matrix4


---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(s) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| s | Number | Skalierungsfaktoren gelten für alle Achsen |

 **Result:**
Matrix4


---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(sx, sy, sz) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse skaliert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| sx | Number | Skalierungsfaktoren gelten für die X-Achse |
| sy | Number | Skalierungsfaktoren gelten für die Y-Achse |
| sz | Number | Skalierungsfaktoren gelten für die Z-Achse |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Name | Beschreibung |
| --- | --- |
| rotateFromEuler(eul) | Erstelle eine Rotationsmatrix aus einem Euler-Winkel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| eul | Vector3 | Rotation im Bogenmaß |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Name | Beschreibung |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Erstelle eine Rotationsmatrix aus einem Euler-Winkel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rx | Number | Rotation um die x-Achse im Bogenmaß |
| ry | Number | Rotation um die y-Achse im Bogenmaß |
| rz | Number | Rotation um die z-Achse im Bogenmaß |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Name | Beschreibung |
| --- | --- |
| rotate(angle, axis) | Erstelle eine Rotationsmatrix anhand des Rotationswinkels und der Achse |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| angle | Number | Drehwinkel im Bogenmaß |
| axis | Vector3 | Rotationsachse |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Name | Beschreibung |
| --- | --- |
| rotate(q) | Erstelle eine Rotationsmatrix aus einem Quaternion |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| q | Quaternion | Rotationsquaternion |

 **Result:**
Matrix4


---



