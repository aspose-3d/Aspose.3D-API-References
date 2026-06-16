---
title: "接口 ICommandList"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.ICommandList 接口。编码一系列将发送到 GPU 进行渲染的命令"
type: docs
weight: 2030
url: /zh/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

对将发送到 GPU 进行渲染的命令序列进行编码。

```csharp
public interface ICommandList
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | 将描述符集绑定到当前管线 |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | 绑定用于渲染的索引缓冲区 |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | 绑定用于渲染的管线实例 |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | 绑定用于渲染的顶点缓冲区 |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | 在没有索引缓冲区的情况下绘制 |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | 在没有索引缓冲区的情况下绘制 |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | 在命令列表中发出带索引的绘制 |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | 在命令列表中发出带索引的绘制 |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | 将常量推送到管线 |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | 将常量推送到管线 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


