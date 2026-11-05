---
title: "Matrix4"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4-Matrix-Implementierung.


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| m00 | Der m00. |
| m01 | Der m01. |
| m02 | Der m02. |
| m03 | Der m03. |
| m10 | Der m10. |
| m11 | Der m11. |
| m12 | Der m12. |
| m13 | Der m13. |
| m20 | Die m20. |
| m21 | Die m21. |
| m22 | Die m22. |
| m23 | Die m23. |
| m30 | Die m30. |
| m31 | Die m31. |
| m32 | Die m32. |
| m33 | Die m33. |

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
| constructor_overload(r0, r1, r2, r3) | Konstruiert eine Matrix aus 4 Zeilen. |

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
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initialisiert eine neue Instanz der Matrix4-Struktur. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| m00 | Zahl | M00. |
| m01 | Zahl | M01. |
| m02 | Zahl | M02. |
| m03 | Zahl | M03. |
| m10 | Zahl | M10. |
| m11 | Zahl | M11. |
| m12 | Zahl | M12. |
| m13 | Zahl | M13. |
| m20 | Zahl | M20. |
| m21 | Zahl | M21. |
| m22 | Zahl | M22. |
| m23 | Zahl | M23. |
| m30 | Zahl | M30. |
| m31 | Zahl | M31. |
| m32 | Zahl | M32. |
| m33 | Zahl | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(m) | Konstruiere Matrix4 aus einer FMatrix4-Instanz |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Name | Beschreibung |
| --- | --- |
| constructor_overload4(m) | Initialisiert eine neue Instanz der Matrix4-Struktur. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Name | Beschreibung |
| --- | --- |
| getIdentity() | Ruft die Einheitsmatrix ab. Die Einheitsmatrix. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Name | Beschreibung |
| --- | --- |
| getDeterminant() | Ermittelt die Determinante der Matrix. Die Determinante. |

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
| setTRS(translation, rotation, scale) | Initialisiert die Matrix mit translation/rotation/scale |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Translation | Vector3 | Übersetzung. |
| Rotation | Vector3 | Euler-Winkel für Rotation, Felder sind in Grad. |
| Skalierung | Vector3 | Skalierung. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Name | Beschreibung |
| --- | --- |
| toArray() | Konvertiert Matrix in ein Array. |

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
| translate(t) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse verschiebt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| t | Vector3 | Übersetzungs-Offset |

 **Result:**
Matrix4


---


### translate{#translate}

| Name | Beschreibung |
| --- | --- |
| translate(tx, ty, tz) | Erstellt eine Matrix, die entlang der x-Achse, der y-Achse und der z-Achse verschiebt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| tx | Zahl | X-Koordinaten-Offset |
| ty | Zahl | Y-Koordinaten-Offset |
| tz | Zahl | Z-Koordinaten-Offset |

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
| s | Vector3 | Skalierungsfaktoren gelten für die x-Achse, die y-Achse und die z-Achse |

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
| s | Zahl | Skalierungsfaktoren gelten für alle Achsen |

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
| sx | Zahl | Skalierungsfaktoren gelten für die x-Achse |
| sy | Zahl | Skalierungsfaktoren gelten für die y-Achse |
| sz | Zahl | Skalierungsfaktoren gelten für die z-Achse |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Name | Beschreibung |
| --- | --- |
| rotateFromEuler(eul) | Erstelle eine Rotationsmatrix aus dem Euler-Winkel |

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
| rotateFromEuler(rx, ry, rz) | Erstelle eine Rotationsmatrix aus dem Euler-Winkel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rx | Zahl | Rotation um die x-Achse im Bogenmaß |
| ry | Zahl | Rotation um die y-Achse im Bogenmaß |
| rz | Zahl | Rotation um die z-Achse im Bogenmaß |

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
| angle | Zahl | Rotationswinkel in Radiant |
| Achse | Vector3 | Rotationsachse |

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



