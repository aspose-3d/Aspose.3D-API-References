---
title: PlyFormat
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

Le format PLY.  @hideconstructor


## Méthodes

### getVersion{#getVersion}

| Nom | Description |
| --- | --- |
| getVersion() | Obtient la version du format de fichier |

 **Result:**



---


### getExtension{#getExtension}

| Nom | Description |
| --- | --- |
| getExtension() | Obtient le nom d'extension de ce type. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nom | Description |
| --- | --- |
| getExtensions() | Obtient les noms d'extension de ce type. |

 **Result:**



---


### getContentType{#getContentType}

| Nom | Description |
| --- | --- |
| getContentType() | Obtient le type de contenu du format de fichier. La valeur de la propriété est la constante entière FileContentType. |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| Nom | Description |
| --- | --- |
| getFileFormatType() | Obtient le type de format de fichier |

 **Result:**



---


### encode{#encode}

| Nom | Description |
| --- | --- |
| encode(entity, fileName) | Encode l'entité et enregistre le résultat dans un fichier externe. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| entity | Entity | L'entité à encoder |
| fileName | String | Le fichier d'écriture |

 **Result:**



---


### encode{#encode}

| Nom | Description |
| --- | --- |
| encode(entity, fileName, opt) | Encode l'entité et enregistre le résultat dans un fichier externe. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| entity | Entity | L'entité à encoder |
| fileName | String | Le fichier d'écriture |
| opt | PlySaveOptions | Enregistrer les options |

 **Result:**



---


### decode{#decode}

| Nom | Description |
| --- | --- |
| decode(fileName) | Décode un nuage de points ou un maillage depuis le flux spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Le flux d'entrée |

 **Result:**
Geometry


---


### decode{#decode}

| Nom | Description |
| --- | --- |
| decode(fileName, opt) | Décode un nuage de points ou un maillage depuis le flux spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Le flux d'entrée |
| opt | PlyLoadOptions | L'option de chargement du format PLY |

 **Result:**
Geometry


---


### createLoadOptions{#createLoadOptions}

| Nom | Description |
| --- | --- |
| createLoadOptions() | Créer des options de chargement par défaut pour ce format de fichier |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nom | Description |
| --- | --- |
| createSaveOptions() | Créer des options d'enregistrement par défaut pour ce format de fichier |

 **Result:**
SaveOptions


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Formats en chaîne |

 **Result:**
String


---



