---
title: "Classe Renderer"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Render.Renderer class. Le contexte concernant le rendu"
type: docs
weight: 2340
url: /fr/net/aspose.threed.render/renderer/
---
## Renderer class

Le contexte du rendu.

```csharp
public abstract class Renderer : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | Répertoires qui stockent les actifs externes |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | Obtient ou définit si les ombres sont activées. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | Obtient ou définit le rendu d'entité de secours lorsqu'aucun rendu spécial n'est défini pour l'entité. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | Obtient ou définit le frustum utilisé pour fournir la matrice de vue. |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | Obtient ou définit le matériau utilisé pour fournir les informations de matériau utilisées par les shaders. |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | Obtient ou définit l'instance [`Node`](./node/) utilisée pour fournir la matrice de transformation du monde. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | Chaîne de post-traitement active |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | Obtient ou définit l'ensemble de shaders prédéfini |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | Obtient la fabrique permettant de créer les objets liés au rendu. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | Obtient l'étape de rendu actuelle. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | Spécifiez la cible de rendu sur laquelle les opérations de rendu suivantes seront effectuées. |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | Obtient ou définit l'instance de shader utilisée pour le rendu de la géométrie. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | Obtient ou définit l'ensemble de shaders utilisé pour rendre la scène |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | Accès aux variables internes utilisées pour le rendu |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | Crée un nouveau `Renderer` avec le profil par défaut. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | Effacez manuellement le cache. Aspose.3D met en cache certains objets tels que les matériaux/géométries dans des types internes compatibles avec le pipeline de rendu. Cette opération doit être appelée manuellement lorsque la scène subit des modifications majeures. |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | Libérez le `Renderer` ainsi que toutes les ressources associées |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | Exécutez un post-traitement sur la cible de rendu spécifiée |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | Obtient un post-processeur intégré pris en charge par le rendu. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | Enregistrez le rendu d'entité pour l'entité spécifiée |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | Rendez la cible spécifiée |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


