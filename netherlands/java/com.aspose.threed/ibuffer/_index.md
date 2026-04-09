---
title: IBuffer
second_title: Aspose.3D for Java API-referentie
description: De basisinterface van alle beheerde buffers die worden gebruikt bij het renderen
type: docs
weight: 239
url: /nl/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

De basisinterface van alle beheerde buffers die worden gebruikt bij het renderen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSize()](#getSize--) | Grootte van deze buffer in bytes |
| [loadData(byte[] data)](#loadData-byte---) | Laad de gegevens in de huidige buffer |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Grootte van deze buffer in bytes

**Returns:**
int - Grootte van deze buffer in bytes
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Laad de gegevens in de huidige buffer

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] |  |

