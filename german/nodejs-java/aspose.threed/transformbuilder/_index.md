---
title: "TransformBuilder"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

Der TransformBuilder wird verwendet, um eine Transformationsmatrix durch eine Kette von Transformationen zu erstellen.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(initial, order) | Erstelle einen TransformBuilder mit einer Anfangstransformationsmatrix und dem angegebenen ComposeOrder |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| initia | Matrix4 | null |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(order) | Erstelle einen TransformBuilder mit einer anfänglichen Identitätstransformationsmatrix und dem angegebenen ComposeOrder |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Name | Beschreibung |
| --- | --- |
| getMatrix() | Liest oder setzt den aktuellen Matrixwert |

 **Result:**



---


### setMatrix{#setMatrix}

| Name | Beschreibung |
| --- | --- |
| setMatrix(value) | Liest oder setzt den aktuellen Matrixwert |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Name | Beschreibung |
| --- | --- |
| getComposeOrder() | Liest oder setzt die Ketten‑Compose‑Reihenfolge. Der Wert der Eigenschaft ist die Ganzzahlkonstante ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Name | Beschreibung |
| --- | --- |
| setComposeOrder(value) | Liest oder setzt die Ketten‑Compose‑Reihenfolge. Der Wert der Eigenschaft ist die Ganzzahlkonstante ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Name | Beschreibung |
| --- | --- |
| compose(m) | Hänge das Argument an die interne Matrix an oder füge es davor ein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Name | Beschreibung |
| --- | --- |
| append(m) | Hänge die neue Transformationsmatrix an die Transformationskette an. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Name | Beschreibung |
| --- | --- |
| prepend(m) | Füge die neue Transformationsmatrix am Anfang der Transformationskette ein. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Name | Beschreibung |
| --- | --- |
| rearrange(newX, newY, newZ) | Ordne das Layout der Achse neu. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| newX | Achse | Achse |
| newY | Achse | Achse |
| newZ | Achse | Achse |

 **Result:**



---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(s) | Verkette eine Skalierungstransformationsmatrix mit einer Komponente, die um s skaliert ist. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Zahl | null |

 **Result:**



---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(x, y, z) | Verkette eine Skalierungs-Transformationsmatrix |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Zahl | null |
|  | Zahl | null |
|  | Zahl | null |

 **Result:**



---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(s) | Verkette eine Skalierungstransformation |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Name | Beschreibung |
| --- | --- |
| rotateDegree(angle, axis) | Verkette eine Rotations-Transformation in Grad |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| angle | Zahl | Der Winkel zum Rotieren in Grad |
| Achse | Vector3 | Die Achse zum Rotieren |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Name | Beschreibung |
| --- | --- |
| rotateRadian(angle, axis) | Verkette eine Rotations-Transformation in Bogenmaß |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| angle | Zahl | Der Winkel zum Rotieren im Bogenmaß |
| Achse | Vector3 | Die Achse zum Rotieren |

 **Result:**



---


### rotate{#rotate}

| Name | Beschreibung |
| --- | --- |
| rotate(q) | Verkette eine Rotation mittels Quaternion |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Quaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Name | Beschreibung |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Verkette eine Rotation durch Euler-Winkel in Grad |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Grad | Zahl | null |
| Grad | Zahl | null |
| Grad | Zahl | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Name | Beschreibung |
| --- | --- |
| rotateEulerRadian(x, y, z) | Verkette eine Rotation durch Euler-Winkel im Bogenmaß |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Zahl | null |
|  | Zahl | null |
|  | Zahl | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Name | Beschreibung |
| --- | --- |
| rotateEulerRadian(r) | Verkette eine Rotation durch Euler-Winkel im Bogenmaß |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Name | Beschreibung |
| --- | --- |
| translate(tx, ty, tz) | Verkette eine Translations-Transformation |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| t | Zahl | null |
| t | Zahl | null |
| t | Zahl | null |

 **Result:**



---


### translate{#translate}

| Name | Beschreibung |
| --- | --- |
| translate(v) | Verkette eine Translations-Transformation |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Name | Beschreibung |
| --- | --- |
| reset() | Setze die Transformation zurück zur Einheitsmatrix |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Name | Beschreibung |
| --- | --- |
| rotateDegree(rot, order) | Füge Rotation mit angegebener Reihenfolge hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rot | Vector3 | Rotation in Grad |
| order | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Name | Beschreibung |
| --- | --- |
| rotateRadian(rot, order) | Füge Rotation mit angegebener Reihenfolge hinzu |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rot | Vector3 | Rotation im Bogenmaß |
| order | RotationOrder | RotationOrder |

 **Result:**



---



