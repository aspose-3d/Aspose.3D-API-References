---
title: "PushConstant"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Una utilidad para proporcionar datos al shader mediante push constant.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor del PushConstant |

 **Result:**



---


### write{#write}

| Nombre | Descripción |
| --- | --- |
| write(mat) | Escribe la matriz en la constante |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| mat | FMatrix4 | La matriz a escribir |

 **Result:**



---


### write{#write}

| Nombre | Descripción |
| --- | --- |
| write(n) | Escribe un valor int a la constante |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Número | null |

 **Result:**



---


### write{#write}

| Nombre | Descripción |
| --- | --- |
| write(f) | Escribe un valor float a la constante |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Número | null |

 **Result:**



---


### write{#write}

| Nombre | Descripción |
| --- | --- |
| write(vec) | Escribe un vector de 4 componentes a la constante |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Nombre | Descripción |
| --- | --- |
| write(vec) | Escribe un vector de 3 componentes a la constante |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Nombre | Descripción |
| --- | --- |
| write(x, y, z, w) | Escribe un vector de 4 componentes a la constante |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
|  | Número | null |
|  | Número | null |
|  | Número | null |
|  | Número | null |

 **Result:**



---


### commit{#commit}

| Nombre | Descripción |
| --- | --- |
| commit(stage, commandList) | Confirma los datos preparados al pipeline gráfico. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| stage | Número | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



