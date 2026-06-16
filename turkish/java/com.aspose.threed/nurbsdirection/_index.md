---
title: "NurbsDirection"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir 3D  iki yön içerir,  ve  ,  her yön için verileri tanımlar."
type: docs
weight: 113
url: /tr/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

Bir 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) iki yön içerir, [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) ve [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), [NurbsDirection](../../com.aspose.threed/nurbsdirection) her yön için verileri tanımlar. Bir yön aslında bir NURBS eğrisidir, bu da onun [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), bir [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors) ve [NurbsSurface](../../com.aspose.threed/nurbssurface) içinde tanımlanan ağırlıklı kontrol noktaları kümesi ile tanımlandığı anlamına gelir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Yeni bir [NurbsDirection](../../com.aspose.threed/nurbsdirection) örneği oluştur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mevcut yönde kontrol noktalarının sayısını döndürür. |
| [getDegree()](#getDegree--) | NURBS eğrisinin derecesini alır, derece Sipariş - 1 olarak tanımlanır |
| [getDivisions()](#getDivisions--) | Mevcut yönde bitişik kontrol noktaları arasındaki bölünme sayısını alır. |
| [getKnotVectors()](#getKnotVectors--) | Düğüm vektörünü alır, bu, kontrol noktalarının NURBS eğrisini nerede ve nasıl etkilediğini belirleyen parametre değerleri dizisidir. |
| [getMultiplicity()](#getMultiplicity--) | Çokluğu alır. |
| [getOrder()](#getOrder--) | NURBS eğrisinin derecesini alır, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar. |
| [getType()](#getType--) | Mevcut yönün tipini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Mevcut yönde kontrol noktalarının sayısını ayarlar. |
| [setDegree(int value)](#setDegree-int-) | NURBS eğrisinin derecesini ayarlar, derece Sipariş - 1 olarak tanımlanır |
| [setDivisions(int value)](#setDivisions-int-) | Mevcut yönde bitişik kontrol noktaları arasındaki bölünme sayısını ayarlar. |
| [setOrder(int value)](#setOrder-int-) | NURBS eğrisinin derecesini ayarlar, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Mevcut yönün tipini ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Yeni bir [NurbsDirection](../../com.aspose.threed/nurbsdirection) örneği oluştur

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
### getCount() {#getCount--}
```
public int getCount()
```


Mevcut yönde kontrol noktalarının sayısını döndürür.

**Returns:**
int - mevcut yönde kontrol noktalarının sayısı.
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS eğrisinin derecesini alır, derece Sipariş - 1 olarak tanımlanır

**Returns:**
int - NURBS eğrisinin derecesi, derece Sipariş - 1 olarak tanımlanır
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Mevcut yönde bitişik kontrol noktaları arasındaki bölünme sayısını alır.

**Returns:**
int - mevcut yönde bitişik kontrol noktaları arasındaki bölünme sayısı.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Düğüm vektörünü alır, bu, kontrol noktalarının NURBS eğrisini nerede ve nasıl etkilediğini belirleyen parametre değerleri dizisidir.

**Returns:**
java.util.List<java.lang.Double> - düğüm vektörü, bu, kontrol noktalarının NURBS eğrisini nerede ve nasıl etkilediğini belirleyen parametre değerleri dizisidir.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Çokluğu alır.

**Returns:**
java.util.List<java.lang.Integer> - çokluk.
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS eğrisinin derecesini alır, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar.

**Returns:**
int - bir NURBS eğrisinin derecesi, eğri üzerindeki herhangi bir noktayı etkileyen yakın kontrol noktalarının sayısını tanımlar.
### getType() {#getType--}
```
public NurbsType getType()
```


Mevcut yönün tipini alır.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
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




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Mevcut yönde kontrol noktalarının sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS eğrisinin derecesini ayarlar, derece Sipariş - 1 olarak tanımlanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Mevcut yönde bitişik kontrol noktaları arasındaki bölünme sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS eğrisinin derecesini ayarlar, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Mevcut yönün tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Yeni değer |

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

