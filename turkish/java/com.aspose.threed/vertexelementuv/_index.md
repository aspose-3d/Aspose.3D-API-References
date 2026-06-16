---
title: "VertexElementUV"
second_title: "Aspose.3D for Java API Referansı"
description: "Belirtilen bileşenler için UV koordinatlarını tanımlar."
type: docs
weight: 220
url: /tr/java/com.aspose.threed/vertexelementuv/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementUV extends VertexElementVector4
```

Belirtilen bileşenler için UV koordinatlarını tanımlar. Bir geometri birden fazla [VertexElementUV](../../com.aspose.threed/vertexelementuv) öğesine sahip olabilir ve her biri farklı [TextureMapping](../../com.aspose.threed/texturemapping) öğelerine sahiptir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VertexElementUV()](#VertexElementUV--) | Yeni bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) sınıfı örneği başlatır. |
| [VertexElementUV(TextureMapping textureMapping)](#VertexElementUV-com.aspose.threed.TextureMapping-) | Yeni bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addData(Iterable<Vector2> data)](#addData-java.lang.Iterable-com.aspose.threed.Vector2--) | VertexElementUV.Data'ye bir [Vector2](../../com.aspose.threed/vector2) kümesi ekle. |
| [addData2(Iterable<Vector3> data)](#addData2-java.lang.Iterable-com.aspose.threed.Vector3--) | VertexElementUV.Data'ye bir [Vector3](../../com.aspose.threed/vector3) kümesi ekle. |
| [clear()](#clear--) | Doğrudan ve indeks dizilerinden tüm öğeleri kaldırır. |
| [clone(boolean withData)](#clone-boolean-) | Vertex öğesinin derin kopyasını oluştur. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | Verileri belirtilen öğeye kopyalar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Vertex verisini alır. |
| [getIndices()](#getIndices--) | İndeks verisini alır. |
| [getMappingMode()](#getMappingMode--) | Öğenin nasıl eşlendiğini alır. |
| [getName()](#getName--) | Adı alır. |
| [getReferenceMode()](#getReferenceMode--) | Öğenin nasıl başvurulduğunu alır. |
| [getVertexElementType()](#getVertexElementType--) | [VertexElement](../../com.aspose.threed/vertexelement) tipini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | Veriyi yükle |
| [setIndices(int[] data)](#setIndices-int---) | İndeksleri yükle |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Öğenin nasıl eşlendiğini ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Öğenin nasıl başvurulduğunu ayarlar. |
| [toString()](#toString--) | Vertex öğesinin dize temsili. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUV() {#VertexElementUV--}
```
public VertexElementUV()
```


Yeni bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) sınıfı örneği başlatır. Varsayılan doku eşleme türü [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) dir.

### VertexElementUV(TextureMapping textureMapping) {#VertexElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV(TextureMapping textureMapping)
```


Yeni bir [VertexElementUV](../../com.aspose.threed/vertexelementuv) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Doku eşleme türü. |

### addData(Iterable<Vector2> data) {#addData-java.lang.Iterable-com.aspose.threed.Vector2--}
```
public void addData(Iterable<Vector2> data)
```


VertexElementUV.Data'ye bir [Vector2](../../com.aspose.threed/vector2) kümesi ekle. Bu bir kısayoldur, bu yöntem [Vector2](../../com.aspose.threed/vector2)'yi z'yi 0 ve w'yi 0 olarak ayarlayarak [Vector4](../../com.aspose.threed/vector4)'e dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | java.lang.Iterable<com.aspose.threed.Vector2> |  |

### addData2(Iterable<Vector3> data) {#addData2-java.lang.Iterable-com.aspose.threed.Vector3--}
```
public void addData2(Iterable<Vector3> data)
```


VertexElementUV.Data'ye bir [Vector3](../../com.aspose.threed/vector3) kümesi ekle. Bu bir kısayoldur, bu yöntem [Vector3](../../com.aspose.threed/vector3)'yi w'yi 0 olarak ayarlayarak [Vector4](../../com.aspose.threed/vector4)'e dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | java.lang.Iterable<com.aspose.threed.Vector3> |  |

### clear() {#clear--}
```
public void clear()
```


Doğrudan ve indeks dizilerinden tüm öğeleri kaldırır.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Vertex öğesinin derin kopyasını oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| withData | boolean | Vertex'i doğrudan ve indeks dizisiyle kopyala. |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


Verileri belirtilen öğeye kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | Hedef. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public List<Vector4> getData()
```


Vertex verisini alır.

**Returns:**
java.util.List<com.aspose.threed.Vector4> - köşe verisi
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


İndeks verisini alır.

**Returns:**
java.util.List<java.lang.Integer> - indeks verisi
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Öğenin nasıl eşlendiğini alır.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Öğenin nasıl başvurulduğunu alır.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


[VertexElement](../../com.aspose.threed/vertexelement) tipini alır.

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


Veriyi yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


İndeksleri yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Öğenin nasıl eşlendiğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Öğenin nasıl başvurulduğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Yeni değer |

### toString() {#toString--}
```
public String toString()
```


Vertex öğesinin dize temsili.

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

