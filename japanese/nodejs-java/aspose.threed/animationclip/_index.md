---
title: "AnimationClip"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Animation クリップはアニメーションのコレクションです。シーンは 1 つ以上のアニメーション クリップを持つことができます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | AnimationClip クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name) | AnimationClip クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### getAnimations{#getAnimations}

| 名前 | 説明 |
| --- | --- |
| getAnimations() | クリップ内に含まれるアニメーションを取得します。レイヤー。 |

 **Result:**



---


### getDescription{#getDescription}

| 名前 | 説明 |
| --- | --- |
| getDescription() | このアニメーションクリップの説明を取得または設定します |

 **Result:**



---


### setDescription{#setDescription}

| 名前 | 説明 |
| --- | --- |
| setDescription(value) | このアニメーションクリップの説明を取得または設定します |

 **Result:**



---


### getStart{#getStart}

| 名前 | 説明 |
| --- | --- |
| getStart() | クリップの開始時刻（秒）を取得または設定します。 |

 **Result:**



---


### setStart{#setStart}

| 名前 | 説明 |
| --- | --- |
| setStart(value) | クリップの開始時刻（秒）を取得または設定します。 |

 **Result:**



---


### getStop{#getStop}

| 名前 | 説明 |
| --- | --- |
| getStop() | クリップの終了時刻（秒）を取得または設定します。 |

 **Result:**



---


### setStop{#setStop}

| 名前 | 説明 |
| --- | --- |
| setStop(value) | クリップの終了時刻（秒）を取得または設定します。 |

 **Result:**



---


### getScene{#getScene}

| 名前 | 説明 |
| --- | --- |
| getScene() | このオブジェクトが属するシーンを取得します。 |

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


### createAnimationNode{#createAnimationNode}

| 名前 | 説明 |
| --- | --- |
| createAnimationNode(nodeName) | 現在のクリップ上でアニメーションノードを作成し登録するためのショートハンド関数です。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| nodeName | 文字列 | 新しいアニメーションノードの名前 |

 **Result:**
AnimationNode


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



