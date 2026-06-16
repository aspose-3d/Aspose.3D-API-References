---
title: "Kemik"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir kemik, geometrinin kontrol noktasının alt kümesini tanımlar ve her kontrol noktası için karışım ağırlığını belirler."
type: docs
weight: 20
url: /tr/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Bir kemik, geometrinin kontrol noktasının alt kümesini tanımlar ve her kontrol noktası için karışım ağırlığını belirler. [Bone](../../com.aspose.threed/bone) nesnesi doğrudan kullanılamaz, geometriyi deform etmek için bir [SkinDeformer](../../com.aspose.threed/skindeformer) örneği kullanılır ve [SkinDeformer](../../com.aspose.threed/skindeformer) bir dizi kemikle birlikte gelir; her kemik bir düğüme bağlanır. NOT: Bir geometrinin kontrol noktası birden fazla Kemik ile ilişkilendirilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | [Bone](../../com.aspose.threed/bone) sınıfının yeni bir örneğini başlatır. |
| [Bone()](#Bone--) | [Bone](../../com.aspose.threed/bone) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Özelliği bulur. |
| [get(int index)](#get-int-) | Belirtilen kontrol noktasının karışım ağırlığını alır |
| [getBoneTransform()](#getBoneTransform--) | Kemikin dönüşüm matrisini alır |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | Bir kemiğin bağlama modu, kemiğin hiyerarşik bir yapıda üst kemik ile nasıl bağlandığını veya ilişkilendirildiğini ifade eder. |
| [getName()](#getName--) | Adı alır. |
| [getNode()](#getNode--) | Düğümü alır. |
| [getProperties()](#getProperties--) | Tüm özelliklerin koleksiyonunu alır. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Belirtilen özelliğin değerini al |
| [getTransform()](#getTransform--) | Kemik içeren düğümün dönüşüm matrisini alır. |
| [getWeight(int index)](#getWeight-int-) | Belirtilen indeksle kontrol noktasının ağırlığını alır |
| [getWeightCount()](#getWeightCount--) | Ağırlık sayısını alır, bu otomatik olarak [setWeight](../../com.aspose.threed/bone\#setWeight) ile genişletilir |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Dinamik bir özelliği kaldırır. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | İsimle tanımlanan belirtilen özelliği kaldır |
| [set(int index, double value)](#set-int-double-) | Belirtilen kontrol noktasının karışım ağırlığını ayarlar |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Kemiğin dönüşüm matrisini ayarlar. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | Bir kemiğin bağlama modu, kemiğin hiyerarşik bir yapıda üst kemik ile nasıl bağlandığını veya ilişkilendirildiğini ifade eder. |
| [setName(String value)](#setName-java.lang.String-) | Adı ayarlar. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Düğümü ayarlar. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Belirtilen özelliğin değerini ayarlar |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Kemik içeren düğümün dönüşüm matrisini ayarlar. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Belirtilen indeksle kontrol noktasının ağırlığını ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


[Bone](../../com.aspose.threed/bone) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Ad. |

### Bone() {#Bone--}
```
public Bone()
```


[Bone](../../com.aspose.threed/bone) sınıfının yeni bir örneğini başlatır.

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Belirtilen kontrol noktasının karışım ağırlığını alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Ağırlığın indeksi |

**Returns:**
double - Ağırlık
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Kemikin dönüşüm matrisini alır

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


Bir kemiğin bağlama modu, kemiğin hiyerarşik bir yapıda üst kemik ile nasıl bağlandığını veya ilişkilendirildiğini ifade eder.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Adı alır.

**Returns:**
java.lang.String - ad.
### getNode() {#getNode--}
```
public Node getNode()
```


Düğümü alır. Kemik düğümü, derinin bağlandığı kemiktir, [SkinDeformer](../../com.aspose.threed/skindeformer) kemik düğümünü kontrol noktalarının yer değiştirmesini etkilemek için kullanır. Kemik düğümünün genellikle bir [Skeleton](../../com.aspose.threed/skeleton) bağlıdır, ancak bu zorunlu değildir. Bağlı [Skeleton](../../com.aspose.threed/skeleton) genellikle DCC yazılımı tarafından kullanıcıya iskelet göstermek için kullanılır.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Kemik içeren düğümün dönüşüm matrisini alır.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Belirtilen indeksle kontrol noktasının ağırlığını alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Kontrol noktasının indeksi |

**Returns:**
double - belirtilen indeksteki ağırlık, indeks geçersizse 0
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Ağırlık sayısını alır, bu otomatik olarak [setWeight](../../com.aspose.threed/bone\#setWeight) ile genişletilir

**Returns:**
int - ağırlık sayısı, bu otomatik olarak [setWeight](../../com.aspose.threed/bone\#setWeight) ile genişletilir
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Belirtilen kontrol noktasının karışım ağırlığını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Ağırlığın indeksi |
| değer | double | Yeni değer |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Kemiğin dönüşüm matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Yeni değer |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


Bir kemiğin bağlama modu, kemiğin hiyerarşik bir yapıda üst kemik ile nasıl bağlandığını veya ilişkilendirildiğini ifade eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Yeni değer |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Adı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Düğümü ayarlar. Kemik düğümü, derinin bağlandığı kemiktir, [SkinDeformer](../../com.aspose.threed/skindeformer) kemik düğümünü kontrol noktalarının yer değiştirmesini etkilemek için kullanır. Kemik düğümünün genellikle bir [Skeleton](../../com.aspose.threed/skeleton) bağlıdır, ancak bu zorunlu değildir. Bağlı [Skeleton](../../com.aspose.threed/skeleton) genellikle DCC yazılımı tarafından kullanıcıya iskelet göstermek için kullanılır.

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Kemik içeren düğümün dönüşüm matrisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Yeni değer |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Belirtilen indeksle kontrol noktasının ağırlığını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Kontrol noktasının indeksi |
| ağırlık | double | Yeni ağırlık |

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

