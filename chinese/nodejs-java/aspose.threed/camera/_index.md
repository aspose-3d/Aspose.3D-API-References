---
title: "Camera"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/camera/
---
## Camera class

camera 描述了观看者注视场景的眼点。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 Camera 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(projectionType) | 初始化 Camera 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(name) | 初始化 Camera 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名称 | 描述 |
| --- | --- |
| constructor_overload3(name, projectionType) | 初始化 Camera 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| 名称 | 描述 |
| --- | --- |
| getApertureMode() | 获取或设置相机的光圈模式。属性的值是 ApertureMode 整数常量。 |

 **Result:**



---


### setApertureMode{#setApertureMode}

| 名称 | 描述 |
| --- | --- |
| setApertureMode(value) | 获取或设置相机的光圈模式。属性的值是 ApertureMode 整数常量。 |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| 名称 | 描述 |
| --- | --- |
| getFieldOfView() | 获取或设置相机的视场角（以度为单位），仅在 ApertureMode 为 ApertureMode.HORIZONTAL 或 ApertureMode.VERTICAL 时使用此属性。 |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| 名称 | 描述 |
| --- | --- |
| setFieldOfView(value) | 获取或设置相机的视场角（以度为单位），仅在 ApertureMode 为 ApertureMode.HORIZONTAL 或 ApertureMode.VERTICAL 时使用此属性。 |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| 名称 | 描述 |
| --- | --- |
| getFieldOfViewX() | 获取或设置相机的水平视场角（以度为单位），仅在 ApertureMode 为 ApertureMode.HORIZ_AND_VERT 时使用此属性。 |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| 名称 | 描述 |
| --- | --- |
| setFieldOfViewX(value) | 获取或设置相机的水平视场角（以度为单位），仅在 ApertureMode 为 ApertureMode.HORIZ_AND_VERT 时使用此属性。 |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| 名称 | 描述 |
| --- | --- |
| getFieldOfViewY() | 获取或设置相机的垂直视场角（以度为单位），仅在 ApertureMode 为 ApertureMode.HORIZ_AND_VERT 时使用此属性。 |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| 名称 | 描述 |
| --- | --- |
| setFieldOfViewY(value) | 获取或设置相机的垂直视场角（以度为单位），仅在 ApertureMode 为 ApertureMode.HORIZ_AND_VERT 时使用此属性。 |

 **Result:**



---


### getWidth{#getWidth}

| 名称 | 描述 |
| --- | --- |
| getWidth() | 获取或设置视平面的宽度（以英寸为单位） |

 **Result:**



---


### setWidth{#setWidth}

| 名称 | 描述 |
| --- | --- |
| setWidth(value) | 获取或设置视平面的宽度（以英寸为单位） |

 **Result:**



---


### getHeight{#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight() | 获取或设置视平面的高度（以英寸为单位） |

 **Result:**



---


### setHeight{#setHeight}

| 名称 | 描述 |
| --- | --- |
| setHeight(value) | 获取或设置视平面的高度（以英寸为单位） |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| 名称 | 描述 |
| --- | --- |
| getAspectRatio() | 获取或设置视平面的宽高比。 |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| 名称 | 描述 |
| --- | --- |
| setAspectRatio(value) | 获取或设置视平面的宽高比。 |

 **Result:**



---


### getMagnification{#getMagnification}

| 名称 | 描述 |
| --- | --- |
| getMagnification() | 获取或设置正交相机使用的放大倍率。 |

 **Result:**



---


### setMagnification{#setMagnification}

| 名称 | 描述 |
| --- | --- |
| setMagnification(value) | 获取或设置正交相机使用的放大倍率。 |

 **Result:**



---


### getProjectionType{#getProjectionType}

| 名称 | 描述 |
| --- | --- |
| getProjectionType() | 获取或设置相机的投影类型。默认使用透视投影。属性的值是 ProjectionType 整数常量。 |

 **Result:**



---


### setProjectionType{#setProjectionType}

| 名称 | 描述 |
| --- | --- |
| setProjectionType(value) | 获取或设置相机的投影类型。默认使用透视投影。属性的值是 ProjectionType 整数常量。 |

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


### moveForward{#moveForward}

| 名称 | 描述 |
| --- | --- |
| moveForward(distance) | 将相机向其方向或目标前进。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| distance | 数字 | 前进的距离 |

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



