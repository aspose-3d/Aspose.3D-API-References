---
title: "Schnittstelle ICommandList"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.ICommandList Schnittstelle. Kodiert eine Sequenz von Befehlen, die an die GPU zum Rendern gesendet werden."
type: docs
weight: 2030
url: /de/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

Kodiert eine Sequenz von Befehlen, die an die GPU zum Rendern gesendet werden.

```csharp
public interface ICommandList
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | Binde das Deskriptorset an die aktuelle Pipeline. |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | Binde den Indexpuffer für das Rendering. |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | Binde die Pipeline‑Instanz für das Rendering. |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | Binde den Vertex‑Puffer für das Rendering. |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | Zeichnen ohne Indexpuffer. |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | Zeichnen ohne Indexpuffer. |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | Führe einen indizierten Zeichenvorgang in eine Befehlsliste aus. |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | Führe einen indizierten Zeichenvorgang in eine Befehlsliste aus. |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | Schiebe die Konstante in die Pipeline. |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | Schiebe die Konstante in die Pipeline. |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


