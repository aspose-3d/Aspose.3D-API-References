---
title: "BindPoint"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

BindPoint は通常、オブジェクトのプロパティ上に作成されます。一部のプロパティ型は複数のコンポーネントフィールド（Vector3 フィールドなど）を含み、BindPoint は各コンポーネントフィールドに対してチャネルを生成し、チャネルを介してフィールドを 1 つ以上のキー フレーム シーケンス インスタンスに接続します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(scene, prop) | BindPoint クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シーン | Scene | アニメーションを含むシーンです。 |
| プロパティ | Property | プロパティ。 |

 **Result:**



---


### getProperty{#getProperty}

| 名前 | 説明 |
| --- | --- |
| getProperty() | CurveMapping に関連付けられたプロパティを取得します |

 **Result:**



---


### setProperty{#setProperty}

| 名前 | 説明 |
| --- | --- |
| setProperty(value) | CurveMapping に関連付けられたプロパティを取得します |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| 名前 | 説明 |
| --- | --- |
| getChannelsCount() | このアニメーションカーブマッピングで定義されたプロパティチャンネルの総数を取得します。 |

 **Result:**
数


---


### getName{#getName}

| 名前 | 説明 |
| --- | --- |
| getName() | 名前を取得または設定します。名前。 |

 **Result:**
数


---


### setName{#setName}

| 名前 | 説明 |
| --- | --- |
| setName(value) | 名前を取得または設定します。名前。 |

 **Result:**
数


---


### getProperties{#getProperties}

| 名前 | 説明 |
| --- | --- |
| getProperties() | すべてのプロパティのコレクションを取得します。 |

 **Result:**
数


---


### get{#get}

| 名前 | 説明 |
| --- | --- |
| get(channelName) |  |

 **Result:**
数


---


### getKeyframeSequence{#getKeyframeSequence}

| 名前 | 説明 |
| --- | --- |
| getKeyframeSequence(channelName) | 指定されたチャンネルの最初のキーフレームシーケンスを取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| channelName | 文字列 | 検索するチャンネル名 |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| 名前 | 説明 |
| --- | --- |
| getKeyframeSequences(channelName) | 指定されたチャンネルのすべてのキーフレームシーケンスを取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| channelName | 文字列 | 検索するチャンネル名 |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| 名前 | 説明 |
| --- | --- |
| createKeyframeSequence(name) | 新しいカーブを作成し、カーブマッピングの最初のチャンネルに接続します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 新しいシーケンスの名前。 |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| 名前 | 説明 |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | キーフレームシーケンスを指定されたチャンネルにバインドします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| channelName | 文字列 | キーフレームシーケンスがバインドされるチャンネル |
| シーケンス | KeyframeSequence | バインドするキーフレームシーケンス |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| 名前 | 説明 |
| --- | --- |
| getChannel(channelName) | 指定された名前でチャンネルを取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| channelName | 文字列 | 検索するチャンネル名 |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| 名前 | 説明 |
| --- | --- |
| addChannel(name, value) | 指定されたチャンネルプロパティを追加します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |
| 値 | オブジェクト | 値。 |

 **Result:**
boolean


---


### addChannel{#addChannel}

| 名前 | 説明 |
| --- | --- |
| addChannel(name, type, value) | 指定されたチャンネルプロパティを追加します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |
| type | クラス | 型。 |
| 値 | オブジェクト | 値。 |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| 名前 | 説明 |
| --- | --- |
| resetChannels() | このアニメーションカーブマッピングのプロパティチャンネルを空にします |

 **Result:**
boolean


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



