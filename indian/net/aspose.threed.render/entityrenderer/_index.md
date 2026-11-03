---
title: "क्लास EntityRenderer"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Render.EntityRenderer क्लास। विभिन्न प्रकार की इकाइयों के लिए रेंडरिंग लागू करने हेतु इसे सबक्लास करें"
type: docs
weight: 1970
url: /hi/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

विभिन्न प्रकार की इकाइयों के लिए रेंडरिंग लागू करने हेतु इसे सबक्लास करें।

```csharp
public class EntityRenderer
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | `EntityRenderer` का कन्स्ट्रक्टर |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | `EntityRenderer` का कन्स्ट्रक्टर |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | इकाई रेंडरर को नष्ट किया जा रहा है, साझा संसाधनों को मुक्त करें। |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | फ़्रेम की रेंडरिंग शुरू करें |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | फ़्रेम की रेंडरिंग समाप्त करता है |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | इकाई रेंडरर को प्रारंभ करें |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | निर्दिष्ट नोड/इकाई जोड़ी के लिए रेंडरिंग कमांड तैयार करें। |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | प्रत्येक रेंडर टास्क जिसे [`IRenderQueue`](../irenderqueue/) में धकेला जाता है, उसके पास एक संबंधित RenderEntity कॉल होगा जो ठोस रेंडरिंग कार्य को निष्पादित करेगा। |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | दृश्य बदल गया है या हटाया गया है, इस में दृश्य-स्तर के रेंडर संसाधनों को नष्ट करने की आवश्यकता है। |

### देखें भी

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


