---
title: Discreet3dsSaveOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Options d'enregistrement pour le fichier 3DS.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de Discreet3dsSaveOptions |

 **Result:**



---


### getExportLight{#getExportLight}

| Nom | Description |
| --- | --- |
| getExportLight() | Obtient ou définit si toutes les lumières sont exportées dans la scène. |

 **Result:**



---


### setExportLight{#setExportLight}

| Nom | Description |
| --- | --- |
| setExportLight(value) | Obtient ou définit si toutes les lumières sont exportées dans la scène. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Nom | Description |
| --- | --- |
| getExportCamera() | Obtient ou définit si toutes les caméras sont exportées dans la scène. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Nom | Description |
| --- | --- |
| setExportCamera(value) | Obtient ou définit si toutes les caméras sont exportées dans la scène. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Nom | Description |
| --- | --- |
| getDuplicatedNameSeparator() | Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "_". Lorsque la scène contient des objets qui utilisent le même nom, l'exportateur 3DS d'Aspose.3D générera un nom différent pour l'objet. Par exemple, il y a deux nœuds nommés "Box", le premier nœud aura le nom "Box", et le deuxième nœud recevra un nouveau nom "Box_2" en utilisant la configuration par défaut. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Nom | Description |
| --- | --- |
| setDuplicatedNameSeparator(value) | Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "_". Lorsque la scène contient des objets qui utilisent le même nom, l'exportateur 3DS d'Aspose.3D générera un nom différent pour l'objet. Par exemple, il y a deux nœuds nommés "Box", le premier nœud aura le nom "Box", et le deuxième nœud recevra un nouveau nom "Box_2" en utilisant la configuration par défaut. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Nom | Description |
| --- | --- |
| getDuplicatedNameCounterBase() | Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Nom | Description |
| --- | --- |
| setDuplicatedNameCounterBase(value) | Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Nom | Description |
| --- | --- |
| getDuplicatedNameCounterFormat() | Le format du compteur dupliqué, la valeur par défaut est une chaîne vide. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Nom | Description |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Le format du compteur dupliqué, la valeur par défaut est une chaîne vide. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Nom | Description |
| --- | --- |
| getMasterScale() | Obtient ou définit l'échelle principale utilisée lors de l'exportation. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Nom | Description |
| --- | --- |
| setMasterScale(value) | Obtient ou définit l'échelle principale utilisée lors de l'exportation. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Nom | Description |
| --- | --- |
| getGammaCorrectedColor() | Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Mettre cela à true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Nom | Description |
| --- | --- |
| setGammaCorrectedColor(value) | Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Mettre cela à true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Nom | Description |
| --- | --- |
| getFlipCoordinateSystem() | Obtient ou définit le système de coordonnées de retournement des points de contrôle/normal lors de l'importation/exportation. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Nom | Description |
| --- | --- |
| setFlipCoordinateSystem(value) | Obtient ou définit le système de coordonnées de retournement des points de contrôle/normal lors de l'importation/exportation. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Nom | Description |
| --- | --- |
| getHighPreciseColor() | Si cette valeur est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en virgule flottante 32 bits. Sinon, le fichier généré utilisera une couleur 24 bits, chaque canal utilisant un octet de 8 bits. La valeur par défaut est false, car toutes les applications ne supportent pas la couleur haute précision. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Nom | Description |
| --- | --- |
| setHighPreciseColor(value) | Si cette valeur est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en virgule flottante 32 bits. Sinon, le fichier généré utilisera une couleur 24 bits, chaque canal utilisant un octet de 8 bits. La valeur par défaut est false, car toutes les applications ne supportent pas la couleur haute précision. |

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



