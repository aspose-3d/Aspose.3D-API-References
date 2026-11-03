---
title: "EntityRenderer.RenderEntity"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "EntityRenderer method. IRenderQueue में धकेले गए प्रत्येक रेंडर टास्क के लिए एक संबंधित RenderEntity कॉल होगा जो ठोस रेंडरिंग कार्य को निष्पादित करेगा"
type: docs
weight: 70
url: /hi/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

प्रत्येक रेंडर टास्क जो [`IRenderQueue`](../../irenderqueue/) में धकेला जाता है, उसके लिए एक संबंधित RenderEntity कॉल होगा जो ठोस रेंडरिंग कार्य को निष्पादित करेगा।

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| renderer | Renderer | रेंडरर |
| commandList | ICommandList | रेंडरिंग कमांड्स को रिकॉर्ड करने के लिए उपयोग किया गया commandList |
| नोड | नोड | वह ही नोड जो रेंडर की जाने वाली इकाई के PrepareRenderQueue को पास किया गया है |
| renderableResource | ऑब्जेक्ट | PrepareRenderQueue के दौरान IRenderQueue को पास किया गया कस्टम ऑब्जेक्ट |
| subEntity | Int32 | IRenderQueue को पास किए गए सब एंटिटी का इंडेक्स |

### देखें भी

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


