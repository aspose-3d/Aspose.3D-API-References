---
title: "इंटरफ़ेस ICommandList"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Render.ICommandList इंटरफ़ेस। कमांड्स की एक श्रृंखला को एन्कोड करता है जिसे रेंडर करने के लिए GPU को भेजा जाएगा"
type: docs
weight: 2030
url: /hi/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

रेंडर करने के लिए GPU को भेजे जाने वाले कमांड्स की श्रृंखला को एन्कोड करता है।

```csharp
public interface ICommandList
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | वर्तमान पाइपलाइन से डिस्क्रिप्टर सेट को बाइंड करें |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | रेंडरिंग के लिए इंडेक्स बफ़र को बाइंड करें |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | रेंडरिंग के लिए पाइपलाइन इंस्टेंस को बाइंड करें |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | रेंडरिंग के लिए वर्टेक्स बफ़र को बाइंड करें |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | इंडेक्स बफ़र के बिना ड्रॉ करें |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | इंडेक्स बफ़र के बिना ड्रॉ करें |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | कमांड सूची में एक इंडेक्स्ड ड्रॉ जारी करें |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | कमांड सूची में एक इंडेक्स्ड ड्रॉ जारी करें |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | स्थिर मान को पाइपलाइन में पुश करें |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | स्थिर मान को पाइपलाइन में पुश करें |

### देखें भी

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


