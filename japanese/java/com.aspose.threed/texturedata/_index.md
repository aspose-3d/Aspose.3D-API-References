---
title: TextureData
second_title: Aspose.3D for Java API リファレンス
description: このクラスはテクスチャの生データとフォーマット定義を含みます。
type: docs
weight: 187
url: /ja/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

このクラスはテクスチャの生データとフォーマット定義を含みます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | [TextureData](../../com.aspose.threed/texturedata) のコンストラクタ |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | 新しい [TextureData](../../com.aspose.threed/texturedata) を作成し、ピクセルデータを割り当てます。 |
| [TextureData()](#TextureData--) | [TextureData](../../com.aspose.threed/texturedata) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | ファイルからテクスチャを読み込みます |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | ストリームからテクスチャを読み込みます |
| [getBytesPerPixel()](#getBytesPerPixel--) | ピクセルあたりのバイト数 |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | ピクセルデータの生バイト列 |
| [getHeight()](#getHeight--) | 垂直方向のピクセル数 |
| [getName()](#getName--) | 名前を取得します。 |
| [getPixelFormat()](#getPixelFormat--) | ピクセルのフォーマット |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getStride()](#getStride--) | 走査線のバイト数。 |
| [getWidth()](#getWidth--) | 水平ピクセル数 |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | 読み書き用にすべてのピクセルをマップする |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | 指定されたピクセル形式で読み書き用にすべてのピクセルをマップする |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | 矩形で指定されたピクセルを、指定されたピクセル形式で読み書き用にマップする |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | テクスチャデータを指定された画像形式で保存する |
| [save(String fileName)](#save-java.lang.String-) | テクスチャデータを画像ファイルに保存する |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | テクスチャデータを画像ファイルに保存する |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | ピクセルのレイアウトを新しいピクセル形式に変換する。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


[TextureData](../../com.aspose.threed/texturedata) のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 幅 | int |  |
| 高さ | int |  |
| ストライド | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| データ | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


新しい [TextureData](../../com.aspose.threed/texturedata) を作成し、ピクセルデータを割り当てます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 幅 | int |  |
| 高さ | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


[TextureData](../../com.aspose.threed/texturedata) のコンストラクタ

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


ファイルからテクスチャを読み込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


ストリームからテクスチャを読み込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


ピクセルあたりのバイト数

**Returns:**
int - ピクセルあたりのバイト数
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


ピクセルデータの生バイト列

**Returns:**
byte[] - ピクセルデータの生バイト列
### getHeight() {#getHeight--}
```
public int getHeight()
```


垂直方向のピクセル数

**Returns:**
int - 垂直ピクセル数
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


ピクセルのフォーマット

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


走査線のバイト数。

**Returns:**
int - 走査線のバイト数。
### getWidth() {#getWidth--}
```
public int getWidth()
```


水平ピクセル数

**Returns:**
int - 水平ピクセル数
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


読み書き用にすべてのピクセルをマップする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | マップモード |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


指定されたピクセル形式で読み書き用にすべてのピクセルをマップする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | マップモード |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | ピクセル形式 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


矩形で指定されたピクセルを、指定されたピクセル形式で読み書き用にマップする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | アクセス対象となるピクセル領域 |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | マップモード |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | ピクセル形式 |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


テクスチャデータを指定された画像形式で保存する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 保存された画像を保持するストリーム |
| format | java.lang.String | 画像形式（通常はファイル拡張子） |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


テクスチャデータを画像ファイルに保存する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | 画像が保存されるファイル名。 |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


テクスチャデータを画像ファイルに保存する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | 画像が保存されるファイル名。 |
| format | java.lang.String | 出力ファイルの画像形式。 |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


ピクセルのレイアウトを新しいピクセル形式に変換する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | 宛先ピクセル形式 |

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

