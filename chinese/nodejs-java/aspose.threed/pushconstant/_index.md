---
title: "PushConstant"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

通过推送常量向着色器提供数据的实用工具。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | PushConstant 的构造函数 |

 **Result:**



---


### write{#write}

| 名称 | 描述 |
| --- | --- |
| write(mat) | 将矩阵写入常量 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mat | FMatrix4 | 要写入的矩阵 |

 **Result:**



---


### write{#write}

| 名称 | 描述 |
| --- | --- |
| write(n) | 将 int 值写入常量 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 数字 | null |

 **Result:**



---


### write{#write}

| 名称 | 描述 |
| --- | --- |
| write(f) | 将 float 值写入常量 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 数字 | null |

 **Result:**



---


### write{#write}

| 名称 | 描述 |
| --- | --- |
| write(vec) | 将 4 分量向量写入常量 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| 名称 | 描述 |
| --- | --- |
| write(vec) | 将 3 分量向量写入常量 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| 名称 | 描述 |
| --- | --- |
| write(x, y, z, w) | 将 4 分量向量写入常量 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 数字 | null |
|  | 数字 | null |
|  | 数字 | null |
|  | 数字 | null |

 **Result:**



---


### commit{#commit}

| 名称 | 描述 |
| --- | --- |
| commit(stage, commandList) | 将准备好的数据提交到图形管线。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stage | 数字 | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



