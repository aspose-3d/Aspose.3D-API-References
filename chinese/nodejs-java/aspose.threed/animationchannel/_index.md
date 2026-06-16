---
title: "AnimationChannel"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/animationchannel/
---
## AnimationChannel class

通道将属性的组件字段映射到一组关键帧序列  @hideconstructor


## 方法

### getComponentType{#getComponentType}

| 名称 | 描述 |
| --- | --- |
| getComponentType() | 获取组件字段的类型 |

 **Result:**



---


### getName{#getName}

| 名称 | 描述 |
| --- | --- |
| getName() | 获取通道的名称 |

 **Result:**



---


### getDefaultValue{#getDefaultValue}

| 名称 | 描述 |
| --- | --- |
| getDefaultValue() | 获取或设置通道的默认值。如果通道没有连接关键帧序列，则在动画评估期间将使用默认值。实际场景：动画仅对节点的 x 坐标进行动画，而 y 和 z 未改变，则在完整平移评估期间将使用默认值。 |

 **Result:**



---


### setDefaultValue{#setDefaultValue}

| 名称 | 描述 |
| --- | --- |
| setDefaultValue(value) | 获取或设置通道的默认值。如果通道没有连接关键帧序列，则在动画评估期间将使用默认值。实际场景：动画仅对节点的 x 坐标进行动画，而 y 和 z 未改变，则在完整平移评估期间将使用默认值。 |

 **Result:**



---


### getKeyframeSequences{#getKeyframeSequences}

| 名称 | 描述 |
| --- | --- |
| getKeyframeSequences() | 获取此通道内的所有关键帧序列 |

 **Result:**



---


### addKeyframeSequence{#addKeyframeSequence}

| 名称 | 描述 |
| --- | --- |
| addKeyframeSequence(sequence) | 向此通道添加关键帧序列 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 序列 | KeyframeSequence | 要添加的关键帧序列。 |

 **Result:**



---


### iterator{#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator() | 保留供内部使用。 |

 **Result:**



---



