---
title: "LinearExtrusion"
second_title: "Aspose.3D for Java API Referansı"
description: "Doğrusal ekstrüzyon, bir 2D şekli girdi olarak alır ve şekli üçüncü boyutta uzatır."
type: docs
weight: 96
url: /tr/java/com.aspose.threed/linearextrusion/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class LinearExtrusion extends Entity implements IMeshConvertible
```

Linear extrusion, giriş olarak 2D bir şekil alır ve şekli 3. boyutta uzatır. **Example:** Aşağıdaki kod, LinearExtrusion'ı kullanarak bir şekli katı modele nasıl ekstrüde edeceğinizi gösterir.

```
//Create a new 3D scene
 		Scene scene = new Scene();
 
 		// Initialize the base profile to be extruded
 		var profile = new RectangleShape();
 		profile.setRoundingRadius(0.3);
 
 		// Create left node
 		var left = scene.getRootNode().createChildNode();
 		left.createChildNode(new Box(0.01, 3, 3));
 
 		// Create right node
 		var right = scene.getRootNode().createChildNode();
 		right.createChildNode(new Box(0.01, 3, 3));
 		right.getTransform().setTranslation(new Vector3(5, 0, 0));
 
 		//Perform linear extrusion on left node using center and slices property
 		var l = new LinearExtrusion(profile, 10);
 		l.setCenter(false);
 		l.setSlices(3);
 		l.setTwist(20);
 		left.createChildNode(l);
 
 		// Perform linear extrusion on left node using center and slices property
 		var r = new LinearExtrusion(profile, 10);
 		r.setCenter(true);
 		r.setSlices(3);
 		r.setTwist(90);
 		right.createChildNode(r);
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LinearExtrusion()](#LinearExtrusion--) | Örnek yapıcı [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
| [LinearExtrusion(Profile shape, double height)](#LinearExtrusion-com.aspose.threed.Profile-double-) | Örnek yapıcı [LinearExtrusion](../../com.aspose.threed/linearextrusion). |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [getBoundingBox()](#getBoundingBox--) | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |
| [getCenter()](#getCenter--) | Bu değer false ise, lineer ekstrüzyon Z aralığı 0'dan yüksekliğe, aksi takdirde aralık -yükseklik/2'den yükseklik/2'ye olur. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Ekstrüzyon yönü, varsayılan değer (0, 0, 1)'dir. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Renderer içinde kaydedilen varlık renderlayıcısının anahtarını alır |
| [getExcluded()](#getExcluded--) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını alır |
| [getHeight()](#getHeight--) | Ekstrüde edilen geometrinin yüksekliği, varsayılan değer 1.0'dır. |
| [getName()](#getName--) | Adı alır. |
| [getParentNode()](#getParentNode--) | İlk üst düğümü alır, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [getParentNodes()](#getParentNodes--) | Tüm üst düğümleri alır, bir varlık geometri örneklemesi için birden fazla üst düğüme bağlanabilir |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getScene()](#getScene--) | Bu nesnenin ait olduğu sahneyi alır |
| [getShape()](#getShape--) | Ekstrüde edilecek temel şekil. |
| [getSlices()](#getSlices--) | Bükülmüş ekstrüde edilen geometrinin dilimleri, varsayılan değer 1'dir. |
| [getTwist()](#getTwist--) | Şeklin ekstrüde edildiği derece sayısı. |
| [getTwistOffset()](#getTwistOffset--) | Bükülmede kullanılan ofset, varsayılan değer (0, 0, 0)'dır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [setCenter(boolean value)](#setCenter-boolean-) | Bu değer false ise, lineer ekstrüzyon Z aralığı 0'dan yüksekliğe, aksi takdirde aralık -yükseklik/2'den yükseklik/2'ye olur. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Ekstrüzyon yönü, varsayılan değer (0, 0, 1)'dir. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Bu varlığın dışa aktarım sırasında dışlanıp dışlanmayacağını ayarlar. |
| [setHeight(double value)](#setHeight-double-) | Ekstrüde edilen geometrinin yüksekliği, varsayılan değer 1.0'dır. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | İlk üst düğümü ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | Ekstrüde edilecek temel şekil. |
| [setSlices(int value)](#setSlices-int-) | Bükülmüş ekstrüde edilen geometrinin dilimleri, varsayılan değer 1'dir. |
| [setTwist(double value)](#setTwist-double-) | Şeklin ekstrüde edildiği derece sayısı. |
| [setTwistOffset(Vector3 value)](#setTwistOffset-com.aspose.threed.Vector3-) | Bükülmede kullanılan ofset, varsayılan değer (0, 0, 0)'dır. |
| [toMesh()](#toMesh--) | Ekstrüzyonu mesh'e dönüştür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearExtrusion() {#LinearExtrusion--}
```
public LinearExtrusion()
```


Örnek yapıcı [LinearExtrusion](../../com.aspose.threed/linearextrusion).

### LinearExtrusion(Profile shape, double height) {#LinearExtrusion-com.aspose.threed.Profile-double-}
```
public LinearExtrusion(Profile shape, double height)
```


Örnek yapıcı [LinearExtrusion](../../com.aspose.threed/linearextrusion).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [Profile](../../com.aspose.threed/profile) |  |
| yükseklik | double |  |

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
### getCenter() {#getCenter--}
```
public boolean getCenter()
```


Bu değer false ise, lineer ekstrüzyon Z aralığı 0'dan yüksekliğe, aksi takdirde aralık -yükseklik/2'den yükseklik/2'ye olur.

**Returns:**
boolean - Bu değer false ise, lineer ekstrüzyon Z aralığı 0'dan yüksekliğe, aksi takdirde aralık -yükseklik/2'den yükseklik/2'ye olur.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Ekstrüzyon yönü, varsayılan değer (0, 0, 1)'dir.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The direction of extrusion, default value is (0, 0, 1)
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


Ekstrüde edilen geometrinin yüksekliği, varsayılan değer 1.0'dır.

**Returns:**
double - Ekstrüde edilen geometrinin yüksekliği, varsayılan değer 1.0'dır.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
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


Ekstrüde edilecek temel şekil.

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base shape to be extruded.
### getSlices() {#getSlices--}
```
public int getSlices()
```


Bükülmüş ekstrüde edilen geometrinin dilimleri, varsayılan değer 1'dir.

**Returns:**
int - Bükülmüş ekstrüde edilen geometrinin dilimleri, varsayılan değer 1'dir.
### getTwist() {#getTwist--}
```
public double getTwist()
```


Şeklin ekstrüde edildiği derece sayısı.

**Returns:**
double - Şeklin ekstrüde edildiği derece sayısı.
### getTwistOffset() {#getTwistOffset--}
```
public Vector3 getTwistOffset()
```


Bükülmede kullanılan ofset, varsayılan değer (0, 0, 0)'dır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The offset that used in twisting, default value is (0, 0, 0).
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
### setCenter(boolean value) {#setCenter-boolean-}
```
public void setCenter(boolean value)
```


Bu değer false ise, lineer ekstrüzyon Z aralığı 0'dan yüksekliğe, aksi takdirde aralık -yükseklik/2'den yükseklik/2'ye olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Ekstrüzyon yönü, varsayılan değer (0, 0, 1)'dir.

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Ekstrüde edilen geometrinin yüksekliği, varsayılan değer 1.0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

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


Ekstrüde edilecek temel şekil.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | Yeni değer |

### setSlices(int value) {#setSlices-int-}
```
public void setSlices(int value)
```


Bükülmüş ekstrüde edilen geometrinin dilimleri, varsayılan değer 1'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setTwist(double value) {#setTwist-double-}
```
public void setTwist(double value)
```


Şeklin ekstrüde edildiği derece sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setTwistOffset(Vector3 value) {#setTwistOffset-com.aspose.threed.Vector3-}
```
public void setTwistOffset(Vector3 value)
```


Bükülmede kullanılan ofset, varsayılan değer (0, 0, 0)'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


Ekstrüzyonu mesh'e dönüştür.

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

