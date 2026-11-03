---
title: "Klasse EntityRenderer"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.EntityRenderer Klasse. Unterklassen Sie diese, um das Rendern für verschiedene Arten von Entitäten zu implementieren."
type: docs
weight: 1970
url: /de/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Erben Sie hiervon, um das Rendering für verschiedene Arten von Entitäten zu implementieren.

```csharp
public class EntityRenderer
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | Konstruktor von `EntityRenderer` |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | Konstruktor von `EntityRenderer` |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | Der Entity-Renderer wird entsorgt, freigegebene Ressourcen werden freigegeben. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | Beginne das Rendern eines Frames |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | Beendet das Rendern eines Frames |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | Initialisiere den Entity-Renderer |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | Bereite Renderbefehle für das angegebene Knoten/Entität-Paar vor. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | Jede Renderaufgabe, die zur [`IRenderQueue`](../irenderqueue/) hinzugefügt wird, hat einen entsprechenden RenderEntity-Aufruf, um den konkreten Rendering‑Job auszuführen. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | Die Szene hat sich geändert oder wurde entfernt, daher müssen die renderbezogenen Ressourcen auf Szenenebene hier freigegeben werden. |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


