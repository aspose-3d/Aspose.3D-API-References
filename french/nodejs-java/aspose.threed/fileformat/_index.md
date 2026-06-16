---
title: "FileFormat"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

Définition du format de fichier  @hideconstructor


## Propriétés

| Nom | Description |
| --- | --- |
| MAYA_BINARY | Autodesk Maya au format binaire |
| STL_BINARY | Format de fichier STL binaire |
| STLASCII | Format de fichier STL ASCII |
| COLLADA | Format de fichier Collada |
| GLTF | glTF du groupe Khronos |
| GLTF_BINARY | glTF du groupe Khronos au format binaire |
| PDF | Format de document portable d'Adobe |
| DXF | AutoCAD DXF |
| PLY | Format de fichier Polygon ou format Stanford Triangle |
| X_BINARY | Fichier X DirectX au format binaire |
| X_TEXT | Fichier X DirectX au format binaire |
| DRACO | Maillage Draco de Google |
| RVM_TEXT | Modèle AVEVA Plant Design Management System au format texte |
| RVM_BINARY | Modèle AVEVA Plant Design Management System au format binaire |
| ASE | Format d'exportateur de scène ASCII de 3D Studio Max. |
| IFC | Modèle de données Industry Foundation Classes ISO 16739-1. |
| AMF | Format de fichier de fabrication additive |
| VRML | Le langage de modélisation de réalité virtuelle |
| ZIP | Archive Zip contenant d'autres formats de fichiers 3d. |
| USD | Description de scène universelle |
| USDZ | Description de scène universelle compressée |
| XYZ | Fichier de nuage de points Xyz |
| PCD | Fichier de données de nuage de points PCL en mode ASCII |
| PCD_BINARY | Fichier de données de nuage de points PCL en mode binaire |

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


### getFormatByExtension{#getFormatByExtension}

| Nom | Description |
| --- | --- |
| getFormatByExtension(extensionName) | Obtient le format de fichier préféré à partir du nom d'extension. Le nom d'extension doit commencer par un point ('.'). |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| extensionNam | String | null |

 **Result:**
FileFormat


---


### detect{#detect}

| Nom | Description |
| --- | --- |
| detect(fileName) | Détecte le format du fichier à partir du nom du fichier, le fichier doit être lisible afin qu'Aspose.3D puisse détecter le format du fichier via l'en-tête du fichier. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
FileFormat


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



