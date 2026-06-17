---
title: "RelativeRectangle"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

相対矩形  相対コンポーネントと絶対値の間の式は:  Scale  (Reference Width) + offset  したがって、絶対値を表したい場合は、すべてのスケールフィールドをゼロにし、代わりにオフセットフィールドを使用してください。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(left, top, width, height) | RelativeRectangle を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 左 | 数 | null |
| to | 数 | null |
| 幅 | 数 | null |
| 高さ | 数 | null |

 **Result:**



---


### getScaleX{#getScaleX}

| 名前 | 説明 |
| --- | --- |
| getScaleX() | 相対座標 X |

 **Result:**



---


### setScaleX{#setScaleX}

| 名前 | 説明 |
| --- | --- |
| setScaleX(value) | 相対座標 X |

 **Result:**



---


### getScaleY{#getScaleY}

| 名前 | 説明 |
| --- | --- |
| getScaleY() | 相対座標 Y |

 **Result:**



---


### setScaleY{#setScaleY}

| 名前 | 説明 |
| --- | --- |
| setScaleY(value) | 相対座標 Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| 名前 | 説明 |
| --- | --- |
| getScaleWidth() | 相対幅 |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| 名前 | 説明 |
| --- | --- |
| setScaleWidth(value) | 相対幅 |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| 名前 | 説明 |
| --- | --- |
| getScaleHeight() | 相対高さ |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| 名前 | 説明 |
| --- | --- |
| setScaleHeight(value) | 相対高さ |

 **Result:**



---


### getOffsetX{#getOffsetX}

| 名前 | 説明 |
| --- | --- |
| getOffsetX() | 座標 X のオフセットを取得または設定します |

 **Result:**



---


### setOffsetX{#setOffsetX}

| 名前 | 説明 |
| --- | --- |
| setOffsetX(value) | 座標 X のオフセットを取得または設定します |

 **Result:**



---


### getOffsetY{#getOffsetY}

| 名前 | 説明 |
| --- | --- |
| getOffsetY() | 座標 Y のオフセットを取得または設定します |

 **Result:**



---


### setOffsetY{#setOffsetY}

| 名前 | 説明 |
| --- | --- |
| setOffsetY(value) | 座標 Y のオフセットを取得または設定します |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| 名前 | 説明 |
| --- | --- |
| getOffsetWidth() | 幅のオフセットを取得または設定します |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| 名前 | 説明 |
| --- | --- |
| setOffsetWidth(value) | 幅のオフセットを取得または設定します |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| 名前 | 説明 |
| --- | --- |
| getOffsetHeight() | 高さのオフセットを取得または設定します |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| 名前 | 説明 |
| --- | --- |
| setOffsetHeight(value) | 高さのオフセットを取得または設定します |

 **Result:**



---


### toAbsolute{#toAbsolute}

| 名前 | 説明 |
| --- | --- |
| toAbsolute(left, top, width, height) | 相対矩形を絶対矩形に変換します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 左 | 数 | 矩形の左側 |
| 上 | 数 | 矩形の上側 |
| 幅 | 数 | 矩形の幅 |
| height | 数 | 矩形の高さ |

 **Result:**
Rect


---


### fromScale{#fromScale}

| 名前 | 説明 |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | すべてのオフセットフィールドを0にし、スケールフィールドを指定されたパラメータから設定した RelativeRectangle を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| スケール | 数 | null |
| スケール | 数 | null |
| scaleWidt | 数 | null |
| scaleHeigh | 数 | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | このインスタンスの値を java.lang.String に変換します。 |

 **Result:**
RelativeRectangle


---



