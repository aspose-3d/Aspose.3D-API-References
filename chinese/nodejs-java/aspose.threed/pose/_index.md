---
title: "姿势"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pose/
---
## Pose class

姿势用于在几何体进行蒙皮时存储变换矩阵。姿势是一组 BonePose，每个 BonePose 保存骨骼节点的具体变换信息。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(name) | 初始化 Pose 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload() | 初始化 Pose 类的新实例。 |

 **Result:**



---


### getPoseType{#getPoseType}

| 名称 | 描述 |
| --- | --- |
| getPoseType() | 获取或设置姿势的类型。属性的值是 PoseType 整数常量。姿势的类型。 |

 **Result:**



---


### setPoseType{#setPoseType}

| 名称 | 描述 |
| --- | --- |
| setPoseType(value) | 获取或设置姿势的类型。属性的值是 PoseType 整数常量。姿势的类型。 |

 **Result:**



---


### getBonePoses{#getBonePoses}

| 名称 | 描述 |
| --- | --- |
| getBonePoses() | 获取所有 BonePose。节点。 |

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


### addBonePose{#addBonePose}

| 名称 | 描述 |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | 保存给定骨骼节点的姿势变换矩阵。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 骨骼节点。 |
| matrix | Matrix4 | 变换矩阵。 |
| localMatrix | boolean | 如果设置为 |

 **Result:**



---


### addBonePose{#addBonePose}

| 名称 | 描述 |
| --- | --- |
| addBonePose(node, matrix) | 为给定的骨骼节点保存姿势变换矩阵。全局变换矩阵是隐含的。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 骨骼节点。 |
| matrix | Matrix4 | 变换矩阵。 |

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



