---
title: "BoundingBox"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

Den axeljusterade avgränsningsboxen


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| NULL | Den nulla avgränsningsboxen |
| INFINITE | Den oändliga avgränsningsboxen |

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
| constructor_overload(minimum, maximum) | Initierar en ändlig avgränsningsbox med angivet minsta och största hörn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| minimum | Vector3 | Det minsta hörnet |
| maximum | Vector3 | Det största hörnet |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Initierar en ändlig avgränsningsbox med angivet minsta och största hörn |

 **Result:**



---


### getExtent{#getExtent}

| Namn | Beskrivning |
| --- | --- |
| getExtent() | Hämtar omfattningen av avgränsningsboxen. Värdet på egenskapen är heltalskonstanten BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Namn | Beskrivning |
| --- | --- |
| getMinimum() | Det minsta hörnet av avgränsningsboxen |

 **Result:**



---


### getMaximum{#getMaximum}

| Namn | Beskrivning |
| --- | --- |
| getMaximum() | Det största hörnet av avgränsningsboxen |

 **Result:**



---


### getSize{#getSize}

| Namn | Beskrivning |
| --- | --- |
| getSize() | Storleken på begränsningsboxen |

 **Result:**



---


### getCenter{#getCenter}

| Namn | Beskrivning |
| --- | --- |
| getCenter() | Centrum av begränsningsboxen. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Namn | Beskrivning |
| --- | --- |
| fromGeometry(geometry) | Skapa en begränsningsbox från given geometri |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| geometr | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Hämtar strängrepresentationen av den omgivande lådan. |

 **Result:**
Sträng


---


### hashCode{#hashCode}

| Namn | Beskrivning |
| --- | --- |
| hashCode() | Returnerar hash-koden för detta objekt |

 **Result:**
Nummer


---


### equals{#equals}

| Namn | Beskrivning |
| --- | --- |
| equals(obj) | Bestämmer om två objekt är lika |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| ob | Objekt | null |

 **Result:**
boolean


---



