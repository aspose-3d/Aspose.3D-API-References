---
title: MorphTargetDeformer
second_title: Aspose.3D for Java API 레퍼런스
description: MorphTargetDeformer는 정점당 애니메이션을 제공합니다.
type: docs
weight: 108
url: /ko/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer는 정점당 애니메이션을 제공합니다. MorphTargetDeformer는 모든 타깃을 [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel) 을 통해 조직하며, 각 채널은 여러 타깃을 조직할 수 있습니다. morph target deformer의 일반적인 사용은 캐릭터에 얼굴 표정을 적용하는 것입니다. 자세한 내용은 https://en.wikipedia.org/wiki/Morph\\_target\\_animation 에서 확인할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 클래스의 새 인스턴스를 초기화합니다. |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | 주어진 지오메트리의 가중치를 가져옵니다. 이는 채널에 접근하지 않고 타깃의 가중치를 수정하는 간편한 방법입니다. |
| [getChannels()](#getChannels--) | 이 디포머에 포함된 모든 채널을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getOwner()](#getOwner--) | 이 디포머를 소유하는 기하학을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | 주어진 지오메트리의 가중치를 설정합니다. 이는 채널에 접근하지 않고 타깃의 가중치를 수정하는 간편한 방법입니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


[MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


[MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) 클래스의 새 인스턴스를 초기화합니다.

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


주어진 지오메트리의 가중치를 가져옵니다. 이는 채널에 접근하지 않고 타깃의 가중치를 수정하는 간편한 방법입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 대상 기하학 |

**Returns:**
double - 가중치
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


이 디포머에 포함된 모든 채널을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - 이 디포머에 포함된 모든 채널
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
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


이 디포머를 소유하는 기하학을 가져옵니다.

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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


주어진 지오메트리의 가중치를 설정합니다. 이는 채널에 접근하지 않고 타깃의 가중치를 수정하는 간편한 방법입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | 대상 기하학 |
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

