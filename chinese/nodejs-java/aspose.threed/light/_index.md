---
title: "Light"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/light/
---
## Light class

光照亮场景。计算光总衰减的公式为：A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 Light 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(name) | 初始化 Light 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(name, type) | 初始化 Light 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |
| 类型 | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| 名称 | 描述 |
| --- | --- |
| getColor() | 获取或设置光源的颜色 |

 **Result:**



---


### setColor{#setColor}

| 名称 | 描述 |
| --- | --- |
| setColor(value) | 获取或设置光源的颜色 |

 **Result:**



---


### getLightType{#getLightType}

| 名称 | 描述 |
| --- | --- |
| getLightType() | 获取或设置光源的类型。属性值为 LightType 整数常量。 |

 **Result:**



---


### setLightType{#setLightType}

| 名称 | 描述 |
| --- | --- |
| setLightType(value) | 获取或设置光源的类型。属性值为 LightType 整数常量。 |

 **Result:**



---


### getCastLight{#getCastLight}

| 名称 | 描述 |
| --- | --- |
| getCastLight() | 获取或设置当前光源实例是否可以照亮其他对象。 |

 **Result:**



---


### setCastLight{#setCastLight}

| 名称 | 描述 |
| --- | --- |
| setCastLight(value) | 获取或设置当前光源实例是否可以照亮其他对象。 |

 **Result:**



---


### getIntensity{#getIntensity}

| 名称 | 描述 |
| --- | --- |
| getIntensity() | 获取或设置光源的强度，默认值为 100。 |

 **Result:**



---


### setIntensity{#setIntensity}

| 名称 | 描述 |
| --- | --- |
| setIntensity(value) | 获取或设置光源的强度，默认值为 100。 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| 名称 | 描述 |
| --- | --- |
| getHotSpot() | 获取或设置热点锥形角度（以度为单位）。 |

 **Result:**



---


### setHotSpot{#setHotSpot}

| 名称 | 描述 |
| --- | --- |
| setHotSpot(value) | 获取或设置热点锥形角度（以度为单位）。 |

 **Result:**



---


### getFalloff{#getFalloff}

| 名称 | 描述 |
| --- | --- |
| getFalloff() | 获取或设置衰减锥形角度（以度为单位）。 |

 **Result:**



---


### setFalloff{#setFalloff}

| 名称 | 描述 |
| --- | --- |
| setFalloff(value) | 获取或设置衰减锥形角度（以度为单位）。 |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| 名称 | 描述 |
| --- | --- |
| getConstantAttenuation() | 获取或设置常数衰减，以计算光的总衰减 |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| 名称 | 描述 |
| --- | --- |
| setConstantAttenuation(value) | 获取或设置常数衰减，以计算光的总衰减 |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| 名称 | 描述 |
| --- | --- |
| getLinearAttenuation() | 获取或设置线性衰减，以计算光的总衰减 |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| 名称 | 描述 |
| --- | --- |
| setLinearAttenuation(value) | 获取或设置线性衰减，以计算光的总衰减 |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| 名称 | 描述 |
| --- | --- |
| getQuadraticAttenuation() | 获取或设置二次衰减，以计算光的总衰减 |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| 名称 | 描述 |
| --- | --- |
| setQuadraticAttenuation(value) | 获取或设置二次衰减，以计算光的总衰减 |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 名称 | 描述 |
| --- | --- |
| getCastShadows() | 获取或设置光是否可以在其他对象上投射阴影。 |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 名称 | 描述 |
| --- | --- |
| setCastShadows(value) | 获取或设置光是否可以在其他对象上投射阴影。 |

 **Result:**



---


### getShadowColor{#getShadowColor}

| 名称 | 描述 |
| --- | --- |
| getShadowColor() | 获取或设置阴影的颜色。 |

 **Result:**



---


### setShadowColor{#setShadowColor}

| 名称 | 描述 |
| --- | --- |
| setShadowColor(value) | 获取或设置阴影的颜色。 |

 **Result:**



---


### getRotationMode{#getRotationMode}

| 名称 | 描述 |
| --- | --- |
| getRotationMode() | 获取或设置视锥体的方向模式。此属性仅在 Target 为 null 时有效。如果值为 RotationMode.FIXED_TARGET，则方向始终由属性 LookAt 计算；否则 LookAt 始终由 Direction 计算。该属性的值是 RotationMode 整数常量。 |

 **Result:**



---


### setRotationMode{#setRotationMode}

