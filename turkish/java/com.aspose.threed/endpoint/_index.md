---
title: "EndPoint"
second_title: "Aspose.3D for Java API Referansı"
description: "Eğriyi kırpmak için uç nokta bir parametre değeri veya Kartezyen nokta olabilir."
type: docs
weight: 51
url: /tr/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Eğriyi kırpmak için son nokta, bir parametre değeri ya da Kartezyen bir nokta olabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Bir Kartezyen noktadan bir [EndPoint](../../com.aspose.threed/endpoint) oluştur. |
| [EndPoint(double v)](#EndPoint-double-) | Gerçek bir parametreden bir [EndPoint](../../com.aspose.threed/endpoint) oluştur. |
| [EndPoint()](#EndPoint--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Derece cinsinden ölçülen bir uç nokta oluştur. |
| [fromRadian(double degree)](#fromRadian-double-) | Radyan cinsinden ölçülen bir uç nokta oluştur. |
| [getAsPoint()](#getAsPoint--) | Uç noktayı Kartezyen nokta olarak alır, aksi takdirde bir istisna fırlatır. |
| [getAsValue()](#getAsValue--) | Uç noktayı gerçek bir parametre olarak alır, aksi takdirde bir istisna fırlatır. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Uç nokta bir Kartezyen nokta mı? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mevcut uç noktanın dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Bir Kartezyen noktadan bir [EndPoint](../../com.aspose.threed/endpoint) oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Oluşturulacak nokta |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Gerçek bir parametreden bir [EndPoint](../../com.aspose.threed/endpoint) oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | double | Uç nokta oluşturmak için gerçek sayı parametresi |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Mevcut örneği kopyala

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Derece cinsinden ölçülen bir uç nokta oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| derece | double | Derece cinsinden değer |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Radyan cinsinden ölçülen bir uç nokta oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| derece | double | Radyan cinsinden değer |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Uç noktayı Kartezyen nokta olarak alır, aksi takdirde bir istisna fırlatır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Uç noktayı gerçek bir parametre olarak alır, aksi takdirde bir istisna fırlatır.

**Returns:**
double - uç nokta gerçek bir parametre olarak, aksi takdirde bir istisna fırlatır.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isCartesianPoint() {#isCartesianPoint--}
```
public boolean isCartesianPoint()
```


Uç nokta bir Kartezyen nokta mı?

**Returns:**
boolean - Uç nokta bir Kartezyen nokta mı?
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


Mevcut uç noktanın dize temsili döndürür.

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

