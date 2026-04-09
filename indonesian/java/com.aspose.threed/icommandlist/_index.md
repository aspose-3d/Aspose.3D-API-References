---
title: ICommandList
second_title: Referensi API Aspose.3D untuk Java
description: Menyandi urutan perintah yang akan dikirim ke GPU untuk merender.
type: docs
weight: 240
url: /id/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Menyandi urutan perintah yang akan dikirim ke GPU untuk merender.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Mengikat set deskriptor ke pipeline saat ini |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Ikat buffer indeks untuk rendering |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Ikat instance pipeline untuk rendering |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Ikat buffer verteks untuk rendering |
| [draw()](#draw--) | Gambar tanpa buffer indeks |
| [draw(int start, int count)](#draw-int-int-) | Gambar tanpa buffer indeks |
| [drawIndex()](#drawIndex--) | Lakukan gambar terindeks ke dalam daftar perintah |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Lakukan gambar terindeks ke dalam daftar perintah |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Dorong konstanta ke pipeline |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Dorong konstanta ke pipeline |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Mengikat set deskriptor ke pipeline saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Ikat buffer indeks untuk rendering

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Ikat instance pipeline untuk rendering

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Ikat buffer verteks untuk rendering

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Gambar tanpa buffer indeks

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Gambar tanpa buffer indeks

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mulai | int |  |
| jumlah | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Lakukan gambar terindeks ke dalam daftar perintah

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Lakukan gambar terindeks ke dalam daftar perintah

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mulai | int | Indeks pertama yang akan digambar |
| jumlah | int | Jumlah indeks yang akan digambar |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Dorong konstanta ke pipeline

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tahap | int | Tahap shader mana yang akan mengkonsumsi data konstanta |
| data | byte[] | Data yang akan dikirim ke shader |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Dorong konstanta ke pipeline

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tahap | int | Tahap shader mana yang akan mengkonsumsi data konstanta |
| data | byte[] | Data yang akan dikirim ke shader |
| ukuran | int | Byte yang akan ditulis ke pipeline |