| 名称 | 描述 |
| --- | --- |
| setRotationMode(value) | 获取或设置视锥体的方向模式。此属性仅在 Target 为 null 时有效。如果值为 RotationMode.FIXED_TARGET，则方向始终由属性 LookAt 计算；否则 LookAt 始终由 Direction 计算。该属性的值是 RotationMode 整数常量。 |

 **Result:**



---


### getNearPlane{#getNearPlane}

| 名称 | 描述 |
| --- | --- |
| getNearPlane() | 获取或设置视锥体的近裁剪面距离。 |

 **Result:**



---


### setNearPlane{#setNearPlane}

| 名称 | 描述 |
| --- | --- |
| setNearPlane(value) | 获取或设置视锥体的近裁剪面距离。 |

 **Result:**



---


### getFarPlane{#getFarPlane}

| 名称 | 描述 |
| --- | --- |
| getFarPlane() | 获取或设置视锥体的远平面距离。 |

 **Result:**



---


### setFarPlane{#setFarPlane}

| 名称 | 描述 |
| --- | --- |
| setFarPlane(value) | 获取或设置视锥体的远平面距离。 |

 **Result:**



---


### getAspect{#getAspect}

| 名称 | 描述 |
| --- | --- |
| getAspect() | 获取或设置视锥体的宽高比 |

 **Result:**



---


### setAspect{#setAspect}

| 名称 | 描述 |
| --- | --- |
| setAspect(value) | 获取或设置视锥体的宽高比 |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| 名称 | 描述 |
| --- | --- |
| getOrthoHeight() | 获取或设置视锥体在正交投影时的高度。 |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| 名称 | 描述 |
| --- | --- |
| setOrthoHeight(value) | 获取或设置视锥体在正交投影时的高度。 |

 **Result:**



---


### getUp{#getUp}

| 名称 | 描述 |
| --- | --- |
| getUp() | 获取或设置相机的上方向 |

 **Result:**



---


### setUp{#setUp}

| 名称 | 描述 |
| --- | --- |
| setUp(value) | 获取或设置相机的上方向 |

 **Result:**



---


### getLookAt{#getLookAt}

| 名称 | 描述 |
| --- | --- |
| getLookAt() | 获取或设置相机所关注的位置。 |

 **Result:**



---


### setLookAt{#setLookAt}

| 名称 | 描述 |
| --- | --- |
| setLookAt(value) | 获取或设置相机所关注的位置。 |

 **Result:**



---


### getDirection{#getDirection}

| 名称 | 描述 |
| --- | --- |
| getDirection() | 获取或设置相机的观察方向。对该属性的更改还会影响 LookAt 和 Target。 |

 **Result:**



---


### setDirection{#setDirection}

| 名称 | 描述 |
| --- | --- |
| setDirection(value) | 获取或设置相机的观察方向。对该属性的更改还会影响 LookAt 和 Target。 |

 **Result:**



---


### getTarget{#getTarget}

| 名称 | 描述 |
| --- | --- |
| getTarget() | 获取或设置相机所看的目标。如果用户支持此属性，应在 LookAt 属性之前使用。 |

 **Result:**



---


### setTarget{#setTarget}

| 名称 | 描述 |
| --- | --- |
| setTarget(value) | 获取或设置相机所看的目标。如果用户支持此属性，应在 LookAt 属性之前使用。 |

 **Result:**



---


### getParentNodes{#getParentNodes}

| 名称 | 描述 |
| --- | --- |
| getParentNodes() | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化。 |

 **Result:**



---


### getExcluded{#getExcluded}

| 名称 | 描述 |
| --- | --- |
| getExcluded() | 获取或设置在导出期间是否排除此实体。 |

 **Result:**



---


### setExcluded{#setExcluded}

| 名称 | 描述 |
| --- | --- |
| setExcluded(value) | 获取或设置在导出期间是否排除此实体。 |

 **Result:**



---


### getParentNode{#getParentNode}

| 名称 | 描述 |
| --- | --- |
| getParentNode() | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。父节点。 |

 **Result:**



---


### setParentNode{#setParentNode}

| 名称 | 描述 |
| --- | --- |
| setParentNode(value) | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。父节点。 |

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


### getBoundingBox{#getBoundingBox}

| 名称 | 描述 |
| --- | --- |
| getBoundingBox() | 获取当前实体在其对象空间坐标系中的边界框。 |

 **Result:**



---


### getEntityRendererKey{#getEntityRendererKey}

| 名称 | 描述 |
| --- | --- |
| getEntityRendererKey() | 获取在渲染器中注册的实体渲染器的键 |

 **Result:**
EntityRendererKey


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



