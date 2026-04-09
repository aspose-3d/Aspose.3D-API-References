---
title: PdfSaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

Les options d'enregistrement lors de l'exportation PDF.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de PdfSaveOptions |

 **Result:**



---


### getRenderMode{#getRenderMode}

| Nom | Description |
| --- | --- |
| getRenderMode() | Le mode de rendu spécifie le style dans lequel le rendu 3D est effectué. La valeur de la propriété est la constante entière PdfRenderMode. |

 **Result:**



---


### setRenderMode{#setRenderMode}

| Nom | Description |
| --- | --- |
| setRenderMode(value) | Le mode de rendu spécifie le style dans lequel le rendu 3D est effectué. La valeur de la propriété est la constante entière PdfRenderMode. |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| Nom | Description |
| --- | --- |
| getLightingScheme() | LightingScheme spécifie l'éclairage à appliquer au rendu 3D. La valeur de la propriété est la constante entière PdfLightingScheme. |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| Nom | Description |
| --- | --- |
| setLightingScheme(value) | LightingScheme spécifie l'éclairage à appliquer au rendu 3D. La valeur de la propriété est la constante entière PdfLightingScheme. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| Nom | Description |
| --- | --- |
| getBackgroundColor() | Couleur d'arrière-plan de la vue 3D dans le fichier PDF. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| Nom | Description |
| --- | --- |
| setBackgroundColor(value) | Couleur d'arrière-plan de la vue 3D dans le fichier PDF. |

 **Result:**



---


### getFaceColor{#getFaceColor}

| Nom | Description |
| --- | --- |
| getFaceColor() | Obtient ou définit la couleur de face à utiliser lors du rendu du contenu 3D. Cela n'est pertinent que lorsque le RenderMode a une valeur d'Illustration. |

 **Result:**



---


### setFaceColor{#setFaceColor}

| Nom | Description |
| --- | --- |
| setFaceColor(value) | Obtient ou définit la couleur de face à utiliser lors du rendu du contenu 3D. Cela n'est pertinent que lorsque le RenderMode a une valeur d'Illustration. |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| Nom | Description |
| --- | --- |
| getAuxiliaryColor() | Obtient ou définit la couleur auxiliaire à utiliser lors du rendu du contenu 3D. L'interprétation de cette couleur dépend du RenderMode. |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| Nom | Description |
| --- | --- |
| setAuxiliaryColor(value) | Obtient ou définit la couleur auxiliaire à utiliser lors du rendu du contenu 3D. L'interprétation de cette couleur dépend du RenderMode. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nom | Description |
| --- | --- |
| getFlipCoordinateSystem() | Obtient ou définit le retournement du système de coordonnées de la scène lors de l'exportation. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nom | Description |
| --- | --- |
| setFlipCoordinateSystem(value) | Obtient ou définit le retournement du système de coordonnées de la scène lors de l'exportation. |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| Nom | Description |
| --- | --- |
| getEmbedTextures() | Intègre les textures externes dans le fichier PDF, la valeur par défaut est false. |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| Nom | Description |
| --- | --- |
| setEmbedTextures(value) | Intègre les textures externes dans le fichier PDF, la valeur par défaut est false. |

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



