---
title: "Интерфейс ICommandList"
second_title: "Справочник API Aspose.3D для .NET"
description: "Интерфейс Aspose.ThreeD.Render.ICommandList. Кодирует последовательность команд, которые будут отправлены на GPU для рендеринга."
type: docs
weight: 2030
url: /ru/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

Кодирует последовательность команд, которые будут отправлены на GPU для рендеринга.

```csharp
public interface ICommandList
```

## Методы

| Имя | Описание |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | Привязать набор дескрипторов к текущему конвейеру |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | Привязать индексный буфер для рендеринга |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | Привязать экземпляр конвейера для рендеринга |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | Привязать вершинный буфер для рендеринга |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | Отрисовать без индексного буфера |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | Отрисовать без индексного буфера |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | Выполнить индексированную отрисовку в список команд |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | Выполнить индексированную отрисовку в список команд |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | Передать константу в конвейер |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | Передать константу в конвейер |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


