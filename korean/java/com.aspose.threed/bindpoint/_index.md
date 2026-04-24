---
title: BindPoint
second_title: Aspose.3D for Java API 레퍼런스
description: 일반적으로 객체의 속성에 생성되며, 일부 속성 유형은 여러 구성 요소 필드(예: Vector3 필드)를 포함합니다. 각 구성 요소 필드에 대해 채널을 생성하고, 해당 필드를 하나 이상의 키프레임 시퀀스 인스턴스에 채널을 통해 연결합니다.
type: docs
weight: 19
url: /ko/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

일반적으로 객체의 속성에 [BindPoint](../../com.aspose.threed/bindpoint)이 생성되며, 일부 속성 유형은 여러 구성 요소 필드(예: Vector3 필드)를 포함합니다. [BindPoint](../../com.aspose.threed/bindpoint)은 각 구성 요소 필드에 대해 채널을 생성하고, 해당 필드를 하나 이상의 키프레임 시퀀스 인스턴스에 채널을 통해 연결합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | 새로운 [BindPoint](../../com.aspose.threed/bindpoint) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | 지정된 채널 속성을 추가합니다. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | 지정된 채널 속성을 추가합니다. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | 키프레임 시퀀스를 지정된 채널에 바인드합니다. |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | 새 곡선을 생성하고 이를 곡선 매핑의 첫 번째 채널에 연결합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [get(String channelName)](#get-java.lang.String-) | 주어진 이름으로 채널을 가져옵니다. |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | 주어진 이름으로 채널을 가져옵니다. |
| [getChannelsCount()](#getChannelsCount--) | 이 애니메이션 곡선 매핑에 정의된 속성 채널의 총 개수를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | 지정된 채널에서 첫 번째 키프레임 시퀀스를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty()](#getProperty--) | CurveMapping과 연결된 속성을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [resetChannels()](#resetChannels--) | 이 애니메이션 곡선 매핑의 속성 채널을 비웁니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | CurveMapping과 연결된 속성을 가져옵니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [toString()](#toString--) | 객체를 문자열로 포맷합니다 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


새로운 [BindPoint](../../com.aspose.threed/bindpoint) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 애니메이션을 포함하는 씬입니다. |
| prop | [Property](../../com.aspose.threed/property) | 속성. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


지정된 채널 속성을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |
| type | java.lang.Class<?> | 형식. |
| 값 | java.lang.Object | 값. |

**Returns:**
boolean - 채널이 추가되었으면 true, 그렇지 않으면 false.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


지정된 채널 속성을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |
| 값 | java.lang.Object | 값. |

**Returns:**
boolean - 채널이 추가되었으면 true, 그렇지 않으면 false.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


키프레임 시퀀스를 지정된 채널에 바인드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| channelName | java.lang.String | 키프레임 시퀀스가 바인드될 채널 |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | 바인드할 키프레임 시퀀스 |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


새 곡선을 생성하고 이를 곡선 매핑의 첫 번째 채널에 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 새 시퀀스의 이름입니다. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


주어진 이름으로 채널을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| channelName | java.lang.String | 채널 이름 |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


주어진 이름으로 채널을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| channelName | java.lang.String | 찾을 채널 이름 |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


이 애니메이션 곡선 매핑에 정의된 속성 채널의 총 개수를 가져옵니다.

**Returns:**
int - 채널 수.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


지정된 채널에서 첫 번째 키프레임 시퀀스를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| channelName | java.lang.String | 찾을 채널 이름 |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


CurveMapping과 연결된 속성을 가져옵니다.

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


이 애니메이션 곡선 매핑의 속성 채널을 비웁니다.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


CurveMapping과 연결된 속성을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | 새 값 |

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


객체를 문자열로 포맷합니다

**Returns:**
java.lang.String - 객체 문자열
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

