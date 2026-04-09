---
title: TransformBuilder
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

Der **TransformBuilder** wird verwendet, um eine Transformationsmatrix durch eine Kette von Transformationen zu erstellen.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(initial, order) | Erstellt einen TransformBuilder mit einer initialen Transformationsmatrix und der angegebenen Zusammensetzungsreihenfolge. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| initia | Matrix4 | null |
| Reihenfolge | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(order) | Erstellt einen TransformBuilder mit einer initialen Identitäts-Transformationsmatrix und der angegebenen Zusammensetzungsreihenfolge. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Reihenfolge | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Name | Beschreibung |
| --- | --- |
| getMatrix() | Liest oder setzt den aktuellen Matrixwert. |

 **Result:**



---


### setMatrix{#setMatrix}

| Name | Beschreibung |
| --- | --- |
| setMatrix(value) | Liest oder setzt den aktuellen Matrixwert. |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Name | Beschreibung |
| --- | --- |
| getComposeOrder() | Liest oder setzt die Ketten‑Zusammensetzungsreihenfolge. Der Wert der Eigenschaft ist die Ganzzahlkonstante ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Name | Beschreibung |
| --- | --- |
| setComposeOrder(value) | Liest oder setzt die Ketten‑Zusammensetzungsreihenfolge. Der Wert der Eigenschaft ist die Ganzzahlkonstante ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Name | Beschreibung |
| --- | --- |
| compose(m) | Füge das Argument zur internen Matrix hinzu oder stelle es voran. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Name | Beschreibung |
| --- | --- |
| append(m) | Füge die neue Transformationsmatrix zur Transformationskette hinzu. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Name | Beschreibung |
| --- | --- |
| prepend(m) | Stelle die neue Transformationsmatrix an den Anfang der Transformationskette. |

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
| scale(s) | Verkettet eine Skalierungs-Transformationsmatrix mit einer Komponente, die um s skaliert wird. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(x, y, z) | Verkettet eine Skalierungs-Transformationsmatrix. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Name | Beschreibung |
| --- | --- |
| scale(s) | Verkettet eine Skalierungstransformation. |

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
| angle | Number | Der Winkel zum Rotieren in Grad |
| axis | Vector3 | Die Achse zum Drehen |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Name | Beschreibung |
| --- | --- |
| rotateRadian(angle, axis) | Verkette eine Rotations-Transformation in Bogenmaß |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| angle | Number | Der Winkel zum Rotieren in Bogenmaß |
| axis | Vector3 | Die Achse zum Drehen |

 **Result:**



---


### rotate{#rotate}

| Name | Beschreibung |
| --- | --- |
| rotate(q) | Verkette eine Rotation mittels eines Quaternion |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Quaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Name | Beschreibung |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Verkette eine Rotation mittels Euler-Winkeln in Grad |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| deg | Number | null |
| deg | Number | null |
| deg | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Name | Beschreibung |
| --- | --- |
| rotateEulerRadian(x, y, z) | Verkette eine Rotation mittels Euler-Winkeln in Bogenmaß |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Name | Beschreibung |
| --- | --- |
| rotateEulerRadian(r) | Verkette eine Rotation mittels Euler-Winkeln in Bogenmaß |

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
| t | Number | null |
| t | Number | null |
| t | Number | null |

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
| reset() | Setze die Transformation auf die Identitätsmatrix zurück |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Name | Beschreibung |
| --- | --- |
| rotateDegree(rot, order) | Rotation mit angegebener Reihenfolge anhängen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rot | Vector3 | Rotation in Grad |
| Reihenfolge | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Name | Beschreibung |
| --- | --- |
| rotateRadian(rot, order) | Rotation mit angegebener Reihenfolge anhängen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rot | Vector3 | Rotation im Bogenmaß |
| Reihenfolge | RotationOrder | RotationOrder |

 **Result:**



---



