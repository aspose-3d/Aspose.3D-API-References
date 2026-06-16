---
title: "DracoFormat"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Format Google Draco  @hideconstructor


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
| getExtension() | Obtient le nom de l'extension de ce type. |

 **Result:**



---


### getExtensions{#getExtensions}

| Nom | Description |
| --- | --- |
| getExtensions() | Obtient les noms des extensions de ce type. |

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


### decode{#decode}

| Nom | Description |
| --- | --- |
| decode(fileName) | Décode le nuage de points ou le maillage à partir du nom de fichier spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Le nom de fichier contient le fichier drc |

 **Result:**
Geometry


---


### decode{#decode}

| Nom | Description |
| --- | --- |
| decode(data) | Décode le nuage de points ou le maillage à partir des données en mémoire |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| data | byte[] | Les octets bruts du drc |

 **Result:**
Geometry


---


### encode{#encode}

| Nom | Description |
| --- | --- |
| encode(entity, fileName, options) | Encode l'entité dans le fichier spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| entity | Entity | L'entité à encoder |
| fileName | String | Le nom de fichier à écrire |
| options | DracoSaveOptions | Options supplémentaires pour l'encodage du nuage de points |

 **Result:**
Geometry


---


### encode{#encode}

| Nom | Description |
| --- | --- |
| encode(entity, options) | Encode l'entité en données brutes Draco |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| entity | Entity | L'entité à encoder |
| options | DracoSaveOptions | Options supplémentaires pour l'encodage du nuage de points |

 **Result:**
byte[]


---


### createLoadOptions{#createLoadOptions}

| Nom | Description |
| --- | --- |
| createLoadOptions() | Crée des options de chargement par défaut pour ce format de fichier |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| Nom | Description |
| --- | --- |
| createSaveOptions() | Crée des options d'enregistrement par défaut pour ce format de fichier |

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



