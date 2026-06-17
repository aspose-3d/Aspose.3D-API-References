---
title: "ボーン"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/bone/
---
## Bone class

ボーンはジオメトリのコントロールポイントのサブセットを定義し、各コントロールポイントにブレンドウェイトを設定します。Bone オブジェクトは直接使用できず、SkinDeformer インスタンスがジオメトリを変形させます。SkinDeformer には複数のボーンが含まれ、各ボーンはノードにリンクされています。NOTE: ジオメトリのコントロールポイントは複数の Bones にバインドできる場合があります。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(name) | Bone クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload() | Bone クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### getWeightCount{#getWeightCount}

| 名前 | 説明 |
| --- | --- |
| getWeightCount() | 重みの数を取得します。これは setWeight(int, double) によって自動的に拡張されます。 |

 **Result:**



---


### getTransform{#getTransform}

| 名前 | 説明 |
| --- | --- |
| getTransform() | ボーンを含むノードの変換行列を取得または設定します。 |

 **Result:**



---


### setTransform{#setTransform}

| 名前 | 説明 |
| --- | --- |
| setTransform(value) | ボーンを含むノードの変換行列を取得または設定します。 |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| 名前 | 説明 |
| --- | --- |
| getBoneTransform() | ボーンの変換行列を取得または設定します。 |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| 名前 | 説明 |
| --- | --- |
| setBoneTransform(value) | ボーンの変換行列を取得または設定します。 |

 **Result:**



---


### getNode{#getNode}

| 名前 | 説明 |
| --- | --- |
| getNode() | ノードを取得または設定します。ボーンノードはスキンが付随するボーンで、SkinDeformer はボーンノードを使用してコントロールポイントの変位に影響を与えます。ボーンノードには通常 Skeleton が付随しますが、必須ではありません。付随した Skeleton は通常、DCC ソフトウェアでユーザーにスケルトンを表示するために使用されます。 |

 **Result:**



---


### setNode{#setNode}

| 名前 | 説明 |
| --- | --- |
| setNode(value) | ノードを取得または設定します。ボーンノードはスキンが付随するボーンで、SkinDeformer はボーンノードを使用してコントロールポイントの変位に影響を与えます。ボーンノードには通常 Skeleton が付随しますが、必須ではありません。付随した Skeleton は通常、DCC ソフトウェアでユーザーにスケルトンを表示するために使用されます。 |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| 名前 | 説明 |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| 名前 | 説明 |
| --- | --- |
| getWeight(index) | インデックスで指定されたコントロールポイントの重みを取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| index | 数 | コントロールポイントのインデックス |

 **Result:**
数


---


### setWeight{#setWeight}

| 名前 | 説明 |
| --- | --- |
| setWeight(index, weight) | インデックスで指定されたコントロールポイントの重みを設定します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| index | 数 | コントロールポイントのインデックス |
| ウェイト | 数 | 新しいウェイト |

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



