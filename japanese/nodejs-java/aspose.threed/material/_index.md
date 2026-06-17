---
title: "マテリアル"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/material/
---
## Material class

Material はジオメトリの視覚的外観に必要なパラメータを定義します。Aspose.3D は LambertMaterial、PhongMaterial、ShaderMaterial のシェーディングモデルを提供します @hideconstructor


## プロパティ

| 名前 | 説明 |
| --- | --- |
| MAP_SPECULAR | setTexture(java.lang.String, com.aspose.threed.TextureBase) で使用され、スペキュラテクスチャマッピングを割り当てます。 |
| MAP_DIFFUSE | setTexture(java.lang.String, com.aspose.threed.TextureBase) で使用され、ディフューズテクスチャマッピングを割り当てます。 |
| MAP_EMISSIVE | setTexture(java.lang.String, com.aspose.threed.TextureBase) で使用され、エミッシブテクスチャマッピングを割り当てます。 |
| MAP_AMBIENT | setTexture(java.lang.String, com.aspose.threed.TextureBase) で使用され、アンビエントテクスチャマッピングを割り当てます。 |
| MAP_NORMAL | setTexture(java.lang.String, com.aspose.threed.TextureBase) で使用され、ノーマルテクスチャマッピングを割り当てます。 |

## メソッド

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



