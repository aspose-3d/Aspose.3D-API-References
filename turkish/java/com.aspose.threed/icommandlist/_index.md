---
title: "ICommandList"
second_title: "Aspose.3D for Java API Referansı"
description: "Renderlemek için GPU'ya gönderilecek komut dizisini kodlar."
type: docs
weight: 240
url: /tr/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Renderlemek için GPU'ya gönderilecek komut dizisini kodlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Tanımlayıcı kümesini mevcut boru hattına bağla |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Render için indeks tamponunu bağla |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Render için pipeline örneğini bağla |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Render için vertex tamponunu bağla |
| [draw()](#draw--) | İndeks tamponu olmadan çiz |
| [draw(int start, int count)](#draw-int-int-) | İndeks tamponu olmadan çiz |
| [drawIndex()](#drawIndex--) | Komut listesine indeksli bir çizim gönder |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Komut listesine indeksli bir çizim gönder |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Sabit değeri pipeline'a it |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Sabit değeri pipeline'a it |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Tanımlayıcı kümesini mevcut boru hattına bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Render için indeks tamponunu bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Render için pipeline örneğini bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Render için vertex tamponunu bağla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


İndeks tamponu olmadan çiz

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


İndeks tamponu olmadan çiz

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlat | int |  |
| sayım | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Komut listesine indeksli bir çizim gönder

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Komut listesine indeksli bir çizim gönder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlat | int | Çizilecek ilk indeks |
| sayım | int | Çizilecek indeks sayısı |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Sabit değeri pipeline'a it

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| aşama | int | Hangi gölgelendirici aşaması sabit veriyi tüketecek |
| veri | byte[] | Gölgelendiriciye gönderilecek veri |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Sabit değeri pipeline'a it

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| aşama | int | Hangi gölgelendirici aşaması sabit veriyi tüketecek |
| veri | byte[] | Gölgelendiriciye gönderilecek veri |
| boyut | int | Pipeline'a yazılacak baytlar |

