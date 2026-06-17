---
title: "PushConstant"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Een hulpmiddel om gegevens aan de shader te leveren via een push-constante.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Constructor van de PushConstant |

 **Result:**



---


### write{#write}

| Naam | Beschrijving |
| --- | --- |
| write(mat) | Schrijf de matrix naar de constante |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| mat | FMatrix4 | De matrix om te schrijven |

 **Result:**



---


### write{#write}

| Naam | Beschrijving |
| --- | --- |
| write(n) | Schrijf een int-waarde naar de constante |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### write{#write}

| Naam | Beschrijving |
| --- | --- |
| write(f) | Schrijf een float-waarde naar de constante |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### write{#write}

| Naam | Beschrijving |
| --- | --- |
| write(vec) | Schrijf een 4-componentenvector naar de constante |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Naam | Beschrijving |
| --- | --- |
| write(vec) | Schrijf een 3-componentenvector naar de constante |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Naam | Beschrijving |
| --- | --- |
| write(x, y, z, w) | Schrijf een 4-componentenvector naar de constante |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### commit{#commit}

| Naam | Beschrijving |
| --- | --- |
| commit(stage, commandList) | Commit voorbereide gegevens naar de grafische pijplijn. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| stage | Number | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



