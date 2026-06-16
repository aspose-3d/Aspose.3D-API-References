---
title: "PolygonBuilder"
second_title: "Aspose.3D for Java API Referansı"
description: "Poligon oluşturmak için bir yardımcı sınıf Example için"
type: docs
weight: 133
url: /tr/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Poligon oluşturmak için bir yardımcı sınıf [Mesh](../../com.aspose.threed/mesh) **Örnek:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Eşittir :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Tüm indeksler kullanıma hazırsa, [Mesh](../../com.aspose.threed/mesh) tercih edilir, aksi takdirde [PolygonBuilder](../../com.aspose.threed/polygonbuilder) daha iyi bir seçim olur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Yeni bir [PolygonBuilder](../../com.aspose.threed/polygonbuilder) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Poligona bir köşe indeksi ekler |
| [begin()](#begin--) | Yeni bir poligon eklemeye başlar |
| [end()](#end--) | Poligon oluşturmayı tamamlar |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


Yeni bir [PolygonBuilder](../../com.aspose.threed/polygonbuilder) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Poligonun hangi mesh üzerinde oluşturulacağı. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Poligona bir köşe indeksi ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int |  |

### begin() {#begin--}
```
public void begin()
```


Yeni bir poligon eklemeye başlar

### end() {#end--}
```
public void end()
```


Poligon oluşturmayı tamamlar

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

