---
title: "FileStream"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تم الإنشاء بواسطة lexchou في 16/6/2017."
type: docs
weight: 66
url: /ar/java/com.aspose.threed/filestream/
---

**Inheritance:**
java.lang.Object، [com.aspose.threed.Stream](../../com.aspose.threed/stream)
```
public class FileStream extends Stream
```

تم الإنشاء بواسطة lexchou في 16/6/2017.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FileStream(String fileName, int fileMode, int fileAccess)](#FileStream-java.lang.String-int-int-) |  |
| [FileStream(String fileName, int fileMode)](#FileStream-java.lang.String-int-) |  |
| [FileStream(File file, int fileMode, int fileAccess)](#FileStream-java.io.File-int-int-) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [APPEND](#APPEND) |  |
| [CREATE](#CREATE) |  |
| [OPEN](#OPEN) |  |
| [READ](#READ) |  |
| [READ_WRITE](#READ-WRITE) |  |
| [SEEK_CURRENT](#SEEK-CURRENT) |  |
| [SEEK_END](#SEEK-END) |  |
| [SEEK_SET](#SEEK-SET) |  |
| [WRITE](#WRITE) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) |  |
| [copyTo(Stream output)](#copyTo-com.aspose.threed.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) |  |
| [getClass()](#getClass--) |  |
| [getInputStream()](#getInputStream--) |  |
| [getLength()](#getLength--) |  |
| [getOutputStream()](#getOutputStream--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] buf)](#read-byte---) |  |
| [read(byte[] buf, int start, int len)](#read-byte---int-int-) |  |
| [read(ByteSpan bytes)](#read-com.aspose.threed.ByteSpan-) |  |
| [readByte()](#readByte--) |  |
| [seek(long offset, int seek)](#seek-long-int-) |  |
| [setLength(long len)](#setLength-long-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [wrap(InputStream stream)](#wrap-java.io.InputStream-) |  |
| [wrap(OutputStream stream)](#wrap-java.io.OutputStream-) | غلف OutputStream كـ Stream، يجب إغلاق الدفق لتفريغ البيانات إلى تدفق الإخراج. |
| [write(byte[] buf)](#write-byte---) |  |
| [write(byte[] buf, int start, int len)](#write-byte---int-int-) |  |
| [write(ByteSpan bytes)](#write-com.aspose.threed.ByteSpan-) |  |
| [writeByte(int b)](#writeByte-int-) |  |
### FileStream(String fileName, int fileMode, int fileAccess) {#FileStream-java.lang.String-int-int-}
```
public FileStream(String fileName, int fileMode, int fileAccess)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String |  |
| fileMode | int |  |
| fileAccess | int |  |

### FileStream(String fileName, int fileMode) {#FileStream-java.lang.String-int-}
```
public FileStream(String fileName, int fileMode)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String |  |
| fileMode | int |  |

### FileStream(File file, int fileMode, int fileAccess) {#FileStream-java.io.File-int-int-}
```
public FileStream(File file, int fileMode, int fileAccess)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| file | java.io.File |  |
| fileMode | int |  |
| fileAccess | int |  |

### APPEND {#APPEND}
```
public static final int APPEND
```


### CREATE {#CREATE}
```
public static final int CREATE
```


### OPEN {#OPEN}
```
public static final int OPEN
```


### READ {#READ}
```
public static final int READ
```


### READ_WRITE {#READ-WRITE}
```
public static final int READ_WRITE
```


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


### WRITE {#WRITE}
```
public static final int WRITE
```


### close() {#close--}
```
public void close()
```




### copyTo(Stream output) {#copyTo-com.aspose.threed.Stream-}
```
public void copyTo(Stream output)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| output | [Stream](../../com.aspose.threed/stream) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```




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
| معامل | نوع | الوصف |
| --- | --- | --- |
| buf | byte[] |  |

**Returns:**
int
### read(byte[] buf, int start, int len) {#read-byte---int-int-}
```
public int read(byte[] buf, int start, int len)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buf | byte[] |  |
| بدء | int |  |
| len | int |  |

**Returns:**
int
### read(ByteSpan bytes) {#read-com.aspose.threed.ByteSpan-}
```
public int read(ByteSpan bytes)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | com.aspose.threed.ByteSpan |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| offset | long |  |
| seek | int |  |

**Returns:**
long
### setLength(long len) {#setLength-long-}
```
public void setLength(long len)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| len | long |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### wrap(InputStream stream) {#wrap-java.io.InputStream-}
```
public static Stream wrap(InputStream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream |  |

**Returns:**
[Stream](../../com.aspose.threed/stream)
### wrap(OutputStream stream) {#wrap-java.io.OutputStream-}
```
public static Stream wrap(OutputStream stream)
```


غلف OutputStream كـ Stream، يجب إغلاق الدفق لتفريغ البيانات إلى تدفق الإخراج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإخراج للتغليف |

**Returns:**
[Stream](../../com.aspose.threed/stream) - wrapped Stream instance
### write(byte[] buf) {#write-byte---}
```
public void write(byte[] buf)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buf | byte[] |  |

### write(byte[] buf, int start, int len) {#write-byte---int-int-}
```
public void write(byte[] buf, int start, int len)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buf | byte[] |  |
| بدء | int |  |
| len | int |  |

### write(ByteSpan bytes) {#write-com.aspose.threed.ByteSpan-}
```
public void write(ByteSpan bytes)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | com.aspose.threed.ByteSpan |  |

### writeByte(int b) {#writeByte-int-}
```
public void writeByte(int b)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| b | int |  |

