---
title: "PbrSpecularMaterial"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

拡散カラー/スペキュラ/光沢に基づく物理ベースレンダリング用マテリアル


## プロパティ

| 名前 | 説明 |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | 鏡面光沢のテクスチャマップ |

## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | PbrSpecularMaterial のコンストラクタ |

 **Result:**



---


### getTransparency{#getTransparency}

| 名前 | 説明 |
| --- | --- |
| getTransparency() | 透明度係数を取得または設定します。係数は 0（0%、完全に不透明）から 1（100%、完全に透明）までの範囲である必要があります。無効な係数値はクランプされます。透明度係数。 |

 **Result:**



---


### setTransparency{#setTransparency}

| 名前 | 説明 |
| --- | --- |
| setTransparency(value) | 透明度係数を取得または設定します。係数は 0（0%、完全に不透明）から 1（100%、完全に透明）までの範囲である必要があります。無効な係数値はクランプされます。透明度係数。 |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| 名前 | 説明 |
| --- | --- |
| getNormalTexture() | 法線マッピングのテクスチャを取得または設定します |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| 名前 | 説明 |
| --- | --- |
| setNormalTexture(value) | 法線マッピングのテクスチャを取得または設定します |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| 名前 | 説明 |
| --- | --- |
| getSpecularGlossinessTexture() | 鏡面色用のテクスチャを取得または設定します。RGB チャンネルは鏡面色を、A チャンネルは光沢度を格納します。 |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| 名前 | 説明 |
| --- | --- |
| setSpecularGlossinessTexture(value) | 鏡面色用のテクスチャを取得または設定します。RGB チャンネルは鏡面色を、A チャンネルは光沢度を格納します。 |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| 名前 | 説明 |
| --- | --- |
| getGlossinessFactor() | 材質の光沢度（滑らかさ）を取得または設定します。1 は完全に滑らか、0 は完全に粗いことを意味します。デフォルト値は 1 で、範囲は [0, 1] です。 |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| 名前 | 説明 |
| --- | --- |
| setGlossinessFactor(value) | 材質の光沢度（滑らかさ）を取得または設定します。1 は完全に滑らか、0 は完全に粗いことを意味します。デフォルト値は 1 で、範囲は [0, 1] です。 |

 **Result:**



---


### getSpecular{#getSpecular}

| 名前 | 説明 |
| --- | --- |
| getSpecular() | 材質の鏡面色を取得または設定します。デフォルト値は (1, 1, 1) です。 |

 **Result:**



---


### setSpecular{#setSpecular}

| 名前 | 説明 |
| --- | --- |
| setSpecular(value) | 材質の鏡面色を取得または設定します。デフォルト値は (1, 1, 1) です。 |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| 名前 | 説明 |
| --- | --- |
| getDiffuseTexture() | 拡散用のテクスチャを取得または設定します |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| 名前 | 説明 |
| --- | --- |
| setDiffuseTexture(value) | 拡散用のテクスチャを取得または設定します |

 **Result:**



---


### getDiffuse{#getDiffuse}

| 名前 | 説明 |
| --- | --- |
| getDiffuse() | 材質の拡散色を取得または設定します。デフォルト値は (1, 1, 1) です |

 **Result:**



---


### setDiffuse{#setDiffuse}

| 名前 | 説明 |
| --- | --- |
| setDiffuse(value) | 材質の拡散色を取得または設定します。デフォルト値は (1, 1, 1) です |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| 名前 | 説明 |
| --- | --- |
| getEmissiveTexture() | 放射用のテクスチャを取得または設定します |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| 名前 | 説明 |
| --- | --- |
| setEmissiveTexture(value) | 放射用のテクスチャを取得または設定します |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| 名前 | 説明 |
| --- | --- |
| getEmissiveColor() | 放射色を取得または設定します。デフォルト値は (0, 0, 0) です |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 名前 | 説明 |
| --- | --- |
| setEmissiveColor(value) | 放射色を取得または設定します。デフォルト値は (0, 0, 0) です |

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



