---
title: Plane
second_title: Aspose.3D for Java API 레퍼런스
description: 매개변수화된 평면.
type: docs
weight: 128
url: /ko/java/com.aspose.threed/plane/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Plane extends Primitive
```

매개변수화된 평면.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Plane()](#Plane--) | 기본 크기 1x1인 [Plane](../../com.aspose.threed/plane)의 새 인스턴스를 초기화합니다. |
| [Plane(double length, double width)](#Plane-double-double-) | [Plane](../../com.aspose.threed/plane)의 새 인스턴스를 초기화합니다. |
| [Plane(String name, double length, double width, int lengthSegments, int widthSegments)](#Plane-java.lang.String-double-double-int-int-) | [Plane](../../com.aspose.threed/plane)의 새 인스턴스를 초기화합니다. |
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
| [getLength()](#getLength--) | 평면의 길이를 가져옵니다. |
| [getLengthSegments()](#getLengthSegments--) | 길이 세그먼트를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getParentNode()](#getParentNode--) | 첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [getParentNodes()](#getParentNodes--) | 모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getReceiveShadows()](#getReceiveShadows--) | 이 기하학이 그림자를 받을 수 있는지 여부를 가져옵니다. |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getUp()](#getUp--) | 평면의 위쪽 벡터를 가져옵니다. 기본값은 (0, 1, 0)이며, 이는 평면 생성에 영향을 줍니다. |
| [getWidth()](#getWidth--) | 평면의 너비를 가져옵니다. |
| [getWidthSegments()](#getWidthSegments--) | 너비 세그먼트를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | 이 기하학이 그림자를 드리울 수 있는지 여부를 설정합니다. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다. |
| [setLength(double value)](#setLength-double-) | 평면의 길이를 설정합니다. |
| [setLengthSegments(int value)](#setLengthSegments-int-) | 길이 세그먼트를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | 이 기하학이 그림자를 받을 수 있는지 여부를 설정합니다. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | 평면의 위쪽 벡터를 설정합니다. 기본값은 (0, 1, 0)이며, 이는 평면 생성에 영향을 줍니다. |
| [setWidth(double value)](#setWidth-double-) | 평면의 너비를 설정합니다. |
| [setWidthSegments(int value)](#setWidthSegments-int-) | 너비 세그먼트를 설정합니다. |
| [toMesh()](#toMesh--) | 현재 객체를 메시로 변환합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Plane() {#Plane--}
```
public Plane()
```


기본 크기 1x1인 [Plane](../../com.aspose.threed/plane)의 새 인스턴스를 초기화합니다.

### Plane(double length, double width) {#Plane-double-double-}
```
public Plane(double length, double width)
```


[Plane](../../com.aspose.threed/plane)의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 길이 | double | 평면의 길이. |
| 너비 | double | 평면의 너비. |

### Plane(String name, double length, double width, int lengthSegments, int widthSegments) {#Plane-java.lang.String-double-double-int-int-}
```
public Plane(String name, double length, double width, int lengthSegments, int widthSegments)
```


[Plane](../../com.aspose.threed/plane)의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |
| 길이 | double | 평면의 길이. |
| 너비 | double | 평면의 너비. |
| lengthSegments | int | 길이 세그먼트. |
| widthSegments | int | 너비 세그먼트. |

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
### getLength() {#getLength--}
```
public double getLength()
```


평면의 길이를 가져옵니다.

**Returns:**
double - 평면의 길이.
### getLengthSegments() {#getLengthSegments--}
```
public int getLengthSegments()
```


길이 세그먼트를 가져옵니다.

**Returns:**
int - 길이 세그먼트.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
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
### getUp() {#getUp--}
```
public Vector3 getUp()
```


평면의 위쪽 벡터를 가져옵니다. 기본값은 (0, 1, 0)이며, 이는 평면 생성에 영향을 줍니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up vector of the plane, default value is (0, 1, 0), this affects the generation of the plane
### getWidth() {#getWidth--}
```
public double getWidth()
```


평면의 너비를 가져옵니다.

**Returns:**
double - 평면의 너비.
### getWidthSegments() {#getWidthSegments--}
```
public int getWidthSegments()
```


너비 세그먼트를 가져옵니다.

**Returns:**
int - 너비 세그먼트.
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

### setLength(double value) {#setLength-double-}
```
public void setLength(double value)
```


평면의 길이를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setLengthSegments(int value) {#setLengthSegments-int-}
```
public void setLengthSegments(int value)
```


길이 세그먼트를 설정합니다.

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


이 기하학이 그림자를 받을 수 있는지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


평면의 위쪽 벡터를 설정합니다. 기본값은 (0, 1, 0)이며, 이는 평면 생성에 영향을 줍니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


평면의 너비를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setWidthSegments(int value) {#setWidthSegments-int-}
```
public void setWidthSegments(int value)
```


너비 세그먼트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

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

