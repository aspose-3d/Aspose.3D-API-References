---
title: PbrSpecularMaterial
second_title: Aspose.3D for Java API リファレンス
description: 拡散カラー/スペキュラ/光沢に基づく物理ベースレンダリング用マテリアル。
type: docs
weight: 122
url: /ja/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

拡散カラー/スペキュラ/光沢に基づく物理ベースレンダリング用マテリアル。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) のコンストラクタ |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | [setTexture](../../com.aspose.threed/material\#setTexture) で環境光テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | [setTexture](../../com.aspose.threed/material\#setTexture) で拡散テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | [setTexture](../../com.aspose.threed/material\#setTexture) で放射テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_NORMAL](#MAP-NORMAL) | [setTexture](../../com.aspose.threed/material\#setTexture) で法線テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_SPECULAR](#MAP-SPECULAR) | [setTexture](../../com.aspose.threed/material\#setTexture) で鏡面テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | 鏡面光沢用のテクスチャマップ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | マテリアルの拡散色を取得します。デフォルト値は (1, 1, 1) です。 |
| [getDiffuseTexture()](#getDiffuseTexture--) | 拡散用テクスチャを取得します |
| [getEmissiveColor()](#getEmissiveColor--) | 放射色を取得します。デフォルト値は (0, 0, 0) です。 |
| [getEmissiveTexture()](#getEmissiveTexture--) | 放射テクスチャを取得します |
| [getGlossinessFactor()](#getGlossinessFactor--) | マテリアルの光沢（滑らかさ）を取得します。1 は完全に滑らか、0 は完全に粗いことを意味し、デフォルト値は 1、範囲は [0, 1] です。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getNormalTexture()](#getNormalTexture--) | 法線マッピングのテクスチャを取得します |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getSpecular()](#getSpecular--) | マテリアルの鏡面色を取得します。デフォルト値は (1, 1, 1) です。 |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | 鏡面色用のテクスチャを取得します。RGB チャネルは鏡面色を、A チャネルは光沢を格納します。 |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 指定されたスロットからテクスチャを取得します。これはマテリアルのプロパティ名またはシェーダーのパラメータ名で指定できます。 |
| [getTransparency()](#getTransparency--) | 透過係数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 内部テクスチャスロットを列挙するための列挙子を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | マテリアルの拡散色を設定します。デフォルト値は (1, 1, 1) です。 |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | 拡散用テクスチャを設定します |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 放射色を設定します。デフォルト値は (0, 0, 0) です。 |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | エミッシブ用のテクスチャを設定します |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | マテリアルの光沢（滑らかさ）を設定します。1 は完全に滑らか、0 は完全に粗いことを意味し、デフォルト値は 1、範囲は [0, 1] です |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | 法線マッピングのテクスチャを設定します |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | マテリアルの鏡面色を設定します。デフォルト値は (1, 1, 1) です。 |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | 鏡面色用のテクスチャを設定します。RGB チャンネルが鏡面色を、A チャンネルが光沢を格納します。 |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | テクスチャを指定されたスロットに設定します。 |
| [setTransparency(double value)](#setTransparency-double-) | 透過係数を設定します。 |
| [toString()](#toString--) | オブジェクトを文字列にフォーマットします |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


[PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) のコンストラクタ

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


[setTexture](../../com.aspose.threed/material\#setTexture) で環境光テクスチャマッピングを割り当てるために使用されます。

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


[setTexture](../../com.aspose.threed/material\#setTexture) で拡散テクスチャマッピングを割り当てるために使用されます。

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


[setTexture](../../com.aspose.threed/material\#setTexture) で放射テクスチャマッピングを割り当てるために使用されます。

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


[setTexture](../../com.aspose.threed/material\#setTexture) で法線テクスチャマッピングを割り当てるために使用されます。

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


[setTexture](../../com.aspose.threed/material\#setTexture) で鏡面テクスチャマッピングを割り当てるために使用されます。

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


鏡面光沢用のテクスチャマップ

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


マテリアルの拡散色を取得します。デフォルト値は (1, 1, 1) です。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


拡散用テクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


放射色を取得します。デフォルト値は (0, 0, 0) です。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


放射テクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


マテリアルの光沢（滑らかさ）を取得します。1 は完全に滑らか、0 は完全に粗いことを意味し、デフォルト値は 1、範囲は [0, 1] です。

**Returns:**
double - マテリアルの光沢（滑らかさ）。1 は完全に滑らか、0 は完全に粗いことを意味し、デフォルト値は 1、範囲は [0, 1] です
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


法線マッピングのテクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


マテリアルの鏡面色を取得します。デフォルト値は (1, 1, 1) です。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


鏡面色用のテクスチャを取得します。RGB チャネルは鏡面色を、A チャネルは光沢を格納します。

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


指定されたスロットからテクスチャを取得します。これはマテリアルのプロパティ名またはシェーダーのパラメータ名で指定できます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| slotName | java.lang.String | スロット名。 |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


透明度係数を取得します。係数は 0（0%、完全に不透明）から 1（100%、完全に透明）の範囲である必要があります。無効な係数値はクランプされます。

**Returns:**
double - 透明度係数。係数は 0（0%、完全に不透明）から 1（100%、完全に透明）の範囲である必要があります。無効な係数値はクランプされます。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


内部テクスチャスロットを列挙するための列挙子を取得します。

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


マテリアルの拡散色を設定します。デフォルト値は (1, 1, 1) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


拡散用テクスチャを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新しい値 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


放射色を設定します。デフォルト値は (0, 0, 0) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


エミッシブ用のテクスチャを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新しい値 |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


マテリアルの光沢（滑らかさ）を設定します。1 は完全に滑らか、0 は完全に粗いことを意味し、デフォルト値は 1、範囲は [0, 1] です

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


法線マッピングのテクスチャを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新しい値 |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


マテリアルの鏡面色を設定します。デフォルト値は (1, 1, 1) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


鏡面色用のテクスチャを設定します。RGB チャンネルが鏡面色を、A チャンネルが光沢を格納します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新しい値 |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


テクスチャを指定されたスロットに設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| slotName | java.lang.String | スロット名。 |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | テクスチャ。 **Example:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


透明度係数を設定します。係数は 0（0%、完全に不透明）から 1（100%、完全に透明）の範囲である必要があります。無効な係数値はクランプされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### toString() {#toString--}
```
public String toString()
```


オブジェクトを文字列にフォーマットします

**Returns:**
java.lang.String - オブジェクト文字列
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

