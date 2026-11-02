---
title: "RenderState"
second_title: "Aspose.3D for Java API Referansı"
description: "İşlem hattını oluşturmak için render durumu  Render durumunda yapılan değişiklikler oluşturulan işlem hattı örneklerini etkilemez."
type: docs
weight: 151
url: /tr/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Render hattını oluşturmak için render durumu. Render durumunda yapılan değişiklikler, oluşturulan pipeline örneklerini etkilemez.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RenderState()](#RenderState--) | Yapıcı [RenderState](../../com.aspose.threed/renderstate) |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | Serbest bırak [RenderState](../../com.aspose.threed/renderstate) ve tüm dahili kaynakları serbest bırak. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Render durumunu başka bir örnekle karşılaştır |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen bir nesneye eşit olup olmadığını gösteren bir değer döndürür. |
| [getBlend()](#getBlend--) | Parçacık karıştırmayı etkinleştir veya devre dışı bırak. |
| [getBlendColor()](#getBlendColor--) | Karıştırma rengini, [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde alır |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Yüz silmeyi etkinleştir veya devre dışı bırak |
| [getCullFaceMode()](#getCullFaceMode--) | Hangi yüzün silineceğini alır. |
| [getDepthFunction()](#getDepthFunction--) | Derinlik testinde kullanılan karşılaştırma işlevini alır |
| [getDepthMask()](#getDepthMask--) | Derinlik yazmayı etkinleştir veya devre dışı bırak. |
| [getDepthTest()](#getDepthTest--) | Derinlik testini etkinleştir veya devre dışı bırak. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Rengin nasıl karıştırıldığını alır. |
| [getFrontFace()](#getFrontFace--) | Ön yüzün hangi sırada olduğunu alır. |
| [getPolygonMode()](#getPolygonMode--) | Poligonun render modunu alır. |
| [getScissorTest()](#getScissorTest--) | Makas testini etkinleştir veya devre dışı bırak |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Rengin nasıl karıştırıldığını alır. |
| [getStencilBackFace()](#getStencilBackFace--) | Arka yüz için şablon durumunu alır. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Ön yüz için şablon durumunu alır. |
| [getStencilMask()](#getStencilMask--) | Test tamamlandığında hem referans hem de depolanan şablon değeriyle AND edilen maskeyi alır. |
| [getStencilReference()](#getStencilReference--) | Şablon testi için referans değerini alır. |
| [getStencilTest()](#getStencilTest--) | Şablon testini etkinleştir veya devre dışı bırak. |
| [hashCode()](#hashCode--) | Bu örnek için hash kodunu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Parçacık karıştırmayı etkinleştir veya devre dışı bırak. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Karıştırma rengini, [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde ayarlar |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Yüz silmeyi etkinleştir veya devre dışı bırak |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Hangi yüzün silineceğini ayarlar. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Derinlik testinde kullanılan karşılaştırma işlevini ayarlar |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Derinlik yazmayı etkinleştir veya devre dışı bırak. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Derinlik testini etkinleştir veya devre dışı bırak. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Rengin nasıl karıştırıldığını ayarlar. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Ön yüzün hangi sırada olduğunu ayarlar. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Poligonun render modunu ayarlar. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Makas testini etkinleştir veya devre dışı bırak |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Rengin nasıl karıştırıldığını ayarlar. |
| [setStencilMask(int value)](#setStencilMask-int-) | Test tamamlandığında referans ve saklanan şablon değerleriyle AND'lenen maskeyi ayarlar. |
| [setStencilReference(int value)](#setStencilReference-int-) | Şablon testi için referans değerini ayarlar. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Şablon testini etkinleştir veya devre dışı bırak. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Yapıcı [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Serbest bırak [RenderState](../../com.aspose.threed/renderstate) ve tüm dahili kaynakları serbest bırak.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Render durumunu başka bir örnekle karşılaştır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Karşılaştırmak için başka bir render durumu |

**Returns:**
int
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
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Parçacık karıştırmayı etkinleştir veya devre dışı bırak.

**Returns:**
boolean - Parçacık karıştırmayı etkinleştir veya devre dışı bırak.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Karıştırma rengini, [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde alır

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


Yüz silmeyi etkinleştir veya devre dışı bırak

**Returns:**
boolean - Yüz silmeyi etkinleştir veya devre dışı bırak
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Hangi yüzün silineceğini alır.

**Returns:**
int - Hangi yüzün silineceği.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Derinlik testinde kullanılan karşılaştırma işlevini alır

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Derinlik yazmayı etkinleştir veya devre dışı bırak.

**Returns:**
boolean - Derinlik yazmayı etkinleştir veya devre dışı bırak.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Derinlik testini etkinleştir veya devre dışı bırak.

**Returns:**
boolean - Derinlik testini etkinleştir veya devre dışı bırak.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Rengin nasıl karıştırıldığını alır.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Ön yüzün hangi sırada olduğunu alır.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Poligonun render modunu alır.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Makas testini etkinleştir veya devre dışı bırak

**Returns:**
boolean - Makas testini etkinleştir veya devre dışı bırak
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Rengin nasıl karıştırıldığını alır.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Arka yüz için şablon durumunu alır.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Ön yüz için şablon durumunu alır.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Test tamamlandığında hem referans hem de depolanan şablon değeriyle AND edilen maskeyi alır.

**Returns:**
int - Test tamamlandığında referans ve saklanan şablon değerleriyle AND'lenen maske.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Şablon testi için referans değerini alır.

**Returns:**
int - Şablon testi için referans değeri.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Şablon testini etkinleştir veya devre dışı bırak.

**Returns:**
boolean - Şablon testini etkinleştir veya devre dışı bırak.
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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


Parçacık karıştırmayı etkinleştir veya devre dışı bırak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Karıştırma rengini, [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Yeni değer |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Yüz silmeyi etkinleştir veya devre dışı bırak

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Hangi yüzün silineceğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Derinlik testinde kullanılan karşılaştırma işlevini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Yeni değer |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Derinlik yazmayı etkinleştir veya devre dışı bırak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Derinlik testini etkinleştir veya devre dışı bırak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Rengin nasıl karıştırıldığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Yeni değer |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Ön yüzün hangi sırada olduğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Yeni değer |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Poligonun render modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Yeni değer |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Makas testini etkinleştir veya devre dışı bırak

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Rengin nasıl karıştırıldığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Yeni değer |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Test tamamlandığında referans ve saklanan şablon değerleriyle AND'lenen maskeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Şablon testi için referans değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Şablon testini etkinleştir veya devre dışı bırak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

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

