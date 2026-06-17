---
title: "変換"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/transform/
---
## Transform class

変換はオブジェクトの平行移動/スケール/回転または変換行列へのアクセスを最小コストで可能にする情報を含みます。これはローカル変換で使用されます。  @hideconstructor


## メソッド

### getGeometricTranslation{#getGeometricTranslation}

| 名前 | 説明 |
| --- | --- |
| getGeometricTranslation() | 幾何学的平行移動を取得または設定します。幾何学的変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何学的変換をエクスポートする場合、ローカル変換としてマージされます。 |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| 名前 | 説明 |
| --- | --- |
| setGeometricTranslation(value) | 幾何学的平行移動を取得または設定します。幾何学的変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何学的変換をエクスポートする場合、ローカル変換としてマージされます。 |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| 名前 | 説明 |
| --- | --- |
| getGeometricScaling() | 幾何学的スケーリングを取得または設定します。幾何学的変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何学的変換をエクスポートする場合、ローカル変換としてマージされます。 |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| 名前 | 説明 |
| --- | --- |
| setGeometricScaling(value) | 幾何学的スケーリングを取得または設定します。幾何学的変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何学的変換をエクスポートする場合、ローカル変換としてマージされます。 |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| 名前 | 説明 |
| --- | --- |
| getGeometricRotation() | 幾何学的オイラー回転（度単位）を取得または設定します。幾何学的変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何学的変換をエクスポートする場合、ローカル変換としてマージされます。 |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| 名前 | 説明 |
| --- | --- |
| setGeometricRotation(value) | 幾何学的オイラー回転（度単位）を取得または設定します。幾何学的変換は、添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何学的変換をエクスポートする場合、ローカル変換としてマージされます。 |

 **Result:**



---


### getTranslation{#getTranslation}

| 名前 | 説明 |
| --- | --- |
| getTranslation() | 変換を取得または設定します |

 **Result:**



---


### setTranslation{#setTranslation}

| 名前 | 説明 |
| --- | --- |
| setTranslation(value) | 変換を取得または設定します |

 **Result:**



---


### getScale{#getScale}

| 名前 | 説明 |
| --- | --- |
| getScale() | スケールを取得または設定します |

 **Result:**



---


### setScale{#setScale}

| 名前 | 説明 |
| --- | --- |
| setScale(value) | スケールを取得または設定します |

 **Result:**



---


### getPreRotation{#getPreRotation}

| 名前 | 説明 |
| --- | --- |
| getPreRotation() | 度で表される事前回転を取得または設定します |

 **Result:**



---


### setPreRotation{#setPreRotation}

| 名前 | 説明 |
| --- | --- |
| setPreRotation(value) | 度で表される事前回転を取得または設定します |

 **Result:**



---


### getPostRotation{#getPostRotation}

| 名前 | 説明 |
| --- | --- |
| getPostRotation() | 度で表される事後回転を取得または設定します |

 **Result:**



---


### setPostRotation{#setPostRotation}

| 名前 | 説明 |
| --- | --- |
| setPostRotation(value) | 度で表される事後回転を取得または設定します |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| 名前 | 説明 |
| --- | --- |
| getEulerAngles() | 度で測定されたEuler角で表される回転を取得または設定します |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| 名前 | 説明 |
| --- | --- |
| setEulerAngles(value) | 度で測定されたEuler角で表される回転を取得または設定します |

 **Result:**



---


### getRotation{#getRotation}

| 名前 | 説明 |
| --- | --- |
| getRotation() | クォータニオンで表される回転を取得または設定します。 |

 **Result:**



---


### setRotation{#setRotation}

| 名前 | 説明 |
| --- | --- |
| setRotation(value) | クォータニオンで表される回転を取得または設定します。 |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| 名前 | 説明 |
| --- | --- |
| getTransformMatrix() | 変換行列を取得または設定します。このプロパティに代入すると Translation、Scale、Rotation がリセットされますが、GeometricRotation、GeometricScaling、GeometricTranslation は影響を受けません。 |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| 名前 | 説明 |
| --- | --- |
| setTransformMatrix(value) | 変換行列を取得または設定します。このプロパティに代入すると Translation、Scale、Rotation がリセットされますが、GeometricRotation、GeometricScaling、GeometricTranslation は影響を受けません。 |

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


### setGeometricTranslation{#setGeometricTranslation}

| 名前 | 説明 |
| --- | --- |
| setGeometricTranslation(x, y, z) | 幾何的平行移動を設定します。幾何変換は添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何変換をエクスポートする際には、ローカル変換としてマージされます。 |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| 名前 | 説明 |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | 幾何的スケーリングを設定します。幾何変換は添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何変換をエクスポートする際には、ローカル変換としてマージされます。 |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| 名前 | 説明 |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | 幾何的Euler回転（度で測定）を設定します。幾何変換は添付されたエンティティにのみ影響し、子ノードには影響しません。サポートされていないファイル形式に幾何変換をエクスポートする際には、ローカル変換としてマージされます。 |

 **Result:**



---


### setTranslation{#setTranslation}

| 名前 | 説明 |
| --- | --- |
| setTranslation(tx, ty, tz) | 現在の変換の平行移動を設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| t | 数 | null |
| t | 数 | null |
| t | 数 | null |

 **Result:**
変換


---


### setScale{#setScale}

| 名前 | 説明 |
| --- | --- |
| setScale(sx, sy, sz) | 現在の変換のスケールを設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| s | 数 | null |
| s | 数 | null |
| s | 数 | null |

 **Result:**
変換


---


### setEulerAngles{#setEulerAngles}

| 名前 | 説明 |
| --- | --- |
| setEulerAngles(rx, ry, rz) | 現在の変換のオイラー角を度単位で設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| r | 数 | null |
| r | 数 | null |
| r | 数 | null |

 **Result:**
変換


---


### setRotation{#setRotation}

| 名前 | 説明 |
| --- | --- |
| setRotation(rw, rx, ry, rz) | 現在の変換の回転を（クォータニオン成分として）設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| r | 数 | null |
| r | 数 | null |
| r | 数 | null |
| r | 数 | null |

 **Result:**
変換


---


### setPreRotation{#setPreRotation}

| 名前 | 説明 |
| --- | --- |
| setPreRotation(rx, ry, rz) | 度で表された事前回転を設定します。 |

 **Result:**
変換


---


### setPostRotation{#setPostRotation}

| 名前 | 説明 |
| --- | --- |
| setPostRotation(rx, ry, rz) | 度で表された事後回転を設定します。 |

 **Result:**
変換


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



