---
title: "PhongMaterial"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/phongmaterial/
---
## PhongMaterial class

Blinn-Phongシェーディングモデル用マテリアル。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | PhongMaterial クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name) | PhongMaterial クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### getSpecularColor{#getSpecularColor}

| 名前 | 説明 |
| --- | --- |
| getSpecularColor() | 鏡面色を取得または設定します。 |

 **Result:**



---


### setSpecularColor{#setSpecularColor}

| 名前 | 説明 |
| --- | --- |
| setSpecularColor(value) | 鏡面色を取得または設定します。 |

 **Result:**



---


### getSpecularFactor{#getSpecularFactor}

| 名前 | 説明 |
| --- | --- |
| getSpecularFactor() | 鏡面係数を取得または設定します。鏡面の式: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### setSpecularFactor{#setSpecularFactor}

| 名前 | 説明 |
| --- | --- |
| setSpecularFactor(value) | 鏡面係数を取得または設定します。鏡面の式: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### getShininess{#getShininess}

| 名前 | 説明 |
| --- | --- |
| getShininess() | 光沢度を取得または設定します。これにより鏡面ハイライトのサイズが制御されます。鏡面の式: SpecularColor SpecularFactor (N dot H) ^ Shininess 光沢度。 |

 **Result:**



---


### setShininess{#setShininess}

| 名前 | 説明 |
| --- | --- |
| setShininess(value) | 光沢度を取得または設定します。これにより鏡面ハイライトのサイズが制御されます。鏡面の式: SpecularColor SpecularFactor (N dot H) ^ Shininess 光沢度。 |

 **Result:**



---


### getReflectionColor{#getReflectionColor}

| 名前 | 説明 |
| --- | --- |
| getReflectionColor() | 反射色を取得または設定します。反射。 |

 **Result:**



---


### setReflectionColor{#setReflectionColor}

| 名前 | 説明 |
| --- | --- |
| setReflectionColor(value) | 反射色を取得または設定します。反射。 |

 **Result:**



---


### getReflectionFactor{#getReflectionFactor}

| 名前 | 説明 |
| --- | --- |
| getReflectionFactor() | 反射色の減衰を取得または設定します。反射係数。 |

 **Result:**



---


### setReflectionFactor{#setReflectionFactor}

| 名前 | 説明 |
| --- | --- |
| setReflectionFactor(value) | 反射色の減衰を取得または設定します。反射係数。 |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| 名前 | 説明 |
| --- | --- |
| getEmissiveColor() | 放射色を取得または設定します |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 名前 | 説明 |
| --- | --- |
| setEmissiveColor(value) | 放射色を取得または設定します |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| 名前 | 説明 |
| --- | --- |
| getAmbientColor() | 環境光の色を取得または設定します。例: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| 名前 | 説明 |
| --- | --- |
| setAmbientColor(value) | 環境光の色を取得または設定します。例: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| 名前 | 説明 |
| --- | --- |
| getDiffuseColor() | 拡散色を取得または設定します。例: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); 拡散色。 |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| 名前 | 説明 |
| --- | --- |
| setDiffuseColor(value) | 拡散色を取得または設定します。例: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); 拡散色。 |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| 名前 | 説明 |
| --- | --- |
| getTransparentColor() | 透過色を取得または設定します。例: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); 透過色。 |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| 名前 | 説明 |
| --- | --- |
| setTransparentColor(value) | 透過色を取得または設定します。例: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); 透過色。 |

 **Result:**



---


### getTransparency{#getTransparency}

| 名前 | 説明 |
| --- | --- |
| getTransparency() | 透明度係数を取得または設定します。係数は0（0%、完全に不透明）から1（100%、完全に透明）の範囲である必要があります。無効な係数値はクランプされます。例: var mat = new LambertMaterial(); mat.Transparency = 0.3; 透明度係数。 |

 **Result:**



---


### setTransparency{#setTransparency}

| 名前 | 説明 |
| --- | --- |
| setTransparency(value) | 透明度係数を取得または設定します。係数は0（0%、完全に不透明）から1（100%、完全に透明）の範囲である必要があります。無効な係数値はクランプされます。例: var mat = new LambertMaterial(); mat.Transparency = 0.3; 透明度係数。 |

 **Result:**



---


### getName{#getName}

| 名前 | 説明 |
| --- | --- |
| getName() | 名前を取得または設定します。名前。 |

 **Result:**



---


### setName{#setName}

| 名前 | 説明 |
| --- | --- |
| setName(value) | 名前を取得または設定します。名前。 |

 **Result:**



---


### getProperties{#getProperties}

| 名前 | 説明 |
| --- | --- |
| getProperties() | すべてのプロパティのコレクションを取得します。 |

 **Result:**



---


### getTexture{#getTexture}

| 名前 | 説明 |
| --- | --- |
| getTexture(slotName) | 指定されたスロットからテクスチャを取得します。スロットはマテリアルのプロパティ名またはシェーダーのパラメータ名にすることができます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| slotName | 文字列 | スロット名。 |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| 名前 | 説明 |
| --- | --- |
| setTexture(slotName, texture) | テクスチャを指定されたスロットに設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| slotName | 文字列 | スロット名。 |
| texture | TextureBase | テクスチャ。 |

 **Result:**
TextureBase


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | オブジェクトを文字列にフォーマットします |

 **Result:**
文字列


---


### removeProperty{#removeProperty}

| 名前 | 説明 |
| --- | --- |
| removeProperty(property) | 動的プロパティを削除します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | Property | 削除するプロパティはどれですか |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 名前 | 説明 |
| --- | --- |
| removeProperty(property) | 名前で識別された指定されたプロパティを削除します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| propert | 文字列 | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 名前 | 説明 |
| --- | --- |
| getProperty(property) | 指定されたプロパティの値を取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | 文字列 | プロパティ名 |

 **Result:**
オブジェクト


---


### setProperty{#setProperty}

| 名前 | 説明 |
| --- | --- |
| setProperty(property, value) | 指定されたプロパティの値を設定します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | 文字列 | プロパティ名 |
| 値 | オブジェクト | プロパティの値 |

 **Result:**
オブジェクト


---


### findProperty{#findProperty}

| 名前 | 説明 |
| --- | --- |
| findProperty(propertyName) | プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| propertyName | 文字列 | プロパティ名。 |

 **Result:**
Property


---


### iterator{#iterator}

| 名前 | 説明 |
| --- | --- |
| iterator() | 内部使用のために予約されています。 |

 **Result:**
Property


---



