---
title: "TransformBuilder"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilder används för att bygga en transformmatris genom en kedja av transformationer.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(initial, order) | Skapa en TransformBuilder med initial transformmatris och angiven sammansättningsordning |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| initia | Matrix4 | null |
| ordning | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(order) | Skapa en TransformBuilder med initial identitets‑transformmatris och angiven sammansättningsordning |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| ordning | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Namn | Beskrivning |
| --- | --- |
| getMatrix() | Hämtar eller anger det aktuella matrisvärdet |

 **Result:**



---


### setMatrix{#setMatrix}

| Namn | Beskrivning |
| --- | --- |
| setMatrix(value) | Hämtar eller anger det aktuella matrisvärdet |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Namn | Beskrivning |
| --- | --- |
| getComposeOrder() | Hämtar eller anger kedjans sammansättningsordning. Värdet på egenskapen är heltalskonstanten ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Namn | Beskrivning |
| --- | --- |
| setComposeOrder(value) | Hämtar eller anger kedjans sammansättningsordning. Värdet på egenskapen är heltalskonstanten ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Namn | Beskrivning |
| --- | --- |
| compose(m) | Lägg till eller sätt in argumentet i den interna matrisen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Namn | Beskrivning |
| --- | --- |
| append(m) | Lägg till den nya transformmatrisen till transformkedjan. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Namn | Beskrivning |
| --- | --- |
| prepend(m) | Lägg till i början den nya transformationsmatrisen i transformationskedjan. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Namn | Beskrivning |
| --- | --- |
| rearrange(newX, newY, newZ) | Ordna om layouten för axeln. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| newX | Axel | Axel |
| newY | Axel | Axel |
| newZ | Axel | Axel |

 **Result:**



---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| skala(r) | Kedja en skalningstransformationsmatris med en komponent skalad med s |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Nummer | null |

 **Result:**



---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| scale(x, y, z) | Kedja en skalningstransformationsmatris |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Nummer | null |
|  | Nummer | null |
|  | Nummer | null |

 **Result:**



---


### scale{#scale}

| Namn | Beskrivning |
| --- | --- |
| skala(r) | Kedja en skalningstransform |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Namn | Beskrivning |
| --- | --- |
| rotateDegree(angle, axis) | Kedja en rotationstransform i grader |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | Nummer | Vinkeln att rotera i grader |
| axel | Vector3 | Axeln att rotera kring |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Namn | Beskrivning |
| --- | --- |
| rotateRadian(angle, axis) | Kedja en rotationstransform i radianer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| vinkel | Nummer | Vinkeln att rotera i radianer |
| axel | Vector3 | Axeln att rotera kring |

 **Result:**



---


### rotate{#rotate}

| Namn | Beskrivning |
| --- | --- |
| rotate(q) | Kedja en rotation med en kvaternion |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Kvaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Namn | Beskrivning |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Kedja en rotation med Euler-vinklar i grader |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| grad | Nummer | null |
| grad | Nummer | null |
| grad | Nummer | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Namn | Beskrivning |
| --- | --- |
| rotateEulerRadian(x, y, z) | Kedja en rotation med Euler-vinklar i radianer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Nummer | null |
|  | Nummer | null |
|  | Nummer | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Namn | Beskrivning |
| --- | --- |
| rotateEulerRadian(r) | Kedja en rotation med Euler-vinklar i radianer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Namn | Beskrivning |
| --- | --- |
| translate(tx, ty, tz) | Kedja en translationstransform |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| t | Nummer | null |
| t | Nummer | null |
| t | Nummer | null |

 **Result:**



---


### translate{#translate}

| Namn | Beskrivning |
| --- | --- |
| translate(v) | Kedja en translationstransform |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Namn | Beskrivning |
| --- | --- |
| reset() | Återställ transformen till identitetsmatrisen |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Namn | Beskrivning |
| --- | --- |
| rotateDegree(rot, order) | Lägg till rotation med angiven ordning |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rot | Vector3 | Rotation i grader |
| ordning | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Namn | Beskrivning |
| --- | --- |
| rotateRadian(rot, order) | Lägg till rotation med angiven ordning |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rot | Vector3 | Rotation i radian |
| ordning | RotationOrder | RotationOrder |

 **Result:**



---



