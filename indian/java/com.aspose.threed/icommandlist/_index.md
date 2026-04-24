---
title: ICommandList
second_title: Aspose.3D for Java API Reference
description: रेंडर करने के लिए GPU को भेजे जाने वाले कमांड्स की श्रृंखला को एन्कोड करता है।
type: docs
weight: 240
url: /hi/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

रेंडर करने के लिए GPU को भेजे जाने वाले कमांड्स की श्रृंखला को एन्कोड करता है।
## Methods

| Method | विवरण |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | डिस्क्रिप्टर सेट को वर्तमान पाइपलाइन से बाइंड करें |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | रेंडरिंग के लिए इंडेक्स बफ़र को बाइंड करें |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | रेंडरिंग के लिए पाइपलाइन इंस्टेंस को बाइंड करें |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | रेंडरिंग के लिए वर्टेक्स बफ़र को बाइंड करें |
| [draw()](#draw--) | इंडेक्स बफ़र के बिना ड्रॉ करें |
| [draw(int start, int count)](#draw-int-int-) | इंडेक्स बफ़र के बिना ड्रॉ करें |
| [drawIndex()](#drawIndex--) | कमांड लिस्ट में एक इंडेक्स्ड ड्रॉ जारी करें |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | कमांड लिस्ट में एक इंडेक्स्ड ड्रॉ जारी करें |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | कॉन्स्टेंट को पाइपलाइन में पुश करें |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | कॉन्स्टेंट को पाइपलाइन में पुश करें |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


डिस्क्रिप्टर सेट को वर्तमान पाइपलाइन से बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


रेंडरिंग के लिए इंडेक्स बफ़र को बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


रेंडरिंग के लिए पाइपलाइन इंस्टेंस को बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


रेंडरिंग के लिए वर्टेक्स बफ़र को बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


इंडेक्स बफ़र के बिना ड्रॉ करें

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


इंडेक्स बफ़र के बिना ड्रॉ करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| शुरू | int |  |
| गणना | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


कमांड लिस्ट में एक इंडेक्स्ड ड्रॉ जारी करें

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


कमांड लिस्ट में एक इंडेक्स्ड ड्रॉ जारी करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| शुरू | int | ड्रॉ करने के लिए पहला इंडेक्स |
| गणना | int | ड्रॉ करने के लिए इंडेक्स की गणना |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


कॉन्स्टेंट को पाइपलाइन में पुश करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्टेज | int | कौन सा शेडर स्टेज कॉन्स्टेंट डेटा को उपभोग करेगा |
| डेटा | byte[] | डेटा जो शेडर को भेजा जाएगा |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


कॉन्स्टेंट को पाइपलाइन में पुश करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्टेज | int | कौन सा शेडर स्टेज कॉन्स्टेंट डेटा को उपभोग करेगा |
| डेटा | byte[] | डेटा जो शेडर को भेजा जाएगा |
| आकार | int | पाइपलाइन में लिखने के लिए बाइट्स |

