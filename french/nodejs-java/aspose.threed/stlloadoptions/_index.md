---
title: StlLoadOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/stlloadoptions/
---
## StlLoadOptions class

Options de chargement pour STL


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de StlLoadOptions. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(contentType) | Initialise une nouvelle instance de StlLoadOptions. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nom | Description |
| --- | --- |
| getFlipCoordinateSystem() | Obtient ou définit si le système de coordonnées des points de contrôle/normale doit être inversé lors de l'importation. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nom | Description |
| --- | --- |
| setFlipCoordinateSystem(value) | Obtient ou définit si le système de coordonnées des points de contrôle/normale doit être inversé lors de l'importation. |

 **Result:**



---


### getRecalculateNormal{#getRecalculateNormal}

| Nom | Description |
| --- | --- |
| getRecalculateNormal() | Ignore les données de normales stockées dans le fichier STL et recalculer les normales en fonction de la position des sommets. La valeur par défaut est false. |

 **Result:**



---


### setRecalculateNormal{#setRecalculateNormal}

| Nom | Description |
| --- | --- |
| setRecalculateNormal(value) | Ignore les données de normales stockées dans le fichier STL et recalculer les normales en fonction de la position des sommets. La valeur par défaut est false. |

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



