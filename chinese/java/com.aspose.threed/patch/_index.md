---
title: "Patch"
second_title: "Aspose.3D for Java API 参考"
description: "A  是一种参数化建模曲面，类似于  ，它也由两个   定义，即  和 。"
type: docs
weight: 119
url: /zh/java/com.aspose.threed/patch/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class Patch extends Geometry
```

A [Patch](../../com.aspose.threed/patch) 是一种参数化建模曲面，类似于 [NurbsSurface](../../com.aspose.threed/nurbssurface)，它也由两个 [PatchDirection](../../com.aspose.threed/patchdirection) 定义，即 [getU](../../com.aspose.threed/patch\#getU) 和 [getV](../../com.aspose.threed/patch\#getV)。但 [Patch](../../com.aspose.threed/patch) 与 [NurbsSurface](../../com.aspose.threed/nurbssurface) 的区别在于，[PatchDirection](../../com.aspose.threed/patchdirection) 曲线可以是以下之一：[PatchDirectionType.BEZIER](../../com.aspose.threed/patchdirectiontype\#BEZIER)、[PatchDirectionType.QUADRATIC\_BEZIER](../../com.aspose.threed/patchdirectiontype\#QUADRATIC-BEZIER)、[PatchDirectionType.BASIS\_SPLINE](../../com.aspose.threed/patchdirectiontype\#BASIS-SPLINE)、[PatchDirectionType.CARDINAL\_SPLINE](../../com.aspose.threed/patchdirectiontype\#CARDINAL-SPLINE) 和 [PatchDirectionType.LINEAR](../../com.aspose.threed/patchdirectiontype\#LINEAR)。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Patch()](#Patch--) | 初始化 [Patch](../../com.aspose.threed/patch) 类的新实例。 |
| [Patch(String name)](#Patch-java.lang.String-) | 初始化 [Patch](../../com.aspose.threed/patch) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | 获取所有具有指定变形器类型的变形器 |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | 向当前几何体添加现有的顶点元素 |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | 创建一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv)。 |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | 创建一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv)。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getCastShadows()](#getCastShadows--) | 获取此几何体是否可以投射阴影 |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | 获取所有控制点 |
| [getDeformers()](#getDeformers--) | 获取与此几何体关联的所有变形器。 |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | 获取具有指定类型的顶点元素 |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getReceiveShadows()](#getReceiveShadows--) | 获取此几何体是否可以接收阴影。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getU()](#getU--) | 获取 u 方向。 |
| [getV()](#getV--) | 获取 v 方向。 |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | 获取一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 实例 |
| [getVertexElements()](#getVertexElements--) | 获取所有顶点元素 |
| [getVisible()](#getVisible--) | 获取几何体是否可见 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 设置此几何体是否可以投射阴影 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | 设置此几何体是否可以接收阴影。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 设置几何体是否可见 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Patch() {#Patch--}
```
public Patch()
```


初始化 [Patch](../../com.aspose.threed/patch) 类的新实例。

### Patch(String name) {#Patch-java.lang.String-}
```
public Patch(String name)
```


初始化 [Patch](../../com.aspose.threed/patch) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称。 |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


获取所有具有指定变形器类型的变形器

**Returns:**
java.util.Collection<T> - 变形器集合
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


向当前几何体添加现有的顶点元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | 要添加的顶点元素 |

### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


创建具有指定类型的顶点元素并将其添加到几何体中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 顶点元素类型 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


创建具有指定类型的顶点元素并将其添加到几何体中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 顶点元素类型 |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | 默认映射模式 |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | 默认引用模式 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


创建一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | 要创建的纹理映射类型 |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


创建一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | 要创建的纹理映射类型 |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | 默认映射模式 |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | 默认引用模式 |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


获取此几何体是否可以投射阴影

**Returns:**
boolean - 此几何体是否可以投射阴影
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


获取所有控制点

**Returns:**
java.util.List<com.aspose.threed.Vector4> - 所有控制点
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


获取与此几何体关联的所有变形器。

**Returns:**
java.util.List<com.aspose.threed.Deformer> - 与此几何体关联的所有变形器。
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


获取具有指定类型的顶点元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 要查找的顶点元素类型 |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


获取在渲染器中注册的实体渲染器的键

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


获取在导出期间是否排除此实体。

**Returns:**
boolean - 是否在导出期间排除此实体。
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
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


获取此几何体是否可以接收阴影。

**Returns:**
boolean - 此几何体是否可以接收阴影。
### getScene() {#getScene--}
```
public Scene getScene()
```


获取此对象所属的场景

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getU() {#getU--}
```
public PatchDirection getU()
```


获取 u 方向。

**Returns:**
[PatchDirection](../../com.aspose.threed/patchdirection) - the u direction.
### getV() {#getV--}
```
public PatchDirection getV()
```


获取 v 方向。

**Returns:**
[PatchDirection](../../com.aspose.threed/patchdirection) - the v direction.
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


获取一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


获取所有顶点元素

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - 所有顶点元素
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


获取几何体是否可见

**Returns:**
boolean - 几何体是否可见
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


设置此几何体是否可以投射阴影

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


设置在导出期间是否排除此实体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


设置此几何体是否可以接收阴影。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


设置几何体是否可见

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

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

