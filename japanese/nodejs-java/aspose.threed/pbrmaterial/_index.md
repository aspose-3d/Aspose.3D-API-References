---
title: "PbrMaterial"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/pbrmaterial/
---
## PbrMaterial class

アルベドカラー/メタリック/ラフネスに基づく物理ベースレンダリング用マテリアル


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | デフォルトの PBR マテリアル インスタンスを作成します |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(albedo) | 指定されたアルベドカラー値でデフォルトの PBR マテリアルを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| albedo | Vector3 | デフォルトのアルベドカラー値 |

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


### getSpecularTexture{#getSpecularTexture}

| 名前 | 説明 |
| --- | --- |
| getSpecularTexture() | 鏡面反射色のテクスチャを取得または設定します |

 **Result:**



---


### setSpecularTexture{#setSpecularTexture}

| 名前 | 説明 |
| --- | --- |
| setSpecularTexture(value) | 鏡面反射色のテクスチャを取得または設定します |

 **Result:**



---


### getAlbedoTexture{#getAlbedoTexture}

| 名前 | 説明 |
| --- | --- |
| getAlbedoTexture() | アルベドのテクスチャを取得または設定します |

 **Result:**



---


### setAlbedoTexture{#setAlbedoTexture}

| 名前 | 説明 |
| --- | --- |
| setAlbedoTexture(value) | アルベドのテクスチャを取得または設定します |

 **Result:**



---


### getAlbedo{#getAlbedo}

| 名前 | 説明 |
| --- | --- |
| getAlbedo() | マテリアルの基本色を取得または設定します |

 **Result:**



---


### setAlbedo{#setAlbedo}

| 名前 | 説明 |
| --- | --- |
| setAlbedo(value) | マテリアルの基本色を取得または設定します |

 **Result:**



---


### getOcclusionTexture{#getOcclusionTexture}

| 名前 | 説明 |
| --- | --- |
| getOcclusionTexture() | アンビエントオクルージョンのテクスチャを取得または設定します |

 **Result:**



---


### setOcclusionTexture{#setOcclusionTexture}

| 名前 | 説明 |
| --- | --- |
| setOcclusionTexture(value) | アンビエントオクルージョンのテクスチャを取得または設定します |

 **Result:**



---


### getOcclusionFactor{#getOcclusionFactor}

| 名前 | 説明 |
| --- | --- |
| getOcclusionFactor() | 環境遮蔽の係数を取得または設定します |

 **Result:**



---


### setOcclusionFactor{#setOcclusionFactor}

| 名前 | 説明 |
| --- | --- |
| setOcclusionFactor(value) | 環境遮蔽の係数を取得または設定します |

 **Result:**



---


### getMetallicFactor{#getMetallicFactor}

| 名前 | 説明 |
| --- | --- |
| getMetallicFactor() | マテリアルの金属性を取得または設定します。値が 1 の場合はマテリアルが金属であり、値が 0 の場合は誘電体です。 |

 **Result:**



---


### setMetallicFactor{#setMetallicFactor}

| 名前 | 説明 |
| --- | --- |
| setMetallicFactor(value) | マテリアルの金属性を取得または設定します。値が 1 の場合はマテリアルが金属であり、値が 0 の場合は誘電体です。 |

 **Result:**



---


### getRoughnessFactor{#getRoughnessFactor}

| 名前 | 説明 |
| --- | --- |
| getRoughnessFactor() | マテリアルの粗さを取得または設定します。値が 1 の場合は完全に粗く、値が 0 の場合は完全に滑らかです。 |

 **Result:**



---


### setRoughnessFactor{#setRoughnessFactor}

| 名前 | 説明 |
| --- | --- |
| setRoughnessFactor(value) | マテリアルの粗さを取得または設定します。値が 1 の場合は完全に粗く、値が 0 の場合は完全に滑らかです。 |

 **Result:**



---


### getMetallicRoughness{#getMetallicRoughness}

| 名前 | 説明 |
| --- | --- |
| getMetallicRoughness() | 金属性（R チャンネル）と粗さ（G チャンネル）のテクスチャを取得または設定します |

 **Result:**



---


### setMetallicRoughness{#setMetallicRoughness}

| 名前 | 説明 |
| --- | --- |
| setMetallicRoughness(value) | 金属性（R チャンネル）と粗さ（G チャンネル）のテクスチャを取得または設定します |

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
| getEmissiveColor() | 放射色を取得または設定します |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 名前 | 説明 |
| --- | --- |
| setEmissiveColor(value) | 放射色を取得または設定します |

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


### fromMaterial{#fromMaterial}

| 名前 | 説明 |
| --- | --- |
| fromMaterial(material) | 他のマテリアルを PbrMaterial に変換できるようにします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| マテリア | マテリアル | null |

 **Result:**
PbrMaterial


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



