---
title: IBuffer
second_title: Справочник API Aspose.3D для Java
description: Базовый интерфейс всех управляемых буферов, используемых в рендеринге.
type: docs
weight: 239
url: /ru/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

Базовый интерфейс всех управляемых буферов, используемых в рендеринге.
## Методы

| Метод | Описание |
| --- | --- |
| [getSize()](#getSize--) | Размер этого буфера в байтах |
| [loadData(byte[] data)](#loadData-byte---) | Загрузить данные в текущий буфер |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Размер этого буфера в байтах

**Returns:**
int - Размер этого буфера в байтах
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Загрузить данные в текущий буфер

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] |  |

