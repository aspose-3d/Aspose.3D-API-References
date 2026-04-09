---
title: GltfSaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

Options d'enregistrement pour le format glTF.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(contentType) | Constructeur de GltfSaveOptions |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(format) | Constructeur de GltfSaveOptions |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| forma | Format de fichier | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| Nom | Description |
| --- | --- |
| getPrettyPrint() | Le contenu JSON du fichier GLTF est indenté pour une lecture humaine, la valeur par défaut est false |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| Nom | Description |
| --- | --- |
| setPrettyPrint(value) | Le contenu JSON du fichier GLTF est indenté pour une lecture humaine, la valeur par défaut est false |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| Nom | Description |
| --- | --- |
| getFallbackNormal() | Lorsque l'exportateur GLTF2 détecte une normale invalide, celle-ci sera utilisée à la place de sa valeur originale pour contourner la validation. La valeur par défaut est (0, 1, 0). |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| Nom | Description |
| --- | --- |
| getEmbedAssets() | Intègre tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false. |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| Nom | Description |
| --- | --- |
| setEmbedAssets(value) | Intègre tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false. |

 **Result:**



---


### getImageFormat{#getImageFormat}

| Nom | Description |
| --- | --- |
| getImageFormat() | Le glTF standard ne prend en charge que les formats PNG/JPG comme format de texture, cette option indique comment Aspose.3D convertit les images non standard en format pris en charge lors de l'exportation. La valeur par défaut est GltfEmbeddedImageFormat.PNG. La valeur de la propriété est la constante entière GltfEmbeddedImageFormat. |

 **Result:**



---


### setImageFormat{#setImageFormat}

| Nom | Description |
| --- | --- |
| setImageFormat(value) | Le glTF standard ne prend en charge que les formats PNG/JPG comme format de texture, cette option indique comment Aspose.3D convertit les images non standard en format pris en charge lors de l'exportation. La valeur par défaut est GltfEmbeddedImageFormat.PNG. La valeur de la propriété est la constante entière GltfEmbeddedImageFormat. |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| Nom | Description |
| --- | --- |
| getMaterialConverter() | Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si celui-ci n'est pas assigné, l'exportateur glTF 2.0 convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. Cette propriété est utilisée lors de l'exportation d'une scène vers un fichier glTF 2.0. |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| Nom | Description |
| --- | --- |
| setMaterialConverter(value) | Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si celui-ci n'est pas assigné, l'exportateur glTF 2.0 convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. Cette propriété est utilisée lors de l'exportation d'une scène vers un fichier glTF 2.0. |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| Nom | Description |
| --- | --- |
| getUseCommonMaterials() | Sérialiser les matériaux en utilisant les extensions de matériau commun KHR, la valeur par défaut est false. Mettre cela à false entraînera l'exportation par Aspose.3D d'un ensemble de shaders vertex/fragment si #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders. |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| Nom | Description |
| --- | --- |
| setUseCommonMaterials(value) | Sérialiser les matériaux en utilisant les extensions de matériau commun KHR, la valeur par défaut est false. Mettre cela à false entraînera l'exportation par Aspose.3D d'un ensemble de shaders vertex/fragment si #Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders. |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| Nom | Description |
| --- | --- |
| getExternalDracoEncoder() | Utiliser un encodeur Draco externe pour accélérer la vitesse de compression Draco. Aspose.3D créera un nouveau sous‑processus pour encoder le maillage au format Draco, utilisez-le à vos propres risques. |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| Nom | Description |
| --- | --- |
| setExternalDracoEncoder(value) | Utiliser un encodeur Draco externe pour accélérer la vitesse de compression Draco. Aspose.3D créera un nouveau sous‑processus pour encoder le maillage au format Draco, utilisez-le à vos propres risques. |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| Nom | Description |
| --- | --- |
| getFlipTexCoordV() | Inverser le composant v(t) de la coordonnée de texture, la valeur par défaut est true. |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| Nom | Description |
| --- | --- |
| setFlipTexCoordV(value) | Inverser le composant v(t) de la coordonnée de texture, la valeur par défaut est true. |

 **Result:**



---


### getBufferFile{#getBufferFile}

| Nom | Description |
| --- | --- |
| getBufferFile() | Le nom du fichier du tampon externe utilisé pour stocker les données binaires. Si ce fichier n'est pas spécifié, Aspose.3D générera un nom pour vous. Cela est ignoré lors de l'exportation glTF en mode binaire. |

 **Result:**



---


### setBufferFile{#setBufferFile}

| Nom | Description |
| --- | --- |
| setBufferFile(value) | Le nom du fichier du tampon externe utilisé pour stocker les données binaires. Si ce fichier n'est pas spécifié, Aspose.3D générera un nom pour vous. Cela est ignoré lors de l'exportation glTF en mode binaire. |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| Nom | Description |
| --- | --- |
| getSaveExtras() | Enregistrer les propriétés dynamiques de l'objet de scène dans les champs 'extra' du fichier glTF généré. Cela est utile pour fournir des données spécifiques à l'application. La valeur par défaut est false. |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| Nom | Description |
| --- | --- |
| setSaveExtras(value) | Enregistrer les propriétés dynamiques de l'objet de scène dans les champs 'extra' du fichier glTF généré. Cela est utile pour fournir des données spécifiques à l'application. La valeur par défaut est false. |

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


### getDracoCompression{#getDracoCompression}

| Nom | Description |
| --- | --- |
| getDracoCompression() | Obtient ou définit si la compression Draco doit être activée. |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| Nom | Description |
| --- | --- |
| setDracoCompression(value) | Obtient ou définit si la compression Draco doit être activée. |

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



