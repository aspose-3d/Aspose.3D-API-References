---
title: "PushConstant"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Una utility per fornire dati allo shader tramite push constant.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Costruttore di PushConstant |

 **Result:**



---


### write{#write}

| Nome | Descrizione |
| --- | --- |
| write(mat) | Scrivi la matrice nella costante |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| mat | FMatrix4 | La matrice da scrivere |

 **Result:**



---


### write{#write}

| Nome | Descrizione |
| --- | --- |
| write(n) | Scrivi un valore int nella costante |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Numero | null |

 **Result:**



---


### write{#write}

| Nome | Descrizione |
| --- | --- |
| write(f) | Scrivi un valore float nella costante |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Numero | null |

 **Result:**



---


### write{#write}

| Nome | Descrizione |
| --- | --- |
| write(vec) | Scrivi un vettore a 4 componenti nella costante |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Nome | Descrizione |
| --- | --- |
| write(vec) | Scrivi un vettore a 3 componenti nella costante |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Nome | Descrizione |
| --- | --- |
| write(x, y, z, w) | Scrivi un vettore a 4 componenti nella costante |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | Numero | null |
|  | Numero | null |
|  | Numero | null |
|  | Numero | null |

 **Result:**



---


### commit{#commit}

| Nome | Descrizione |
| --- | --- |
| commit(stage, commandList) | Conferma i dati preparati al pipeline grafico. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| stage | Numero | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



