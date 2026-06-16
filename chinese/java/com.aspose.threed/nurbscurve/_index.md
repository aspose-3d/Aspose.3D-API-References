---
title: "NurbsCurve"
second_title: "Aspose.3D for Java API 参考"
description: "NURBS 曲线是一种由 NURBSNon-uniform rational basis spline 表示的曲线。NURBS 曲线由其一组加权控制点和一个 … 定义。控制点中的 w 分量用作控制点的权重，无论它是 … 或者。"
type: docs
weight: 112
url: /zh/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | 初始化 [NurbsCurve](../../com.aspose.threed/nurbscurve) 类的新实例。 |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | 初始化 [NurbsCurve](../../com.aspose.threed/nurbscurve) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | 评估 NURBS 曲线 |
| [evaluate(int steps)](#evaluate-int-) | 评估 NURBS 曲线 |
| [evaluateAt(double u)](#evaluateAt-double-) | 在指定位置评估曲线的点 |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getBoundingBox()](#getBoundingBox--) | 获取当前实体在其对象空间坐标系中的边界框。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取线的颜色，默认值为白色 (1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | 获取所有控制点 |
| [getCurveType()](#getCurveType--) | 获取曲线的类型。 |
| [getDegree()](#getDegree--) | 获取 NURBS 曲线的次数，次数定义为 Order - 1 |
| [getDimension()](#getDimension--) | 获取曲线的维度。 |
| [getEntityRendererKey()](#getEntityRendererKey--) | 获取在渲染器中注册的实体渲染器的键 |
| [getExcluded()](#getExcluded--) | 获取在导出期间是否排除此实体。 |
| [getKnotVectors()](#getKnotVectors--) | 获取节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。 |
| [getMultiplicity()](#getMultiplicity--) | 获取多重性。 |
| [getName()](#getName--) | 获取名称。 |
| [getOrder()](#getOrder--) | 获取 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。 |
| [getParentNode()](#getParentNode--) | 获取第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [getParentNodes()](#getParentNodes--) | 获取所有父节点，实体可以附加到多个父节点以进行几何实例化 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getRational()](#getRational--) | 获取它是否为有理的，此值指示该 [NurbsCurve](../../com.aspose.threed/nurbscurve) 是有理样条还是非有理样条。 |
| [getScene()](#getScene--) | 获取此对象所属的场景 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | 设置线的颜色，默认值为白色 (1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | 设置曲线的类型。 |
| [setDegree(int value)](#setDegree-int-) | 设置 NURBS 曲线的次数，次数定义为 Order - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | 设置曲线的维度。 |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 设置在导出期间是否排除此实体。 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setOrder(int value)](#setOrder-int-) | 设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 设置第一个父节点，如果设置第一个父节点，则此实体将从其他父节点分离。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setRational(boolean value)](#setRational-boolean-) | 设置它是否为有理的，此值指示该 [NurbsCurve](../../com.aspose.threed/nurbscurve) 是有理样条还是非有理样条。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


初始化 [NurbsCurve](../../com.aspose.threed/nurbscurve) 类的新实例。

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


初始化 [NurbsCurve](../../com.aspose.threed/nurbscurve) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


评估 NURBS 曲线

**Returns:**
com.aspose.threed.Vector4[] - 曲线中的点
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


评估 NURBS 曲线

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 步 | int | 两个相邻节点之间的评估频率，默认值为 20 |

**Returns:**
com.aspose.threed.Vector4[] - 曲线中的点
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


在指定位置评估曲线的点

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| u | double | 曲线中的位置，范围在 0 到 1 之间 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### getColor() {#getColor--}
```
public Vector3 getColor()
```


获取线的颜色，默认值为白色 (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


获取所有控制点

**Returns:**
java.util.List<com.aspose.threed.Vector4> - 所有控制点
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


获取曲线的类型。

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


获取 NURBS 曲线的次数，次数定义为 Order - 1

**Returns:**
int - NURBS 曲线的次数，次数定义为 Order - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


获取曲线的维度。

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
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
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


获取节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。

**Returns:**
java.util.List<java.lang.Double> - 节点向量，它是一系列参数值，决定控制点在何处以及如何影响 NURBS 曲线。
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


获取多重性。

**Returns:**
java.util.List<java.lang.Integer> - 多重性。
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getOrder() {#getOrder--}
```
public int getOrder()
```


获取 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。

**Returns:**
int - NURBS 曲线的阶数，它定义了影响曲线上任意点的邻近控制点的数量。
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
### getRational() {#getRational--}
```
public boolean getRational()
```


获取是否为有理的，此值指示此 [NurbsCurve](../../com.aspose.threed/nurbscurve) 是有理样条还是非有理样条。非有理 B 样条是有理 B 样条的特例。

**Returns:**
boolean - 是否为有理的，此值指示此 [NurbsCurve](../../com.aspose.threed/nurbscurve) 是有理样条还是非有理样条。非有理 B 样条是有理 B 样条的特例。
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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


设置线的颜色，默认值为白色 (1, 1, 1)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


设置曲线的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | 新值 |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


设置 NURBS 曲线的次数，次数定义为 Order - 1

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


设置曲线的维度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | 新值 **备注:** 对于 [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) 曲线，控制点中的 z 分量未使用。 |

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

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的相邻控制点的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


设置是否为有理的，此值指示此 [NurbsCurve](../../com.aspose.threed/nurbscurve) 是有理样条还是非有理样条。非有理 B 样条是有理 B 样条的特例。

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

