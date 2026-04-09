---
title: Cylinder
second_title: Aspose.3D for Java API 레퍼런스
description: 파라미터화된 실린더.
type: docs
weight: 40
url: /ko/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

Parameterized Cylinder. It can also be used to represent the cone when one of radiusTop/radiusBottom is zero.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Cylinder()](#Cylinder--) | Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class. |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class. |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class. |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class. |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getBoundingBox()](#getBoundingBox--) | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| [getCastShadows()](#getCastShadows--) | 이 기하학이 그림자를 드리울 수 있는지 여부를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [getExcluded()](#getExcluded--) | 내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다. |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | Gets whether to generate the fan-style cylinder when the ThetaLength is less than 2\*PI, otherwise the model will not be cut. |
| [getHeight()](#getHeight--) | Gets the height of the cylinder. |
| [getHeightSegments()](#getHeightSegments--) | 세로 세그먼트를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getOffsetBottom()](#getOffsetBottom--) | Gets the vertices transformation offset of the bottom side. |
| [getOffsetTop()](#getOffsetTop--) | Gets the vertices transformation offset of the top side. |
| [getOpenEnded()](#getOpenEnded--) | Gets a value indicating whether this [Cylinder](../../com.aspose.threed/cylinder) open ended. |
| [getParentNode()](#getParentNode--) | 첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [getParentNodes()](#getParentNodes--) | 모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRadialSegments()](#getRadialSegments--) | Gets the radial segments. |
| [getRadiusBottom()](#getRadiusBottom--) | Gets the radius of cylinder's bottom cap. |
| [getRadiusTop()](#getRadiusTop--) | 실린더 상단 캡의 반경을 가져옵니다. |
| [getReceiveShadows()](#getReceiveShadows--) | 이 기하학이 그림자를 받을 수 있는지 여부를 가져옵니다. |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getShearBottom()](#getShearBottom--) | 하단 면의 전단 변환을 가져옵니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |
| [getShearTop()](#getShearTop--) | 상단 면의 전단 변환을 가져옵니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |
| [getThetaLength()](#getThetaLength--) | theta의 길이를 가져옵니다. |
| [getThetaStart()](#getThetaStart--) | theta 시작값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 이 기하학이 그림자를 드리울 수 있는지 여부를 설정합니다. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | ThetaLength가 2\*PI보다 작을 때 팬 스타일 실린더를 생성할지 여부를 설정합니다. 그렇지 않으면 모델이 잘리지 않습니다. |
| [setHeight(double value)](#setHeight-double-) | 실린더의 높이를 설정합니다. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | 높이 세그먼트를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | 하단 면의 정점 변환 오프셋을 설정합니다. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | 상단 면의 정점 변환 오프셋을 설정합니다. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | 이 [Cylinder](../../com.aspose.threed/cylinder)이 개방형인지 여부를 나타내는 값을 설정합니다. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRadialSegments(int value)](#setRadialSegments-int-) | 방사형 세그먼트를 설정합니다. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | 실린더 하단 캡의 반경을 설정합니다. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | 실린더 상단 캡의 반경을 설정합니다. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | 이 기하학이 그림자를 받을 수 있는지 여부를 설정합니다. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | 하단 면의 전단 변환을 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | 상단 면의 전단 변환을 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |
| [setThetaLength(double value)](#setThetaLength-double-) | theta의 길이를 설정합니다. |
| [setThetaStart(double value)](#setThetaStart-double-) | theta 시작을 설정합니다. |
| [toMesh()](#toMesh--) | 현재 객체를 메시로 변환합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class.

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 반경 | double | 상단 및 하단 캡의 반경. |
| 높이 | double | 높이. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radiusTop | double | 상단 반경. |
| radiusBottom | double | 하단 반경. |
| 높이 | double | 높이. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| radiusTop | double | 실린더 상단 캡의 반경. |
| radiusBottom | double | 실린더 하단 캡의 반경. |
| 높이 | double | 실린더의 높이. |
| radialSegments | int | 상단 및 하단 원의 방사형 세그먼트.. |
| heightSegments | int | 높이 세그먼트. |
| openEnded | boolean | true 로 설정하면 실린더에 바닥/위쪽 캡이 없게 됩니다.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


Initializes a new instance of the [Cylinder](../../com.aspose.threed/cylinder) class.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이 객체의 이름 |
| radiusTop | double | 실린더 상단 캡의 반경. |
| radiusBottom | double | 실린더 하단 캡의 반경. |
| 높이 | double | 실린더의 높이. |
| radialSegments | int | 상단 및 하단 원의 방사형 세그먼트.. |
| heightSegments | int | 높이 세그먼트. |
| openEnded | boolean | true 로 설정하면 실린더에 바닥/위쪽 캡이 없게 됩니다.. |
| thetaStart | double | Theta 시작. |
| thetaLength | double | Theta 길이. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


이 기하학이 그림자를 드리울 수 있는지 여부를 가져옵니다.

**Returns:**
boolean - 이 기하학이 그림자를 드리울 수 있는지 여부
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


렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다.

**Returns:**
boolean - 내보내기 중에 이 엔터티를 제외할지 여부.
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


Gets whether to generate the fan-style cylinder when the ThetaLength is less than 2\*PI, otherwise the model will not be cut.

**Returns:**
boolean - ThetaLength가 2\*PI보다 작을 때 팬 스타일 실린더를 생성할지 여부, 그렇지 않으면 모델이 잘리지 않습니다.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of the cylinder.

**Returns:**
double - 실린더의 높이.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


세로 세그먼트를 가져옵니다.

**Returns:**
int - 높이 세그먼트.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


Gets the vertices transformation offset of the bottom side.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


Gets the vertices transformation offset of the top side.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


이 [Cylinder](../../com.aspose.threed/cylinder)가 열린 끝인지 나타내는 값을 가져옵니다. 기본값은 false입니다.

**Returns:**
boolean - 이 [Cylinder](../../com.aspose.threed/cylinder)가 열린 끝인지 나타내는 값. 기본값은 false입니다.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


Gets the radial segments.

**Returns:**
int - 방사형 세그먼트.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


Gets the radius of cylinder's bottom cap.

**Returns:**
double - 실린더 바닥 캡의 반지름.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


실린더 상단 캡의 반경을 가져옵니다.

**Returns:**
double - 실린더 상단 캡의 반지름.
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


이 기하학이 그림자를 받을 수 있는지 여부를 가져옵니다.

**Returns:**
boolean - 이 기하학이 그림자를 받을 수 있는지 여부.
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


하단 면의 전단 변환을 가져옵니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


상단 면의 전단 변환을 가져옵니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


theta의 길이를 가져옵니다. 기본값은 2\\u03c0입니다.

**Returns:**
double - theta의 길이. 기본값은 2\\u03c0입니다.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


theta 시작값을 가져옵니다. 기본값은 0입니다.

**Returns:**
double - theta 시작값. 기본값은 0입니다.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


이 기하학이 그림자를 드리울 수 있는지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


ThetaLength가 2\*PI보다 작을 때 팬 스타일 실린더를 생성할지 여부를 설정합니다. 그렇지 않으면 모델이 잘리지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


실린더의 높이를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


높이 세그먼트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


하단 면의 정점 변환 오프셋을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


상단 면의 정점 변환 오프셋을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


이 [Cylinder](../../com.aspose.threed/cylinder)가 열린 끝인지 나타내는 값을 설정합니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


방사형 세그먼트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


실린더 하단 캡의 반경을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


실린더 상단 캡의 반경을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


이 기하학이 그림자를 받을 수 있는지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


하단 면의 전단 변환을 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


상단 면의 전단 변환을 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


theta의 길이를 설정합니다. 기본값은 2\\u03c0입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


theta 시작값을 설정합니다. 기본값은 0입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


현재 객체를 메시로 변환합니다.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

