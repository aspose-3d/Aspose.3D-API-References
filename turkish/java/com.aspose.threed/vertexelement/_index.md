---
title: "VertexElement"
second_title: "Aspose.3D for Java API Referansı"
description: "Vertex elemanlarının temel sınıfı."
type: docs
weight: 207
url: /tr/java/com.aspose.threed/vertexelement/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.IIndexedVertexElement](../../com.aspose.threed/iindexedvertexelement)
```
public abstract class VertexElement implements IIndexedVertexElement
```

Vertex elemanlarının temel sınıfı. Bir vertex eleman tipi VertexElementType tarafından tanımlanır. Bir VertexElement, vertex elemanının bir geometri yüzeyine nasıl eşlendiğini ve eşleme bilgisinin bellekte nasıl düzenlendiğini açıklar. Bir VertexElement Normal, UV veya diğer türde bilgileri içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clear()](#clear--) | Bu vertex elemanındaki tüm verileri temizler. |
| [clone(boolean withData)](#clone-boolean-) | Vertex öğesinin derin kopyasını oluştur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIndices()](#getIndices--) | İndeks verisini alır. |
| [getMappingMode()](#getMappingMode--) | Öğenin nasıl eşlendiğini alır. |
| [getName()](#getName--) | Adı alır. |
| [getReferenceMode()](#getReferenceMode--) | Öğenin nasıl başvurulduğunu alır. |
| [getVertexElementType()](#getVertexElementType--) | [VertexElement](../../com.aspose.threed/vertexelement) tipini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setIndices(int[] data)](#setIndices-int---) | İndeksleri yükle |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Öğenin nasıl eşlendiğini ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Öğenin nasıl başvurulduğunu ayarlar. |
| [toString()](#toString--) | Vertex öğesinin dize temsili. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clear() {#clear--}
```
public abstract void clear()
```


Bu vertex elemanındaki tüm verileri temizler.

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

