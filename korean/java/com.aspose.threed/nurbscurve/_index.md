---
title: NurbsCurve
second_title: Aspose.3D for Java API 레퍼런스
description: NURBS 곡선은 NURBSNon-uniform rational basis spline으로 표현되는 곡선입니다. NURBS 곡선은 가중치가 적용된 점들의 집합과 ...에 의해 정의됩니다. 제어점의 w 구성 요소는 제어점의 가중치로 사용됩니다.
type: docs
weight: 112
url: /ko/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | 새로운 [NurbsCurve](../../com.aspose.threed/nurbscurve) 클래스의 인스턴스를 초기화합니다. |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | 새로운 [NurbsCurve](../../com.aspose.threed/nurbscurve) 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | NURBS 곡선을 평가합니다 |
| [evaluate(int steps)](#evaluate-int-) | NURBS 곡선을 평가합니다 |
| [evaluateAt(double u)](#evaluateAt-double-) | 지정된 위치에서 곡선의 점을 평가합니다 |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getBoundingBox()](#getBoundingBox--) | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 선의 색상을 가져옵니다. 기본값은 흰색(1, 1, 1)입니다 |
| [getControlPoints()](#getControlPoints--) | 모든 제어점을 가져옵니다. |
| [getCurveType()](#getCurveType--) | 곡선의 유형을 가져옵니다. |
| [getDegree()](#getDegree--) | NURBS 곡선의 차수를 가져옵니다. 차수는 Order - 1 로 정의됩니다 |
| [getDimension()](#getDimension--) | 곡선의 차원을 가져옵니다. |
| [getEntityRendererKey()](#getEntityRendererKey--) | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [getExcluded()](#getExcluded--) | 내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다. |
| [getKnotVectors()](#getKnotVectors--) | 노트 벡터를 가져옵니다. 이는 매개변수 값들의 순서로, 제어점이 NURBS 곡선에 영향을 미치는 위치와 방식을 결정합니다. |
| [getMultiplicity()](#getMultiplicity--) | 중복도를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getOrder()](#getOrder--) | NURBS 곡선의 차수를 가져옵니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다. |
| [getParentNode()](#getParentNode--) | 첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [getParentNodes()](#getParentNodes--) | 모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRational()](#getRational--) | 이것이 유리형인지 여부를 가져옵니다. 이 값은 해당 [NurbsCurve](../../com.aspose.threed/nurbscurve)가 유리 스플라인인지 비유리 스플라인인지를 나타냅니다. |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | 선의 색상을 설정합니다. 기본값은 흰색(1, 1, 1)입니다 |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | 곡선의 유형을 설정합니다. |
| [setDegree(int value)](#setDegree-int-) | NURBS 곡선의 차수를 설정합니다. 차수는 Order - 1 로 정의됩니다 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | 곡선의 차원을 설정합니다. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setOrder(int value)](#setOrder-int-) | NURBS 곡선의 차수를 설정합니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRational(boolean value)](#setRational-boolean-) | 유리형인지 여부를 설정합니다. 이 값은 해당 [NurbsCurve](../../com.aspose.threed/nurbscurve)가 유리 스플라인인지 비유리 스플라인인지를 나타냅니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


새로운 [NurbsCurve](../../com.aspose.threed/nurbscurve) 클래스의 인스턴스를 초기화합니다.

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


새로운 [NurbsCurve](../../com.aspose.threed/nurbscurve) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


NURBS 곡선을 평가합니다

**Returns:**
com.aspose.threed.Vector4[] - 곡선의 점들
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


NURBS 곡선을 평가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 단계 | int | 두 인접 노트 사이의 평가 빈도이며, 기본값은 20입니다 |

**Returns:**
com.aspose.threed.Vector4[] - 곡선의 점들
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


지정된 위치에서 곡선의 점을 평가합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| u | double | 곡선 내 위치이며, 0과 1 사이입니다 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성 (Identified by its name)일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String | 속성 이름. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다.

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


선의 색상을 가져옵니다. 기본값은 흰색(1, 1, 1)입니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


모든 제어점을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Vector4> - 모든 제어점
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


곡선의 유형을 가져옵니다.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


NURBS 곡선의 차수를 가져옵니다. 차수는 Order - 1 로 정의됩니다

**Returns:**
int - NURBS 곡선의 차수이며, 차수는 Order - 1 로 정의됩니다
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


곡선의 차원을 가져옵니다.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다.

**Returns:**
boolean - 내보내기 중에 이 엔터티를 제외할지 여부.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


노트 벡터를 가져옵니다. 이는 매개변수 값들의 순서로, 제어점이 NURBS 곡선에 영향을 미치는 위치와 방식을 결정합니다.

**Returns:**
java.util.List<java.lang.Double> - 노트 벡터이며, 이는 매개변수 값들의 순서로 제어점이 NURBS 곡선에 영향을 미치는 위치와 방식을 결정합니다.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


중복도를 가져옵니다.

**Returns:**
java.util.List<java.lang.Integer> - 다중성.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getOrder() {#getOrder--}
```
public int getOrder()
```


NURBS 곡선의 차수를 가져옵니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다.

**Returns:**
int - NURBS 곡선의 차수이며, 곡선상의 임의의 점에 영향을 주는 인접 제어점들의 수를 정의합니다.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - 모든 부모 노드, 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 연결될 수 있습니다
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


모든 속성의 컬렉션을 가져옵니다.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


지정된 속성의 값을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 찾은 속성의 값
### getRational() {#getRational--}
```
public boolean getRational()
```


합리적인지 여부를 가져옵니다. 이 값은 이 [NurbsCurve](../../com.aspose.threed/nurbscurve)가 합리 스플라인인지 비합리 스플라인인지를 나타냅니다. 비합리 B-스플라인은 합리 B-스플라인의 특수한 경우입니다.

**Returns:**
boolean - 합리적인지 여부이며, 이 값은 이 [NurbsCurve](../../com.aspose.threed/nurbscurve)가 합리 스플라인인지 비합리 스플라인인지를 나타냅니다. 비합리 B-스플라인은 합리 B-스플라인의 특수한 경우입니다.
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

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


동적 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


이름으로 식별되는 지정된 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


선의 색상을 설정합니다. 기본값은 흰색(1, 1, 1)입니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


곡선의 유형을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | 새 값 |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


NURBS 곡선의 차수를 설정합니다. 차수는 Order - 1 로 정의됩니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


곡선의 차원을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | 새 값 **Remarks:** [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) 곡선의 경우, 제어점의 z 구성 요소는 사용되지 않습니다. |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


NURBS 곡선의 차수를 설정합니다. 이는 곡선상의 특정 점에 영향을 주는 인접 제어점의 수를 정의합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


지정된 속성의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |
| 값 | java.lang.Object | 속성의 값 |

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


합리적인지 여부를 설정합니다. 이 값은 이 [NurbsCurve](../../com.aspose.threed/nurbscurve)가 합리 스플라인인지 비합리 스플라인인지를 나타냅니다. 비합리 B-스플라인은 합리 B-스플라인의 특수한 경우입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

