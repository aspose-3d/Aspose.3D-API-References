---
title: "ShaderMaterial"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

着色器材质允许通过外部渲染引擎或着色器语言来描述材质。ShaderMaterial 使用 ShaderTechnique 来描述具体的渲染细节，并且会根据最终渲染平台选择最合适的实现。例如，您的 ShaderMaterial 实例可以拥有两种 technique，一种由 HLSL 定义，另一种由 GLSL 定义。在非 Windows 平台下应使用 GLSL 而不是 HLSL。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 ShaderMaterial 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(name) | 初始化 ShaderMaterial 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### getTechniques{#getTechniques}

| 名称 | 描述 |
| --- | --- |
| getTechniques() | 获取此材料中定义的所有可用技术。 |

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


### getTexture{#getTexture}

| 名称 | 描述 |
| --- | --- |
| getTexture(slotName) | 获取指定槽位的纹理，它可以是材质的属性名称或着色器的参数名称 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slotName | 字符串 | 槽位名称。 |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| 名称 | 描述 |
| --- | --- |
| setTexture(slotName, texture) | 将纹理设置到指定槽位 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slotName | 字符串 | 槽位名称。 |
| texture | TextureBase | 纹理。 |

 **Result:**
TextureBase


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


### iterator{#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator() | 保留供内部使用。 |

 **Result:**
Property


---



