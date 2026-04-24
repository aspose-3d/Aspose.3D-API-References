---
title: AnimationNode
second_title: Aspose.3D for Java API 레퍼런스
description: Aspose.3Ds는 애니메이션 계층 구조를 지원하며, 각 애니메이션은 여러 애니메이션과 애니메이션 키프레임 정의로 구성될 수 있습니다.
type: docs
weight: 15
url: /ko/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D는 애니메이션 계층 구조를 지원하며, 각 애니메이션은 여러 애니메이션과 애니메이션 키프레임 정의로 구성될 수 있습니다. [AnimationNode](../../com.aspose.threed/animationnode) 은 시간에 따라 속성 값의 변환을 정의합니다. 예를 들어, 애니메이션 노드를 사용하여 노드의 변환이나 다른 [A3DObject](../../com.aspose.threed/a3dobject) 객체의 수치 속성을 제어할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | 새로운 [AnimationNode](../../com.aspose.threed/animationnode) 클래스 인스턴스를 초기화합니다. |
| [AnimationNode()](#AnimationNode--) | 새로운 [AnimationNode](../../com.aspose.threed/animationnode) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | 속성 데이터 유형을 기반으로 BindPoint를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | 대상 및 이름으로 바인드 포인트를 찾습니다. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | 주어진 속성에 대한 애니메이션 바인드 포인트를 가져옵니다. |
| [getBindPoints()](#getBindPoints--) | 현재 속성 바인드 포인트를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | 주어진 속성에 대한 키프레임 시퀀스를 가져옵니다. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | 주어진 속성과 채널에 대한 키프레임 시퀀스를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getSubAnimations()](#getSubAnimations--) | 현재 애니메이션 아래의 하위 애니메이션 노드를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


새로운 [AnimationNode](../../com.aspose.threed/animationnode) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름 |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


새로운 [AnimationNode](../../com.aspose.threed/animationnode) 클래스 인스턴스를 초기화합니다.

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


속성 데이터 유형을 기반으로 BindPoint를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | 객체. |
| propName | java.lang.String | 속성 이름. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


대상 및 이름으로 바인드 포인트를 찾습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 찾을 바인드 포인트의 대상. |
| 이름 | java.lang.String | 찾을 바인드 포인트의 이름. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


주어진 속성에 대한 애니메이션 바인드 포인트를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 바인드 포인트를 생성할 객체. |
| propName | java.lang.String | 속성의 이름. |
| 생성 | boolean | true 로 설정하면 바인드 포인트가 없을 경우 생성합니다. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


현재 속성 바인드 포인트를 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - 현재 속성 바인드 포인트
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


주어진 속성에 대한 키프레임 시퀀스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 키프레임 시퀀스를 생성할 인스턴스. |
| propName | java.lang.String | 속성의 이름. |
| 생성 | boolean | true 로 설정하면 시퀀스가 없을 경우 생성합니다. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


주어진 속성과 채널에 대한 키프레임 시퀀스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | 키프레임 시퀀스를 생성할 인스턴스. |
| propName | java.lang.String | 속성의 이름. |
| channelName | java.lang.String | 채널 이름. |
| 생성 | boolean | true 로 설정하면 애니메이션 시퀀스가 없을 경우 생성합니다. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


현재 애니메이션 아래의 하위 애니메이션 노드를 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - 현재 애니메이션 아래의 하위 애니메이션 노드
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

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

