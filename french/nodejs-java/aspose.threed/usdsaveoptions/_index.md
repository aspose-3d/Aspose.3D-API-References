---
title: "UsdSaveOptions"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

Enregistrer les options pour les formats USD/USDZ.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise un nouvel UsdSaveOptions avec le format FileFormat.USD. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(fileFormat) | Initialise un nouvel UsdSaveOptions avec le format USD/USDZ spécifié. |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| Nom | Description |
| --- | --- |
| getPrimitiveToMesh() | Convertit les entités primitives en maillage lors de l'exportation. Ou encode directement les primitives dans le fichier de sortie (utilisera la définition d'extension d'Aspose pour les primitives non officielles comme Dish, Torus). La valeur par défaut est true. |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| Nom | Description |
| --- | --- |
| setPrimitiveToMesh(value) | Convertit les entités primitives en maillage lors de l'exportation. Ou encode directement les primitives dans le fichier de sortie (utilisera la définition d'extension d'Aspose pour les primitives non officielles comme Dish, Torus). La valeur par défaut est true. |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| Nom | Description |
| --- | --- |
| getExportMetaData() | Exporte les propriétés du nœud via le champ customData d'USD. |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| Nom | Description |
| --- | --- |
| setExportMetaData(value) | Exporte les propriétés du nœud via le champ customData d'USD. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nom | Description |
| --- | --- |
| getMaterialConverter() | Convertisseur personnalisé pour transformer le matériau de la géométrie en matériau PBR. Si aucun n'est assigné, l'exportateur USD convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nom | Description |
| --- | --- |
| setMaterialConverter(value) | Convertisseur personnalisé pour transformer le matériau de la géométrie en matériau PBR. Si aucun n'est assigné, l'exportateur USD convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Nom | Description |
| --- | --- |
| getExportTextures() | Essayer de copier les textures utilisées dans la scène vers le répertoire de sortie. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Nom | Description |
| --- | --- |
| setExportTextures(value) | Essayer de copier les textures utilisées dans la scène vers le répertoire de sortie. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Nom | Description |
| --- | --- |
| getFileFormat() | Obtient le format de fichier spécifié dans l'option Enregistrer/Charger actuelle. |

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
| getFileSystem() | Autorise l'utilisateur à gérer la façon de gérer les dépendances externes lors du chargement/enregistrement. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Nom | Description |
| --- | --- |
| setFileSystem(value) | Autorise l'utilisateur à gérer la façon de gérer les dépendances externes lors du chargement/enregistrement. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Nom | Description |
| --- | --- |
| getLookupPaths() | Certains fichiers comme OBJ dépendent d'un fichier externe ; les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |

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



