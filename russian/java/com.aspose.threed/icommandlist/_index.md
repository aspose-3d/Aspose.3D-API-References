---
title: ICommandList
second_title: Справочник API Aspose.3D для Java
description: Кодирует последовательность команд, которые будут отправлены на GPU для рендеринга.
type: docs
weight: 240
url: /ru/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

Кодирует последовательность команд, которые будут отправлены на GPU для рендеринга.
## Методы

| Метод | Описание |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | Привязать набор дескрипторов к текущему конвейеру |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | Привязать индексный буфер для рендеринга |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | Привязать экземпляр конвейера для рендеринга |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | Привязать буфер вершин для рендеринга |
| [draw()](#draw--) | Отрисовать без индексного буфера |
| [draw(int start, int count)](#draw-int-int-) | Отрисовать без индексного буфера |
| [drawIndex()](#drawIndex--) | Выполнить индексированную отрисовку в список команд |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | Выполнить индексированную отрисовку в список команд |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | Передать константу в конвейер |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | Передать константу в конвейер |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


Привязать набор дескрипторов к текущему конвейеру

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


Привязать индексный буфер для рендеринга

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


Привязать экземпляр конвейера для рендеринга

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


Привязать буфер вершин для рендеринга

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


Отрисовать без индексного буфера

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


Отрисовать без индексного буфера

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| начало | int |  |
| количество | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


Выполнить индексированную отрисовку в список команд

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


Выполнить индексированную отрисовку в список команд

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| начало | int | Первый индекс для отрисовки |
| количество | int | Количество индексов для отрисовки |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


Передать константу в конвейер

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| этап | int | Какой этап шейдера будет использовать константные данные |
| данные | byte[] | Данные, которые будут отправлены в шейдер |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


Передать константу в конвейер

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| этап | int | Какой этап шейдера будет использовать константные данные |
| данные | byte[] | Данные, которые будут отправлены в шейдер |
| размер | int | Байты для записи в конвейер |

