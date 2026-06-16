---
title: "AssetInfo"
second_title: "Aspose.3D for Java API 参考"
description: "资产信息。"
type: docs
weight: 17
url: /zh/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

资产信息。资产信息可以附加到 [Scene](../../com.aspose.threed/scene)。子 [Scene](../../com.aspose.threed/scene) 可以拥有自己的 [AssetInfo](../../com.aspose.threed/assetinfo) 来覆盖父级的定义。**示例:** 以下代码展示了如何从 fbx 文件读取资产信息：

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | 初始化 [AssetInfo](../../com.aspose.threed/assetinfo) 类的新实例。 |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | 初始化 [AssetInfo](../../com.aspose.threed/assetinfo) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getAmbient()](#getAmbient--) | 获取或设置此资产的默认环境颜色 |
| [getApplicationName()](#getApplicationName--) | 获取创建此资产的应用程序 |
| [getApplicationVendor()](#getApplicationVendor--) | 获取应用程序供应商的名称 |
| [getApplicationVersion()](#getApplicationVersion--) | 获取创建此资产的应用程序的版本。 |
| [getAuthor()](#getAuthor--) | 获取此资产的作者 |
| [getAxisSystem()](#getAxisSystem--) | 获取资产信息的坐标系/上向量/前向量。 |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | 获取此资产的注释。 |
| [getCoordinateSystem()](#getCoordinateSystem--) | 获取此资产使用的坐标系。 |
| [getCopyright()](#getCopyright--) | 获取文档的版权信息 |
| [getCreationTime()](#getCreationTime--) | 获取或设置此资产的创建时间 |
| [getFrontVector()](#getFrontVector--) | 获取此资产使用的前向向量。 |
| [getKeywords()](#getKeywords--) | 获取此资产的关键字 |
| [getModificationTime()](#getModificationTime--) | 获取或设置此资产的修改时间 |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getRevision()](#getRevision--) | 获取此资产的修订号，通常用于版本控制系统。 |
| [getSubject()](#getSubject--) | 获取此资产的主题 |
| [getTitle()](#getTitle--) | 获取此资产的标题 |
| [getUnitName()](#getUnitName--) | 获取此资产使用的长度单位。 |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | 获取到实际米的比例因子。 |
| [getUpVector()](#getUpVector--) | 获取此资产使用的上向向量。 |
| [getUrl()](#getUrl--) | 获取或设置此资产的 URL。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | 获取或设置此资产的默认环境颜色 |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | 设置创建此资产的应用程序 |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | 设置应用程序供应商的名称 |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | 设置创建此资产的应用程序版本。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 设置此资产的作者 |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | 设置资产信息的坐标系/上向向量/前向向量。 |
| [setComment(String value)](#setComment-java.lang.String-) | 设置此资产的注释。 |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | 设置此资产使用的坐标系。 |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | 设置文档的版权 |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | 获取或设置此资产的创建时间 |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | 设置此资产使用的前向向量。 |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 设置此资产的关键字 |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | 获取或设置此资产的修改时间 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setRevision(String value)](#setRevision-java.lang.String-) | 设置此资产的修订号，通常用于版本控制系统。 |
| [setSubject(String value)](#setSubject-java.lang.String-) | 设置此资产的主题 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 设置此资产的标题 |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | 设置此资产使用的长度单位。 |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | 设置比例因子为实际米。 |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | 设置此资产使用的上向量。 |
| [setUrl(String value)](#setUrl-java.lang.String-) | 获取或设置此资产的 URL。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


初始化 [AssetInfo](../../com.aspose.threed/assetinfo) 类的新实例。

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


初始化 [AssetInfo](../../com.aspose.threed/assetinfo) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


获取或设置此资产的默认环境颜色

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


获取创建此资产的应用程序

**Returns:**
java.lang.String - 创建此资产的应用程序
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


获取应用程序供应商的名称

**Returns:**
java.lang.String - 应用程序供应商的名称
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


获取创建此资产的应用程序的版本。

**Returns:**
java.lang.String - 创建此资产的应用程序的版本。
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


获取此资产的作者

**Returns:**
java.lang.String - 此资产的作者
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


获取资产信息的坐标系/上向量/前向量。

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


获取此资产的注释。

**Returns:**
java.lang.String - 此资产的注释。
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


获取此资产使用的坐标系。

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


获取文档的版权信息

**Returns:**
java.lang.String - 文档的版权
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


获取或设置此资产的创建时间

**Returns:**
java.util.Calendar - 或 设置此资产的创建时间
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


获取此资产使用的前向向量。

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


获取此资产的关键字

**Returns:**
java.lang.String - 此资产的关键字
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


获取或设置此资产的修改时间

**Returns:**
java.util.Calendar - 或 设置此资产的修改时间
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
### getRevision() {#getRevision--}
```
public String getRevision()
```


获取此资产的修订号，通常用于版本控制系统。

**Returns:**
java.lang.String - 此资产的修订号，通常在版本控制系统中使用。
### getSubject() {#getSubject--}
```
public String getSubject()
```


获取此资产的主题

**Returns:**
java.lang.String - 此资产的主题
### getTitle() {#getTitle--}
```
public String getTitle()
```


获取此资产的标题

**Returns:**
java.lang.String - 此资产的标题
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


获取此资产使用的长度单位。例如：cm/m/km/inch/feet

**Returns:**
java.lang.String - 此资产使用的长度单位。例如：cm/m/km/inch/feet
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


获取到实际米的比例因子。

**Returns:**
double - 实际米的比例因子。**Remarks:** 如果单位名称为 null，则在序列化期间忽略此项。
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


获取此资产使用的上向向量。

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


获取或设置此资产的 URL。

**Returns:**
java.lang.String - 或 设置此资产的 URL。
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


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


获取或设置此资产的默认环境颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | 新值 |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


设置创建此资产的应用程序

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


设置应用程序供应商的名称

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


设置创建此资产的应用程序版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


设置此资产的作者

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


设置资产信息的坐标系/上向向量/前向向量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | 新值 |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


设置此资产的注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


设置此资产使用的坐标系。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | 新值 |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


设置文档的版权

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


获取或设置此资产的创建时间

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Calendar | 新值 |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


设置此资产使用的前向向量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | 新值 |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


设置此资产的关键字

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


获取或设置此资产的修改时间

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Calendar | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


设置此资产的修订号，通常用于版本控制系统。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


设置此资产的主题

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


设置此资产的标题

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


设置此资产使用的长度单位。例如：cm/m/km/inch/feet

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


设置比例因子为实际米。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 **Remarks:** 如果单位名称为 null，则在序列化期间忽略此项。 |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


设置此资产使用的上向量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | 新值 |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


获取或设置此资产的 URL。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

