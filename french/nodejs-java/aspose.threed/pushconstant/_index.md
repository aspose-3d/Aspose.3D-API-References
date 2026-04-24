---
title: PushConstant
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

Un utilitaire pour fournir des données au shader via une constante push.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de PushConstant |

 **Result:**



---


### write{#write}

| Nom | Description |
| --- | --- |
| write(mat) | Écrire la matrice dans la constante |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mat | FMatrix4 | La matrice à écrire |

 **Result:**



---


### write{#write}

| Nom | Description |
| --- | --- |
| write(n) | Écrire une valeur int dans la constante |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### write{#write}

| Nom | Description |
| --- | --- |
| write(f) | Écrire une valeur float dans la constante |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### write{#write}

| Nom | Description |
| --- | --- |
| write(vec) | Écrire un vecteur à 4 composantes dans la constante |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| Nom | Description |
| --- | --- |
| write(vec) | Écrire un vecteur à 3 composantes dans la constante |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| Nom | Description |
| --- | --- |
| write(x, y, z, w) | Écrire un vecteur à 4 composantes dans la constante |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### commit{#commit}

| Nom | Description |
| --- | --- |
| commit(stage, commandList) | Valide les données préparées dans le pipeline graphique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| étape | Number | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



