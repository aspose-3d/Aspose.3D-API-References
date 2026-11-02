---
title: "VertexDeclaration"
second_title: "Aspose.3D for Java API Referansı"
description: "Özel tanımlı bir köşe yapısının bildirimi"
type: docs
weight: 206
url: /tr/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

Özel tanımlı bir verteksin yapısının bildirimi
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Yeni bir köşe alanı ekle |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Yeni bir köşe alanı ekle |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Yeni bir köşe alanı ekle |
| [clear()](#clear--) | Tüm alanları temizle. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Bu örneği belirtilen bir nesneyle karşılaştırır ve değerlerinin göreceli bir göstergesini döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örnek ile belirtilen nesnenin, aynı zamanda bir [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) nesnesi olması koşuluyla, aynı değere sahip olup olmadığını belirler. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Bir [Geometry](../../com.aspose.threed/geometry) düzenine dayalı bir [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) oluştur. |
| [get(int index)](#get-int-) | İndeksle [VertexField](../../com.aspose.threed/vertexfield) öğesini alır |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Bu [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) içinde tanımlı tüm alanların sayısını alır |
| [getSealed()](#getSealed--) | Bir [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), [TriMesh](../../com.aspose.threed/trimesh) tarafından kullanıldığında mühürlenir, artık değişiklik yapılmasına izin verilmez. |
| [getSize()](#getSize--) | Köşe yapısının bayt cinsinden boyutu. |
| [hashCode()](#hashCode--) | Bu dize için karma kodunu döndürür. |
| [iterator()](#iterator--) | Bu örnekteki tüm köşe alanları arasında gezinmek için bir yineleyici alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) dizesel temsili |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


Yeni bir köşe alanı ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataType | int | Köşe alanının veri tipi |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Bu alan ne amaçla kullanılacak |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Yeni bir köşe alanı ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataType | int | Köşe alanının veri tipi |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Bu alan ne amaçla kullanılacak |
| indeks | int | Aynı alan anlamsalının indeksi, otomatik oluşturma için -1 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Yeni bir köşe alanı ekle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataType | int | Köşe alanının veri tipi |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Bu alan ne amaçla kullanılacak |
| indeks | int | Aynı alan anlamsalının indeksi, otomatik oluşturma için -1 |
| takma ad | java.lang.String | Alan için takma ad |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Tüm alanları temizle.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Bu örneği belirtilen bir nesneyle karşılaştırır ve değerlerinin göreceli bir göstergesini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örnek ile belirtilen nesnenin, aynı zamanda bir [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) nesnesi olması koşuluyla, aynı değere sahip olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Bir [Geometry](../../com.aspose.threed/geometry) düzenine dayalı bir [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | double tipinin yerine float kullanın |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


İndeksle [VertexField](../../com.aspose.threed/vertexfield) öğesini alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Bu [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) içinde tanımlı tüm alanların sayısını alır

**Returns:**
int - bu [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) içinde tanımlanan tüm alanların sayısı
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


Bir [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), [TriMesh](../../com.aspose.threed/trimesh) tarafından kullanıldığında mühürlenir, artık değişiklik yapılmasına izin verilmez.

**Returns:**
boolean - Bir [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), [TriMesh](../../com.aspose.threed/trimesh) tarafından kullanıldığında mühürlenecek, artık değişiklik yapılamaz.
### getSize() {#getSize--}
```
public int getSize()
```


Köşe yapısının bayt cinsinden boyutu.

**Returns:**
int - vertex yapısının bayt cinsinden boyutu.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu dize için karma kodunu döndürür.

**Returns:**
int - 32-bit işaretli tamsayı karma kodu.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Bu örnekteki tüm köşe alanları arasında gezinmek için bir yineleyici alır.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Enumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) dizesel temsili

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

