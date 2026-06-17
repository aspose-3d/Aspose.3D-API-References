---
title: "AnimationNode"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D はアニメーション階層をサポートし、各アニメーションは複数のアニメーションとアニメーションのキーフレーム定義で構成できます。AnimationNode は時間経過に伴うプロパティ値の変換を定義します。例えば、animation node はノードの変換や他の A3DObject オブジェクトの数値プロパティを制御するために使用できます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(name) | AnimationNode クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload() | AnimationNode クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### getBindPoints{#getBindPoints}

| 名前 | 説明 |
| --- | --- |
| getBindPoints() | 現在のプロパティバインドポイントを取得します |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| 名前 | 説明 |
| --- | --- |
| getSubAnimations() | 現在のアニメーションの下にあるサブアニメーションノードを取得します |

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


### findBindPoint{#findBindPoint}

| 名前 | 説明 |
| --- | --- |
| findBindPoint(name) | 名前でバインドポイントを検索します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 検索するバインドポイントの名前。 |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| 名前 | 説明 |
| --- | --- |
| getBindPoint(target, propName, create) | 指定されたプロパティのアニメーションバインドポイントを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ターゲット | A3DObject | バインドポイントを作成するオブジェクトを指定します。 |
| propName | 文字列 | プロパティの名前です。 |
| 作成 | boolean | 設定する場合は |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| 名前 | 説明 |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | 指定されたプロパティとチャンネルのキーフレームシーケンスを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ターゲット | A3DObject | キーフレームシーケンスを作成するインスタンスを指定します。 |
| propName | 文字列 | プロパティの名前です。 |
| channelName | 文字列 | チャンネル名です。 |
| 作成 | boolean | 設定する場合は |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| 名前 | 説明 |
| --- | --- |
| getKeyframeSequence(target, propName, create) | 指定されたプロパティのキーフレームシーケンスを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ターゲット | A3DObject | キーフレームシーケンスを作成するインスタンスを指定します。 |
| propName | 文字列 | プロパティの名前です。 |
| 作成 | boolean | 設定する場合は |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| 名前 | 説明 |
| --- | --- |
| createBindPoint(obj, propName) | プロパティのデータ型に基づいて BindPoint を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| obj | A3DObject | オブジェクト。 |
| propName | 文字列 | プロパティ名。 |

 **Result:**
BindPoint


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



