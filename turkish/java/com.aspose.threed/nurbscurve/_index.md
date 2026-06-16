---
title: "NurbsCurve"
second_title: "Aspose.3D for Java API Referansı"
description: "NURBS eğrisi, NURBSNon-uniform rational basis spline tarafından temsil edilen bir eğridir. Bir NURBS eğrisi, ağırlıklı bir dizi kontrol noktası ve bir ... ile tanımlanır. Kontrol noktasındaki w bileşeni, kontrol noktası ağırlığı olarak kullanılır; ne olursa olsun ..."
type: docs
weight: 112
url: /tr/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | Yeni bir [NurbsCurve](../../com.aspose.threed/nurbscurve) sınıfı örneği başlatır. |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | Yeni bir [NurbsCurve](../../com.aspose.threed/nurbscurve) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | NURBS eğrisini değerlendir |
| [evaluate(int steps)](#evaluate-int-) | NURBS eğrisini değerlendir |
| [evaluateAt(double u)](#evaluateAt-double-) | Eğrinin belirtilen konumdaki noktasını değerlendir |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Çizginin rengini alır, varsayılan değer beyaz(1, 1, 1)'dir |
| [getControlPoints()](#getControlPoints--) | Tüm kontrol noktalarını al |
| [getCurveType()](#getCurveType--) | Eğrinin tipini alır. |
| [getDegree()](#getDegree--) | NURBS eğrisinin derecesini alır, derece Sipariş - 1 olarak tanımlanır |
| [getDimension()](#getDimension--) | Eğrinin boyutunu alır. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getKnotVectors()](#getKnotVectors--) | Düğüm vektörünü alır, bu, kontrol noktalarının NURBS eğrisini nerede ve nasıl etkilediğini belirleyen parametre değerleri dizisidir. |
| [getMultiplicity()](#getMultiplicity--) | Çokluğu alır. |
| [getName()](#getName--) | Adı alır. |
| [getOrder()](#getOrder--) | NURBS eğrisinin derecesini alır, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getRational()](#getRational--) | Rasyonel olup olmadığını alır, bu değer bu [NurbsCurve](../../com.aspose.threed/nurbscurve) 'nin rasyonel spline mı yoksa rasyonel olmayan spline mı olduğunu gösterir. |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Çizginin rengini ayarlar, varsayılan değer beyaz(1, 1, 1)'dir |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | Eğrinin tipini ayarlar. |
| [setDegree(int value)](#setDegree-int-) | NURBS eğrisinin derecesini ayarlar, derece Sipariş - 1 olarak tanımlanır |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | Eğrinin boyutunu ayarlar. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setOrder(int value)](#setOrder-int-) | NURBS eğrisinin derecesini ayarlar, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setRational(boolean value)](#setRational-boolean-) | Rasyonel olup olmadığını ayarlar, bu değer bu [NurbsCurve](../../com.aspose.threed/nurbscurve) 'nin rasyonel spline mı yoksa rasyonel olmayan spline mı olduğunu gösterir. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


Yeni bir [NurbsCurve](../../com.aspose.threed/nurbscurve) sınıfı örneği başlatır.

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


Yeni bir [NurbsCurve](../../com.aspose.threed/nurbscurve) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


NURBS eğrisini değerlendir

**Returns:**
com.aspose.threed.Vector4[] - Eğrinin noktaları
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


NURBS eğrisini değerlendir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| adımlar | int | İki komşu düğüm arasındaki değerlendirme frekansı, varsayılan değer 20'dir |

**Returns:**
com.aspose.threed.Vector4[] - Eğrinin noktaları
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


Eğrinin belirtilen konumdaki noktasını değerlendir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| u | double | Eğrinin konumu, 0 ile 1 arasında |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty) veya native property(Identified by its name) olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyName | java.lang.String | Özellik adı. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Çizginin rengini alır, varsayılan değer beyaz(1, 1, 1)'dir

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


Tüm kontrol noktalarını al

**Returns:**
java.util.List<com.aspose.threed.Vector4> - tüm kontrol noktaları
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


Eğrinin tipini alır.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS eğrisinin derecesini alır, derece Sipariş - 1 olarak tanımlanır

**Returns:**
int - NURBS eğrisinin derecesi, derece Sipariş - 1 olarak tanımlanır
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


Eğrinin boyutunu alır.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır

**Returns:**
boolean - bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağı.
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
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS eğrisinin derecesini alır, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar.

**Returns:**
int - bir NURBS eğrisinin derecesi, eğri üzerindeki herhangi bir noktayı etkileyen yakın kontrol noktalarının sayısını tanımlar.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - tüm üst düğümler, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Tüm özelliklerin koleksiyonunu alır.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Belirtilen özelliğin değerini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |

**Returns:**
java.lang.Object - Bulunan özelliğin değeri
### getRational() {#getRational--}
```
public boolean getRational()
```


Rasyonel olup olmadığını alır, bu değer bu [NurbsCurve](../../com.aspose.threed/nurbscurve) nesnesinin rasyonel spline mı yoksa rasyonel olmayan spline mı olduğunu gösterir. Rasyonel olmayan B-spline, rasyonel B-spline'ların özel bir durumudur.

**Returns:**
boolean - rasyonel olup olmadığı, bu değer bu [NurbsCurve](../../com.aspose.threed/nurbscurve) nesnesinin rasyonel spline mı yoksa rasyonel olmayan spline mı olduğunu gösterir. Rasyonel olmayan B-spline, rasyonel B-spline'ların özel bir durumudur.
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Dinamik bir özelliği kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


İsimle tanımlanan belirtilen özelliği kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Hangi özelliğin kaldırılacağı |

**Returns:**
boolean - özellik başarıyla kaldırıldıysa true
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Çizginin rengini ayarlar, varsayılan değer beyaz(1, 1, 1)'dir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


Eğrinin tipini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Yeni değer |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS eğrisinin derecesini ayarlar, derece Sipariş - 1 olarak tanımlanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


Eğrinin boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | Yeni değer **Remarks:** Bir [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) eğri için kontrol noktasındaki z bileşeni kullanılmaz. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS eğrisinin derecesini ayarlar, bu, eğrinin herhangi bir noktasını etkileyen yakın kontrol noktalarının sayısını tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Yeni değer |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Belirtilen özelliğin değerini ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Özellik adı |
| değer | java.lang.Object | Özelliğin değeri |

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


Rasyonel olup olmadığını ayarlar, bu değer bu [NurbsCurve](../../com.aspose.threed/nurbscurve) nesnesinin rasyonel spline mı yoksa rasyonel olmayan spline mı olduğunu gösterir. Rasyonel olmayan B-spline, rasyonel B-spline'ların özel bir durumudur.

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

