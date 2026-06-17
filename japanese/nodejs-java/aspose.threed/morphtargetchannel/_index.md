---
title: "MorphTargetChannel"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetChannel は MorphTargetDeformer によってターゲットジオメトリを整理するために使用されます。FBX のような一部のファイル形式は複数のチャネルを同時にサポートします。ウェイトは 0 から 1.0 の範囲で、ターゲットのデフォルトウェイトは 0.0 です；


## プロパティ

| 名前 | 説明 |
| --- | --- |
| DEFAULT_WEIGHT | モーフターゲットのデフォルトウェイトです。 |

## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(name) | MorphTargetChannel クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload() | MorphTargetChannel クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### getWeights{#getWeights}

| 名前 | 説明 |
| --- | --- |
| getWeights() | ターゲットジオメトリの完全なウェイト値を取得します。完全なウェイトです。 |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| 名前 | 説明 |
| --- | --- |
| getChannelWeight() | このチャネルのデフォーマーウェイトを取得または設定します。ウェイトは 0.0 から 1.0 の間です。 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| 名前 | 説明 |
| --- | --- |
| setChannelWeight(value) | このチャネルのデフォーマーウェイトを取得または設定します。ウェイトは 0.0 から 1.0 の間です。 |

 **Result:**



---


### getTargets{#getTargets}

| 名前 | 説明 |
| --- | --- |
| getTargets() | チャネルに関連付けられたすべてのターゲットを取得します。 |

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


### get{#get}

| 名前 | 説明 |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| 名前 | 説明 |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| 名前 | 説明 |
| --- | --- |
| getWeight(target) | 指定されたターゲットの重みを取得します。ターゲットがこのチャネルに属さない場合、デフォルト値の0が返されます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| targe | シェイプ | null |

 **Result:**
数


---


### setWeight{#setWeight}

| 名前 | 説明 |
| --- | --- |
| setWeight(target, weight) | 指定されたターゲットの重みを設定します。デフォルト値は1で、範囲は0〜1の間である必要があります。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| targe | シェイプ | null |
| 重み付け | 数 | null |

 **Result:**
数


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



