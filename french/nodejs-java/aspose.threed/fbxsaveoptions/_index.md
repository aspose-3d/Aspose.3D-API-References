---
title: FbxSaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Options d'enregistrement pour le fichier Fbx.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(format) | Initialise un FbxSaveOptions |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| forma | Format de fichier | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(contentType) | Initialisez un FbxSaveOptions en utilisant la dernière version prise en charge. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| Nom | Description |
| --- | --- |
| getReusePrimitiveMesh() | Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille de la sortie FBX lorsque la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). La valeur par défaut est false |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| Nom | Description |
| --- | --- |
| setReusePrimitiveMesh(value) | Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille de la sortie FBX lorsque la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). La valeur par défaut est false |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| Nom | Description |
| --- | --- |
| getEnableCompression() | Compression de grandes données binaires dans le fichier FBX (par ex. données d'animation, points de contrôle, données d'éléments de sommet, indices), la valeur par défaut est true. |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| Nom | Description |
| --- | --- |
| setEnableCompression(value) | Compression de grandes données binaires dans le fichier FBX (par ex. données d'animation, points de contrôle, données d'éléments de sommet, indices), la valeur par défaut est true. |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| Nom | Description |
| --- | --- |
| getFoldRepeatedCurveData() | Obtient ou définit si les données de courbe répétées sont réutilisées en augmentant le compteur de références des dernières données ; vrai si fold repeated curve data ; sinon, faux. |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| Nom | Description |
| --- | --- |
| getExportLegacyMaterialProperties() | Obtient ou définit si les propriétés de matériau héritées sont exportées, utilisées pour la rétrocompatibilité. Cette option est activée par défaut. |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| Nom | Description |
| --- | --- |
| setExportLegacyMaterialProperties(value) | Obtient ou définit si les propriétés de matériau héritées sont exportées, utilisées pour la rétrocompatibilité. Cette option est activée par défaut. |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| Nom | Description |
| --- | --- |
| getVideoForTexture() | Obtient ou définit si une instance Video est générée pour la Texture lors de l'exportation au format FBX. |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| Nom | Description |
| --- | --- |
| setVideoForTexture(value) | Obtient ou définit si une instance Video est générée pour la Texture lors de l'exportation au format FBX. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Nom | Description |
| --- | --- |
| getEmbedTextures() | Obtient ou définit si la texture doit être intégrée au fichier de sortie final. L'exportateur FBX essaiera de trouver les données brutes de la texture dans le système de fichiers et d'intégrer le fichier au FBX final. La valeur par défaut est false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Nom | Description |
| --- | --- |
| setEmbedTextures(value) | Obtient ou définit si la texture doit être intégrée au fichier de sortie final. L'exportateur FBX essaiera de trouver les données brutes de la texture dans le système de fichiers et d'intégrer le fichier au FBX final. La valeur par défaut est false. |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| Nom | Description |
| --- | --- |
| getGenerateVertexElementMaterial() | Obtient ou définit si un VertexElementMaterial est toujours généré pour les géométries lorsque le nœud attaché contient des matériaux. Cette option est désactivée par défaut. |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| Nom | Description |
| --- | --- |
| setGenerateVertexElementMaterial(value) | Obtient ou définit si un VertexElementMaterial est toujours généré pour les géométries lorsque le nœud attaché contient des matériaux. Cette option est désactivée par défaut. |

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



