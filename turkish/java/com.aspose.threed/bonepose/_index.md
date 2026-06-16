---
title: "BonePose"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu, bir kemik düğümü için dönüşüm matrisini içerir"
type: docs
weight: 21
url: /tr/java/com.aspose.threed/bonepose/
---

**Inheritance:**
java.lang.Object
```
public class BonePose
```

Bu [BonePose](../../com.aspose.threed/bonepose) bir kemik düğümü için dönüşüm matrisini içerir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BonePose()](#BonePose--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Geçerli pozda düğümün dönüşüm matrisini alır. |
| [getNode()](#getNode--) | Sahne düğümünü alır, bir kaplamalı iskelet düğümüne işaret eder |
| [hashCode()](#hashCode--) |  |
| [isLocal()](#isLocal--) | Matrisin yerel koordinatta tanımlanıp tanımlanmadığını alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLocal(boolean value)](#setLocal-boolean-) | Matrisin yerel koordinatta tanımlanıp tanımlanmadığını ayarlar. |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | Geçerli pozda düğümün dönüşüm matrisini ayarlar. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Sahne düğümünü ayarlar, bir kaplamalı iskelet düğümüne işaret eder. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BonePose() {#BonePose--}
```
public BonePose()
```


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
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


Geçerli pozda düğümün dönüşüm matrisini alır.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node in current pose.
### getNode() {#getNode--}
```
public Node getNode()
```


Sahne düğümünü alır, bir kaplamalı iskelet düğümüne işaret eder

**Returns:**
[Node](../../com.aspose.threed/node) - the scene node, points to a skinned skeleton node
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLocal() {#isLocal--}
```
public boolean isLocal()
```


Matrisin yerel koordinatta tanımlanıp tanımlanmadığını alır.

**Returns:**
boolean - matrisin yerel koordinatta tanımlanıp tanımlanmadığı.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLocal(boolean value) {#setLocal-boolean-}
```
public void setLocal(boolean value)
```


Matrisin yerel koordinatta tanımlanıp tanımlanmadığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


Geçerli pozda düğümün dönüşüm matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Yeni değer |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Sahne düğümünü ayarlar, bir kaplamalı iskelet düğümüne işaret eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Yeni değer |

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

