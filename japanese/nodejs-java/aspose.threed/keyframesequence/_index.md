---
title: "KeyframeSequence"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

キーフレームのシーケンスで、サンプル値が時間とともに変化する様子を記述します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(name) | KeyframeSequence クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload() | KeyframeSequence クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### getBindPoint{#getBindPoint}

| 名前 | 説明 |
| --- | --- |
| getBindPoint() | この曲線を所有するプロパティのバインドポイントを取得します。 |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| 名前 | 説明 |
| --- | --- |
| getKeyFrames() | この曲線のキーフレームを取得します。キーです。 |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| 名前 | 説明 |
| --- | --- |
| getPostBehavior() | ポストビヘイビアを取得します。これは、最後のキーフレームの後にサンプル値がどうなるべきかを示します。 |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| 名前 | 説明 |
| --- | --- |
| getPreBehavior() | プリビヘイビアを取得します。これは、最初のキーの前にサンプル値がどうなるべきかを示します。 |

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


### add{#add}

| 名前 | 説明 |
| --- | --- |
| add(time, value) | 指定された値で新しいキーフレームを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 時間 | 数 | 時間位置(秒単位で測定) |
| 値 | 数 | この時間位置の値 |

 **Result:**



---


### add{#add}

| 名前 | 説明 |
| --- | --- |
| add(time, value, interpolation) | 指定された値で新しいキーフレームを作成します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 時間 | 数 | 時間位置(秒単位で測定) |
| 値 | 数 | この時間位置の値 |
| 補間 | 補間 | 補間 |

 **Result:**



---


### reset{#reset}

| 名前 | 説明 |
| --- | --- |
| reset() | すべてのキーフレームを削除し、ポスト/プリビヘイビアをリセットします。 |

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


### iterator{#iterator}

| 名前 | 説明 |
| --- | --- |
| iterator() | 内部使用のために予約されています。 |

 **Result:**
Property


---



