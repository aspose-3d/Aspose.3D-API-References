---
title: テクスチャ
second_title: Aspose.3D for Java API リファレンス
description: このクラスは外部ファイルからテクスチャを定義します。
type: docs
weight: 184
url: /ja/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)、[com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

このクラスは外部ファイルからテクスチャを定義します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Texture()](#Texture--) | [Texture](../../com.aspose.threed/texture) クラスの新しいインスタンスを初期化します。 |
| [Texture(String name)](#Texture-java.lang.String-) | [Texture](../../com.aspose.threed/texture) クラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getAlpha()](#getAlpha--) | テクスチャのデフォルトアルファ値を取得します。この値は、[getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) が [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) の場合に有効です。デフォルト値は 1.0 で、有効な範囲は 0 から 1 です。 |
| [getAlphaSource()](#getAlphaSource--) | テクスチャがアルファチャンネルを定義しているかどうかを取得します。 |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | テクスチャのバイナリ内容を取得します。 |
| [getEnableMipMap()](#getEnableMipMap--) | このテクスチャのミップマップが有効かどうかを取得します |
| [getFileName()](#getFileName--) | 関連付けられたテクスチャファイルを取得します。 |
| [getMagFilter()](#getMagFilter--) | 拡大時のフィルタを取得します。 |
| [getMinFilter()](#getMinFilter--) | 縮小時のフィルタを取得します。 |
| [getMipFilter()](#getMipFilter--) | ミップレベルサンプリングのフィルタを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getUVRotation()](#getUVRotation--) | テクスチャの回転を取得します |
| [getUVScale()](#getUVScale--) | UV スケールを取得します。 |
| [getUVTranslation()](#getUVTranslation--) | UV 平行移動を取得します。 |
| [getWrapModeU()](#getWrapModeU--) | U 方向のテクスチャラップモードを取得します。 |
| [getWrapModeV()](#getWrapModeV--) | V 方向のテクスチャラップモードを取得します。 |
| [getWrapModeW()](#getWrapModeW--) | W 方向のテクスチャラップモードを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setAlpha(double value)](#setAlpha-double-) | テクスチャのデフォルトアルファ値を設定します。この値は、[getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) が [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) の場合に有効です。デフォルト値は 1.0 で、有効な範囲は 0 から 1 です。 |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | テクスチャがアルファチャンネルを定義しているかどうかを設定します。 |
| [setContent(byte[] value)](#setContent-byte---) | テクスチャのバイナリ コンテンツを設定します。 |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | このテクスチャでミップマップが有効かどうかを設定します。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | 関連付けられたテクスチャ ファイルを設定します。 |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | 拡大時のフィルタを設定します。 |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | 縮小時のフィルタを設定します。 |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | ミップレベル サンプリングのフィルタを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setRotation(double u, double v)](#setRotation-double-double-) | UV の回転を設定します。 |
| [setScale(double u, double v)](#setScale-double-double-) | UV のスケールを設定します。 |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | UV の平行移動を設定します。 |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | テクスチャの回転を設定します。 |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | UV のスケールを設定します。 |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | UV の平行移動を設定します。 |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | U 方向のテクスチャ ラップ モードを設定します。 |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | V 方向のテクスチャ ラップ モードを設定します。 |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | W 方向のテクスチャ ラップ モードを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


[Texture](../../com.aspose.threed/texture) クラスの新しいインスタンスを初期化します。

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


[Texture](../../com.aspose.threed/texture) クラスの新しいインスタンスを初期化します。

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


テクスチャのデフォルトアルファ値を取得します。この値は、[getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) が [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) の場合に有効です。デフォルト値は 1.0 で、有効な範囲は 0 から 1 です。

**Returns:**
double - テクスチャのデフォルトアルファ値です。この値は [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) が [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) の場合に有効です。デフォルト値は 1.0 で、有効な範囲は 0 から 1 です。
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


テクスチャがアルファ チャネルを定義しているかどうかを取得します。デフォルト値は [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE) です。

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContent() {#getContent--}
```
public byte[] getContent()
```


テクスチャのバイナリ コンテンツを取得します。埋め込みテクスチャ コンテンツはオプションで、存在しない場合はユーザーが外部ファイルからテクスチャをロードすべきです。

**Returns:**
byte[] - テクスチャのバイナリ コンテンツです。埋め込みテクスチャ コンテンツはオプションで、存在しない場合はユーザーが外部ファイルからテクスチャをロードすべきです。
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


このテクスチャのミップマップが有効かどうかを取得します

**Returns:**
boolean - このテクスチャでミップマップが有効かどうか
### getFileName() {#getFileName--}
```
public String getFileName()
```


関連付けられたテクスチャファイルを取得します。

**Returns:**
java.lang.String - 関連付けられたテクスチャ ファイルです。
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


拡大時のフィルタを取得します。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


縮小時のフィルタを取得します。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


ミップレベルサンプリングのフィルタを取得します。

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


テクスチャの回転を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


UV スケールを取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


UV 平行移動を取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


U 方向のテクスチャラップモードを取得します。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


V 方向のテクスチャラップモードを取得します。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


W 方向のテクスチャラップモードを取得します。

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


テクスチャのデフォルトアルファ値を設定します。この値は、[getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) が [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) の場合に有効です。デフォルト値は 1.0 で、有効な範囲は 0 から 1 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


テクスチャがアルファ チャネルを定義するかどうかを設定します。デフォルト値は [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | 新しい値 |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


テクスチャのバイナリ コンテンツを設定します。埋め込みテクスチャ コンテンツはオプションで、存在しない場合はユーザーが外部ファイルからテクスチャをロードすべきです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | byte[] | 新しい値 |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


このテクスチャでミップマップが有効かどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


関連付けられたテクスチャ ファイルを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


拡大時のフィルタを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新しい値 |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


縮小時のフィルタを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新しい値 |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


ミップレベル サンプリングのフィルタを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | 新しい値 |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


UV の回転を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| u | double | U。 |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


UV のスケールを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| u | double | U。 |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


UV の平行移動を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| u | double | U。 |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


テクスチャの回転を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


UV のスケールを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


UV の平行移動を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


U 方向のテクスチャ ラップ モードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新しい値 |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


V 方向のテクスチャ ラップ モードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新しい値 |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


W 方向のテクスチャ ラップ モードを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | 新しい値 |

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

