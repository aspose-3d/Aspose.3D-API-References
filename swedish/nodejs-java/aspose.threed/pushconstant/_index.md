---
title: "PushConstant"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Ett verktyg för att tillhandahålla data till shader genom push constant.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Konstruktor för PushConstant |

 **Result:**



---


### write{#write}

| Namn | Beskrivning |
| --- | --- |
| write(mat) | Skriv matrisen till konstanten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| mat | FMatrix4 | Matrisen att skriva |

 **Result:**



---


### write{#write}

| Namn | Beskrivning |
| --- | --- |
| write(n) | Skriv ett int‑värde till konstanten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Nummer | null |

 **Result:**



---


### write{#write}

| Namn | Beskrivning |
| --- | --- |
| write(f) | Skriv ett float‑värde till konstanten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Nummer | null |

 **Result:**



---


### write{#write}

| Namn | Beskrivning |
| --- | --- |
| write(vec) | Skriv en 4‑komponentsvektor till konstanten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Namn | Beskrivning |
| --- | --- |
| write(vec) | Skriv en 3‑komponentsvektor till konstanten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Namn | Beskrivning |
| --- | --- |
| write(x, y, z, w) | Skriv en 4‑komponentsvektor till konstanten |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
|  | Nummer | null |
|  | Nummer | null |
|  | Nummer | null |
|  | Nummer | null |

 **Result:**



---


### commit{#commit}

| Namn | Beskrivning |
| --- | --- |
| commit(stage, commandList) | Skicka förberedda data till grafikpipeline. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| stage | Nummer | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



