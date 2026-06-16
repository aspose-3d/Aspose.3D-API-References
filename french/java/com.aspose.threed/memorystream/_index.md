---
title: "MemoryStream"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Créé par lexchou le 13/06/2017."
type: docs
weight: 101
url: /fr/java/com.aspose.threed/memorystream/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.Stream](../../com.aspose.threed/stream)

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class MemoryStream extends Stream implements AutoCloseable
```

Créé par lexchou le 13/06/2017.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MemoryStream()](#MemoryStream--) |  |
| [MemoryStream(int capacity)](#MemoryStream-int-) |  |
| [MemoryStream(byte[] data)](#MemoryStream-byte---) |  |
## Champs

| Champ | Description |
| --- | --- |
| [SEEK_CURRENT](#SEEK-CURRENT) |  |
| [SEEK_END](#SEEK-END) |  |
| [SEEK_SET](#SEEK-SET) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [close()](#close--) |  |
| [copyTo(Stream stream)](#copyTo-com.aspose.threed.Stream-) |  |
| [copyTo(OutputStream stream)](#copyTo-java.io.OutputStream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) |  |
| [getBuffer()](#getBuffer--) |  |
| [getClass()](#getClass--) |  |
| [getInputStream()](#getInputStream--) |  |
| [getLength()](#getLength--) |  |
| [getOutputStream()](#getOutputStream--) |  |
| [getSize()](#getSize--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] buf)](#read-byte---) |  |
| [read(byte[] buf, int start, int len)](#read-byte---int-int-) |  |
| [read(ByteSpan bytes)](#read-com.aspose.threed.ByteSpan-) |  |
| [readByte()](#readByte--) |  |
| [seek(long offset, int seek)](#seek-long-int-) |  |
| [setCapacity(int cap)](#setCapacity-int-) | Définit la capacité à la valeur spécifiée |
| [setLength(long len)](#setLength-long-) |  |
| [toArray()](#toArray--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [wrap(InputStream stream)](#wrap-java.io.InputStream-) |  |
| [wrap(OutputStream stream)](#wrap-java.io.OutputStream-) | Enveloppez un OutputStream en tant que Stream, le flux doit être fermé pour vider les données vers le flux de sortie. |
| [write(byte[] buf)](#write-byte---) |  |
| [write(byte[] buf, int start, int len)](#write-byte---int-int-) |  |
| [write(ByteSpan bytes)](#write-com.aspose.threed.ByteSpan-) |  |
| [writeByte(int b)](#writeByte-int-) |  |
### MemoryStream() {#MemoryStream--}
```
public MemoryStream()
```


### MemoryStream(int capacity) {#MemoryStream-int-}
```
public MemoryStream(int capacity)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| capacité | int |  |

### MemoryStream(byte[] data) {#MemoryStream-byte---}
```
public MemoryStream(byte[] data)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] |  |

### SEEK_CURRENT {#SEEK-CURRENT}
```
public static final int SEEK_CURRENT
```


### SEEK_END {#SEEK-END}
```
public static final int SEEK_END
```


### SEEK_SET {#SEEK-SET}
```
public static final int SEEK_SET
```


### close() {#close--}
```
public void close()
```




### copyTo(Stream stream) {#copyTo-com.aspose.threed.Stream-}
```
public void copyTo(Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### copyTo(OutputStream stream) {#copyTo-java.io.OutputStream-}
```
public void copyTo(OutputStream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```




### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```




**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```




**Returns:**
java.io.InputStream
### getLength() {#getLength--}
```
public long getLength()
```




**Returns:**
long
### getOutputStream() {#getOutputStream--}
```
public OutputStream getOutputStream()
```




**Returns:**
java.io.OutputStream
### getSize() {#getSize--}
```
public int getSize()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### read(byte[] buf) {#read-byte---}
```
public int read(byte[] buf)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buf | byte[] |  |

**Returns:**
int
### read(byte[] buf, int start, int len) {#read-byte---int-int-}
```
public int read(byte[] buf, int start, int len)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buf | byte[] |  |
| début | int |  |
| len | int |  |

**Returns:**
int
### read(ByteSpan bytes) {#read-com.aspose.threed.ByteSpan-}
```
public int read(ByteSpan bytes)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | com.aspose.threed.ByteSpan |  |

**Returns:**
int
### readByte() {#readByte--}
```
public int readByte()
```




**Returns:**
int
### seek(long offset, int seek) {#seek-long-int-}
```
public long seek(long offset, int seek)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| décalage | long |  |
| seek | int |  |

**Returns:**
long
### setCapacity(int cap) {#setCapacity-int-}
```
public void setCapacity(int cap)
```


Définit la capacité à la valeur spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cap | int | nouvelle capacité du flux mémoire. |

### setLength(long len) {#setLength-long-}
```
public void setLength(long len)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| len | long |  |

### toArray() {#toArray--}
```
public byte[] toArray()
```




**Returns:**
byte[]
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### wrap(InputStream stream) {#wrap-java.io.InputStream-}
```
public static Stream wrap(InputStream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream |  |

**Returns:**
[Stream](../../com.aspose.threed/stream)
### wrap(OutputStream stream) {#wrap-java.io.OutputStream-}
```
public static Stream wrap(OutputStream stream)
```


Enveloppez un OutputStream en tant que Stream, le flux doit être fermé pour vider les données vers le flux de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.OutputStream | flux de sortie à envelopper |

**Returns:**
[Stream](../../com.aspose.threed/stream) - wrapped Stream instance
### write(byte[] buf) {#write-byte---}
```
public void write(byte[] buf)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buf | byte[] |  |

### write(byte[] buf, int start, int len) {#write-byte---int-int-}
```
public void write(byte[] buf, int start, int len)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buf | byte[] |  |
| début | int |  |
| len | int |  |

### write(ByteSpan bytes) {#write-com.aspose.threed.ByteSpan-}
```
public void write(ByteSpan bytes)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bytes | com.aspose.threed.ByteSpan |  |

### writeByte(int b) {#writeByte-int-}
```
public void writeByte(int b)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| b | int |  |

