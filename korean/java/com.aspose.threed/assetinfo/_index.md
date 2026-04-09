---
title: AssetInfo
second_title: Aspose.3D for Java API 레퍼런스
description: 자산 정보.
type: docs
weight: 17
url: /ko/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

자산 정보. 자산 정보는 [Scene](../../com.aspose.threed/scene)에 첨부될 수 있습니다. 하위 [Scene](../../com.aspose.threed/scene)은 자체 [AssetInfo](../../com.aspose.threed/assetinfo)를 가질 수 있어 부모 정의를 재정의합니다. **Example:** 다음 코드는 fbx 파일에서 자산 정보를 읽는 방법을 보여줍니다:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | [AssetInfo](../../com.aspose.threed/assetinfo) 클래스의 새 인스턴스를 초기화합니다. |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | [AssetInfo](../../com.aspose.threed/assetinfo) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getAmbient()](#getAmbient--) | 이 자산의 기본 주변 색상을 가져오거나 설정합니다. |
| [getApplicationName()](#getApplicationName--) | 이 자산을 만든 애플리케이션을 가져옵니다. |
| [getApplicationVendor()](#getApplicationVendor--) | 애플리케이션 공급업체의 이름을 가져옵니다. |
| [getApplicationVersion()](#getApplicationVersion--) | 이 자산을 만든 애플리케이션의 버전을 가져옵니다. |
| [getAuthor()](#getAuthor--) | 이 자산의 저자를 가져옵니다. |
| [getAxisSystem()](#getAxisSystem--) | 자산 정보의 좌표계/업 벡터/전방 벡터를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | 이 자산의 주석을 가져옵니다. |
| [getCoordinateSystem()](#getCoordinateSystem--) | 이 자산에서 사용되는 좌표계를 가져옵니다. |
| [getCopyright()](#getCopyright--) | 문서의 저작권 정보를 가져옵니다. |
| [getCreationTime()](#getCreationTime--) | 이 자산의 생성 시간을 가져오거나 설정합니다 |
| [getFrontVector()](#getFrontVector--) | 이 자산에 사용된 앞쪽 벡터를 가져옵니다. |
| [getKeywords()](#getKeywords--) | 이 자산의 키워드를 가져옵니다 |
| [getModificationTime()](#getModificationTime--) | 이 자산의 수정 시간을 가져오거나 설정합니다 |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRevision()](#getRevision--) | 이 자산의 리비전 번호를 가져옵니다(보통 버전 관리 시스템에서 사용됩니다). |
| [getSubject()](#getSubject--) | 이 자산의 주제를 가져옵니다 |
| [getTitle()](#getTitle--) | 이 자산의 제목을 가져옵니다 |
| [getUnitName()](#getUnitName--) | 이 자산에 사용된 길이 단위를 가져옵니다. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | 실제 미터에 대한 스케일 팩터를 가져옵니다. |
| [getUpVector()](#getUpVector--) | 이 자산에 사용된 위쪽 벡터를 가져옵니다. |
| [getUrl()](#getUrl--) | 이 자산의 URL을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | 이 자산의 기본 주변 색상을 가져오거나 설정합니다. |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | 이 자산을 만든 애플리케이션을 설정합니다 |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | 애플리케이션 공급업체 이름을 설정합니다 |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | 이 자산을 만든 애플리케이션의 버전을 설정합니다. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 이 자산의 저자를 설정합니다 |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | 자산 정보의 좌표계/위쪽 벡터/앞쪽 벡터를 설정합니다. |
| [setComment(String value)](#setComment-java.lang.String-) | 이 자산의 주석을 설정합니다. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | 이 자산에 사용된 좌표계를 설정합니다. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 문서의 저작권을 설정합니다 |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | 이 자산의 생성 시간을 가져오거나 설정합니다 |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | 이 자산에 사용된 앞쪽 벡터를 설정합니다. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 이 자산의 키워드를 설정합니다 |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | 이 자산의 수정 시간을 가져오거나 설정합니다 |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRevision(String value)](#setRevision-java.lang.String-) | 이 자산의 리비전 번호를 설정합니다(보통 버전 관리 시스템에서 사용됩니다). |
| [setSubject(String value)](#setSubject-java.lang.String-) | 이 자산의 주제를 설정합니다 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 이 자산의 제목을 설정합니다 |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | 이 자산에 사용된 길이 단위를 설정합니다. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | 실제 세계 미터에 대한 스케일 팩터를 설정합니다. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | 이 자산에서 사용되는 업 벡터를 설정합니다. |
| [setUrl(String value)](#setUrl-java.lang.String-) | 이 자산의 URL을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


[AssetInfo](../../com.aspose.threed/assetinfo) 클래스의 새 인스턴스를 초기화합니다.

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


[AssetInfo](../../com.aspose.threed/assetinfo) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름 |

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


이 자산의 기본 주변 색상을 가져오거나 설정합니다.

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


이 자산을 만든 애플리케이션을 가져옵니다.

**Returns:**
java.lang.String - 이 자산을 만든 애플리케이션
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


애플리케이션 공급업체의 이름을 가져옵니다.

**Returns:**
java.lang.String - 애플리케이션 공급업체 이름
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


이 자산을 만든 애플리케이션의 버전을 가져옵니다.

**Returns:**
java.lang.String - 이 자산을 만든 애플리케이션의 버전.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


이 자산의 저자를 가져옵니다.

**Returns:**
java.lang.String - 이 자산의 작성자
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


자산 정보의 좌표계/업 벡터/전방 벡터를 가져옵니다.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


이 자산의 주석을 가져옵니다.

**Returns:**
java.lang.String - 이 자산에 대한 댓글.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


이 자산에서 사용되는 좌표계를 가져옵니다.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


문서의 저작권 정보를 가져옵니다.

**Returns:**
java.lang.String - 문서의 저작권
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


이 자산의 생성 시간을 가져오거나 설정합니다

**Returns:**
java.util.Calendar - 또는 이 자산의 생성 시간을 설정합니다
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


이 자산에 사용된 앞쪽 벡터를 가져옵니다.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


이 자산의 키워드를 가져옵니다

**Returns:**
java.lang.String - 이 자산의 키워드
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


이 자산의 수정 시간을 가져오거나 설정합니다

**Returns:**
java.util.Calendar - 또는 이 자산의 수정 시간을 설정합니다
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


이 자산의 리비전 번호를 가져옵니다(보통 버전 관리 시스템에서 사용됩니다).

**Returns:**
java.lang.String - 이 자산의 리비전 번호(보통 버전 관리 시스템에서 사용됩니다).
### getSubject() {#getSubject--}
```
public String getSubject()
```


이 자산의 주제를 가져옵니다

**Returns:**
java.lang.String - 이 자산의 주제
### getTitle() {#getTitle--}
```
public String getTitle()
```


이 자산의 제목을 가져옵니다

**Returns:**
java.lang.String - 이 자산의 제목
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


이 자산에서 사용되는 길이 단위를 가져옵니다. 예: cm/m/km/inch/feet

**Returns:**
java.lang.String - 이 자산에서 사용되는 길이 단위. 예: cm/m/km/inch/feet
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


실제 미터에 대한 스케일 팩터를 가져옵니다.

**Returns:**
double - 실제 세계 미터에 대한 스케일 팩터. **Remarks:** 단위 이름이 null인 경우 직렬화 중에 무시됩니다.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


이 자산에 사용된 위쪽 벡터를 가져옵니다.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


이 자산의 URL을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 또는 이 자산의 URL을 설정합니다.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


이 자산의 기본 주변 색상을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | 새 값 |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


이 자산을 만든 애플리케이션을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


애플리케이션 공급업체 이름을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


이 자산을 만든 애플리케이션의 버전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


이 자산의 저자를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


자산 정보의 좌표계/위쪽 벡터/앞쪽 벡터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | 새 값 |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


이 자산의 주석을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


이 자산에 사용된 좌표계를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | 새 값 |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


문서의 저작권을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


이 자산의 생성 시간을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Calendar | 새 값 |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


이 자산에 사용된 앞쪽 벡터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | 새 값 |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


이 자산의 키워드를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


이 자산의 수정 시간을 가져오거나 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Calendar | 새 값 |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


이 자산의 리비전 번호를 설정합니다(보통 버전 관리 시스템에서 사용됩니다).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


이 자산의 주제를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


이 자산의 제목을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


이 자산에서 사용되는 길이 단위를 설정합니다. 예: cm/m/km/inch/feet

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


실제 세계 미터에 대한 스케일 팩터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 **Remarks:** 단위 이름이 null인 경우 직렬화 중에 무시됩니다. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


이 자산에서 사용되는 업 벡터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | 새 값 |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


이 자산의 URL을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

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

