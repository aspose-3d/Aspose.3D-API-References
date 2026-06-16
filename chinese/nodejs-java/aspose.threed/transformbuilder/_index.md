---
title: "TransformBuilder"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilder用于通过一系列变换构建变换矩阵。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(initial, order) | 使用初始变换矩阵和指定的组合顺序构造一个 TransformBuilder |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| initia | Matrix4 | null |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(order) | 使用初始单位变换矩阵和指定的组合顺序构造一个 TransformBuilder |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| 名称 | 描述 |
| --- | --- |
| getMatrix() | 获取或设置当前矩阵值 |

 **Result:**



---


### setMatrix{#setMatrix}

| 名称 | 描述 |
| --- | --- |
| setMatrix(value) | 获取或设置当前矩阵值 |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| 名称 | 描述 |
| --- | --- |
| getComposeOrder() | 获取或设置链式组合顺序。属性的值是 ComposeOrder 整数常量。 |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| 名称 | 描述 |
| --- | --- |
| setComposeOrder(value) | 获取或设置链式组合顺序。属性的值是 ComposeOrder 整数常量。 |

 **Result:**



---


### compose{#compose}

| 名称 | 描述 |
| --- | --- |
| compose(m) | 将参数追加或前置到内部矩阵。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| 名称 | 描述 |
| --- | --- |
| append(m) | 将新的变换矩阵追加到变换链中。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| 名称 | 描述 |
| --- | --- |
| prepend(m) | 将新的变换矩阵前置到变换链中。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| 名称 | 描述 |
| --- | --- |
| rearrange(newX, newY, newZ) | 重新排列轴的布局。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| newX | 轴 | 轴 |
| newY | 轴 | 轴 |
| newZ | 轴 | 轴 |

 **Result:**



---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(s) | 链式连接一个按 s 缩放的缩放变换矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 数字 | null |

 **Result:**



---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(x, y, z) | 链式连接一个缩放变换矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 数字 | null |
|  | 数字 | null |
|  | 数字 | null |

 **Result:**



---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(s) | 链式连接一个缩放变换 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| 名称 | 描述 |
| --- | --- |
| rotateDegree(angle, axis) | 链式连接一个以度为单位的旋转变换 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 数字 | 旋转角度（单位：度） |
| 轴 | Vector3 | 旋转轴 |

 **Result:**



---


### rotateRadian{#rotateRadian}

| 名称 | 描述 |
| --- | --- |
| rotateRadian(angle, axis) | 链式连接一个以弧度为单位的旋转变换 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 数字 | 旋转角度（单位：弧度） |
| 轴 | Vector3 | 旋转轴 |

 **Result:**



---


### rotate{#rotate}

| 名称 | 描述 |
| --- | --- |
| rotate(q) | 链式连接一个四元数旋转 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 四元数 | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| 名称 | 描述 |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | 链式连接一个以度为单位的欧拉角旋转 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 度 | 数字 | null |
| 度 | 数字 | null |
| 度 | 数字 | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| 名称 | 描述 |
| --- | --- |
| rotateEulerRadian(x, y, z) | 链式连接一个以弧度为单位的欧拉角旋转 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 数字 | null |
|  | 数字 | null |
|  | 数字 | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| 名称 | 描述 |
| --- | --- |
| rotateEulerRadian(r) | 链式连接一个以弧度为单位的欧拉角旋转 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| 名称 | 描述 |
| --- | --- |
| translate(tx, ty, tz) | 链式连接一个平移变换 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| t | 数字 | null |
| t | 数字 | null |
| t | 数字 | null |

 **Result:**



---


### translate{#translate}

| 名称 | 描述 |
| --- | --- |
| translate(v) | 链式连接一个平移变换 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| 名称 | 描述 |
| --- | --- |
| reset() | 将变换重置为单位矩阵 |

 **Result:**



---


### rotateDegree{#rotateDegree}

| 名称 | 描述 |
| --- | --- |
| rotateDegree(rot, order) | 在指定顺序下追加旋转 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rot | Vector3 | 以度数表示的旋转 |
| order | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| 名称 | 描述 |
| --- | --- |
| rotateRadian(rot, order) | 在指定顺序下追加旋转 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rot | Vector3 | 弧度制旋转 |
| order | RotationOrder | RotationOrder |

 **Result:**



---



