---
title: "EntityRenderer.RenderEntity"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método EntityRenderer. Cada tarea de renderizado enviada a IRenderQueue tendrá una llamada correspondiente a RenderEntity para ejecutar el trabajo de renderizado concreto"
type: docs
weight: 70
url: /es/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Cada tarea de renderizado enviada a [`IRenderQueue`](../../irenderqueue/) tendrá una llamada correspondiente a RenderEntity para ejecutar el trabajo de renderizado concreto.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderer | Renderer | El renderizador |
| commandList | ICommandList | La commandList utilizada para registrar los comandos de renderizado |
| nodo | Nodo | El mismo nodo que se pasó a PrepareRenderQueue de la entidad que será renderizada |
| renderableResource | Objeto | El objeto personalizado que se pasó a IRenderQueue durante el PrepareRenderQueue |
| subEntity | Int32 | El índice de la subentidad que se pasó a IRenderQueue |

### Ver también

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


