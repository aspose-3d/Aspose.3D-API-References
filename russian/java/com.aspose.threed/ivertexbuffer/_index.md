---
title: IVertexBuffer
second_title: Справочник API Aspose.3D для Java
description: Вершинный буфер хранит данные вершин полигонов, которые будут отправлены в конвейер рендеринга.
type: docs
weight: 259
url: /ru/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

Вершинный буфер хранит данные вершин полигонов, которые будут отправлены в конвейер рендеринга.
## Методы

| Метод | Описание |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Получает объявление вершины |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Загрузить данные вершин из [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Загрузить данные из массива |
| [loadData(long data, int size)](#loadData-long-int-) | Загрузить данные из заданной позиции |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Получает объявление вершины

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Загрузить данные вершин из [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Загрузить данные из массива

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Загрузить данные из заданной позиции

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long |  |
| размер | int |  |

