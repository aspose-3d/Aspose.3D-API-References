---
title: UsdSaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Options d’enregistrement pour les formats USD/USDZ.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle UsdSaveOptions avec le format FileFormat.USD |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(fileFormat) | Initialise une nouvelle UsdSaveOptions avec le format USD/USDZ spécifié. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Nom | Description |
| --- | --- |
| getPrimitiveToMesh() | Convertir les entités primitives en maillage lors de l'exportation. Ou encoder directement les primitives dans le fichier de sortie (utilisera la définition d'extension d'Aspose pour les primitives non officielles comme Dish, Torus). La valeur par défaut est true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Nom | Description |
| --- | --- |
| setPrimitiveToMesh(value) | Convertir les entités primitives en maillage lors de l'exportation. Ou encoder directement les primitives dans le fichier de sortie (utilisera la définition d'extension d'Aspose pour les primitives non officielles comme Dish, Torus). La valeur par défaut est true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Nom | Description |
| --- | --- |
| getExportMetaData() | Exportez les propriétés du nœud via le champ customData d'USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Nom | Description |
| --- | --- |
| setExportMetaData(value) | Exportez les propriétés du nœud via le champ customData d'USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nom | Description |
| --- | --- |
| getMaterialConverter() | Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si cela n'est pas assigné, l'exportateur USD convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nom | Description |
| --- | --- |
| setMaterialConverter(value) | Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si cela n'est pas assigné, l'exportateur USD convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. |

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



