---
title: "Property"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/property/
---
## Property class

ユーザー定義プロパティを保持するクラス。  @hideconstructor


## メソッド

### getValue{#getValue}

| 名前 | 説明 |
| --- | --- |
| getValue() | 値を取得または設定します。値。 |

 **Result:**



---


### setValue{#setValue}

| 名前 | 説明 |
| --- | --- |
| setValue(value) | 値を取得または設定します。値。 |

 **Result:**



---


### setName{#setName}

| 名前 | 説明 |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| 名前 | 説明 |
| --- | --- |
| getValueType() | プロパティ値の型を取得します。値の型。 |

 **Result:**



---


### getProperties{#getProperties}

| 名前 | 説明 |
| --- | --- |
| getProperties() | すべてのプロパティのコレクションを取得します。 |

 **Result:**



---


### getBindPoint{#getBindPoint}

| 名前 | 説明 |
| --- | --- |
| getBindPoint(anim, create) | 指定されたアニメーションインスタンス上のプロパティバインドポイントを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| anim | AnimationNode | どのアニメーションでバインドポイントを作成するか。 |
| 作成 | boolean | プロパティバインドポイントが見つからない場合は作成してください。 |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| 名前 | 説明 |
| --- | --- |
| getKeyframeSequence(anim, create) | 指定されたアニメーションインスタンスのキーフレームシーケンスを取得します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| anim | AnimationNode | どのアニメーションでキーフレームシーケンスを作成するか。 |
| 作成 | boolean | キーフレームシーケンスが見つからない場合は作成してください。 |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | 現在のプロパティを表す文字列を返します。 |

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



