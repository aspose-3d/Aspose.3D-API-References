---
title: ICommandList
second_title: Aspose.3D for Java API Reference
description: Codifica una sequenza di comandi che saranno inviati alla GPU per il rendering.
type: docs
weight: 240
url: /it/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Codifica una sequenza di comandi che saranno inviati alla GPU per il rendering.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Associa il set di descrittori alla pipeline corrente |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Associa il buffer di indice per il rendering |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Associa l'istanza della pipeline per il rendering |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Associa il buffer dei vertici per il rendering |
| [draw()](#draw--) | Disegna senza buffer di indice |
| [draw(int start, int count)](#draw-int-int-) | Disegna senza buffer di indice |
| [drawIndex()](#drawIndex--) | Esegui un disegno indicizzato in una lista di comandi |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Esegui un disegno indicizzato in una lista di comandi |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Invia la costante alla pipeline |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Invia la costante alla pipeline |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Associa il set di descrittori alla pipeline corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Associa il buffer di indice per il rendering

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Associa l'istanza della pipeline per il rendering

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Associa il buffer dei vertici per il rendering

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Disegna senza buffer di indice

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Disegna senza buffer di indice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inizio | int |  |
| conteggio | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Esegui un disegno indicizzato in una lista di comandi

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Esegui un disegno indicizzato in una lista di comandi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inizio | int | Il primo indice da disegnare |
| conteggio | int | Il numero di indici da disegnare |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Invia la costante alla pipeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fase | int | Quale fase dello shader consumerà i dati costanti |
| dati | byte[] | I dati che saranno inviati allo shader |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Invia la costante alla pipeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fase | int | Quale fase dello shader consumerà i dati costanti |
| dati | byte[] | I dati che saranno inviati allo shader |
| dimensione | int | Byte da scrivere nella pipeline |

