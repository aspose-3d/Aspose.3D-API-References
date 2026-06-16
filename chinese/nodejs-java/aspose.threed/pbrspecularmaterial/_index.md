---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

基于漫反射颜色/高光/光泽度的物理渲染材质


## 属性

| 名称 | 描述 |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | 用于镜面光泽的纹理贴图 |

## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | PbrSpecularMaterial 的构造函数 |

 **Result:**



---


### getTransparency{#getTransparency}

| 名称 | 描述 |
| --- | --- |
| getTransparency() | 获取或设置透明度因子。该因子的取值范围应在 0（0%，完全不透明）和 1（100%，完全透明）之间。任何无效的因子值将被限制。透明度因子。 |

 **Result:**



---


### setTransparency{#setTransparency}

| 名称 | 描述 |
| --- | --- |
| setTransparency(value) | 获取或设置透明度因子。该因子的取值范围应在 0（0%，完全不透明）和 1（100%，完全透明）之间。任何无效的因子值将被限制。透明度因子。 |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| 名称 | 描述 |
| --- | --- |
| getNormalTexture() | 获取或设置法线映射的纹理 |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| 名称 | 描述 |
| --- | --- |
| setNormalTexture(value) | 获取或设置法线映射的纹理 |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| 名称 | 描述 |
| --- | --- |
| getSpecularGlossinessTexture() | 获取或设置用于高光颜色的纹理，RGB 通道存储高光颜色，A 通道存储光泽度。 |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| 名称 | 描述 |
| --- | --- |
| setSpecularGlossinessTexture(value) | 获取或设置用于高光颜色的纹理，RGB 通道存储高光颜色，A 通道存储光泽度。 |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| 名称 | 描述 |
| --- | --- |
| getGlossinessFactor() | 获取或设置材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，取值范围为 [0, 1] |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| 名称 | 描述 |
| --- | --- |
| setGlossinessFactor(value) | 获取或设置材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，取值范围为 [0, 1] |

 **Result:**



---


### getSpecular{#getSpecular}

| 名称 | 描述 |
| --- | --- |
| getSpecular() | 获取或设置材质的高光颜色，默认值为 (1, 1, 1)。 |

 **Result:**



---


### setSpecular{#setSpecular}

| 名称 | 描述 |
| --- | --- |
| setSpecular(value) | 获取或设置材质的高光颜色，默认值为 (1, 1, 1)。 |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| 名称 | 描述 |
| --- | --- |
| getDiffuseTexture() | 获取或设置漫反射纹理 |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| 名称 | 描述 |
| --- | --- |
| setDiffuseTexture(value) | 获取或设置漫反射纹理 |

 **Result:**



---


### getDiffuse{#getDiffuse}

| 名称 | 描述 |
| --- | --- |
| getDiffuse() | 获取或设置材质的漫反射颜色，默认值为 (1, 1, 1) |

 **Result:**



---


### setDiffuse{#setDiffuse}

| 名称 | 描述 |
| --- | --- |
| setDiffuse(value) | 获取或设置材质的漫反射颜色，默认值为 (1, 1, 1) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| 名称 | 描述 |
| --- | --- |
| getEmissiveTexture() | 获取或设置自发光纹理 |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| 名称 | 描述 |
| --- | --- |
| setEmissiveTexture(value) | 获取或设置自发光纹理 |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| 名称 | 描述 |
| --- | --- |
| getEmissiveColor() | 获取或设置自发光颜色，默认值为 (0, 0, 0) |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 名称 | 描述 |
| --- | --- |
| setEmissiveColor(value) | 获取或设置自发光颜色，默认值为 (0, 0, 0) |

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



