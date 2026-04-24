---
title: KeyframeSequence
second_title: Aspose.3D for Java API 레퍼런스
description: 키프레임 시퀀스는 시간에 따라 샘플링된 값의 변환을 설명합니다.
type: docs
weight: 90
url: /ko/java/com.aspose.threed/keyframesequence/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class KeyframeSequence extends A3DObject implements Iterable<KeyFrame>
```

키 프레임의 순서로, 시간에 따른 샘플링 값의 변환을 설명합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [KeyframeSequence(String name)](#KeyframeSequence-java.lang.String-) | 새로운 [KeyframeSequence](../../com.aspose.threed/keyframesequence) 클래스의 인스턴스를 초기화합니다. |
| [KeyframeSequence()](#KeyframeSequence--) | 새로운 [KeyframeSequence](../../com.aspose.threed/keyframesequence) 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | 지정된 값으로 새 키 프레임을 생성합니다. |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | 지정된 값으로 새 키 프레임을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getBindPoint()](#getBindPoint--) | 이 곡선을 소유하는 속성 바인드 포인트를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getKeyFrames()](#getKeyFrames--) | 이 곡선의 키 프레임을 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getPostBehavior()](#getPostBehavior--) | 마지막 키 프레임 이후에 샘플링된 값이 어떻게 되어야 하는지를 나타내는 포스트 동작을 가져옵니다. |
| [getPreBehavior()](#getPreBehavior--) | 첫 번째 키 프레임 이전에 샘플링된 값이 어떻게 되어야 하는지를 나타내는 프리 동작을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 모든 키 프레임을 순회하기 위한 열거자를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [reset()](#reset--) | 모든 키 프레임을 제거하고 포스트/프리 동작을 재설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyframeSequence(String name) {#KeyframeSequence-java.lang.String-}
```
public KeyframeSequence(String name)
```


새로운 [KeyframeSequence](../../com.aspose.threed/keyframesequence) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름 |

### KeyframeSequence() {#KeyframeSequence--}
```
public KeyframeSequence()
```


새로운 [KeyframeSequence](../../com.aspose.threed/keyframesequence) 클래스의 인스턴스를 초기화합니다.

### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


지정된 값으로 새 키 프레임을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시간 | double | 시간 위치(초 단위 측정) |
| 값 | float | 이 시간 위치에서의 값 |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


지정된 값으로 새 키 프레임을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시간 | double | 시간 위치(초 단위 측정) |
| 값 | float | 이 시간 위치에서의 값 |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | 이 키 프레임의 보간 유형 |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


이 곡선을 소유하는 속성 바인드 포인트를 가져옵니다.

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


이 곡선의 키 프레임을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - 이 곡선의 키 프레임.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


마지막 키 프레임 이후에 샘플링된 값이 어떻게 되어야 하는지를 나타내는 포스트 동작을 가져옵니다.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


첫 번째 키 프레임 이전에 샘플링된 값이 어떻게 되어야 하는지를 나타내는 프리 동작을 가져옵니다.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


모든 키 프레임을 순회하기 위한 열거자를 가져옵니다.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


모든 키 프레임을 제거하고 포스트/프리 동작을 재설정합니다.

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

