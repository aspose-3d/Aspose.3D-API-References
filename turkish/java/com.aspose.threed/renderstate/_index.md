---
title: "RenderState"
second_title: "Aspose.3D for Java API Referansı"
description: "İşlem hattı oluşturmak için render durumu  Render durumunda yapılan değişiklikler oluşturulan işlem hattı örneklerini etkilemez."
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
| [RenderState()](#RenderState--) | [RenderState](../../com.aspose.threed/renderstate) yapıcısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | [RenderState](../../com.aspose.threed/renderstate) nesnesini serbest bırakın ve tüm dahili kaynakları serbest bırakın. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Render durumunu başka bir örnekle karşılaştırın. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen bir nesneye eşit olup olmadığını gösteren bir değer döndürür. |
| [getBlend()](#getBlend--) | Parçacık harmanlamasını etkinleştirin veya devre dışı bırakın. |
| [getBlendColor()](#getBlendColor--) | [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde harmanlama rengini alır. |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Yüz kapatmayı etkinleştirin veya devre dışı bırakın. |
| [getCullFaceMode()](#getCullFaceMode--) | Hangi yüzün kapatılacağını alır. |
| [getDepthFunction()](#getDepthFunction--) | Derinlik testinde kullanılan karşılaştırma işlevini alır. |
| [getDepthMask()](#getDepthMask--) | Derinlik yazımını etkinleştirin veya devre dışı bırakın. |
| [getDepthTest()](#getDepthTest--) | Derinlik testini etkinleştirin veya devre dışı bırakın. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Rengin nasıl harmanlandığını alır. |
| [getFrontFace()](#getFrontFace--) | Hangi sıranın ön yüz olduğunu alır. |
| [getPolygonMode()](#getPolygonMode--) | Poligonun render modunu alır. |
| [getScissorTest()](#getScissorTest--) | Makas testini etkinleştirin veya devre dışı bırakın. |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Rengin nasıl harmanlandığını alır. |
| [getStencilBackFace()](#getStencilBackFace--) | Arka yüz için şablon durumunu alır. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Ön yüz için şablon durumunu alır. |
| [getStencilMask()](#getStencilMask--) | Test tamamlandığında hem referans hem de depolanan şablon değeriyle AND yapılan maskeyi alır. |
| [getStencilReference()](#getStencilReference--) | Şablon testi için referans değerini alır. |
| [getStencilTest()](#getStencilTest--) | Şablon testini etkinleştirin veya devre dışı bırakın. |
| [hashCode()](#hashCode--) | Bu örnek için hash kodunu döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Parçacık harmanlamasını etkinleştirin veya devre dışı bırakın. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde harmanlama rengini ayarlar. |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Yüz kapatmayı etkinleştirin veya devre dışı bırakın. |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Hangi yüzün kapatılacağını ayarlar. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Derinlik testinde kullanılan karşılaştırma işlevini ayarlar. |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Derinlik yazımını etkinleştirin veya devre dışı bırakın. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Derinlik testini etkinleştirin veya devre dışı bırakın. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Rengin nasıl harmanlandığını ayarlar. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Hangi sıranın ön yüz olduğunu ayarlar. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Poligonun render modunu ayarlar. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Makas testini etkinleştirin veya devre dışı bırakın. |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Rengin nasıl harmanlandığını ayarlar. |
| [setStencilMask(int value)](#setStencilMask-int-) | Test tamamlandığında hem referans hem de depolanan stencil değeriyle AND'lenen maskeyi ayarlar. |
| [setStencilReference(int value)](#setStencilReference-int-) | Stencil testi için referans değerini ayarlar. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Şablon testini etkinleştirin veya devre dışı bırakın. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


[RenderState](../../com.aspose.threed/renderstate) yapıcısı

### close() {#close--}
```
public void close()
```


[RenderState](../../com.aspose.threed/renderstate) nesnesini serbest bırakın ve tüm dahili kaynakları serbest bırakın.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Render durumunu başka bir örnekle karşılaştırın.

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


Parçacık harmanlamasını etkinleştirin veya devre dışı bırakın.

**Returns:**
boolean - Parçacık karıştırmayı etkinleştir veya devre dışı bırak.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


[BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde harmanlama rengini alır.

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


Yüz kapatmayı etkinleştirin veya devre dışı bırakın.

**Returns:**
boolean - Yüz silmeyi etkinleştir veya devre dışı bırak
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Hangi yüzün kapatılacağını alır.

**Returns:**
int - Hangi yüzün silineceği.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Derinlik testinde kullanılan karşılaştırma işlevini alır.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Derinlik yazımını etkinleştirin veya devre dışı bırakın.

**Returns:**
boolean - Derinlik yazmayı etkinleştir veya devre dışı bırak.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Derinlik testini etkinleştirin veya devre dışı bırakın.

**Returns:**
boolean - Derinlik testini etkinleştir veya devre dışı bırak.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Rengin nasıl harmanlandığını alır.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Hangi sıranın ön yüz olduğunu alır.

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


Makas testini etkinleştirin veya devre dışı bırakın.

**Returns:**
boolean - Makas testini etkinleştir veya devre dışı bırak
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Rengin nasıl harmanlandığını alır.

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


Test tamamlandığında hem referans hem de depolanan şablon değeriyle AND yapılan maskeyi alır.

**Returns:**
int - Test tamamlandığında hem referans hem de depolanan stencil değeriyle AND'lenen maskeyi.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Şablon testi için referans değerini alır.

**Returns:**
int - Stencil testi için referans değeri.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Şablon testini etkinleştirin veya devre dışı bırakın.

**Returns:**
boolean - Stencil testini etkinleştir veya devre dışı bırak.
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


Parçacık harmanlamasını etkinleştirin veya devre dışı bırakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


[BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) içinde kullanıldığı yerde harmanlama rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Yeni değer |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Yüz kapatmayı etkinleştirin veya devre dışı bırakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Hangi yüzün kapatılacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Derinlik testinde kullanılan karşılaştırma işlevini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Yeni değer |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Derinlik yazımını etkinleştirin veya devre dışı bırakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Derinlik testini etkinleştirin veya devre dışı bırakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Rengin nasıl harmanlandığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Yeni değer |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Hangi sıranın ön yüz olduğunu ayarlar.

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


Makas testini etkinleştirin veya devre dışı bırakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Rengin nasıl harmanlandığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Yeni değer |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Test tamamlandığında hem referans hem de depolanan stencil değeriyle AND'lenen maskeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Stencil testi için referans değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Şablon testini etkinleştirin veya devre dışı bırakın.

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

