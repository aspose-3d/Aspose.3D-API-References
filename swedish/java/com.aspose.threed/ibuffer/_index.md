---
title: IBuffer
second_title: Aspose.3D for Java API-referens
description: Basgränssnittet för alla hanterade buffertar som används vid rendering
type: docs
weight: 239
url: /sv/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

Basgränssnittet för alla hanterade buffertar som används vid rendering
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Storlek på denna buffert i byte |
| [loadData(byte[] data)](#loadData-byte---) | Läs in data i aktuell buffert |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Storlek på denna buffert i byte

**Returns:**
int - Storlek på denna buffert i byte
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Läs in data i aktuell buffert

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] |  |

