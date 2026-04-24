---
title: IIndexBuffer
second_title: Справочник API Aspose.3D для Java
description: Индексный буфер описывает геометрию, используемую в конвейере рендеринга.
type: docs
weight: 242
url: /ru/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

Индексный буфер описывает геометрию, используемую в конвейере рендеринга.
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) | Получает количество индексов в этом буфере. |
| [getIndexDataType()](#getIndexDataType--) | Получает тип данных каждого элемента. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Загрузить данные индексов из [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Загрузить данные индексов |
| [loadData(short[] indices)](#loadData-short---) | Загрузить данные индексов |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Получает количество индексов в этом буфере.

**Returns:**
int — количество индексов в этом буфере.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Получает тип данных каждого элемента.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Загрузить данные индексов из [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Загрузить данные индексов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индексы | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Загрузить данные индексов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индексы | short[] |  |

