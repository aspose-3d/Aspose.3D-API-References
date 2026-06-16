---
title: "StencilState"
second_title: "Aspose.3D for Java API Referansı"
description: "Yüzey başına şablon durumları."
type: docs
weight: 175
url: /tr/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Yüzey başına şablon durumları.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen bir nesneye eşit olup olmadığını gösteren bir değer döndürür. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Stencil testinde kullanılan karşılaştırma işlevini alır. |
| [getDepthFailAction()](#getDepthFailAction--) | Stencil testi geçtiğinde ancak derinlik testi başarısız olduğunda stencil eylemini alır. |
| [getFailAction()](#getFailAction--) | Stencil testi başarısız olduğunda stencil eylemini alır. |
| [getPassAction()](#getPassAction--) | Stencil testi ve derinlik testi ikisi de geçtiğinde stencil eylemini alır. |
| [hashCode()](#hashCode--) | Bu örnek için hash kodunu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Stencil testinde kullanılan karşılaştırma işlevini ayarlar. |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Stencil testi geçtiğinde ancak derinlik testi başarısız olduğunda stencil eylemini ayarlar. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Stencil testi başarısız olduğunda stencil eylemini ayarlar. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Stencil testi ve derinlik testi ikisi de geçtiğinde stencil eylemini ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen bir nesneye eşit olup olmadığını gösteren bir değer döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


Stencil testinde kullanılan karşılaştırma işlevini alır.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Stencil testi geçtiğinde ancak derinlik testi başarısız olduğunda stencil eylemini alır.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Stencil testi başarısız olduğunda stencil eylemini alır.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Stencil testi ve derinlik testi ikisi de geçtiğinde stencil eylemini alır.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için hash kodunu döndürür.

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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


Stencil testinde kullanılan karşılaştırma işlevini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Yeni değer |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Stencil testi geçtiğinde ancak derinlik testi başarısız olduğunda stencil eylemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Yeni değer |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Stencil testi başarısız olduğunda stencil eylemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Yeni değer |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Stencil testi ve derinlik testi ikisi de geçtiğinde stencil eylemini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Yeni değer |

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

