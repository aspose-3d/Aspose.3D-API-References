---
title: "Watermark"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/watermark/
---
## Watermark class

メッシュへの/からブラインドウォーターマークをエンコード/デコードするユーティリティです。  @hideconstructor


## メソッド

### encodeWatermark{#encodeWatermark}

| 名前 | 説明 |
| --- | --- |
| encodeWatermark(input, text) | テキストをメッシュのブラインドウォーターマークにエンコードします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 入力 | Mesh | ブラインドウォーターマークをエコードするメッシュ |
| text | 文字列 | メッシュにエンコードするテキスト |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| 名前 | 説明 |
| --- | --- |
| encodeWatermark(input, text, password) | テキストをメッシュのブラインドウォーターマークにエンコードします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 入力 | Mesh | ブラインドウォーターマークをエコードするメッシュ |
| text | 文字列 | メッシュにエンコードするテキスト |
| password | 文字列 | ウォーターマークを保護するパスワード（オプション） |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| 名前 | 説明 |
| --- | --- |
| decodeWatermark(input) | メッシュからウォーターマークをデコードします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 入力 | Mesh | ウォーターマークを抽出するメッシュ |

 **Result:**
文字列


---


### decodeWatermark{#decodeWatermark}

| 名前 | 説明 |
| --- | --- |
| decodeWatermark(input, password) | メッシュからウォーターマークをデコードします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 入力 | Mesh | ウォーターマークを抽出するメッシュ |
| password | 文字列 | ウォーターマークを復号化するパスワード |

 **Result:**
文字列


---



