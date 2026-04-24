---
title: Transform
second_title: Aspose.3D for Java API 레퍼런스
description: 변환은 객체의 이동/스케일/회전 또는 변환 행렬에 최소 비용으로 접근할 수 있는 정보를 포함합니다. 이는 로컬 변환에 사용됩니다.
type: docs
weight: 190
url: /ko/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

변환은 객체의 이동/스케일/회전 또는 변환 행렬에 최소 비용으로 접근할 수 있는 정보를 포함합니다. 이는 로컬 변환에 사용됩니다. **Example:** 다음 코드는 노드의 변환을 변경하는 방법을 보여줍니다:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Euler 각도(도)로 표현된 회전을 가져옵니다. |
| [getGeometricRotation()](#getGeometricRotation--) | 기하학적 오일러 회전을 가져옵니다(단위:도). |
| [getGeometricScaling()](#getGeometricScaling--) | 기하학적 스케일을 가져옵니다. |
| [getGeometricTranslation()](#getGeometricTranslation--) | 기하학적 이동을 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getPostRotation()](#getPostRotation--) | 도 단위로 표시된 후 회전을 가져옵니다 |
| [getPreRotation()](#getPreRotation--) | 도 단위로 표시된 사전 회전을 가져옵니다 |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRotation()](#getRotation--) | 쿼터니언으로 표현된 회전을 가져옵니다. |
| [getRotationOffset()](#getRotationOffset--) | 회전 오프셋을 가져옵니다 |
| [getRotationPivot()](#getRotationPivot--) | 회전 피벗을 가져옵니다 |
| [getScaling()](#getScaling--) | 스케일링을 가져옵니다 |
| [getScalingOffset()](#getScalingOffset--) | 스케일링 오프셋을 가져옵니다 |
| [getScalingPivot()](#getScalingPivot--) | 스케일링 피벗을 가져옵니다 |
| [getTransformMatrix()](#getTransformMatrix--) | 변환 행렬을 가져옵니다. |
| [getTranslation()](#getTranslation--) | 이동을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | Euler 각도로 표시된 회전을 설정합니다(단위:도). |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | 현재 변환의 Euler 각도를 도 단위로 설정합니다. |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | 기하학적 Euler 회전을 설정합니다(단위:도). |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | 기하학적 Euler 회전을 설정합니다(단위:도). |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | 기하학적 스케일링을 설정합니다. |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | 기하학적 스케일링을 설정합니다. |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | 기하학적 변환을 설정합니다. |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | 기하학적 변환을 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | 도 단위로 표시된 사후 회전을 설정합니다. |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | 도 단위로 표시된 사후 회전을 설정합니다 **Example:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | 도 단위로 표시된 사전 회전을 설정합니다. |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | 도 단위로 표시된 사전 회전을 설정합니다 **Example:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | 쿼터니언으로 표시된 회전을 설정합니다. |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | 현재 변환의 회전을 (쿼터니언 구성 요소로) 설정합니다. |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | 회전 오프셋을 설정합니다. |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | 회전 피벗을 설정합니다. |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | 현재 변환의 스케일을 설정합니다. |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | 스케일링을 설정합니다. |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | 스케일링 오프셋을 설정합니다. |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | 스케일링 피벗을 설정합니다. |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | 변환 행렬을 설정합니다. |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | 이동을 설정합니다. |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | 현재 변환의 이동을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEulerAngles() {#getEulerAngles--}
```
public Vector3 getEulerAngles()
```


Euler 각도(도)로 표현된 회전을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
```
### getGeometricRotation() {#getGeometricRotation--}
```
public Vector3 getGeometricRotation()
```


기하학적 Euler 회전을 가져옵니다(단위:도). 기하학적 변환은 연결된 엔터티에만 영향을 주며 자식 노드에는 영향을 주지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


기하학적 스케일링을 가져옵니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric scaling. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
```
### getGeometricTranslation() {#getGeometricTranslation--}
```
public Vector3 getGeometricTranslation()
```


기하학적 평행이동을 가져옵니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric translation. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
```
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


도 단위로 표시된 후 회전을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
```
### getPreRotation() {#getPreRotation--}
```
public Vector3 getPreRotation()
```


도 단위로 표시된 사전 회전을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
```
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
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


쿼터니언으로 표현된 회전을 가져옵니다.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
```
### getRotationOffset() {#getRotationOffset--}
```
public Vector3 getRotationOffset()
```


회전 오프셋을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


회전 피벗을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


스케일링을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling **Example:**

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
```
### getScalingOffset() {#getScalingOffset--}
```
public Vector3 getScalingOffset()
```


스케일링 오프셋을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


스케일링 피벗을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


변환 행렬을 가져옵니다.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Remarks:** Assign on this will reset the [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) and [getRotation](../../com.aspose.threed/transform\#getRotation), the [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) and [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) will not be affected. **Example:**

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


이동을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
```
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
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


Euler 각도로 표시된 회전을 설정합니다(단위:도).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


현재 변환의 오일러 각도를 도 단위로 설정합니다. **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricRotation(Vector3 value) {#setGeometricRotation-com.aspose.threed.Vector3-}
```
public void setGeometricRotation(Vector3 value)
```


기하학적 오일러 회전을 (도 단위) 설정합니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


기하학적 오일러 회전을 (도 단위) 설정합니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricScaling(Vector3 value) {#setGeometricScaling-com.aspose.threed.Vector3-}
```
public void setGeometricScaling(Vector3 value)
```


기하학적 스케일링을 설정합니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


기하학적 스케일링을 설정합니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricTranslation(Vector3 value) {#setGeometricTranslation-com.aspose.threed.Vector3-}
```
public void setGeometricTranslation(Vector3 value)
```


기하학적 평행이동을 설정합니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


기하학적 평행이동을 설정합니다. 기하학적 변환은 연결된 엔터티에만 영향을 미치며 자식 노드는 영향을 받지 않습니다. 지원하지 않는 파일 형식으로 기하학적 변환을 내보낼 때 로컬 변환으로 병합됩니다. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


도 단위로 표시된 사후 회전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


도 단위로 표시된 사후 회전을 설정합니다 **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setPreRotation(Vector3 value) {#setPreRotation-com.aspose.threed.Vector3-}
```
public void setPreRotation(Vector3 value)
```


도 단위로 표시된 사전 회전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


도 단위로 표시된 사전 회전을 설정합니다 **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


쿼터니언으로 표시된 회전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


현재 변환의 회전을 (쿼터니언 구성 요소) 로 설정합니다. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rw | double |  |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setRotationOffset(Vector3 value) {#setRotationOffset-com.aspose.threed.Vector3-}
```
public void setRotationOffset(Vector3 value)
```


회전 오프셋을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


회전 피벗을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


현재 변환의 스케일을 설정합니다. **Example:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setScaling(Vector3 value) {#setScaling-com.aspose.threed.Vector3-}
```
public void setScaling(Vector3 value)
```


스케일링을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


스케일링 오프셋을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


스케일링 피벗을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


변환 행렬을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | 새 값 **Remarks:** 이 값에 할당하면 [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) 및 [getRotation](../../com.aspose.threed/transform\#getRotation)이 재설정되고, [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) 및 [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation)은 영향을 받지 않습니다. **Example:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


이동을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


현재 변환의 평행이동을 설정합니다. **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

