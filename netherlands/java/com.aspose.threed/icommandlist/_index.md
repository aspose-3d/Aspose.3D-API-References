---
title: ICommandList
second_title: Aspose.3D for Java API-referentie
description: Codeert een reeks commando's die naar de GPU worden gestuurd om te renderen.
type: docs
weight: 240
url: /nl/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Codeert een reeks commando's die naar de GPU worden gestuurd om te renderen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Koppel de descriptorset aan de huidige pipeline |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Koppel de indexbuffer voor weergave |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Koppel de pipeline‑instantie voor weergave |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Koppel de vertexbuffer voor weergave |
| [draw()](#draw--) | Teken zonder indexbuffer |
| [draw(int start, int count)](#draw-int-int-) | Teken zonder indexbuffer |
| [drawIndex()](#drawIndex--) | Voer een geïndexeerde tekening uit in een commandolijst |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Voer een geïndexeerde tekening uit in een commandolijst |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Stuur de constante naar de pipeline |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Stuur de constante naar de pipeline |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Koppel de descriptorset aan de huidige pipeline

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Koppel de indexbuffer voor weergave

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Koppel de pipeline‑instantie voor weergave

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Koppel de vertexbuffer voor weergave

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Teken zonder indexbuffer

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Teken zonder indexbuffer

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| begin | int |  |
| aantal | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Voer een geïndexeerde tekening uit in een commandolijst

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Voer een geïndexeerde tekening uit in een commandolijst

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| begin | int | De eerste index om te tekenen |
| aantal | int | Het aantal indexen om te tekenen |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Stuur de constante naar de pipeline

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fase | int | Welke shaderfase de constante gegevens zal gebruiken |
| gegevens | byte[] | De gegevens die naar de shader worden verzonden |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Stuur de constante naar de pipeline

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fase | int | Welke shaderfase de constante gegevens zal gebruiken |
| gegevens | byte[] | De gegevens die naar de shader worden verzonden |
| grootte | int | Bytes om naar de pipeline te schrijven |

