---
title: "ポーズ"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/pose/
---
## Pose class

ジオメトリがスキンされているときに変換行列を保存するために使用されるポーズです。ポーズはBonePoseの集合で、各BonePoseはボーンノードの具体的な変換情報を保存します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(name) | Pose クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload() | Pose クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### getPoseType{#getPoseType}

| 名前 | 説明 |
| --- | --- |
| getPoseType() | ポーズのタイプを取得または設定します。プロパティの値は PoseType 整数定数です。ポーズのタイプ。 |

 **Result:**



---


### setPoseType{#setPoseType}

| 名前 | 説明 |
| --- | --- |
| setPoseType(value) | ポーズのタイプを取得または設定します。プロパティの値は PoseType 整数定数です。ポーズのタイプ。 |

 **Result:**



---


### getBonePoses{#getBonePoses}

| 名前 | 説明 |
| --- | --- |
| getBonePoses() | すべての BonePose を取得します。ノード。 |

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


### addBonePose{#addBonePose}

| 名前 | 説明 |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | 指定されたボーンノードのポーズ変換行列を保存します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ノード | ノード | ボーンノード。 |
| matrix | Matrix4 | 変換行列。 |
| localMatrix | boolean | 設定する場合は |

 **Result:**



---


### addBonePose{#addBonePose}

| 名前 | 説明 |
| --- | --- |
| addBonePose(node, matrix) | 指定されたボーンノードのポーズ変換行列を保存します。グローバル変換行列が暗黙的に使用されます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ノード | ノード | ボーンノード。 |
| matrix | Matrix4 | 変換行列。 |

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



