---
title: RenderEntity
second_title: .NET API संदर्भ के लिए Aspose.3D
description: प्रत्येक रेंडर टस्क क पुश कय गयIRenderQueueaspose.threed.render/irenderqueue/ ठस रेंडरंग कर्य करने के लए संबंधत RenderEntity call हग
type: docs
weight: 70
url: /hi/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

प्रत्येक रेंडर टास्क को पुश किया गया[`IRenderQueue`](../../irenderqueue/) ठोस रेंडरिंग कार्य करने के लिए संबंधित RenderEntity call होगा।

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderer | Renderer | रेंडरर |
| commandList | ICommandList | कमांड लिस्ट का उपयोग रेंडरिंग कमांड को रिकॉर्ड करने के लिए किया जाता है |
| node | Node | वही नोड जो रेंडर किए जाने वाले निकाय के ReadyRenderQueue को पास किया गया है |
| renderableResource | Object | कस्टम ऑब्जेक्ट जो रेडेंडरक्यू के दौरान IRenderQueue को पास किया गया |
| subEntity | Int32 | IRenderQueue को पारित उप इकाई का सूचकांक |

### यह सभी देखें

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* नाम स्थान [Aspose.ThreeD.Render](../../entityrenderer/)
* सभा [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
