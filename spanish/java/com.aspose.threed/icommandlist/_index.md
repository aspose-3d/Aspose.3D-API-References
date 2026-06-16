---
title: ICommandList
second_title: Referencia de API de Aspose.3D para Java
description: Codifica una secuencia de comandos que se enviarán a la GPU para renderizar.
type: docs
weight: 240
url: /es/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Codifica una secuencia de comandos que se enviarán a la GPU para renderizar.
## Métodos

| Método | Descripción |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Enlazar el conjunto de descriptores al pipeline actual |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Vincular el búfer de índices para renderizar |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Vincular la instancia de la canalización para renderizar |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Vincular el búfer de vértices para renderizar |
| [draw()](#draw--) | Dibujar sin búfer de índices |
| [draw(int start, int count)](#draw-int-int-) | Dibujar sin búfer de índices |
| [drawIndex()](#drawIndex--) | Emitir un dibujo indexado en una lista de comandos |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Emitir un dibujo indexado en una lista de comandos |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Enviar la constante a la canalización |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Enviar la constante a la canalización |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Enlazar el conjunto de descriptores al pipeline actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Vincular el búfer de índices para renderizar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Vincular la instancia de la canalización para renderizar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Vincular el búfer de vértices para renderizar

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Dibujar sin búfer de índices

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Dibujar sin búfer de índices

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inicio | int |  |
| conteo | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Emitir un dibujo indexado en una lista de comandos

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Emitir un dibujo indexado en una lista de comandos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inicio | int | El primer índice a dibujar |
| conteo | int | El número de índices a dibujar |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Enviar la constante a la canalización

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etapa | int | Qué etapa del shader consumirá los datos constantes |
| datos | byte[] | Los datos que se enviarán al shader |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Enviar la constante a la canalización

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etapa | int | Qué etapa del shader consumirá los datos constantes |
| datos | byte[] | Los datos que se enviarán al shader |
| tamaño | int | Bytes a escribir en la canalización |

