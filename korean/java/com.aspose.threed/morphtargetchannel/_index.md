---
title: MorphTargetChannel
second_title: Aspose.3D for Java API 레퍼런스
description: MorphTargetChannel은  에 의해 대상 기하학을 조직하는 데 사용됩니다.
type: docs
weight: 107
url: /ko/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

MorphTargetChannel은 [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 에 의해 대상 기하학을 조직하는 데 사용됩니다. FBX와 같은 일부 파일 형식은 여러 채널을 병렬로 지원합니다. **Remarks:** 가중치는 0과 1.0 사이이며, 대상의 기본 가중치는 0.0입니다;
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | 새로운 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 클래스 인스턴스를 초기화합니다. |
| [MorphTargetChannel()](#MorphTargetChannel--) | 새로운 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 클래스 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | 모프 타겟의 기본 가중치. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | 지정된 기하학에 대한 가중치를 가져옵니다 |
| [getChannelWeight()](#getChannelWeight--) | 이 채널의 디포머 가중치를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getTargets()](#getTargets--) | 채널과 연결된 모든 타겟을 가져옵니다. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | 지정된 타겟에 대한 가중치를 가져옵니다. 타겟이 이 채널에 속하지 않으면 기본값 0이 반환됩니다. |
| [getWeights()](#getWeights--) | 타겟 기하학의 전체 가중치 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | 지정된 기하학에 대한 가중치를 설정합니다 |
| [setChannelWeight(double value)](#setChannelWeight-double-) | 이 채널의 디포머 가중치를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | 지정된 타겟에 대한 가중치를 설정합니다. 기본값은 1이며, 범위는 0~1 사이여야 합니다. |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | 지정된 타겟에 대한 가중치를 설정합니다. 기본값은 1이며, 범위는 0~1 사이여야 합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


새로운 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


새로운 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 클래스 인스턴스를 초기화합니다.

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


모프 타겟의 기본 가중치.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


지정된 기하학에 대한 가중치를 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 타겟 기하학. |

**Returns:**
double - 가중치
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


이 채널의 디포머 가중치를 가져옵니다. 가중치는 0.0에서 1.0 사이입니다.

**Returns:**
double - 이 채널의 디포머 가중치. 가중치는 0.0에서 1.0 사이입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


채널과 연결된 모든 타겟을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Shape> - 채널과 연결된 모든 타겟.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


지정된 타겟에 대한 가중치를 가져옵니다. 타겟이 이 채널에 속하지 않으면 기본값 0이 반환됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


타겟 기하학의 전체 가중치 값을 가져옵니다.

**Returns:**
java.util.List<java.lang.Double> - 타겟 기하학의 전체 가중치 값.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


지정된 기하학에 대한 가중치를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 타겟 기하학. |
| 값 | double | 새 값 |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


이 채널의 디포머 가중치를 설정합니다. 가중치는 0.0에서 1.0 사이입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


지정된 타겟에 대한 가중치를 설정합니다. 기본값은 1이며, 범위는 0~1 사이여야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


지정된 타겟에 대한 가중치를 설정합니다. 기본값은 1이며, 범위는 0~1 사이여야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| 가중치 | double |  |

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

