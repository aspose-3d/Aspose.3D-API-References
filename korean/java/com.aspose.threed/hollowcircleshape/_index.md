---
title: HollowCircleShape
second_title: Aspose.3D for Java API 레퍼런스
description: IFC 호환 중공 원형 프로파일.
type: docs
weight: 78
url: /ko/java/com.aspose.threed/hollowcircleshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile), [com.aspose.threed.CircleShape](../../com.aspose.threed/circleshape)
```
public class HollowCircleShape extends CircleShape
```

IFC 호환 중공 원형 프로파일.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [HollowCircleShape()](#HollowCircleShape--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getBoundingBox()](#getBoundingBox--) | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [getExcluded()](#getExcluded--) | 내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다. |
| [getExtent()](#getExtent--) | x 및 y 차원에서 범위를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getParentNode()](#getParentNode--) | 첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [getParentNodes()](#getParentNodes--) | 모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRadius()](#getRadius--) | 원의 반경을 가져옵니다. |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getWallThickness()](#getWallThickness--) | 외부 반경과 내부 반경 사이의 차이를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRadius(double value)](#setRadius-double-) | 원의 반경을 설정합니다. |
| [setWallThickness(double value)](#setWallThickness-double-) | 외부 반경과 내부 반경 사이의 차이를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HollowCircleShape() {#HollowCircleShape--}
```
public HollowCircleShape()
```


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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다.

**Returns:**
boolean - 내보내기 중에 이 엔터티를 제외할지 여부.
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


x 및 y 차원에서 범위를 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
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
### getRadius() {#getRadius--}
```
public double getRadius()
```


원의 반경을 가져옵니다.

**Returns:**
double - 원의 반지름.
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getWallThickness() {#getWallThickness--}
```
public double getWallThickness()
```


외부 반경과 내부 반경 사이의 차이를 가져옵니다.

**Returns:**
double - 외부 반경과 내부 반경 사이의 차이.
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

### setRadius(double value) {#setRadius-double-}
```
public void setRadius(double value)
```


원의 반경을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setWallThickness(double value) {#setWallThickness-double-}
```
public void setWallThickness(double value)
```


외부 반경과 내부 반경 사이의 차이를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

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

