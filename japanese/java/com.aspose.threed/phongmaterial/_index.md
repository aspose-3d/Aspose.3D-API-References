---
title: PhongMaterial
second_title: Aspose.3D for Java API リファレンス
description: Blinn-Phong シェーディングモデル用マテリアル。
type: docs
weight: 126
url: /ja/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

Blinn-Phong シェーディングモデル用マテリアル。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | 新しい [PhongMaterial](../../com.aspose.threed/phongmaterial) クラスのインスタンスを初期化します。 |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | 新しい [PhongMaterial](../../com.aspose.threed/phongmaterial) クラスのインスタンスを初期化します。 |
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
| [getAmbientColor()](#getAmbientColor--) | 環境光の色を取得します。 |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | 拡散色を取得します。 |
| [getEmissiveColor()](#getEmissiveColor--) | 放射色を取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getReflectionColor()](#getReflectionColor--) | 反射色を取得します。 |
| [getReflectionFactor()](#getReflectionFactor--) | 反射色の減衰を取得します。 |
| [getShininess()](#getShininess--) | 光沢度を取得します。これによりスペキュラハイライトのサイズが制御されます。 |
| [getSpecularColor()](#getSpecularColor--) | スペキュラカラーを取得します。 |
| [getSpecularFactor()](#getSpecularFactor--) | スペキュラ係数を取得します。 |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 指定されたスロットからテクスチャを取得します。これはマテリアルのプロパティ名またはシェーダーのパラメータ名で指定できます。 |
| [getTransparency()](#getTransparency--) | 透過係数を取得します。 |
| [getTransparentColor()](#getTransparentColor--) | 透過色を取得します。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 内部テクスチャスロットを列挙するための列挙子を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | 環境光の色を設定します。 |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | 拡散色を設定します。 |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 放射色を設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | 反射色を設定します。 |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | 反射色の減衰を設定します。 |
| [setShininess(double value)](#setShininess-double-) | 光沢度を設定します。これにより鏡面ハイライトのサイズが制御されます。 |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | 鏡面色を設定します。 |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | 鏡面係数を設定します。 |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | テクスチャを指定されたスロットに設定します。 |
| [setTransparency(double value)](#setTransparency-double-) | 透過係数を設定します。 |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | 透過色を設定します。 |
| [toString()](#toString--) | オブジェクトを文字列にフォーマットします |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


新しい [PhongMaterial](../../com.aspose.threed/phongmaterial) クラスのインスタンスを初期化します。

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


新しい [PhongMaterial](../../com.aspose.threed/phongmaterial) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前 |

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


環境光の色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


拡散色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


放射色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


反射色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


反射色の減衰を取得します。

**Returns:**
double - 反射色の減衰。
### getShininess() {#getShininess--}
```
public double getShininess()
```


光沢度を取得します。これにより鏡面ハイライトのサイズが制御されます。鏡面の式: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - 光沢度、これにより鏡面ハイライトのサイズが制御されます。鏡面の式: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


スペキュラカラーを取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


鏡面係数を取得します。鏡面の式: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - 鏡面係数。鏡面の式: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
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
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


透過色を取得します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


環境光の色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


拡散色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


放射色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


反射色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


反射色の減衰を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


光沢度を設定します。これにより鏡面ハイライトのサイズが制御されます。鏡面の式: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


鏡面色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


鏡面係数を設定します。鏡面の式: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


透過色を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

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

