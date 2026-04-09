---
title: RvmSaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Options d'enregistrement pour le fichier RVM Aveva PDMS.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de RvmSaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(contentType) | Constructeur de RvmSaveOptions |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| Nom | Description |
| --- | --- |
| getFileNote() | Note du fichier dans l'en-tête du fichier. |

 **Result:**



---


### setFileNote{#setFileNote}

| Nom | Description |
| --- | --- |
| setFileNote(value) | Note du fichier dans l'en-tête du fichier. |

 **Result:**



---


### getAuthor{#getAuthor}

| Nom | Description |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| Nom | Description |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| Nom | Description |
| --- | --- |
| getCreationTime() | L'horodatage qui a exporté ce fichier, la valeur par défaut est l'heure actuelle |

 **Result:**



---


### setCreationTime{#setCreationTime}

| Nom | Description |
| --- | --- |
| setCreationTime(value) | L'horodatage qui a exporté ce fichier, la valeur par défaut est l'heure actuelle |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nom | Description |
| --- | --- |
| getAttributePrefix() | Obtient ou définit le préfixe des attributs qui seront exportés, la propriété exportée ne contiendra aucun préfixe, les propriétés personnalisées avec un préfixe différent ne seront pas exportées, la valeur par défaut est 'rvm:'. Par exemple, si une propriété est rvm:Refno=345, l'attribut exporté sera Refno = 345, le préfixe est supprimé. |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nom | Description |
| --- | --- |
| setAttributePrefix(value) | Obtient ou définit le préfixe des attributs qui seront exportés, la propriété exportée ne contiendra aucun préfixe, les propriétés personnalisées avec un préfixe différent ne seront pas exportées, la valeur par défaut est 'rvm:'. Par exemple, si une propriété est rvm:Refno=345, l'attribut exporté sera Refno = 345, le préfixe est supprimé. |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| Nom | Description |
| --- | --- |
| getAttributeListFile() | Obtient ou définit le nom de fichier de la liste d'attributs, l'exportateur générera un nom basé sur le nom du fichier .rvm lorsque cette propriété est indéfinie, la valeur par défaut est null. |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| Nom | Description |
| --- | --- |
| setAttributeListFile(value) | Obtient ou définit le nom de fichier de la liste d'attributs, l'exportateur générera un nom basé sur le nom du fichier .rvm lorsque cette propriété est indéfinie, la valeur par défaut est null. |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| Nom | Description |
| --- | --- |
| getExportAttributes() | Obtient ou définit si la liste d'attributs doit être exportée vers un fichier .att externe, la valeur par défaut est false. |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| Nom | Description |
| --- | --- |
| setExportAttributes(value) | Obtient ou définit si la liste d'attributs doit être exportée vers un fichier .att externe, la valeur par défaut est false. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nom | Description |
| --- | --- |
| getExportTextures() | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nom | Description |
| --- | --- |
| setExportTextures(value) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nom | Description |
| --- | --- |
| getFileFormat() | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |

 **Result:**



---


### getEncoding{#getEncoding}

| Nom | Description |
| --- | --- |
| getEncoding() | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Nom | Description |
| --- | --- |
| getFileSystem() | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nom | Description |
| --- | --- |
| setFileSystem(value) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nom | Description |
| --- | --- |
| getLookupPaths() | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |

 **Result:**



---


### getFileName{#getFileName}

| Nom | Description |
| --- | --- |
| getFileName() | Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |

 **Result:**



---


### setFileName{#setFileName}

| Nom | Description |
| --- | --- |
| setFileName(value) | Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |

 **Result:**



---



