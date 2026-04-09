---
title: IRenderQueue
second_title: Aspose.3D for Java API Reference
description: एंटिटी रेंडरर इस कतार का उपयोग रेंडर कार्यों को प्रबंधित करने के लिए करता है।
type: docs
weight: 248
url: /hi/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

एंटिटी रेंडरर इस कतार का उपयोग रेंडर कार्यों को प्रबंधित करने के लिए करता है।
## Methods

| Method | विवरण |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | रेंडर टास्क को रेंडर कतार में जोड़ें। |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


रेंडर टास्क को रेंडर कतार में जोड़ें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | रेंडर टास्क किस कतार समूह में होगा |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | इस रेंडर टास्क के लिए उपयोग किया गया पाइपलाइन इंस्टेंस |
| renderableResource | java.lang.Object | कस्टम ऑब्जेक्ट जो [EntityRenderer](../../com.aspose.threed/entityrenderer) को भेजा जाएगा |
| subEntity | int | सब एंटिटीज़ का इंडेक्स, उपयोगी जब इकाई में एक से अधिक सब रेंडरेबल कंपोनेंट्स हों। |

