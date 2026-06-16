---
title: "网格"
second_title: "Aspose.3D for Java API 参考"
description: "网格由许多 n 边多边形组成。"
type: docs
weight: 102
url: /zh/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

网格由许多 n 边多边形组成。**Example:** 在网格中添加多边形的方法：

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

遍历网格中的所有多边形：

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Mesh()](#Mesh--) | 初始化 [Mesh](../../com.aspose.threed/mesh) 类的新实例。 |
| [Mesh(String name)](#Mesh-java.lang.String-) | 初始化 [Mesh](../../com.aspose.threed/mesh) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | 获取所有具有指定变形器类型的变形器 |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | 向网格添加新的控制点，这样更高效。 |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | 向网格添加新的控制点，这样更高效。 |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | 向当前几何体添加现有的顶点元素 |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | 创建具有指定类型的顶点元素并将其添加到几何体中。 |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | 创建一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv)。 |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | 创建一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv)。 |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | 创建一个具有3个顶点的多边形（三角形） |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | 创建一个具有4个顶点的多边形（四边形） |
| [createPolygon(int[] indices)](#createPolygon-int---) | 创建一个新多边形，所有顶点在 `indices` 中定义。 |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | 创建一个新多边形，所有顶点在 `indices` 中定义。 |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 计算两个网格的差集 |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | 对两个网格执行布尔运算 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getCastShadows()](#getCastShadows--) | 获取此几何体是否可以投射阴影 |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | 获取所有控制点 |
| [getDeformers()](#getDeformers--) | 获取与此几何体关联的所有变形器。 |
| [getEdges()](#getEdges--) | 获取网格的边缘。 |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | 获取具有指定类型的顶点元素 |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getName()](#getName--) | 获取名称。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getPolygonCount()](#getPolygonCount--) | 获取多边形的数量 |
| [getPolygonSize(int index)](#getPolygonSize-int-) | 获取指定多边形的顶点数量。 |
| [getPolygons()](#getPolygons--) | 获取网格的多边形定义 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getReceiveShadows()](#getReceiveShadows--) | 获取此几何体是否可以接收阴影。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | 获取一个具有给定纹理映射类型的 [VertexElementUV](../../com.aspose.threed/vertexelementuv) 实例 |
| [getVertexElements()](#getVertexElements--) | 获取所有顶点元素 |
| [getVisible()](#getVisible--) | 获取几何体是否可见 |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 计算两个网格的交集 |
| [isManifold()](#isManifold--) | 检查当前网格是否为流形网格。 |
| [iterator()](#iterator--) | 获取每个内部多边形的枚举器。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | 通过消除重复的控制点来优化网格的内存使用。 |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | 通过消除重复的控制点来优化网格的内存使用。 |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | 通过消除重复的控制点来优化网格的内存使用。 |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | 通过消除重复的控制点来优化网格的内存使用。 |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | 通过消除重复的控制点来优化网格的内存使用。 |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 设置此几何体是否可以投射阴影 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | 设置此几何体是否可以接收阴影。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 设置几何体是否可见 |
| [toMesh()](#toMesh--) | 从当前实体获取 Mesh 实例。 |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | 返回三角化网格 |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 计算两个网格的并集 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


初始化 [Mesh](../../com.aspose.threed/mesh) 类的新实例。

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


初始化 [Mesh](../../com.aspose.threed/mesh) 类的新实例。

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
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


向网格添加新的控制点，这样更高效。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | 控制点的 x 分量 |
| y | double | 控制点的 y 分量 |
| z | double | 控制点的 z 分量 |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


向网格添加新的控制点，这样更高效。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | 控制点的 x 分量 |
| y | double | 控制点的 y 分量 |
| z | double | 控制点的 z 分量 |
| w | double | 控制点的 w 分量 |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


向当前几何体添加现有的顶点元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | 要添加的顶点元素 |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


创建一个具有3个顶点的多边形（三角形）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v1 | int | 第一个顶点的索引 |
| v2 | int | 第二个顶点的索引 |
|  | v3 | int | 第三个顶点的索引 **Example:** 以下代码展示了如何使用控制点的索引创建新多边形。 |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


创建一个具有4个顶点的多边形（四边形）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v1 | int | 第一个顶点的索引 |
| v2 | int | 第二个顶点的索引 |
| v3 | int | 第三个顶点的索引 |
|  | v4 | int | 第四个顶点的索引 **Example:** 以下代码展示了如何使用控制点的索引创建新多边形。 |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


使用 `indices` 中定义的所有顶点创建新多边形。若要逐顶点创建多边形，请使用 [PolygonBuilder](../../com.aspose.threed/polygonbuilder)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 索引 | int[] | 多边形索引的数组，每个索引指向构成多边形的控制点。 **Example:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


使用 `indices` 中定义的所有顶点创建新多边形。若要逐顶点创建多边形，请使用 [PolygonBuilder](../../com.aspose.threed/polygonbuilder)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int[] | 多边形索引的数组，每个索引指向构成多边形的控制点。 |
| 偏移 | int | 第一个多边形索引的偏移量 |
|  | 长度 | int | 索引的长度 **Example:** 以下代码展示了如何使用控制点的索引创建新多边形。 |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


计算两个网格的差集

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 第一个网格 |
| b | [Mesh](../../com.aspose.threed/mesh) | 第二个网格 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


对两个网格执行布尔运算

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | 布尔运算类型。 |
| a | [Mesh](../../com.aspose.threed/mesh) | 要操作的第一个网格。 |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | 第一个网格的变换矩阵 |
| b | [Mesh](../../com.aspose.threed/mesh) | 要操作的第二个网格 |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | 第二个网格的变换矩阵 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


获取网格的边。网格中的边是可选的，因此可能为空。

**Returns:**
java.util.List<java.lang.Integer> - 网格的边。网格中的边是可选的，因此可能为空。
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


获取多边形的数量

**Returns:**
int - 多边形的数量 **Example:** 以下代码展示了如何获取网格的多边形数量。

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


获取指定多边形的顶点数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 索引。 |

**Returns:**
int - 多边形的大小。
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


获取网格的多边形定义

**Returns:**
java.util.List<int[]> - 网格的多边形定义
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
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


计算两个网格的交集

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 第一个网格 |
| b | [Mesh](../../com.aspose.threed/mesh) | 第二个网格 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


检查当前网格是否为流形网格。此函数不会缓存流形计算结果。

**Returns:**
boolean - 如果网格是流形网格，则为 true。
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


获取每个内部多边形的枚举器。

**Returns:**
java.util.Iterator<int[]> - 枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


通过消除重复的控制点来优化网格的内存使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexElements | 布尔 | 优化重复的顶点元素数据 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


通过消除重复的控制点来优化网格的内存使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexElements | 布尔 | 优化重复的顶点元素数据 |
| toleranceControlPoint | float | 控制点的容差，默认值为 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


通过消除重复的控制点来优化网格的内存使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexElements | 布尔 | 优化重复的顶点元素数据 |
| toleranceControlPoint | float | 控制点的容差，默认值为 1e-9 |
| toleranceNormal | float | 法线/切线/双切线的容差，默认值为 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


通过消除重复的控制点来优化网格的内存使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexElements | 布尔 | 优化重复的顶点元素数据 |
| toleranceControlPoint | float | 控制点的容差，默认值为 1e-9 |
| toleranceNormal | float | 法线/切线/双切线的容差，默认值为 1e-9 |
| toleranceUV | float | uv 的容差，默认值为 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


通过消除重复的控制点来优化网格的内存使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexElements | 布尔 | 优化重复的顶点元素数据 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


从当前实体获取 Mesh 实例。

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


返回三角化网格

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


计算两个网格的并集

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 第一个网格 |
| b | [Mesh](../../com.aspose.threed/mesh) | 第二个网格 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
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

