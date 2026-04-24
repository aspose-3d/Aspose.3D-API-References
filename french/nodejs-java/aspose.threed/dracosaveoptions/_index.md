---
title: DracoSaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/dracosaveoptions/
---
## DracoSaveOptions class

Options d'enregistrement pour les fichiers Google draco


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Construire une configuration par défaut pour l'enregistrement des fichiers draco. |

 **Result:**



---


### getPositionBits{#getPositionBits}

| Nom | Description |
| --- | --- |
| getPositionBits() | Bits de quantification pour la position, la valeur par défaut est 14 |

 **Result:**



---


### setPositionBits{#setPositionBits}

| Nom | Description |
| --- | --- |
| setPositionBits(value) | Bits de quantification pour la position, la valeur par défaut est 14 |

 **Result:**



---


### getTextureCoordinateBits{#getTextureCoordinateBits}

| Nom | Description |
| --- | --- |
| getTextureCoordinateBits() | Bits de quantification pour les coordonnées de texture, la valeur par défaut est 12 |

 **Result:**



---


### setTextureCoordinateBits{#setTextureCoordinateBits}

| Nom | Description |
| --- | --- |
| setTextureCoordinateBits(value) | Bits de quantification pour les coordonnées de texture, la valeur par défaut est 12 |

 **Result:**



---


### getColorBits{#getColorBits}

| Nom | Description |
| --- | --- |
| getColorBits() | Bits de quantification pour la couleur des sommets, la valeur par défaut est 10 |

 **Result:**



---


### setColorBits{#setColorBits}

| Nom | Description |
| --- | --- |
| setColorBits(value) | Bits de quantification pour la couleur des sommets, la valeur par défaut est 10 |

 **Result:**



---


### getNormalBits{#getNormalBits}

| Nom | Description |
| --- | --- |
| getNormalBits() | Bits de quantification pour les vecteurs normaux, la valeur par défaut est 10 |

 **Result:**



---


### setNormalBits{#setNormalBits}

| Nom | Description |
| --- | --- |
| setNormalBits(value) | Bits de quantification pour les vecteurs normaux, la valeur par défaut est 10 |

 **Result:**



---


### getCompressionLevel{#getCompressionLevel}

| Nom | Description |
| --- | --- |
| getCompressionLevel() | Niveau de compression, la valeur par défaut est DracoCompressionLevel.STANDARD. La valeur de la propriété est la constante entière DracoCompressionLevel. |

 **Result:**



---


### setCompressionLevel{#setCompressionLevel}

| Nom | Description |
| --- | --- |
| setCompressionLevel(value) | Niveau de compression, la valeur par défaut est DracoCompressionLevel.STANDARD. La valeur de la propriété est la constante entière DracoCompressionLevel. |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| Nom | Description |
| --- | --- |
| getApplyUnitScale() | Appliquer AssetInfo.UnitScaleFactor au maillage. La valeur par défaut est false. |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| Nom | Description |
| --- | --- |
| setApplyUnitScale(value) | Appliquer AssetInfo.UnitScaleFactor au maillage. La valeur par défaut est false. |

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



