---
title: "AnimationClip"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Animation clip 是动画的集合。场景可以拥有一个或多个 animation clips。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 AnimationClip 类的一个新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(name) | 初始化 AnimationClip 类的一个新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### getAnimations{#getAnimations}

| 名称 | 描述 |
| --- | --- |
| getAnimations() | 获取剪辑中包含的动画。层。 |

 **Result:**



---


### getDescription{#getDescription}

| 名称 | 描述 |
| --- | --- |
| getDescription() | 获取或设置此动画剪辑的描述 |

 **Result:**



---


### setDescription{#setDescription}

| 名称 | 描述 |
| --- | --- |
| setDescription(value) | 获取或设置此动画剪辑的描述 |

 **Result:**



---


### getStart{#getStart}

| 名称 | 描述 |
| --- | --- |
| getStart() | 获取或设置剪辑开始时的时间（秒）。 |

 **Result:**



---


### setStart{#setStart}

| 名称 | 描述 |
| --- | --- |
| setStart(value) | 获取或设置剪辑开始时的时间（秒）。 |

 **Result:**



---


### getStop{#getStop}

| 名称 | 描述 |
| --- | --- |
| getStop() | 获取或设置剪辑结束时的时间（秒）。 |

 **Result:**



---


### setStop{#setStop}

| 名称 | 描述 |
| --- | --- |
| setStop(value) | 获取或设置剪辑结束时的时间（秒）。 |

 **Result:**



---


### getScene{#getScene}

| 名称 | 描述 |
| --- | --- |
| getScene() | 获取此对象所属的场景 |

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


### createAnimationNode{#createAnimationNode}

| 名称 | 描述 |
| --- | --- |
| createAnimationNode(nodeName) | 在当前剪辑上创建并注册动画节点的简写函数。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 新动画节点的名称 |

 **Result:**
AnimationNode


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



