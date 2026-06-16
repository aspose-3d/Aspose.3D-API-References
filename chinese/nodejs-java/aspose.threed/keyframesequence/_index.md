---
title: "KeyframeSequence"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

关键帧序列，描述了采样值随时间的变化。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(name) | 初始化 KeyframeSequence 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload() | 初始化 KeyframeSequence 类的新实例。 |

 **Result:**



---


### getBindPoint{#getBindPoint}

| 名称 | 描述 |
| --- | --- |
| getBindPoint() | 获取拥有此曲线的属性绑定点 |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| 名称 | 描述 |
| --- | --- |
| getKeyFrames() | 获取此曲线的关键帧。关键帧。 |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| 名称 | 描述 |
| --- | --- |
| getPostBehavior() | 获取后置行为，指示在最后一个关键帧之后采样值应为何。 |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| 名称 | 描述 |
| --- | --- |
| getPreBehavior() | 获取前置行为，指示在第一个关键帧之前采样值应为何。 |

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


### add{#add}

| 名称 | 描述 |
| --- | --- |
| add(time, value) | 创建一个具有指定值的新关键帧 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 时间 | 数字 | 时间位置（以秒为单位） |
| 值 | 数字 | 该时间位置的值 |

 **Result:**



---


### add{#add}

| 名称 | 描述 |
| --- | --- |
| add(time, value, interpolation) | 创建一个具有指定值的新关键帧 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 时间 | 数字 | 时间位置（以秒为单位） |
| 值 | 数字 | 该时间位置的值 |
| 插值 | 插值 | 插值 |

 **Result:**



---


### reset{#reset}

| 名称 | 描述 |
| --- | --- |
| reset() | 移除所有关键帧并重置后置/前置行为。 |

 **Result:**



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


### iterator{#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator() | 保留供内部使用。 |

 **Result:**
Property


---



