---
title: Renderer
second_title: Référence de l'API Aspose.3D pour .NET
description: Le contexte du moteur de rendu.
type: docs
weight: 2100
url: /fr/net/aspose.threed.render/renderer/
---
## Renderer class

Le contexte du moteur de rendu.

```csharp
public abstract class Renderer : IDisposable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories) { get; } | Répertoires qui stockaient des ressources externes |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows) { get; set; } | Obtient ou définit s'il faut activer les ombres. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer) { get; set; } | Obtient ou définit le rendu d'entité de secours lorsque l'entité n'a pas de rendu spécial défini. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum) { get; set; } | Obtient ou définit le frustum utilisé pour fournir la matrice de vue. |
| virtual [Material](../../aspose.threed.render/renderer/material) { get; set; } | Obtient ou définit le matériau utilisé pour fournir les informations sur le matériau utilisées par les shaders. |
| [Node](../../aspose.threed.render/renderer/node) { get; set; } | Obtient ou définit le[`Node`](./node) instance utilisée pour fournir la matrice de transformation du monde. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings) { get; } | Chaîne de post-traitement active |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders) { get; set; } | Obtient ou définit le jeu de shaders prédéfini |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory) { get; } | Obtient la fabrique pour créer des objets liés au rendu. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage) { get; } | Obtient l'étape de rendu actuelle. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget) { get; } | Spécifiez la cible de rendu sur laquelle les opérations de rendu suivantes seront effectuées. |
| [Shader](../../aspose.threed.render/renderer/shader) { get; set; } | Obtient ou définit l'instance de shader utilisée pour le rendu de la géométrie. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset) { get; set; } | Obtient ou définit le jeu de shaders utilisé pour rendre la scène |
| [Variables](../../aspose.threed.render/renderer/variables) { get; } | Accès aux variables internes utilisées pour le rendu |

## Méthodes

| Nom | La description |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer)() | Crée un nouveau[`Renderer`](../renderer)avec le profil par défaut. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache)() | Effacez manuellement le cache. Aspose.3D mettra en cache certains objets comme les matériaux/géométries dans des types internes compatibles avec le pipeline de rendu. Cela devrait être appelé manuellement lorsque la scène a des changements majeurs. |
| [Dispose](../../aspose.threed.render/renderer/dispose)() | Jeter le[`Renderer`](../renderer) et toutes les ressources associées |
| abstract [Execute](../../aspose.threed.render/renderer/execute)(PostProcessing, IRenderTarget) | Exécuter un post-traitement sur la cible de rendu spécifiée |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing)(string) | Obtient un post-processeur intégré pris en charge par le moteur de rendu. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer)(EntityRenderer) | Enregistrer le rendu d'entité pour l'entité spécifiée |
| virtual [Render](../../aspose.threed.render/renderer/render)(IRenderTarget) | Rendre la cible spécifiée |

### Voir également

* espace de noms [Aspose.ThreeD.Render](../../aspose.threed.render)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
