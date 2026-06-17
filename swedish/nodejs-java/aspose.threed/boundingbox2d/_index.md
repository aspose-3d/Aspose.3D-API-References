---
title: "BoundingBox2D"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Den axeljusterade avgränsningsboxen för Vector2


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
| minimum | Vector2 | Det minsta hörnet |
| maximum | Vector2 | Det största hörnet |

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


### merge{#merge}

| Namn | Beskrivning |
| --- | --- |
| merge(pt) | Sammanfogar den nya boxen med den aktuella avgränsningsboxen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Namn | Beskrivning |
| --- | --- |
| merge(bb) | Sammanfogar den nya boxen med den aktuella avgränsningsboxen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Hämtar strängrepresentationen av den omgivande lådan. |

 **Result:**
Sträng


---



