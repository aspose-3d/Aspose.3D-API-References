---
title: "Bone"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/bone/
---
## Bone class

bone 定义了几何体控制点的子集，并为每个控制点定义了混合权重。Bone 对象不能直接使用，需使用 SkinDeformer 实例来变形几何体，SkinDeformer 附带一组 bones，每个 bone 链接到一个节点。注意：几何体的控制点可以绑定到多个 Bones。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(name) | 初始化 Bone 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload() | 初始化 Bone 类的新实例。 |

 **Result:**



---


### getWeightCount{#getWeightCount}

| 名称 | 描述 |
| --- | --- |
| getWeightCount() | 获取权重计数，此计数会在调用 setWeight(int, double) 时自动扩展 |

 **Result:**



---


### getTransform{#getTransform}

| 名称 | 描述 |
| --- | --- |
| getTransform() | 获取或设置包含骨骼的节点的变换矩阵。 |

 **Result:**



---


### setTransform{#setTransform}

| 名称 | 描述 |
| --- | --- |
| setTransform(value) | 获取或设置包含骨骼的节点的变换矩阵。 |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| 名称 | 描述 |
| --- | --- |
| getBoneTransform() | 获取或设置骨骼的变换矩阵。 |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| 名称 | 描述 |
| --- | --- |
| setBoneTransform(value) | 获取或设置骨骼的变换矩阵。 |

 **Result:**



---


### getNode{#getNode}

| 名称 | 描述 |
| --- | --- |
| getNode() | 获取或设置节点。骨骼节点是皮肤附着的骨骼，SkinDeformer 将使用骨骼节点来影响控制点的位移。骨骼节点通常会附加一个 Skeleton，但这不是必需的。附加的 Skeleton 通常由 DCC 软件用于向用户显示骨架。 |

 **Result:**



---


### setNode{#setNode}

| 名称 | 描述 |
| --- | --- |
| setNode(value) | 获取或设置节点。骨骼节点是皮肤附着的骨骼，SkinDeformer 将使用骨骼节点来影响控制点的位移。骨骼节点通常会附加一个 Skeleton，但这不是必需的。附加的 Skeleton 通常由 DCC 软件用于向用户显示骨架。 |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| 名称 | 描述 |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| 名称 | 描述 |
| --- | --- |
| getWeight(index) | 获取指定索引的控制点的权重 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | 数字 | 控制点索引 |

 **Result:**
数字


---


### setWeight{#setWeight}

| 名称 | 描述 |
| --- | --- |
| setWeight(index, weight) | 设置指定索引的控制点的权重 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | 数字 | 控制点索引 |
| 权重 | 数字 | 新权重 |

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



