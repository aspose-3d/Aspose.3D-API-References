---
title: "RevolvedAreaSolid"
second_title: "Aspose.3D for Java API Referansı"
description: "Bu sınıf, bir profil tarafından sağlanan kesit bir eksen etrafında döndürülerek katı bir modeli temsil eder."
type: docs
weight: 155
url: /tr/java/com.aspose.threed/revolvedareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class RevolvedAreaSolid extends Entity implements IMeshConvertible
```

Bu sınıf, bir profil tarafından sağlanan kesit bölümü bir eksen etrafında döndürerek katı bir model temsil eder. **Örnek:** Aşağıdaki kod, RevolvedAreaSolid'ı kullanarak bir şekli katı modele nasıl döndüreceğinizi gösterir.

```
//Create a new 3D scene
         Scene scene = new Scene();
 
         // Initialize the base profile to be extruded
         var profile = new RectangleShape();
         profile.setRoundingRadius(0.3);
 
         var revolved = new RevolvedAreaSolid();
         revolved.setShape(profile);
         revolved.setOrigin(new Vector3(1, 0, 0));
         revolved.setAngleStart(0);
         revolved.setAngleEnd(Math.PI);
         scene.getRootNode().createChildNode(revolved);
 
         scene.save("revolved.obj");
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RevolvedAreaSolid()](#RevolvedAreaSolid--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getAngleEnd()](#getAngleEnd--) | Döndürme prosedürünün bitiş açısını, radyan cinsinden alır, varsayılan değer pi'dir. |
| [getAngleStart()](#getAngleStart--) | Devir prosedürünün başlangıç açısını alır, radyan cinsinden ölçülür, varsayılan değer 0'dır. |
| [getAxis()](#getAxis--) | Eksen yönünü alır, varsayılan değer (0, 1, 0)'dır. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getName()](#getName--) | Adı alır. |
| [getOrigin()](#getOrigin--) | Devirin orijinal noktasını alır, varsayılan değer (0, 0, 0)'dır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getShape()](#getShape--) | Devir için kullanılan temel profili alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setAngleEnd(double value)](#setAngleEnd-double-) | Devir prosedürünün bitiş açısını ayarlar, radyan cinsinden ölçülür, varsayılan değer pi'dir. |
| [setAngleStart(double value)](#setAngleStart-double-) | Devir prosedürünün başlangıç açısını ayarlar, radyan cinsinden ölçülür, varsayılan değer 0'dır. |
| [setAxis(Vector3 value)](#setAxis-com.aspose.threed.Vector3-) | Eksen yönünü ayarlar, varsayılan değer (0, 1, 0)'dır. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setOrigin(Vector3 value)](#setOrigin-com.aspose.threed.Vector3-) | Devirin orijinal noktasını ayarlar, varsayılan değer (0, 0, 0)'dır. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | Devir için kullanılan temel profili ayarlar. |
| [toMesh()](#toMesh--) | [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) nesnesini bir mesh'e dönüştür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RevolvedAreaSolid() {#RevolvedAreaSolid--}
```
public RevolvedAreaSolid()
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
### getAngleEnd() {#getAngleEnd--}
```
public double getAngleEnd()
```


Döndürme prosedürünün bitiş açısını, radyan cinsinden alır, varsayılan değer pi'dir.

**Returns:**
double - devir prosedürünün bitiş açısı, radyan cinsinden ölçülür, varsayılan değer pi.
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


Devir prosedürünün başlangıç açısını alır, radyan cinsinden ölçülür, varsayılan değer 0'dır.

**Returns:**
double - devir prosedürünün başlangıç açısı, radyan cinsinden ölçülür, varsayılan değer 0.
### getAxis() {#getAxis--}
```
public Vector3 getAxis()
```


Eksen yönünü alır, varsayılan değer (0, 1, 0)'dır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the axis direction, default value is (0, 1, 0).
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
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır

**Returns:**
boolean - bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağı.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getOrigin() {#getOrigin--}
```
public Vector3 getOrigin()
```


Devirin orijinal noktasını alır, varsayılan değer (0, 0, 0)'dır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the origin point of the revolving, default value is (0, 0, 0).
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Bu nesnenin ait olduğu sahneyi alır

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShape() {#getShape--}
```
public Profile getShape()
```


Devir için kullanılan temel profili alır.

**Returns:**
[Profile](../../com.aspose.threed/profile) - the base profile used to revolve.
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
### setAngleEnd(double value) {#setAngleEnd-double-}
```
public void setAngleEnd(double value)
```


Devir prosedürünün bitiş açısını ayarlar, radyan cinsinden ölçülür, varsayılan değer pi'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


Devir prosedürünün başlangıç açısını ayarlar, radyan cinsinden ölçülür, varsayılan değer 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setAxis(Vector3 value) {#setAxis-com.aspose.threed.Vector3-}
```
public void setAxis(Vector3 value)
```


Eksen yönünü ayarlar, varsayılan değer (0, 1, 0)'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

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

### setOrigin(Vector3 value) {#setOrigin-com.aspose.threed.Vector3-}
```
public void setOrigin(Vector3 value)
```


Devirin orijinal noktasını ayarlar, varsayılan değer (0, 0, 0)'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


Devir için kullanılan temel profili ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | Yeni değer |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


[RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) nesnesini bir mesh'e dönüştür.

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

