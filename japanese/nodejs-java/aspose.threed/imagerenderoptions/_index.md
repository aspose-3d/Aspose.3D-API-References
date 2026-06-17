---
title: "ImageRenderOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/imagerenderoptions/
---
## ImageRenderOptions class

Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) および Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions) のオプション


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | ImageRenderOptions のインスタンスを初期化します |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| 名前 | 説明 |
| --- | --- |
| getBackgroundColor() | レンダリング結果の背景色です。 |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| 名前 | 説明 |
| --- | --- |
| setBackgroundColor(value) | レンダリング結果の背景色です。 |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| 名前 | 説明 |
| --- | --- |
| getAssetDirectories() | 外部アセット（テクスチャなど）を格納するディレクトリ |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| 名前 | 説明 |
| --- | --- |
| getEnableShadows() | シャドウをレンダリングするかどうかを取得または設定します。 |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| 名前 | 説明 |
| --- | --- |
| setEnableShadows(value) | シャドウをレンダリングするかどうかを取得または設定します。 |

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



