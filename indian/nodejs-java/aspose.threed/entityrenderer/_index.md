---
title: "EntityRenderer"
second_title: "Aspose.3D के लिए Node.js के माध्यम से Java API संदर्भ"
description: 
type: docs

url: /hi/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

विभिन्न प्रकार की एंटिटीज़ के लिए रेंडरिंग लागू करने हेतु इसे सबक्लास करें।


## विधियाँ

### constructor{#constructor}

| नाम | विवरण |
| --- | --- |
| constructor(key, features) | EntityRenderer का कंस्ट्रक्टर |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| key | स्ट्रिंग | entity renderer की कुंजी |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| नाम | विवरण |
| --- | --- |
| constructor_overload(key) | EntityRenderer का कंस्ट्रक्टर |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| key | स्ट्रिंग | entity renderer की कुंजी |

 **Result:**



---


### initialize{#initialize}

| नाम | विवरण |
| --- | --- |
| initialize(renderer) | entity renderer को इनिशियलाइज़ करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| rendere | रेंडरर | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| नाम | विवरण |
| --- | --- |
| resetSceneCache() | दृश्य बदल गया है या हटाया गया है, इस में scene-level render resources को मुक्त करने की आवश्यकता है |

 **Result:**



---


### frameBegin{#frameBegin}

| नाम | विवरण |
| --- | --- |
| frameBegin(renderer, renderQueue) | फ़्रेम का रेंडरिंग शुरू करें |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| रेंडरर | रेंडरर | वर्तमान रेंडरर |
| renderQueue | IRenderQueue | रेंडर कतार |

 **Result:**



---


### frameEnd{#frameEnd}

| नाम | विवरण |
| --- | --- |
| frameEnd(renderer, renderQueue) | फ़्रेम का रेंडरिंग समाप्त करता है |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| रेंडरर | रेंडरर | वर्तमान रेंडरर |
| renderQueue | IRenderQueue | रेंडर कतार |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| नाम | विवरण |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | निर्दिष्ट node/entity जोड़ी के लिए रेंडरिंग कमांड तैयार करें। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| रेंडरर | रेंडरर | वर्तमान renderer इंस्टेंस |
| कतार | IRenderQueue | रेंडर कार्यों को प्रबंधित करने के लिए उपयोग की जाने वाली render queue |
| नोड | नोड | वर्तमान नोड |
| एंटिटी | एंटिटी | जिस एंटिटी को रेंडर करने की आवश्यकता है |

 **Result:**



---


### renderEntity{#renderEntity}

| नाम | विवरण |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | com.aspose.threed.IRenderQueue में पुश किया गया प्रत्येक render task के पास एक संबंधित RenderEntity कॉल होगा जो वास्तविक रेंडरिंग कार्य को निष्पादित करेगा। |

 **Parameters:**

| नाम | प्रकार | विवरण |
| --- | --- | --- |
| रेंडरर | रेंडरर | रेंडरर |
| commandList | ICommandList | रेंडरिंग कमांड्स को रिकॉर्ड करने के लिए उपयोग किया गया commandList |
| नोड | नोड | वही नोड जो रेंडर होने वाली इकाई के PrepareRenderQueue को पास किया गया |
| renderableResource | ऑब्जेक्ट | PrepareRenderQueue के दौरान IRenderQueue को पास किया गया कस्टम ऑब्जेक्ट |
| subEntity | Number | subEntity का इंडेक्स जो IRenderQueue को पास किया गया |

 **Result:**



---


### dispose{#dispose}

| नाम | विवरण |
| --- | --- |
| dispose() | एंटिटी रेंडरर को डिस्पोज किया जा रहा है, साझा संसाधनों को रिलीज़ करें। |

 **Result:**



---



