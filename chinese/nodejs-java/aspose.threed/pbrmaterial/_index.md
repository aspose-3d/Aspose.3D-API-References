---
title: "PbrMaterial"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pbrmaterial/
---
## PbrMaterial class

基于 albedo 颜色/金属度/粗糙度的物理渲染材质


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 构造默认的 PBR 材质实例 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(albedo) | 使用指定的 albedo 颜色值构造默认的 PBR 材质。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| albedo | Vector3 | 默认的 albedo 颜色值 |

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


### getSpecularTexture{#getSpecularTexture}

| 名称 | 描述 |
| --- | --- |
| getSpecularTexture() | 获取或设置高光颜色的纹理 |

 **Result:**



---


### setSpecularTexture{#setSpecularTexture}

| 名称 | 描述 |
| --- | --- |
| setSpecularTexture(value) | 获取或设置高光颜色的纹理 |

 **Result:**



---


### getAlbedoTexture{#getAlbedoTexture}

| 名称 | 描述 |
| --- | --- |
| getAlbedoTexture() | 获取或设置 albedo 的纹理 |

 **Result:**



---


### setAlbedoTexture{#setAlbedoTexture}

| 名称 | 描述 |
| --- | --- |
| setAlbedoTexture(value) | 获取或设置 albedo 的纹理 |

 **Result:**



---


### getAlbedo{#getAlbedo}

| 名称 | 描述 |
| --- | --- |
| getAlbedo() | 获取或设置材质的基础颜色 |

 **Result:**



---


### setAlbedo{#setAlbedo}

| 名称 | 描述 |
| --- | --- |
| setAlbedo(value) | 获取或设置材质的基础颜色 |

 **Result:**



---


### getOcclusionTexture{#getOcclusionTexture}

| 名称 | 描述 |
| --- | --- |
| getOcclusionTexture() | 获取或设置环境遮蔽的纹理 |

 **Result:**



---


### setOcclusionTexture{#setOcclusionTexture}

| 名称 | 描述 |
| --- | --- |
| setOcclusionTexture(value) | 获取或设置环境遮蔽的纹理 |

 **Result:**



---


### getOcclusionFactor{#getOcclusionFactor}

| 名称 | 描述 |
| --- | --- |
| getOcclusionFactor() | 获取或设置环境光遮蔽因子 |

 **Result:**



---


### setOcclusionFactor{#setOcclusionFactor}

| 名称 | 描述 |
| --- | --- |
| setOcclusionFactor(value) | 获取或设置环境光遮蔽因子 |

 **Result:**



---


### getMetallicFactor{#getMetallicFactor}

| 名称 | 描述 |
| --- | --- |
| getMetallicFactor() | 获取或设置材料的金属度，值为 1 表示材料是金属，值为 0 表示材料是介电体。 |

 **Result:**



---


### setMetallicFactor{#setMetallicFactor}

| 名称 | 描述 |
| --- | --- |
| setMetallicFactor(value) | 获取或设置材料的金属度，值为 1 表示材料是金属，值为 0 表示材料是介电体。 |

 **Result:**



---


### getRoughnessFactor{#getRoughnessFactor}

| 名称 | 描述 |
| --- | --- |
| getRoughnessFactor() | 获取或设置材料的粗糙度，值为 1 表示材料完全粗糙，值为 0 表示材料完全光滑。 |

 **Result:**



---


### setRoughnessFactor{#setRoughnessFactor}

| 名称 | 描述 |
| --- | --- |
| setRoughnessFactor(value) | 获取或设置材料的粗糙度，值为 1 表示材料完全粗糙，值为 0 表示材料完全光滑。 |

 **Result:**



---


### getMetallicRoughness{#getMetallicRoughness}

| 名称 | 描述 |
| --- | --- |
| getMetallicRoughness() | 获取或设置金属度（R 通道）和粗糙度（G 通道）的纹理 |

 **Result:**



---


### setMetallicRoughness{#setMetallicRoughness}

| 名称 | 描述 |
| --- | --- |
| setMetallicRoughness(value) | 获取或设置金属度（R 通道）和粗糙度（G 通道）的纹理 |

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
| getEmissiveColor() | 获取或设置自发光颜色 |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 名称 | 描述 |
| --- | --- |
| setEmissiveColor(value) | 获取或设置自发光颜色 |

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


### fromMaterial{#fromMaterial}

| 名称 | 描述 |
| --- | --- |
| fromMaterial(material) | 允许将其他材料转换为 PbrMaterial |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 物质 | 材质 | null |

 **Result:**
PbrMaterial


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



