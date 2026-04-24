---
title: AnimationClip
second_title: Aspose.3D for Java API 레퍼런스
description: Animation 클립은 애니메이션의 컬렉션입니다.
type: docs
weight: 14
url: /ko/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

Animation clip은 애니메이션의 컬렉션입니다. 씬은 하나 이상의 애니메이션 클립을 가질 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | [AnimationClip](../../com.aspose.threed/animationclip) 클래스의 새 인스턴스를 초기화합니다. |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | [AnimationClip](../../com.aspose.threed/animationclip) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | 현재 클립에 애니메이션 노드를 생성하고 등록하는 단축 함수입니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getAnimations()](#getAnimations--) | 클립에 포함된 애니메이션을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 이 애니메이션 클립의 설명을 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getStart()](#getStart--) | 클립 시작 시점의 시간을 초 단위로 가져옵니다. |
| [getStop()](#getStop--) | 클립 종료 시점의 시간을 초 단위로 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setDescription(String value)](#setDescription-java.lang.String-) | 이 애니메이션 클립의 설명을 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setStart(double value)](#setStart-double-) | 클립 시작 시점을 초 단위로 설정합니다. |
| [setStop(double value)](#setStop-double-) | 클립 종료 시점을 초 단위로 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


[AnimationClip](../../com.aspose.threed/animationclip) 클래스의 새 인스턴스를 초기화합니다.

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


[AnimationClip](../../com.aspose.threed/animationclip) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름 |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


현재 클립에 애니메이션 노드를 생성하고 등록하는 단축 함수입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nodeName | java.lang.String | 새 애니메이션 노드 이름 |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
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
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


클립에 포함된 애니메이션을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - 클립에 포함된 애니메이션들.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


이 애니메이션 클립의 설명을 가져옵니다.

**Returns:**
java.lang.String - 이 애니메이션 클립에 대한 설명
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
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


클립 시작 시점의 시간을 초 단위로 가져옵니다.

**Returns:**
double - 클립 시작 시점의 초 단위 시간.
### getStop() {#getStop--}
```
public double getStop()
```


클립 종료 시점의 시간을 초 단위로 가져옵니다.

**Returns:**
double - 클립 종료 시점의 초 단위 시간.
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
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


이 애니메이션 클립의 설명을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

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

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


클립 시작 시점을 초 단위로 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


클립 종료 시점을 초 단위로 설정합니다.

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

