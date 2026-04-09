---
title: ICommandList
second_title: Aspose.3D for Java API-referens
description: Kodar en sekvens av kommandon som kommer att skickas till GPU för rendering.
type: docs
weight: 240
url: /sv/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Kodar en sekvens av kommandon som kommer att skickas till GPU för rendering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Bind descriptoruppsättningen till den aktuella pipelinen |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Bind indexbufferten för rendering |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Bind pipeline-instansen för rendering |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Bind vertexbufferten för rendering |
| [draw()](#draw--) | Rita utan indexbuffert |
| [draw(int start, int count)](#draw-int-int-) | Rita utan indexbuffert |
| [drawIndex()](#drawIndex--) | Utför en indexerad ritning i en kommandolista |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Utför en indexerad ritning i en kommandolista |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Skicka konstanten till pipeline |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Skicka konstanten till pipeline |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Bind descriptoruppsättningen till den aktuella pipelinen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Bind indexbufferten för rendering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Bind pipeline-instansen för rendering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Bind vertexbufferten för rendering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Rita utan indexbuffert

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Rita utan indexbuffert

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | int |  |
| antal | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Utför en indexerad ritning i en kommandolista

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Utför en indexerad ritning i en kommandolista

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | int | Det första indexet att rita |
| antal | int | Antalet index att rita |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Skicka konstanten till pipeline

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| steg | int | Vilken shadersteg kommer att konsumera den konstanta datan |
| data | byte[] | Datan som kommer att skickas till shadern |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Skicka konstanten till pipeline

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| steg | int | Vilken shadersteg kommer att konsumera den konstanta datan |
| data | byte[] | Datan som kommer att skickas till shadern |
| storlek | int | Byte som ska skrivas till pipeline |

