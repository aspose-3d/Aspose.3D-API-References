---
title: PlySaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

Options d'enregistrement pour exporter la scène au format PLY.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de PlySaveOptions |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(contentType) | Constructeur de PlySaveOptions |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| Nom | Description |
| --- | --- |
| getPointCloud() | Exporter la scène en nuage de points, la valeur par défaut est false. |

 **Result:**



---


### setPointCloud{#setPointCloud}

| Nom | Description |
| --- | --- |
| setPointCloud(value) | Exporter la scène en nuage de points, la valeur par défaut est false. |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| Nom | Description |
| --- | --- |
| getFlipCoordinate() | Inverser les coordonnées lors de l'enregistrement de la scène, la valeur par défaut est true |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| Nom | Description |
| --- | --- |
| setFlipCoordinate(value) | Inverser les coordonnées lors de l'enregistrement de la scène, la valeur par défaut est true |

 **Result:**



---


### getVertexElement{#getVertexElement}

| Nom | Description |
| --- | --- |
| getVertexElement() | Le nom de l'élément pour les données de sommet, la valeur par défaut est "vertex" |

 **Result:**



---


### setVertexElement{#setVertexElement}

| Nom | Description |
| --- | --- |
| setVertexElement(value) | Le nom de l'élément pour les données de sommet, la valeur par défaut est "vertex" |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| Nom | Description |
| --- | --- |
| getPositionComponents() | Les noms des composants pour les données de position, la valeur par défaut est ("x", "y", "z") |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| Nom | Description |
| --- | --- |
| getNormalComponents() | Les noms des composants pour les données normales, la valeur par défaut est ("nx", "ny", "nz") |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| Nom | Description |
| --- | --- |
| getTextureCoordinateComponents() | Les noms des composants pour les données de coordonnées de texture, la valeur par défaut est ("u", "v") |

 **Result:**



---


### getColorComponents{#getColorComponents}

| Nom | Description |
| --- | --- |
| getColorComponents() | Les noms des composants pour la couleur des sommets, la valeur par défaut est (\"red\", \"green\", \"blue\") |

 **Result:**



---


### getFaceElement{#getFaceElement}

| Nom | Description |
| --- | --- |
| getFaceElement() | Le nom de l'élément pour les données de face, la valeur par défaut est "face" |

 **Result:**



---


### setFaceElement{#setFaceElement}

| Nom | Description |
| --- | --- |
| setFaceElement(value) | Le nom de l'élément pour les données de face, la valeur par défaut est "face" |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| Nom | Description |
| --- | --- |
| getFaceProperty() | Le nom de la propriété pour les données de face, la valeur par défaut est "vertex_index" |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| Nom | Description |
| --- | --- |
| setFaceProperty(value) | Le nom de la propriété pour les données de face, la valeur par défaut est "vertex_index" |

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



