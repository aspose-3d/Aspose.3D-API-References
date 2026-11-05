---
title: "PushConstant"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Ein Hilfswerkzeug, um Daten über Push-Konstanten an den Shader zu übermitteln.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Konstruktor von PushConstant. |

 **Result:**



---


### write{#write}

| Name | Beschreibung |
| --- | --- |
| write(mat) | Schreibt die Matrix in die Konstante. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| mat | FMatrix4 | Die zu schreibende Matrix. |

 **Result:**



---


### write{#write}

| Name | Beschreibung |
| --- | --- |
| write(n) | Schreibe einen int-Wert in die Konstante. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Zahl | null |

 **Result:**



---


### write{#write}

| Name | Beschreibung |
| --- | --- |
| write(f) | Schreibe einen float-Wert in die Konstante. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Zahl | null |

 **Result:**



---


### write{#write}

| Name | Beschreibung |
| --- | --- |
| write(vec) | Schreibe einen 4-Komponenten-Vektor in die Konstante. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Name | Beschreibung |
| --- | --- |
| write(vec) | Schreibe einen 3-Komponenten-Vektor in die Konstante. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Name | Beschreibung |
| --- | --- |
| write(x, y, z, w) | Schreibe einen 4-Komponenten-Vektor in die Konstante. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
|  | Zahl | null |
|  | Zahl | null |
|  | Zahl | null |
|  | Zahl | null |

 **Result:**



---


### commit{#commit}

| Name | Beschreibung |
| --- | --- |
| commit(stage, commandList) | Übertrage vorbereitete Daten an die Grafikpipeline. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| stage | Zahl | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



