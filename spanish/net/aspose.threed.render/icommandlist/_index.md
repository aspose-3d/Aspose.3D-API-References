---
title: "Interfaz ICommandList"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Interfaz Aspose.ThreeD.Render.ICommandList. Codifica una secuencia de comandos que se enviarán a la GPU para renderizar"
type: docs
weight: 2030
url: /es/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

Codifica una secuencia de comandos que se enviarán a la GPU para renderizar.

```csharp
public interface ICommandList
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | Vincular el conjunto de descriptores al pipeline actual |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | Vincular el búfer de índices para renderizar |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | Vincular la instancia del pipeline para renderizar |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | Vincular el búfer de vértices para renderizar |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | Dibujar sin búfer de índices |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | Dibujar sin búfer de índices |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | Emitir un dibujo indexado en una lista de comandos |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | Emitir un dibujo indexado en una lista de comandos |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | Enviar la constante al pipeline |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | Enviar la constante al pipeline |

### Ver también

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


