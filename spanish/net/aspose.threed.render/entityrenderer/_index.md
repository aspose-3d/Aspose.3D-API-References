---
title: "Clase EntityRenderer"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Render.EntityRenderer. Subclase esta para implementar el renderizado de diferentes tipos de entidades"
type: docs
weight: 1970
url: /es/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Cree una subclase de esta para implementar el renderizado de diferentes tipos de entidades.

```csharp
public class EntityRenderer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | Constructor de `EntityRenderer` |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | Constructor de `EntityRenderer` |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | El renderizador de entidades está siendo eliminado, libere los recursos compartidos. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | Iniciar el renderizado de un fotograma |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | Finaliza el renderizado de un fotograma |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | Inicializar el renderizador de entidades |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | Preparar comandos de renderizado para el par nodo/entidad especificado. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | Cada tarea de renderizado enviada a la [`IRenderQueue`](../irenderqueue/) tendrá una llamada RenderEntity correspondiente para ejecutar el trabajo de renderizado concreto. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | La escena ha cambiado o se ha eliminado, es necesario disponer de los recursos de renderizado a nivel de escena en este |

### Ver también

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


