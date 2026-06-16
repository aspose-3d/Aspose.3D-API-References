---
title: "AnimationNode"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D 支持动画层次结构，每个动画可以由多个动画及其关键帧定义组成。AnimationNode 定义属性值随时间的变换，例如，animation node 可用于控制节点的变换或其他 A3DObject 对象的数值属性。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(name) | 初始化 AnimationNode 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload() | 初始化 AnimationNode 类的新实例。 |

 **Result:**



---


### getBindPoints{#getBindPoints}

| 名称 | 描述 |
| --- | --- |
| getBindPoints() | 获取当前属性绑定点 |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| 名称 | 描述 |
| --- | --- |
| getSubAnimations() | 获取当前动画下的子动画节点 |

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


### findBindPoint{#findBindPoint}

| 名称 | 描述 |
| --- | --- |
| findBindPoint(name) | 按名称查找绑定点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 要查找的绑定点名称。 |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| 名称 | 描述 |
| --- | --- |
| getBindPoint(target, propName, create) | 获取给定属性上的动画绑定点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 目标 | A3DObject | 在何对象上创建绑定点。 |
| propName | 字符串 | 属性的名称。 |
| 创建 | boolean | 如果设置为 |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| 名称 | 描述 |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | 获取给定属性和通道上的关键帧序列。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 目标 | A3DObject | 在何实例上创建关键帧序列。 |
| propName | 字符串 | 属性的名称。 |
| channelName | 字符串 | 通道的名称。 |
| 创建 | boolean | 如果设置为 |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| 名称 | 描述 |
| --- | --- |
| getKeyframeSequence(target, propName, create) | 获取给定属性上的关键帧序列。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 目标 | A3DObject | 在何实例上创建关键帧序列。 |
| propName | 字符串 | 属性的名称。 |
| 创建 | boolean | 如果设置为 |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| 名称 | 描述 |
| --- | --- |
| createBindPoint(obj, propName) | 根据属性数据类型创建一个 BindPoint。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| obj | A3DObject | 对象。 |
| propName | 字符串 | 属性名称。 |

 **Result:**
BindPoint


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



