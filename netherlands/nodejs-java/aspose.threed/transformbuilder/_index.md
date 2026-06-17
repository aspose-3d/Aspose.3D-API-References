---
title: "TransformBuilder"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

De TransformBuilder wordt gebruikt om een transformatie‑matrix op te bouwen via een keten van transformaties.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(initial, order) | Construeer een TransformBuilder met een initiële transformatiematrix en een gespecificeerde compose-volgorde |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| initia | Matrix4 | null |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(order) | Construeer een TransformBuilder met een initiële identiteits-transformatiematrix en een gespecificeerde compose-volgorde |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Naam | Beschrijving |
| --- | --- |
| getMatrix() | Haalt de huidige matrixwaarde op of stelt deze in |

 **Result:**



---


### setMatrix{#setMatrix}

| Naam | Beschrijving |
| --- | --- |
| setMatrix(value) | Haalt de huidige matrixwaarde op of stelt deze in |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Naam | Beschrijving |
| --- | --- |
| getComposeOrder() | Haalt de compose-volgorde van de keten op of stelt deze in. De waarde van de eigenschap is een integer-constante ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Naam | Beschrijving |
| --- | --- |
| setComposeOrder(value) | Haalt de compose-volgorde van de keten op of stelt deze in. De waarde van de eigenschap is een integer-constante ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Naam | Beschrijving |
| --- | --- |
| compose(m) | Voeg het argument toe aan het einde of het begin van de interne matrix. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Naam | Beschrijving |
| --- | --- |
| append(m) | Voeg de nieuwe transformatiematrix toe aan de transformketen. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Naam | Beschrijving |
| --- | --- |
| prepend(m) | Voeg de nieuwe transformatie-matrix toe aan de transformatie-keten. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Naam | Beschrijving |
| --- | --- |
| rearrange(newX, newY, newZ) | Herschik de lay-out van de as. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| newX | As | As |
| newY | As | As |
| newZ | As | As |

 **Result:**



---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(s) | Koppel een schaaltransformatie-matrix met een component geschaald met s |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(x, y, z) | Koppel een schaaltransformatie-matrix |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Naam | Beschrijving |
| --- | --- |
| scale(s) | Koppel een schaaltransformatie |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Naam | Beschrijving |
| --- | --- |
| rotateDegree(angle, axis) | Koppel een rotatie-transformatie in graden |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| hoek | Number | De hoek om te roteren in graden |
| as | Vector3 | De as om te roteren |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Naam | Beschrijving |
| --- | --- |
| rotateRadian(angle, axis) | Koppel een rotatie-transformatie in radialen |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| hoek | Number | De hoek om te roteren in radialen |
| as | Vector3 | De as om te roteren |

 **Result:**



---


### rotate{#rotate}

| Naam | Beschrijving |
| --- | --- |
| rotate(q) | Koppel een rotatie met een quaternion |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Quaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Naam | Beschrijving |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Koppel een rotatie met Euler-hoeken in graden |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| deg | Number | null |
| deg | Number | null |
| deg | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Naam | Beschrijving |
| --- | --- |
| rotateEulerRadian(x, y, z) | Koppel een rotatie met Euler-hoeken in radialen |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Naam | Beschrijving |
| --- | --- |
| rotateEulerRadian(r) | Koppel een rotatie met Euler-hoeken in radialen |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Naam | Beschrijving |
| --- | --- |
| translate(tx, ty, tz) | Koppel een translatie-transformatie |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**



---


### translate{#translate}

| Naam | Beschrijving |
| --- | --- |
| translate(v) | Koppel een translatie-transformatie |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Naam | Beschrijving |
| --- | --- |
| reset() | Reset de transformatie naar de identiteitsmatrix |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Naam | Beschrijving |
| --- | --- |
| rotateDegree(rot, order) | Voeg rotatie toe met gespecificeerde volgorde |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rot | Vector3 | Rotatie in graden |
| order | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Naam | Beschrijving |
| --- | --- |
| rotateRadian(rot, order) | Voeg rotatie toe met gespecificeerde volgorde |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rot | Vector3 | Rotatie in radialen |
| order | RotationOrder | RotationOrder |

 **Result:**



---



