---
title: "BindPoint"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

BindPoint 通常在对象的属性上创建，某些属性类型包含多个组件字段（如 Vector3 字段），BindPoint 将为每个组件字段生成通道，并通过这些通道将字段连接到一个或多个关键帧序列实例。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(scene, prop) | 初始化 BindPoint 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 场景 | Scene | 包含动画的场景。 |
| 属性 | Property | 属性。 |

 **Result:**



---


### getProperty{#getProperty}

| 名称 | 描述 |
| --- | --- |
| getProperty() | 获取与 CurveMapping 关联的属性 |

 **Result:**



---


### setProperty{#setProperty}

| 名称 | 描述 |
| --- | --- |
| setProperty(value) | 获取与 CurveMapping 关联的属性 |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| 名称 | 描述 |
| --- | --- |
| getChannelsCount() | 获取此动画曲线映射中定义的属性通道的总数。 |

 **Result:**
数字


---


### getName{#getName}

| 名称 | 描述 |
| --- | --- |
| getName() | 获取或设置名称。名称。 |

 **Result:**
数字


---


### setName{#setName}

| 名称 | 描述 |
| --- | --- |
| setName(value) | 获取或设置名称。名称。 |

 **Result:**
数字


---


### getProperties{#getProperties}

| 名称 | 描述 |
| --- | --- |
| getProperties() | 获取所有属性的集合。 |

 **Result:**
数字


---


### get{#get}

| 名称 | 描述 |
| --- | --- |
| get(channelName) |  |

 **Result:**
数字


---


### getKeyframeSequence{#getKeyframeSequence}

| 名称 | 描述 |
| --- | --- |
| getKeyframeSequence(channelName) | 获取指定通道中的第一个关键帧序列 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| channelName | 字符串 | 要查找的通道名称 |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| 名称 | 描述 |
| --- | --- |
| getKeyframeSequences(channelName) | 获取指定通道中的所有关键帧序列 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| channelName | 字符串 | 要查找的通道名称 |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| 名称 | 描述 |
| --- | --- |
| createKeyframeSequence(name) | 创建一个新曲线并将其连接到曲线映射的第一个通道 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 新序列的名称。 |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| 名称 | 描述 |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | 将关键帧序列绑定到指定通道 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| channelName | 字符串 | 关键帧序列将绑定到的通道 |
| 序列 | KeyframeSequence | 要绑定的关键帧序列 |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| 名称 | 描述 |
| --- | --- |
| getChannel(channelName) | 根据给定名称获取通道 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| channelName | 字符串 | 要查找的通道名称 |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| 名称 | 描述 |
| --- | --- |
| addChannel(name, value) | 添加指定的通道属性。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |
| 值 | 对象 | 值。 |

 **Result:**
boolean


---


### addChannel{#addChannel}

| 名称 | 描述 |
| --- | --- |
| addChannel(name, type, value) | 添加指定的通道属性。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |
| 类型 | 类 | 类型。 |
| 值 | 对象 | 值。 |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| 名称 | 描述 |
| --- | --- |
| resetChannels() | 清空此动画曲线映射的属性通道。 |

 **Result:**
boolean


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 将对象格式化为字符串 |

 **Result:**
字符串


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



