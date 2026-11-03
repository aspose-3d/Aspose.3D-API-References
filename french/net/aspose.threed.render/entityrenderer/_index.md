---
title: "Classe EntityRenderer"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Render.EntityRenderer classe. Sous-classez-la pour implémenter le rendu de différents types d'entités"
type: docs
weight: 1970
url: /fr/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Sous‑classez ceci pour implémenter le rendu pour différents types d'entités.

```csharp
public class EntityRenderer
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | Constructeur de `EntityRenderer` |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | Constructeur de `EntityRenderer` |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | Le rendu d'entité est en cours de libération, libérez les ressources partagées. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | Commencer le rendu d'une trame |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | Termine le rendu d'une trame |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | Initialiser le rendu d'entité |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | Préparer les commandes de rendu pour la paire nœud/entité spécifiée. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | Chaque tâche de rendu poussée dans le [`IRenderQueue`](../irenderqueue/) aura un appel RenderEntity correspondant pour exécuter le travail de rendu concret. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | La scène a changé ou a été supprimée, il faut libérer les ressources de rendu au niveau de la scène dans ce cas |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


