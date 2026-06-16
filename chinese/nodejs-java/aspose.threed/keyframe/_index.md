---
title: "KeyFrame"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

关键帧主要由时间和数值定义，对于某些插值类型，还会使用切线/张力/偏差/连续性来计算最终的采样值。非关键帧时间位置的采样值由前后关键帧之间的关键帧进行插值。首个/最后一个关键帧之前或之后的数值由 Extrapolation 类计算。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(curve, time) | 在指定曲线上创建一个新的关键帧 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| curve | KeyframeSequence | 将在其上创建关键帧的曲线 |
| 时间 | 数字 | 关键帧的时间位置 |

 **Result:**



---


### getTime{#getTime}

| 名称 | 描述 |
| --- | --- |
| getTime() | 获取或设置 list.data[index] 关键帧的时间位置，单位为秒。时间。 |

 **Result:**



---


### setTime{#setTime}

| 名称 | 描述 |
| --- | --- |
| setTime(value) | 获取或设置 list.data[index] 关键帧的时间位置，单位为秒。时间。 |

 **Result:**



---


### getValue{#getValue}

| 名称 | 描述 |
| --- | --- |
| getValue() | 获取或设置关键帧的值。值。 |

 **Result:**



---


### setValue{#setValue}

| 名称 | 描述 |
| --- | --- |
| setValue(value) | 获取或设置关键帧的值。值。 |

 **Result:**



---


### getInterpolation{#getInterpolation}

| 名称 | 描述 |
| --- | --- |
| getInterpolation() | 获取或设置关键帧的插值类型，list.data[index] 定义了采样值的计算算法。属性的值是 Interpolation 整数常量。插值。 |

 **Result:**



---


### setInterpolation{#setInterpolation}

| 名称 | 描述 |
| --- | --- |
| setInterpolation(value) | 获取或设置关键帧的插值类型，list.data[index] 定义了采样值的计算算法。属性的值是 Interpolation 整数常量。插值。 |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| 名称 | 描述 |
| --- | --- |
| getTangentWeightMode() | 获取或设置关键帧的切线权重模式。可以通过选择正确的 WeightedMode 来自定义出切线或下一个入切线。属性的值是 WeightedMode 整数常量。切线权重模式。 |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| 名称 | 描述 |
| --- | --- |
| setTangentWeightMode(value) | 获取或设置关键帧的切线权重模式。可以通过选择正确的 WeightedMode 来自定义出切线或下一个入切线。属性的值是 WeightedMode 整数常量。切线权重模式。 |

 **Result:**



---


### getStepMode{#getStepMode}

| 名称 | 描述 |
| --- | --- |
| getStepMode() | 获取或设置关键帧的步进模式。如果插值类型是 Interpolation.CONSTANT，list.data[index] 决定在插值期间使用哪个关键帧的值。StepMode.PREVIOUS_VALUE 表示使用左侧关键帧的值，StepMode.NEXT_VALUE 表示使用右侧下一个关键帧的值。属性的值是 StepMode 整数常量。步进模式。 |

 **Result:**



---


### setStepMode{#setStepMode}

| 名称 | 描述 |
| --- | --- |
| setStepMode(value) | 获取或设置关键帧的步进模式。如果插值类型是 Interpolation.CONSTANT，list.data[index] 决定在插值期间使用哪个关键帧的值。StepMode.PREVIOUS_VALUE 表示使用左侧关键帧的值，StepMode.NEXT_VALUE 表示使用右侧下一个关键帧的值。属性的值是 StepMode 整数常量。步进模式。 |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| 名称 | 描述 |
| --- | --- |
| getNextInTangent() | 获取或设置此关键帧的下一个入（左）切线。 |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| 名称 | 描述 |
| --- | --- |
| setNextInTangent(value) | 获取或设置此关键帧的下一个入（左）切线。 |

 **Result:**



---


### getOutTangent{#getOutTangent}

| 名称 | 描述 |
| --- | --- |
| getOutTangent() | 获取或设置此关键帧的出（右）切线。 |

 **Result:**



---


### setOutTangent{#setOutTangent}

| 名称 | 描述 |
| --- | --- |
| setOutTangent(value) | 获取或设置此关键帧的出（右）切线。 |

 **Result:**



---


### getOutWeight{#getOutWeight}

| 名称 | 描述 |
| --- | --- |
| getOutWeight() | 获取或设置此关键帧的出（右）权重。 |

 **Result:**



---


### setOutWeight{#setOutWeight}

| 名称 | 描述 |
| --- | --- |
| setOutWeight(value) | 获取或设置此关键帧的出（右）权重。 |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| 名称 | 描述 |
| --- | --- |
| getNextInWeight() | 获取或设置此关键帧上的下一个输入（左）权重。 |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| 名称 | 描述 |
| --- | --- |
| setNextInWeight(value) | 获取或设置此关键帧上的下一个输入（左）权重。 |

 **Result:**



---


### getTension{#getTension}

| 名称 | 描述 |
| --- | --- |
| getTension() | 获取或设置在 TCB 样条中使用的张力 |

 **Result:**



---


### setTension{#setTension}

| 名称 | 描述 |
| --- | --- |
| setTension(value) | 获取或设置在 TCB 样条中使用的张力 |

 **Result:**



---


### getContinuity{#getContinuity}

| 名称 | 描述 |
| --- | --- |
| getContinuity() | 获取或设置在 TCB 样条中使用的连续性 |

 **Result:**



---


### setContinuity{#setContinuity}

| 名称 | 描述 |
| --- | --- |
| setContinuity(value) | 获取或设置在 TCB 样条中使用的连续性 |

 **Result:**



---


### getBias{#getBias}

| 名称 | 描述 |
| --- | --- |
| getBias() | 获取或设置在 TCB 样条中使用的偏差 |

 **Result:**



---


### setBias{#setBias}

| 名称 | 描述 |
| --- | --- |
| setBias(value) | 获取或设置在 TCB 样条中使用的偏差 |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| 名称 | 描述 |
| --- | --- |
| getIndependentTangent() | 获取或设置外切线和下一个输入切线为独立。 |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| 名称 | 描述 |
| --- | --- |
| setIndependentTangent(value) | 获取或设置外切线和下一个输入切线为独立。 |

 **Result:**



---


### getFlat{#getFlat}

| 名称 | 描述 |
| --- | --- |
| getFlat() | 获取或设置关键帧是否为平坦。如果下一个或上一个关键帧具有相同的值，则关键帧应为平坦。平坦的关键帧具有平坦的切线和固定的插值。 |

 **Result:**



---


### setFlat{#setFlat}

| 名称 | 描述 |
| --- | --- |
| setFlat(value) | 获取或设置关键帧是否为平坦。如果下一个或上一个关键帧具有相同的值，则关键帧应为平坦。平坦的关键帧具有平坦的切线和固定的插值。 |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| 名称 | 描述 |
| --- | --- |
| getTimeIndependentTangent() | 获取或设置切线为时间无关 |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| 名称 | 描述 |
| --- | --- |
| setTimeIndependentTangent(value) | 获取或设置切线为时间无关 |

 **Result:**



---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 获取关键帧的字符串表示形式 |

 **Result:**
字符串


---



