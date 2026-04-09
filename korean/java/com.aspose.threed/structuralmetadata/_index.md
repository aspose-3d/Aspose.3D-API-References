---
title: StructuralMetadata
second_title: Aspose.3D for Java API 레퍼런스
description: 이 클래스는 glTF에서만 사용되는 EXT_structural_metadata에 대한 지원을 제공합니다.
type: docs
weight: 180
url: /ko/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

이 클래스는 glTF에서만 사용되는 EXT\_structural\_metadata에 대한 지원을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | 현재 메타 데이터를 지정된 씬에 연결합니다 |
| [createClass(String name)](#createClass-java.lang.String-) | 메타 클래스 유형을 생성합니다 |
| [createEnum(String name)](#createEnum-java.lang.String-) | 열거형 유형을 생성합니다 |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | 주어진 메타 클래스 유형으로 새로운 속성 테이블을 생성합니다 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | 지정된 씬과 연결된 [StructuralMetadata](../../com.aspose.threed/structuralmetadata)를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | 클래스 정의. |
| [getEnums()](#getEnums--) | 열거형 유형 정의 |
| [getPropertyTables()](#getPropertyTables--) | 이 메타데이터의 속성 테이블. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuralMetadata() {#StructuralMetadata--}
```
public StructuralMetadata()
```


### attach(Scene scene) {#attach-com.aspose.threed.Scene-}
```
public void attach(Scene scene)
```


현재 메타 데이터를 지정된 씬에 연결합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


메타 클래스 유형을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 클래스 이름 |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


열거형 유형을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | The enum type's name |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


주어진 메타 클래스 유형으로 새로운 속성 테이블을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | The name of the property table |
| clazz | [ClassType](../../com.aspose.threed/classtype) | The class type of the new property table |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


지정된 씬과 연결된 [StructuralMetadata](../../com.aspose.threed/structuralmetadata)를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Which scene to look for the structural metadata |

**Returns:**
[StructuralMetadata](../../com.aspose.threed/structuralmetadata) - A valid instance of [StructuralMetadata](../../com.aspose.threed/structuralmetadata) if its found in the scene, otherwise null returned
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClasses() {#getClasses--}
```
public HashMap<String,StructuralMetadata.ClassType> getClasses()
```


클래스 정의.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - The class definitions .
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


열거형 유형 정의

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - The enum type definitions
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


이 메타데이터의 속성 테이블.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - The property tables in this metadata.
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

