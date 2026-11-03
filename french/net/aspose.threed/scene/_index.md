---
title: "Classe Scene"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Scene class. Une scène est un objet de niveau supérieur qui contient les nœuds, les géométries, les matériaux, les textures, les animations, les poses, les sous‑scènes, etc. La scène peut avoir des sous‑scènes et agit comme support multi‑document dans des fichiers tels que collada/blender/fbx. La hiérarchie des nœuds est accessible via RootNodeLibrary et est utilisée pour conserver une référence aux objets détachés lors de la sérialisation (comme les métadonnées ou les objets personnalisés) afin qu’elle puisse être utilisée comme bibliothèque."
type: docs
weight: 2500
url: /fr/net/aspose.threed/scene/
---
## Scene class

Une scène est un objet de niveau supérieur qui contient les nœuds, les géométries, les matériaux, les textures, les animations, les poses, les sous‑scènes, etc. La scène peut avoir des sous‑scènes, agit comme support multi‑document dans des fichiers tels que collada/blender/fbx. La hiérarchie des nœuds est accessible via [`RootNode`](./rootnode/)[`Library`](./library/) et est utilisée pour conserver une référence aux objets détachés lors de la sérialisation (comme les métadonnées ou les objets personnalisés) afin qu’elle puisse être utilisée comme bibliothèque.

```csharp
public class Scene : SceneObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Scene](scene/#constructor)() | Initialise une nouvelle instance de la classe `Scene`. |
| [Scene](scene/#constructor_1)(Entity) | Initialise une nouvelle instance de la classe `Scene` avec une entité attachée à un nouveau nœud. |
| [Scene](scene/#constructor_2)(Scene, string) | Initialise une nouvelle instance de la classe `Scene` en tant que sous‑scène. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | Récupère tous les [`AnimationClip`](../../aspose.threed.animation/animationclip/) définis dans la scène. |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | Obtient ou définit les informations d’actif de niveau supérieur |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | Obtient ou définit le [`AnimationClip`](../../aspose.threed.animation/animationclip/) actif |
| [Library](../../aspose.threed/scene/library/) { get; } | Les objets qui ne sont pas directement utilisés dans la hiérarchie de la scène peuvent être définis dans la Bibliothèque. Ceci est utile lorsque vous utilisez des sous‑scènes et placez des composants réutilisables sous les sous‑scènes. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Poses](../../aspose.threed/scene/poses/) { get; } | Récupère tous les [`Pose`](../pose/) utilisés dans cette scène. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | Récupère le nœud racine de la scène. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | Récupère toutes les sous‑scènes |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | Ouvre la scène à partir du chemin fourni |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | Ouvre la scène à partir du chemin fourni |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | Ouvre la scène à partir du flux fourni |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | Ouvre la scène à partir du flux fourni en utilisant le format de fichier spécifié. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | Ouvre la scène à partir du flux fourni en utilisant la configuration d’E/S spécifiée. |
| [Clear](../../aspose.threed/scene/clear/)() | Efface le contenu de la scène et restaure les paramètres par défaut. |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | Une fonction raccourcie pour créer et enregistrer le [`AnimationClip`](../../aspose.threed.animation/animationclip/). Le premier [`AnimationClip`](../../aspose.threed.animation/animationclip/) sera assigné au [`CurrentAnimationClip`](./currentanimationclip/). |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | Récupère un [`AnimationClip`](../../aspose.threed.animation/animationclip/) nommé |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | Ouvre la scène à partir du flux fourni |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | Ouvre la scène à partir du chemin fourni |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | Ouvre la scène à partir du flux fourni |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | Ouvre la scène à partir du chemin fourni |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié. |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | Ouvre la scène à partir du flux fourni en utilisant le format de fichier spécifié. |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | Ouvre la scène à partir du flux fourni en utilisant la configuration d’E/S spécifiée. |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié. |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | Ouvre la scène à partir du chemin fourni en utilisant le format de fichier spécifié. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | Rendu de la scène dans un fichier externe depuis la perspective de la caméra donnée. La taille de sortie par défaut est 1024x768 et le format de sortie est png. |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | Rendu de la scène en bitmap depuis la perspective de la caméra donnée. |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | Rendu de la scène en bitmap depuis la perspective de la caméra donnée. |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | Rendu de la scène dans un fichier externe depuis la perspective de la caméra donnée. |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | Rendu de la scène dans un fichier externe depuis la perspective de la caméra donnée. |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | Enregistre la scène dans le flux en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié. |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | Enregistre la scène au chemin spécifié en utilisant le format de fichier spécifié. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

## Champs

| Nom | Description |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | Récupère la version de publication actuelle |

### Voir aussi

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


