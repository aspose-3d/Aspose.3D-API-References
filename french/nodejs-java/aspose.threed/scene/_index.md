---
title: Scène
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/scene/
---
## Scene class

Une scène est un objet de niveau supérieur qui contient les nœuds, géométries, matériaux, textures, animations, poses, sous‑scènes, etc. Une scène peut avoir des sous‑scènes, servant de prise en charge multi‑document dans des fichiers tels que collada/blender/fbx. La hiérarchie des nœuds peut être accédée via RootNodeLibrary, qui est utilisé pour conserver une référence des objets détachés pendant la sérialisation (comme les métadonnées ou objets personnalisés) afin de pouvoir les utiliser comme bibliothèque.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe Scene. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(entity) | Initialise une nouvelle instance de la classe Scene avec une entité attachée à un nouveau nœud. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| entity | Entity | L'entité initiale qui a été attachée à la scène |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(parentScene, name) | Initialise une nouvelle instance de la classe Scene en tant que sous-scène. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| parentScene | Scène | La scène parente. |
| nom | String | Nom de la scène. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(fileName) | Initialise une nouvelle instance de la classe Scene et ouvre le fichier immédiatement. Ce constructeur est obsolète, veuillez utiliser #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier à ouvrir. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Nom | Description |
| --- | --- |
| getSubScenes() | Obtient toutes les sous‑scènes |

 **Result:**



---


### getLibrary{#getLibrary}

| Nom | Description |
| --- | --- |
| getLibrary() | Les objets qui ne sont pas directement utilisés dans la hiérarchie de la scène peuvent être définis dans la Bibliothèque. Ceci est utile lorsque vous utilisez des sous‑scènes et placez des composants réutilisables sous les sous‑scènes. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Nom | Description |
| --- | --- |
| getAnimationClips() | Récupère tous les AnimationClip définis dans la scène. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Nom | Description |
| --- | --- |
| getCurrentAnimationClip() | Obtient ou définit l'AnimationClip actif |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Nom | Description |
| --- | --- |
| setCurrentAnimationClip(value) | Obtient ou définit l'AnimationClip actif |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nom | Description |
| --- | --- |
| getAssetInfo() | Obtient ou définit les informations d'actif de niveau supérieur. Les informations du document. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nom | Description |
| --- | --- |
| setAssetInfo(value) | Obtient ou définit les informations d'actif de niveau supérieur. Les informations du document. |

 **Result:**



---


### getPoses{#getPoses}

| Nom | Description |
| --- | --- |
| getPoses() | Récupère toutes les Pose utilisées dans cette scène. Les poses. |

 **Result:**



---


### getRootNode{#getRootNode}

| Nom | Description |
| --- | --- |
| getRootNode() | Récupère le nœud racine de la scène. Le nœud racine. |

 **Result:**



---


### getScene{#getScene}

| Nom | Description |
| --- | --- |
| getScene() | Obtient la scène à laquelle cet objet appartient |

 **Result:**



---


### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**



---


### getAnimationClip{#getAnimationClip}

| Nom | Description |
| --- | --- |
| getAnimationClip(name) | Récupère un AnimationClip nommé |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Le |

 **Result:**
AnimationClip


---


### clear{#clear}

| Nom | Description |
| --- | --- |
| clear() | Efface le contenu de la scène et restaure les paramètres par défaut. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Nom | Description |
| --- | --- |
| createAnimationClip(name) | Une fonction raccourcie pour créer et enregistrer l'AnimationClip. Le premier AnimationClip sera assigné au CurrentAnimationClip |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom du clip d'animation |

 **Result:**
AnimationClip


---


### open{#open}

| Nom | Description |
| --- | --- |
| open(fileName, options) | Ouvre la scène depuis le chemin fourni en utilisant le format de fichier spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier. |
| options | LoadOptions | Configuration plus détaillée pour ouvrir le flux. |

 **Result:**
AnimationClip


---


### open{#open}

| Nom | Description |
| --- | --- |
| open(fileName) | Ouvre la scène depuis le chemin fourni |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Nom | Description |
| --- | --- |
| fromFile(fileName) | Ouvre la scène depuis le chemin fourni |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier. |

 **Result:**
AnimationClip


---


### save{#save}

| Nom | Description |
| --- | --- |
| save(fileName) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier. |

 **Result:**
AnimationClip


---


### save{#save}

| Nom | Description |
| --- | --- |
| save(fileName, format) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier. |
| format | Format de fichier | Format. |

 **Result:**
AnimationClip


---


### save{#save}

| Nom | Description |
| --- | --- |
| save(fileName, options) | Enregistre la scène à l'emplacement spécifié en utilisant le format de fichier spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Nom du fichier. |
| options | SaveOptions | Configuration plus détaillée pour enregistrer le flux. |

 **Result:**
AnimationClip


---


### render{#render}

| Nom | Description |
| --- | --- |
| render(camera, fileName) | Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée. La taille de sortie par défaut est 1024x768 et le format de sortie est png |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| caméra | Camera | Depuis quelle perspective de caméra rendre la scène |
| fileName | String | Le nom du fichier de sortie |

 **Result:**
AnimationClip


---


### render{#render}

| Nom | Description |
| --- | --- |
| render(camera, fileName, size, format) | Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| caméra | Camera | Depuis quelle perspective de caméra rendre la scène |
| fileName | String | Le nom du fichier de sortie |
| taille | Vector2 | La taille de l'image rendue finale |
| format | String | Le format d'image du fichier de sortie |

 **Result:**
AnimationClip


---


### render{#render}

| Nom | Description |
| --- | --- |
| render(camera, fileName, size, format, options) | Rendre la scène dans un fichier externe depuis la perspective de la caméra donnée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| caméra | Camera | Depuis quelle perspective de caméra rendre la scène |
| fileName | String | Le nom du fichier de sortie |
| taille | Vector2 | La taille de l'image rendue finale |
| format | String | Le format d'image du fichier de sortie |
| options | ImageRenderOptions | L'option de personnaliser certains paramètres internes. |

 **Result:**
AnimationClip


---


### render{#render}

| Nom | Description |
| --- | --- |
| render(camera, bitmap) | Rendre la scène en bitmap depuis la perspective de la caméra donnée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| caméra | Camera | Depuis quelle perspective de caméra rendre la scène |
| bitmap | TextureData | Cible du résultat rendu |

 **Result:**
AnimationClip


---


### render{#render}

| Nom | Description |
| --- | --- |
| render(camera, bitmap, options) | Rendre la scène en bitmap depuis la perspective de la caméra donnée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| caméra | Camera | Depuis quelle perspective de caméra rendre la scène |
| bitmap | TextureData | Cible du résultat rendu |
| options | ImageRenderOptions | L'option de personnaliser certains paramètres internes. |

 **Result:**
AnimationClip


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime une propriété dynamique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | Property | Quelle propriété supprimer |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime la propriété spécifiée identifiée par son nom |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nom | Description |
| --- | --- |
| getProperty(property) | Obtenir la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nom | Description |
| --- | --- |
| setProperty(property, value) | Définit la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |
| valeur | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---



