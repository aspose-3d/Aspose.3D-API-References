---
title: "VertexDeclaration"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

カスタム定義された頂点構造の宣言


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| 名前 | 説明 |
| --- | --- |
| getSealed() | VertexDeclaration は com.aspose.threed.TriMesh`1 または TriMesh に使用されたときにシールドされ、これ以上の変更は許可されません。 |

 **Result:**



---


### getCount{#getCount}

| 名前 | 説明 |
| --- | --- |
| getCount() | この VertexDeclaration で定義されたすべてのフィールドの数を取得します |

 **Result:**



---


### getSize{#getSize}

| 名前 | 説明 |
| --- | --- |
| getSize() | 頂点構造体のバイト単位のサイズです。 |

 **Result:**



---


### get{#get}

| 名前 | 説明 |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| 名前 | 説明 |
| --- | --- |
| clear() | すべてのフィールドをクリアします。 |

 **Result:**



---


### addField{#addField}

| 名前 | 説明 |
| --- | --- |
| addField(dataType, semantic, index, alias) | 新しい頂点フィールドを追加します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| dataType | 数 | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| index | 数 | 同じフィールドのセマンティックのインデックス、-1 は自動生成を意味します |
| alias | 文字列 | フィールドのエイリアス名です |

 **Result:**



---


### fromGeometry{#fromGeometry}

| 名前 | 説明 |
| --- | --- |
| fromGeometry(geometry, useFloat) | Geometry のレイアウトに基づいて VertexDeclaration を作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| geometr | ジオメトリ | null |
| useFloat | boolean | double 型の代わりに float を使用します |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| 名前 | 説明 |
| --- | --- |
| compareTo(other) | このインスタンスを指定されたオブジェクトと比較し、相対的な値の指標を返します。 |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() |  |

 **Result:**
文字列


---


### hashCode{#hashCode}

| 名前 | 説明 |
| --- | --- |
| hashCode() |  |

 **Result:**
数


---


### equals{#equals}

| 名前 | 説明 |
| --- | --- |
| equals(obj) | このインスタンスと、VertexDeclaration オブジェクトである必要がある指定されたオブジェクトが同じ値かどうかを判断します。 |

 **Result:**
数


---


### iterator{#iterator}

| 名前 | 説明 |
| --- | --- |
| iterator() | 内部使用のために予約されています。 |

 **Result:**
数


---



