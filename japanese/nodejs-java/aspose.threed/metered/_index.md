---
title: "Metered"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/metered/
---
## Metered class

メータ付きキーを設定するためのメソッドを提供します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | このクラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| 名前 | 説明 |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | メーター付きの公開キーと秘密キーを設定します。メーター付きライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常はこれだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を回避するために、ライセンスステータスを定期的に確認し、評価ステータスの場合は再度この API を呼び出してください。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| publicKey | 文字列 | 公開キー |
| privateKey | 文字列 | プライベートキー |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| 名前 | 説明 |
| --- | --- |
| getConsumptionQuantity() | 消費ファイルサイズを取得します |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| 名前 | 説明 |
| --- | --- |
| getConsumptionCredit() | 消費クレジットを取得します |

 **Result:**
BigDecimal


---



