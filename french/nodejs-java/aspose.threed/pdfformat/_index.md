---
title: PdfFormat
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

Format de document portable d'Adobe  @hideconstructor


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


### extract{#extract}

| Nom | Description |
| --- | --- |
| extract(fileName, password) | Extraire le contenu 3D brut du fichier PDF. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |
| motdepasse | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| Nom | Description |
| --- | --- |
| extractScene(fileName) | Extraire les scènes 3D du fichier PDF. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| Nom | Description |
| --- | --- |
| extractScene(fileName, password) | Extraire les scènes 3D du fichier PDF. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |
| motdepasse | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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



