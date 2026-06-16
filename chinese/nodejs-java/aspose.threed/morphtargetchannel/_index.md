---
title: "形态目标通道"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetChannel 被 MorphTargetDeformer 用于组织目标几何体。某些文件格式如 FBX 支持并行的多个通道。权重介于 0 到 1.0 之间，目标的默认权重为 0.0；


## 属性

| 名称 | 描述 |
| --- | --- |
| DEFAULT_WEIGHT | 形态目标的默认权重。 |

## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(name) | 初始化 MorphTargetChannel 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload() | 初始化 MorphTargetChannel 类的新实例。 |

 **Result:**



---


### getWeights{#getWeights}

| 名称 | 描述 |
| --- | --- |
| getWeights() | 获取目标几何体的完整权重值。完整权重。 |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| 名称 | 描述 |
| --- | --- |
| getChannelWeight() | 获取或设置此通道的变形器权重。权重介于 0.0 到 1.0 之间。 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| 名称 | 描述 |
| --- | --- |
| setChannelWeight(value) | 获取或设置此通道的变形器权重。权重介于 0.0 到 1.0 之间。 |

 **Result:**



---


### getTargets{#getTargets}

| 名称 | 描述 |
| --- | --- |
| getTargets() | 获取与该通道关联的所有目标。 |

 **Result:**



---


### getName{#getName}

| 名称 | 描述 |
| --- | --- |
| getName() | 获取或设置名称。名称。 |

 **Result:**



---


### setName{#setName}

| 名称 | 描述 |
| --- | --- |
| setName(value) | 获取或设置名称。名称。 |

 **Result:**



---


### getProperties{#getProperties}

| 名称 | 描述 |
| --- | --- |
| getProperties() | 获取所有属性的集合。 |

 **Result:**



---


### get{#get}

| 名称 | 描述 |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| 名称 | 描述 |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| 名称 | 描述 |
| --- | --- |
| getWeight(target) | 获取指定目标的权重，如果目标不属于此通道，则返回默认值 0。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 目标 | Shape | null |

 **Result:**
数字


---


### setWeight{#setWeight}

| 名称 | 描述 |
| --- | --- |
| setWeight(target, weight) | 设置指定目标的权重，默认值为 1，范围应在 0~1 之间。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 目标 | Shape | null |
| 称重 | 数字 | null |

 **Result:**
数字


---


### removeProperty{#removeProperty}

| 名称 | 描述 |
| --- | --- |
| removeProperty(property) | 移除动态属性。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| property | Property | 要移除哪个属性 |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 名称 | 描述 |
| --- | --- |
| removeProperty(property) | 移除按名称标识的指定属性 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propert | 字符串 | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 名称 | 描述 |
| --- | --- |
| getProperty(property) | 获取指定属性的值 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| property | 字符串 | 属性名称 |

 **Result:**
对象


---


### setProperty{#setProperty}

| 名称 | 描述 |
| --- | --- |
| setProperty(property, value) | 设置指定属性的值 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| property | 字符串 | 属性名称 |
| 值 | 对象 | 属性的值 |

 **Result:**
对象


---


### findProperty{#findProperty}

| 名称 | 描述 |
| --- | --- |
| findProperty(propertyName) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | 字符串 | 属性名称。 |

 **Result:**
Property


---



