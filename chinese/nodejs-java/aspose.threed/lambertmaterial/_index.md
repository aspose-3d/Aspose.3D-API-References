---
title: "LambertMaterial"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Lambert 着色模型的材质


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 LambertMaterial 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(name) | 初始化 LambertMaterial 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| 名称 | 描述 |
| --- | --- |
| getEmissiveColor() | 获取或设置自发光颜色 |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 名称 | 描述 |
| --- | --- |
| setEmissiveColor(value) | 获取或设置自发光颜色 |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| 名称 | 描述 |
| --- | --- |
| getAmbientColor() | 获取或设置环境光颜色 示例：var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| 名称 | 描述 |
| --- | --- |
| setAmbientColor(value) | 获取或设置环境光颜色 示例：var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| 名称 | 描述 |
| --- | --- |
| getDiffuseColor() | 获取或设置漫反射颜色 示例：var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); 漫反射。 |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| 名称 | 描述 |
| --- | --- |
| setDiffuseColor(value) | 获取或设置漫反射颜色 示例：var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); 漫反射。 |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| 名称 | 描述 |
| --- | --- |
| getTransparentColor() | 获取或设置透明颜色。 示例：var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); 透明颜色。 |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| 名称 | 描述 |
| --- | --- |
| setTransparentColor(value) | 获取或设置透明颜色。 示例：var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); 透明颜色。 |

 **Result:**



---


### getTransparency{#getTransparency}

| 名称 | 描述 |
| --- | --- |
| getTransparency() | 获取或设置透明度因子。 该因子应在 0（0%，完全不透明） 与 1（100%，完全透明） 之间取值，任何无效的因子值将被限制。 示例：var mat = new LambertMaterial(); mat.Transparency = 0.3; 透明度因子。 |

 **Result:**



---


### setTransparency{#setTransparency}

| 名称 | 描述 |
| --- | --- |
| setTransparency(value) | 获取或设置透明度因子。 该因子应在 0（0%，完全不透明） 与 1（100%，完全透明） 之间取值，任何无效的因子值将被限制。 示例：var mat = new LambertMaterial(); mat.Transparency = 0.3; 透明度因子。 |

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



