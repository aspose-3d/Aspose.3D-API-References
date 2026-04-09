---
title: Bone
second_title: Aspose.3D for Java API 레퍼런스
description: 본은 지오메트리의 컨트롤 포인트 하위 집합을 정의하고 각 컨트롤 포인트에 대한 블렌드 가중치를 정의합니다.
type: docs
weight: 20
url: /ko/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

본은 지오메트리의 컨트롤 포인트 하위 집합을 정의하고 각 컨트롤 포인트에 대한 블렌드 가중치를 정의합니다. [Bone](../../com.aspose.threed/bone) 객체는 직접 사용할 수 없으며, [SkinDeformer](../../com.aspose.threed/skindeformer) 인스턴스를 사용하여 지오메트리를 변형하고, [SkinDeformer](../../com.aspose.threed/skindeformer)에는 여러 본이 포함된 세트가 있으며 각 본은 노드에 연결됩니다. 참고: 지오메트리의 컨트롤 포인트는 둘 이상의 본에 연결될 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | [Bone](../../com.aspose.threed/bone) 클래스의 새 인스턴스를 초기화합니다. |
| [Bone()](#Bone--) | [Bone](../../com.aspose.threed/bone) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [get(int index)](#get-int-) | 지정된 컨트롤 포인트의 블렌드 가중치를 가져옵니다. |
| [getBoneTransform()](#getBoneTransform--) | 본의 변환 행렬을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | 뼈대의 연결 모드는 계층 구조 내에서 뼈가 부모 뼈와 연결되거나 링크되는 방식을 나타냅니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getNode()](#getNode--) | 노드를 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getTransform()](#getTransform--) | 뼈를 포함하는 노드의 변환 행렬을 가져옵니다. |
| [getWeight(int index)](#getWeight-int-) | 인덱스로 지정된 제어점의 가중치를 가져옵니다. |
| [getWeightCount()](#getWeightCount--) | 가중치 개수를 가져옵니다. 이는 [setWeight](../../com.aspose.threed/bone\#setWeight)으로 자동으로 확장됩니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [set(int index, double value)](#set-int-double-) | 지정된 제어점의 블렌드 가중치를 설정합니다. |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | 뼈의 변환 행렬을 설정합니다. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | 뼈대의 연결 모드는 계층 구조 내에서 뼈가 부모 뼈와 연결되거나 링크되는 방식을 나타냅니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | 노드를 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | 뼈를 포함하는 노드의 변환 행렬을 설정합니다. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | 인덱스로 지정된 제어점의 가중치를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


[Bone](../../com.aspose.threed/bone) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |

### Bone() {#Bone--}
```
public Bone()
```


[Bone](../../com.aspose.threed/bone) 클래스의 새 인스턴스를 초기화합니다.

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
### get(int index) {#get-int-}
```
public double get(int index)
```


지정된 컨트롤 포인트의 블렌드 가중치를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 가중치 인덱스 |

**Returns:**
double - 가중치
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


본의 변환 행렬을 가져옵니다.

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


뼈대의 연결 모드는 계층 구조 내에서 뼈가 부모 뼈와 연결되거나 링크되는 방식을 나타냅니다.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getNode() {#getNode--}
```
public Node getNode()
```


노드를 가져옵니다. 뼈 노드는 스킨이 부착되는 뼈이며, [SkinDeformer](../../com.aspose.threed/skindeformer)는 뼈 노드를 사용하여 제어점들의 변위를 영향을 줍니다. 뼈 노드에는 일반적으로 [Skeleton](../../com.aspose.threed/skeleton)이 연결되어 있지만 필수는 아닙니다. 연결된 [Skeleton](../../com.aspose.threed/skeleton)은 보통 DCC 소프트웨어에서 사용자가 스켈레톤을 볼 수 있도록 사용됩니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


뼈를 포함하는 노드의 변환 행렬을 가져옵니다.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


인덱스로 지정된 제어점의 가중치를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 제어점 인덱스 |

**Returns:**
double - 지정된 인덱스의 가중치, 인덱스가 유효하지 않으면 0
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


가중치 개수를 가져옵니다. 이는 [setWeight](../../com.aspose.threed/bone\#setWeight)으로 자동으로 확장됩니다.

**Returns:**
int - 가중치 개수, 이는 [setWeight](../../com.aspose.threed/bone\#setWeight)으로 자동으로 확장됩니다.
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


지정된 제어점의 블렌드 가중치를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 가중치 인덱스 |
| 값 | double | 새 값 |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


뼈의 변환 행렬을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 새 값 |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


뼈대의 연결 모드는 계층 구조 내에서 뼈가 부모 뼈와 연결되거나 링크되는 방식을 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


노드를 설정합니다. 뼈 노드는 스킨이 부착되는 뼈이며, [SkinDeformer](../../com.aspose.threed/skindeformer)는 뼈 노드를 사용하여 제어점들의 변위를 영향을 줍니다. 뼈 노드에는 일반적으로 [Skeleton](../../com.aspose.threed/skeleton)이 연결되어 있지만 필수는 아닙니다. 연결된 [Skeleton](../../com.aspose.threed/skeleton)은 보통 DCC 소프트웨어에서 사용자가 스켈레톤을 볼 수 있도록 사용됩니다.

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


뼈를 포함하는 노드의 변환 행렬을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | 새 값 |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


인덱스로 지정된 제어점의 가중치를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 제어점 인덱스 |
| 가중치 | double | 새 가중치 |

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

