---
title: AssetInfo
second_title: Aspose.3D for Java API リファレンス
description: アセットの情報。
type: docs
weight: 17
url: /ja/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Information of asset. Asset information can be attached to a [Scene](../../com.aspose.threed/scene). Child [Scene](../../com.aspose.threed/scene) can have its own [AssetInfo](../../com.aspose.threed/assetinfo) to override parent's definition. **Example:** The following code shows how to read asset info from a fbx file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Initializes a new instance of the [AssetInfo](../../com.aspose.threed/assetinfo) class. |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Initializes a new instance of the [AssetInfo](../../com.aspose.threed/assetinfo) class. |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getAmbient()](#getAmbient--) | Gets or Sets the default ambient color of this asset |
| [getApplicationName()](#getApplicationName--) | Gets the application that created this asset |
| [getApplicationVendor()](#getApplicationVendor--) | Gets the application vendor's name |
| [getApplicationVersion()](#getApplicationVersion--) | Gets the version of the application that created this asset. |
| [getAuthor()](#getAuthor--) | Gets the author of this asset |
| [getAxisSystem()](#getAxisSystem--) | Gets the coordinate system/up vector/front vector of the asset info. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Gets the comment of this asset. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Gets the coordinate system used in this asset. |
| [getCopyright()](#getCopyright--) | Gets the document's copyright |
| [getCreationTime()](#getCreationTime--) | このアセットの作成時刻を取得または設定します |
| [getFrontVector()](#getFrontVector--) | このアセットで使用される前方ベクトルを取得します。 |
| [getKeywords()](#getKeywords--) | このアセットのキーワードを取得します |
| [getModificationTime()](#getModificationTime--) | このアセットの変更時刻を取得または設定します |
| [getName()](#getName--) | 名前を取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getRevision()](#getRevision--) | このアセットのリビジョン番号を取得します（通常はバージョン管理システムで使用されます）。 |
| [getSubject()](#getSubject--) | このアセットの件名を取得します |
| [getTitle()](#getTitle--) | このアセットのタイトルを取得します |
| [getUnitName()](#getUnitName--) | このアセットで使用される長さの単位を取得します。 |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | 実際のメートルへのスケール係数を取得します。 |
| [getUpVector()](#getUpVector--) | このアセットで使用される上方向ベクトルを取得します。 |
| [getUrl()](#getUrl--) | このアセットのURLを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Gets or Sets the default ambient color of this asset |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | このアセットを作成したアプリケーションを設定します |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | アプリケーションベンダーの名前を設定します |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | このアセットを作成したアプリケーションのバージョンを設定します。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | このアセットの作成者を設定します |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | アセット情報の座標系/上ベクトル/前ベクトルを設定します。 |
| [setComment(String value)](#setComment-java.lang.String-) | このアセットのコメントを設定します。 |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | このアセットで使用される座標系を設定します。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | ドキュメントの著作権を設定します |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | このアセットの作成時刻を取得または設定します |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | このアセットで使用される前方ベクトルを設定します。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | このアセットのキーワードを設定します |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | このアセットの変更時刻を取得または設定します |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setRevision(String value)](#setRevision-java.lang.String-) | このアセットのリビジョン番号を設定します（通常はバージョン管理システムで使用されます）。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | このアセットの件名を設定します |
| [setTitle(String value)](#setTitle-java.lang.String-) | このアセットのタイトルを設定します |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | このアセットで使用される長さの単位を設定します。 |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | 実世界のメートルへのスケール係数を設定します。 |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | このアセットで使用されるアップベクトルを設定します。 |
| [setUrl(String value)](#setUrl-java.lang.String-) | このアセットのURLを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Initializes a new instance of the [AssetInfo](../../com.aspose.threed/assetinfo) class.

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Initializes a new instance of the [AssetInfo](../../com.aspose.threed/assetinfo) class.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty により作成）またはネイティブプロパティ（名前で識別）になる可能性があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| propertyName | java.lang.String | プロパティ名。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Gets or Sets the default ambient color of this asset

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Gets the application that created this asset

**Returns:**
java.lang.String - このアセットを作成したアプリケーション
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Gets the application vendor's name

**Returns:**
java.lang.String - アプリケーションベンダーの名前
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Gets the version of the application that created this asset.

**Returns:**
java.lang.String - このアセットを作成したアプリケーションのバージョン。
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets the author of this asset

**Returns:**
java.lang.String - このアセットの作者
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Gets the coordinate system/up vector/front vector of the asset info.

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


Gets the comment of this asset.

**Returns:**
java.lang.String - このアセットのコメント。
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Gets the coordinate system used in this asset.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Gets the document's copyright

**Returns:**
java.lang.String - ドキュメントの著作権
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


このアセットの作成時刻を取得または設定します

**Returns:**
java.util.Calendar - またはこのアセットの作成時間を設定します
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


このアセットで使用される前方ベクトルを取得します。

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


このアセットのキーワードを取得します

**Returns:**
java.lang.String - このアセットのキーワード
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


このアセットの変更時刻を取得または設定します

**Returns:**
java.util.Calendar - またはこのアセットの変更時間を設定します
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


すべてのプロパティのコレクションを取得します。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


指定されたプロパティの値を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |

**Returns:**
java.lang.Object - 見つかったプロパティの値
### getRevision() {#getRevision--}
```
public String getRevision()
```


このアセットのリビジョン番号を取得します（通常はバージョン管理システムで使用されます）。

**Returns:**
java.lang.String - このアセットのリビジョン番号（通常はバージョン管理システムで使用されます）。
### getSubject() {#getSubject--}
```
public String getSubject()
```


このアセットの件名を取得します

**Returns:**
java.lang.String - このアセットの件名
### getTitle() {#getTitle--}
```
public String getTitle()
```


このアセットのタイトルを取得します

**Returns:**
java.lang.String - このアセットのタイトル
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


このアセットで使用される長さの単位を取得します。例: cm/m/km/inch/feet

**Returns:**
java.lang.String - このアセットで使用される長さの単位。例: cm/m/km/inch/feet
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


実際のメートルへのスケール係数を取得します。

**Returns:**
double - 実世界のメートルへのスケール係数。**Remarks:** ユニット名が null の場合、シリアライズ時に無視されます。
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


このアセットで使用される上方向ベクトルを取得します。

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


このアセットのURLを取得または設定します。

**Returns:**
java.lang.String - またはこのアセットの URL を設定します。
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


動的プロパティを削除します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


名前で識別される指定されたプロパティを削除します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Gets or Sets the default ambient color of this asset

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | 新しい値 |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


このアセットを作成したアプリケーションを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


アプリケーションベンダーの名前を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


このアセットを作成したアプリケーションのバージョンを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


このアセットの作成者を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


アセット情報の座標系/上ベクトル/前ベクトルを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | 新しい値 |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


このアセットのコメントを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


このアセットで使用される座標系を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | 新しい値 |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


ドキュメントの著作権を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


このアセットの作成時刻を取得または設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.util.Calendar | 新しい値 |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


このアセットで使用される前方ベクトルを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | 新しい値 |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


このアセットのキーワードを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


このアセットの変更時刻を取得または設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.util.Calendar | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


指定されたプロパティの値を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |
| 値 | java.lang.Object | プロパティの値 |

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


このアセットのリビジョン番号を設定します（通常はバージョン管理システムで使用されます）。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


このアセットの件名を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


このアセットのタイトルを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


このアセットで使用される長さの単位を設定します。例: cm/m/km/inch/feet

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


実世界のメートルへのスケール係数を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 **Remarks:** ユニット名が null の場合、シリアライズ時に無視されます。 |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


このアセットで使用されるアップベクトルを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | 新しい値 |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


このアセットのURLを取得または設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

