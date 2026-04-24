---
title: PbrMaterial
second_title: Aspose.3D for Java API リファレンス
description: アルベドカラー/メタリック/ラフネスに基づく物理ベースレンダリング用マテリアル。
type: docs
weight: 121
url: /ja/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

アルベドカラー/メタリック/ラフネスに基づく物理ベースレンダリング用マテリアル。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | デフォルトの PBR マテリアル インスタンスを構築します |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | 指定されたアルベドカラー値でデフォルトの PBR マテリアルを構築します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | [setTexture](../../com.aspose.threed/material\#setTexture) で環境光テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | [setTexture](../../com.aspose.threed/material\#setTexture) で拡散テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | [setTexture](../../com.aspose.threed/material\#setTexture) で放射テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_NORMAL](#MAP-NORMAL) | [setTexture](../../com.aspose.threed/material\#setTexture) で法線テクスチャマッピングを割り当てるために使用されます。 |
| [MAP_SPECULAR](#MAP-SPECULAR) | [setTexture](../../com.aspose.threed/material\#setTexture) で鏡面テクスチャマッピングを割り当てるために使用されます。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | 他のマテリアルを PbrMaterial に変換できる **Example:** |
| [getAlbedo()](#getAlbedo--) | マテリアルのベースカラーを取得します |
| [getAlbedoTexture()](#getAlbedoTexture--) | アルベド用テクスチャを取得します |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | 放射色を取得します。 |
| [getEmissiveTexture()](#getEmissiveTexture--) | 放射テクスチャを取得します |
| [getMetallicFactor()](#getMetallicFactor--) | マテリアルの金属性を取得します。値が 1 の場合は金属で、0 の場合は誘電体です。 |
| [getMetallicRoughness()](#getMetallicRoughness--) | 金属性（R チャンネル）と粗さ（G チャンネル）のテクスチャを取得します |
| [getName()](#getName--) | 名前を取得します。 |
| [getNormalTexture()](#getNormalTexture--) | 法線マッピングのテクスチャを取得します |
| [getOcclusionFactor()](#getOcclusionFactor--) | アンビエントオクルージョンの係数を取得します |
| [getOcclusionTexture()](#getOcclusionTexture--) | アンビエントオクルージョン用テクスチャを取得します |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getRoughnessFactor()](#getRoughnessFactor--) | マテリアルの粗さを取得します。値が 1 の場合は完全に粗く、0 の場合は完全に滑らかです。 |
| [getSpecularTexture()](#getSpecularTexture--) | 鏡面反射色用テクスチャを取得します |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 指定されたスロットからテクスチャを取得します。これはマテリアルのプロパティ名またはシェーダーのパラメータ名で指定できます。 |
| [getTransparency()](#getTransparency--) | 透過係数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 内部テクスチャスロットを列挙するための列挙子を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | マテリアルのベースカラーを設定します |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | アルベドのテクスチャを設定します |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 放射色を設定します。 |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | エミッシブ用のテクスチャを設定します |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | マテリアルの金属度を設定します。値が 1 の場合は金属で、値が 0 の場合は誘電体です。 |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | 金属度（R チャネル）と粗さ（G チャネル）のテクスチャを設定します |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | 法線マッピングのテクスチャを設定します |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | アンビエントオクルージョンの係数を設定します |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | アンビエントオクルージョンのテクスチャを設定します |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | マテリアルの粗さを設定します。値が 1 の場合は完全に粗く、値が 0 の場合は完全に滑らかです。 |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | スペキュラカラーのテクスチャを設定します |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | テクスチャを指定されたスロットに設定します。 |
| [setTransparency(double value)](#setTransparency-double-) | 透過係数を設定します。 |
| [toString()](#toString--) | オブジェクトを文字列にフォーマットします |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


デフォルトの PBR マテリアル インスタンスを構築します

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


指定されたアルベドカラー値でデフォルトの PBR マテリアルを構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | デフォルトのアルベドカラー値 |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


他のマテリアルを PbrMaterial に変換できる **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


マテリアルのベースカラーを取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


アルベド用テクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


放射色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


放射テクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


マテリアルの金属性を取得します。値が 1 の場合は金属で、0 の場合は誘電体です。

**Returns:**
double - マテリアルの金属度。値が 1 の場合は金属で、値が 0 の場合は誘電体です。
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


金属性（R チャンネル）と粗さ（G チャンネル）のテクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


アンビエントオクルージョンの係数を取得します

**Returns:**
double - アンビエントオクルージョンの係数
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


アンビエントオクルージョン用テクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


マテリアルの粗さを取得します。値が 1 の場合は完全に粗く、0 の場合は完全に滑らかです。

**Returns:**
double - マテリアルの粗さ。値が 1 の場合は完全に粗く、値が 0 の場合は完全に滑らかです。
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


鏡面反射色用テクスチャを取得します

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


マテリアルのベースカラーを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


アルベドのテクスチャを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新しい値 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


放射色を設定します。

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


マテリアルの金属度を設定します。値が 1 の場合は金属で、値が 0 の場合は誘電体です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


金属度（R チャネル）と粗さ（G チャネル）のテクスチャを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新しい値 |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


アンビエントオクルージョンの係数を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


アンビエントオクルージョンのテクスチャを設定します

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


マテリアルの粗さを設定します。値が 1 の場合は完全に粗く、値が 0 の場合は完全に滑らかです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


スペキュラカラーのテクスチャを設定します

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

