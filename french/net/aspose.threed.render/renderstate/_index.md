---
title: "Classe RenderState"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Render.RenderState. État de rendu pour la construction du pipeline. Les modifications apportées à l'état de rendu n'affecteront pas les instances de pipeline créées."
type: docs
weight: 2330
url: /fr/net/aspose.threed.render/renderstate/
---
## RenderState class

État de rendu pour la construction du pipeline Les modifications apportées à l'état de rendu n'affecteront pas les instances de pipeline créées.

```csharp
public class RenderState : IComparable<RenderState>, IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RenderState](renderstate/)() | Constructeur de `RenderState` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Blend](../../aspose.threed.render/renderstate/blend/) { get; set; } | Activer ou désactiver le mélange des fragments. |
| [BlendColor](../../aspose.threed.render/renderstate/blendcolor/) { get; set; } | Obtient ou définit la couleur de mélange lorsqu'elle est utilisée dans ConstantColor |
| [CullFace](../../aspose.threed.render/renderstate/cullface/) { get; set; } | Activer ou désactiver la suppression des faces |
| [CullFaceMode](../../aspose.threed.render/renderstate/cullfacemode/) { get; set; } | Obtient ou définit quelle face sera supprimée. |
| [DepthFunction](../../aspose.threed.render/renderstate/depthfunction/) { get; set; } | Obtient ou définit la fonction de comparaison utilisée dans le test de profondeur |
| [DepthMask](../../aspose.threed.render/renderstate/depthmask/) { get; set; } | Activer ou désactiver l'écriture de la profondeur. |
| [DepthTest](../../aspose.threed.render/renderstate/depthtest/) { get; set; } | Activer ou désactiver le test de profondeur. |
| [DestinationBlendFactor](../../aspose.threed.render/renderstate/destinationblendfactor/) { get; set; } | Obtient ou définit comment la couleur est mélangée. |
| [FrontFace](../../aspose.threed.render/renderstate/frontface/) { get; set; } | Obtient ou définit quel ordre correspond à la face avant. |
| [PolygonMode](../../aspose.threed.render/renderstate/polygonmode/) { get; set; } | Obtient ou définit le mode de rendu du polygone. |
| [ScissorTest](../../aspose.threed.render/renderstate/scissortest/) { get; set; } | Activer ou désactiver le test de ciseaux |
| [SourceBlendFactor](../../aspose.threed.render/renderstate/sourceblendfactor/) { get; set; } | Obtient ou définit comment la couleur est mélangée. |
| [StencilBackFace](../../aspose.threed.render/renderstate/stencilbackface/) { get; } | Obtient l'état du stencil pour la face arrière. |
| [StencilFrontFace](../../aspose.threed.render/renderstate/stencilfrontface/) { get; } | Obtient l'état du stencil pour la face avant. |
| [StencilMask](../../aspose.threed.render/renderstate/stencilmask/) { get; set; } | Obtient ou définit le masque qui est ETé avec la référence et la valeur de stencil stockée lorsque le test est terminé. |
| [StencilReference](../../aspose.threed.render/renderstate/stencilreference/) { get; set; } | Obtient ou définit la valeur de référence pour le test de stencil. |
| [StencilTest](../../aspose.threed.render/renderstate/stenciltest/) { get; set; } | Activer ou désactiver le test de stencil. |

## Méthodes

| Nom | Description |
| --- | --- |
| [CompareTo](../../aspose.threed.render/renderstate/compareto/)(RenderState) | Comparer l'état de rendu avec une autre instance |
| [Dispose](../../aspose.threed.render/renderstate/dispose/)() | Libérez le `RenderState` et libérez toutes les ressources internes. |
| override [Equals](../../aspose.threed.render/renderstate/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à un objet spécifié. |
| override [GetHashCode](../../aspose.threed.render/renderstate/gethashcode/)() | Renvoie le code de hachage pour cette instance. |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


