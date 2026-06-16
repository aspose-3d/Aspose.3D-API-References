---
title: "RelativeRectangle"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

相对矩形  相对组件到绝对值的公式为：  Scale (Reference Width) + offset  因此如果我们想让它表示绝对值，请将所有 scale 字段设为零，并改用 offset 字段。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(left, top, width, height) | 构造一个 RelativeRectangle |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 左 | 数字 | null |
| to | 数字 | null |
| 宽度 | 数字 | null |
| 高度 | 数字 | null |

 **Result:**



---


### getScaleX{#getScaleX}

| 名称 | 描述 |
| --- | --- |
| getScaleX() | 相对坐标 X |

 **Result:**



---


### setScaleX{#setScaleX}

| 名称 | 描述 |
| --- | --- |
| setScaleX(value) | 相对坐标 X |

 **Result:**



---


### getScaleY{#getScaleY}

| 名称 | 描述 |
| --- | --- |
| getScaleY() | 相对坐标 Y |

 **Result:**



---


### setScaleY{#setScaleY}

| 名称 | 描述 |
| --- | --- |
| setScaleY(value) | 相对坐标 Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| 名称 | 描述 |
| --- | --- |
| getScaleWidth() | 相对宽度 |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| 名称 | 描述 |
| --- | --- |
| setScaleWidth(value) | 相对宽度 |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| 名称 | 描述 |
| --- | --- |
| getScaleHeight() | 相对高度 |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| 名称 | 描述 |
| --- | --- |
| setScaleHeight(value) | 相对高度 |

 **Result:**



---


### getOffsetX{#getOffsetX}

| 名称 | 描述 |
| --- | --- |
| getOffsetX() | 获取或设置坐标 X 的偏移量 |

 **Result:**



---


### setOffsetX{#setOffsetX}

| 名称 | 描述 |
| --- | --- |
| setOffsetX(value) | 获取或设置坐标 X 的偏移量 |

 **Result:**



---


### getOffsetY{#getOffsetY}

| 名称 | 描述 |
| --- | --- |
| getOffsetY() | 获取或设置坐标 Y 的偏移量 |

 **Result:**



---


### setOffsetY{#setOffsetY}

| 名称 | 描述 |
| --- | --- |
| setOffsetY(value) | 获取或设置坐标 Y 的偏移量 |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| 名称 | 描述 |
| --- | --- |
| getOffsetWidth() | 获取或设置宽度的偏移量 |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| 名称 | 描述 |
| --- | --- |
| setOffsetWidth(value) | 获取或设置宽度的偏移量 |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| 名称 | 描述 |
| --- | --- |
| getOffsetHeight() | 获取或设置高度的偏移量 |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| 名称 | 描述 |
| --- | --- |
| setOffsetHeight(value) | 获取或设置高度的偏移量 |

 **Result:**



---


### toAbsolute{#toAbsolute}

| 名称 | 描述 |
| --- | --- |
| toAbsolute(left, top, width, height) | 将相对矩形转换为绝对矩形 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 左 | 数字 | 矩形的左侧 |
| 上 | 数字 | 矩形的顶部 |
| 宽度 | 数字 | 矩形的宽度 |
| height | 数字 | 矩形的高度 |

 **Result:**
Rect


---


### fromScale{#fromScale}

| 名称 | 描述 |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | 使用所有偏移字段为零且比例字段来自给定参数来构造 RelativeRectangle。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 缩放 | 数字 | null |
| 缩放 | 数字 | null |
| scaleWidt | 数字 | null |
| scaleHeigh | 数字 | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 将此实例的值转换为 java.lang.String。 |

 **Result:**
RelativeRectangle


---



