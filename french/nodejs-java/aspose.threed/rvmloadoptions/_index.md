---
title: RvmLoadOptions
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

Options de chargement pour le fichier RVM du système de gestion de conception d'usine AVEVA.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(contentType) | Construit une instance de RvmLoadOptions |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Construit une instance de RvmLoadOptions |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| Nom | Description |
| --- | --- |
| getGenerateMaterials() | Générer des matériaux avec des couleurs aléatoires pour chaque objet dans la scène si la table de couleurs n'est pas exportée dans le fichier RVM. La valeur par défaut est true |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| Nom | Description |
| --- | --- |
| setGenerateMaterials(value) | Générer des matériaux avec des couleurs aléatoires pour chaque objet dans la scène si la table de couleurs n'est pas exportée dans le fichier RVM. La valeur par défaut est true |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| Nom | Description |
| --- | --- |
| getCylinderRadialSegments() | Obtient ou définit le nombre de segments radiaux du cylindre, la valeur par défaut est 16 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| Nom | Description |
| --- | --- |
| setCylinderRadialSegments(value) | Obtient ou définit le nombre de segments radiaux du cylindre, la valeur par défaut est 16 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| Nom | Description |
| --- | --- |
| getDishLongitudeSegments() | Obtient ou définit le nombre de segments de longitude du plat, la valeur par défaut est 12 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| Nom | Description |
| --- | --- |
| setDishLongitudeSegments(value) | Obtient ou définit le nombre de segments de longitude du plat, la valeur par défaut est 12 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| Nom | Description |
| --- | --- |
| getDishLatitudeSegments() | Obtient ou définit le nombre de segments de latitude du plat, la valeur par défaut est 8 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| Nom | Description |
| --- | --- |
| setDishLatitudeSegments(value) | Obtient ou définit le nombre de segments de latitude du plat, la valeur par défaut est 8 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| Nom | Description |
| --- | --- |
| getTorusTubularSegments() | Obtient ou définit le nombre de segments tubulaires du tore, la valeur par défaut est 20 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| Nom | Description |
| --- | --- |
| setTorusTubularSegments(value) | Obtient ou définit le nombre de segments tubulaires du tore, la valeur par défaut est 20 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| Nom | Description |
| --- | --- |
| getRectangularTorusSegments() | Obtient ou définit le nombre de segments radiaux du tore rectangulaire, la valeur par défaut est 20 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| Nom | Description |
| --- | --- |
| setRectangularTorusSegments(value) | Obtient ou définit le nombre de segments radiaux du tore rectangulaire, la valeur par défaut est 20 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| Nom | Description |
| --- | --- |
| getCenterScene() | Centrer la scène après son chargement. |

 **Result:**



---


### setCenterScene{#setCenterScene}

| Nom | Description |
| --- | --- |
| setCenterScene(value) | Centrer la scène après son chargement. |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| Nom | Description |
| --- | --- |
| getAttributePrefix() | Obtient ou définit le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes. Le préfixe est utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:" |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| Nom | Description |
| --- | --- |
| setAttributePrefix(value) | Obtient ou définit le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes. Le préfixe est utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:" |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| Nom | Description |
| --- | --- |
| getLookupAttributes() | Obtient ou définit si les attributs doivent être chargés à partir d'un fichier de liste d'attributs externe (.att/.attrib/.txt), la valeur par défaut est true. |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| Nom | Description |
| --- | --- |
| setLookupAttributes(value) | Obtient ou définit si les attributs doivent être chargés à partir d'un fichier de liste d'attributs externe (.att/.attrib/.txt), la valeur par défaut est true. |

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



