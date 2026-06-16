---
title: "文本"
second_title: "Aspose.3D for Java API 参考"
description: "文本配置文件 此配置文件描述使用字体和文本的轮廓。"
type: docs
weight: 183
url: /zh/java/com.aspose.threed/text/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile)
```
public class Text extends Profile
```

文本配置文件，此配置文件描述使用字体和文本的轮廓。 **Example:** 以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Text()](#Text--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | 文本内容 |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getFont()](#getFont--) | 文本的字体。 |
| [getFontSize()](#getFontSize--) | 字体大小比例。 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setContent(String value)](#setContent-java.lang.String-) | 文本内容 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setFont(FontFile value)](#setFont-com.aspose.threed.FontFile-) | 文本的字体。 |
| [setFontSize(float value)](#setFontSize-float-) | 字体大小比例。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Text() {#Text--}
```
public Text()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


获取当前实体在其对象空间坐标系中的边界框。

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
### getContent() {#getContent--}
```
public String getContent()
```


文本内容

**Returns:**
java.lang.String - 文本内容 **Example:** 以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


获取在渲染器中注册的实体渲染器的键

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


获取在导出期间是否排除此实体。

**Returns:**
boolean - 是否在导出期间排除此实体。
### getFont() {#getFont--}
```
public FontFile getFont()
```


文本的字体。

**Returns:**
[FontFile](../../com.aspose.threed/fontfile) - The font of the text. **Example:** The following code shows how to create a 3D mesh from text using specified font file.

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


字体大小比例。

**Returns:**
float - 字体大小比例。 **Example:** 以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
```
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


获取所有父节点，实体可以附加到多个父节点以进行几何实例化

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - 所有父节点，实体可以附加到多个父节点以实现几何实例化
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

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


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### setContent(String value) {#setContent-java.lang.String-}
```
public void setContent(String value)
```


文本内容

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 新值 **Example:** 以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。 |

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
``` |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


设置在导出期间是否排除此实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setFont(FontFile value) {#setFont-com.aspose.threed.FontFile-}
```
public void setFont(FontFile value)
```


文本的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [FontFile](../../com.aspose.threed/fontfile) | 新值 **Example:** 以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。 |

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
``` |

### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


字体大小比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | float | 新值 **Example:** 以下代码展示了如何使用指定的字体文件从文本创建 3D 网格。 |

```
var font = FontFile.fromFile("CascadiaCode-Regular.otf");
             var text = new Text();
             text.setFont(font);
             text.setContent("ABC");
             text.setFontSize(10);
             var linear = new LinearExtrusion(text, 10).toMesh();
             var scene = new Scene(linear);
             scene.save("test.stl");
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

