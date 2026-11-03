---
title: "Διεπαφή ICommandList"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Render.ICommandList interface. Κωδικοποιεί μια ακολουθία εντολών που θα σταλούν στην GPU για απόδοση"
type: docs
weight: 2030
url: /el/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

Κωδικοποιεί μια ακολουθία εντολών που θα σταλούν στην GPU για απόδοση.

```csharp
public interface ICommandList
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | Δέστε το σύνολο περιγραφέων στην τρέχουσα pipeline |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | Δέστε το buffer δεικτών για απόδοση |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | Δέστε το στιγμιότυπο pipeline για απόδοση |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | Δέστε το vertex buffer για απόδοση |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | Σχεδιάστε χωρίς buffer δεικτών |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | Σχεδιάστε χωρίς buffer δεικτών |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | Εκτελέστε μια σχεδίαση με δείκτες σε μια λίστα εντολών |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | Εκτελέστε μια σχεδίαση με δείκτες σε μια λίστα εντολών |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | Σπρώξτε τη σταθερά στην pipeline |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | Σπρώξτε τη σταθερά στην pipeline |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


