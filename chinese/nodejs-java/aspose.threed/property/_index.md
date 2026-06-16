---
title: "Property"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/property/
---
## Property class

用于保存用户自定义属性的类。  @hideconstructor


## 方法

### getValue{#getValue}

| 名称 | 描述 |
| --- | --- |
| getValue() | 获取或设置该值。该值。 |

 **Result:**



---


### setValue{#setValue}

| 名称 | 描述 |
| --- | --- |
| setValue(value) | 获取或设置该值。该值。 |

 **Result:**



---


### setName{#setName}

| 名称 | 描述 |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| 名称 | 描述 |
| --- | --- |
| getValueType() | 获取属性值的类型。该值的类型。 |

 **Result:**



---


### getProperties{#getProperties}

| 名称 | 描述 |
| --- | --- |
| getProperties() | 获取所有属性的集合。 |

 **Result:**



---


### getBindPoint{#getBindPoint}

| 名称 | 描述 |
| --- | --- |
| getBindPoint(anim, create) | 获取指定动画实例上的属性绑定点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| anim | AnimationNode | 在哪个动画上创建绑定点。 |
| 创建 | boolean | 如果未找到属性绑定点，则创建它。 |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| 名称 | 描述 |
| --- | --- |
| getKeyframeSequence(anim, create) | 获取指定动画实例上的关键帧序列。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| anim | AnimationNode | 在哪个动画上创建关键帧序列。 |
| 创建 | boolean | 如果未找到关键帧序列，则创建它。 |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 返回表示当前属性的字符串。 |

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



