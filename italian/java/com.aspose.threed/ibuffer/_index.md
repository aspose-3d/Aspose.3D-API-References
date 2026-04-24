---
title: IBuffer
second_title: Aspose.3D for Java API Reference
description: L'interfaccia base di tutti i buffer gestiti utilizzati nel rendering
type: docs
weight: 239
url: /it/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

L'interfaccia base di tutti i buffer gestiti utilizzati nel rendering
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Dimensione di questo buffer in byte |
| [loadData(byte[] data)](#loadData-byte---) | Carica i dati nel buffer corrente |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Dimensione di questo buffer in byte

**Returns:**
int - Dimensione di questo buffer in byte
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Carica i dati nel buffer corrente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] |  |

