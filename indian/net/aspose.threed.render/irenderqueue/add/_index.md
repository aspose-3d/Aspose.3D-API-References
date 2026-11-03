---
title: "IRenderQueue.Add"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "IRenderQueue मेथड। रेंडर टास्क को रेंडर कतार में जोड़ता है"
type: docs
weight: 10
url: /hi/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

रेंडर कतार में रेंडर कार्य जोड़ें।

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| groupId | RenderQueueGroupId | रेंडर टास्क किस कतार समूह में होगा |
| पाइपलाइन | IPipeline | इस रेंडर कार्य के लिए उपयोग किया गया पाइपलाइन इंस्टेंस |
| renderableResource | Object | कस्टम ऑब्जेक्ट जो [`RenderEntity`](../../entityrenderer/renderentity/) को भेजा जाएगा |
| subEntity | Int32 | सब एंटिटीज़ का सूचकांक, उपयोगी जब एंटिटी एक से अधिक सब रेंडरेबल घटकों से बनी हो। |

### देखें भी

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


