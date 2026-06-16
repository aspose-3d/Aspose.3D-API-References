---
title: "圆柱体"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

参数化圆柱体。当 radiusTop/radiusBottom 为零时，它也可用于表示圆锥体。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 Cylinder 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(radius, height) | 初始化 Cylinder 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 半径 | 数字 | 顶部和底部盖的半径。 |
| height | 数字 | 高度。 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | 初始化 Cylinder 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| radiusTop | 数字 | 顶部半径。 |
| radiusBottom | 数字 | 底部半径。 |
| height | 数字 | 高度。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名称 | 描述 |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | 初始化 Cylinder 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| radiusTop | 数字 | 圆柱体顶部盖的半径。 |
| radiusBottom | 数字 | 圆柱体底部盖的半径。 |
| height | 数字 | 圆柱体的高度。 |
| radialSegments | 数字 | 顶部和底部圆的径向分段.. |
| heightSegments | 数字 | 高度段。 |
| openEnded | boolean | 如果设置为 |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 名称 | 描述 |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | 初始化 Cylinder 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 此对象的名称 |
| radiusTop | 数字 | 圆柱体顶部盖的半径。 |
| radiusBottom | 数字 | 圆柱体底部盖的半径。 |
| height | 数字 | 圆柱体的高度。 |
| radialSegments | 数字 | 顶部和底部圆的径向分段.. |
| heightSegments | 数字 | 高度段。 |
| openEnded | boolean | 如果设置为 |
| thetaStart | 数字 | Theta 起始。 |
| thetaLength | 数字 | Theta 长度。 |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| 名称 | 描述 |
| --- | --- |
| getOffsetBottom() | 获取或设置底部侧的顶点变换偏移。 |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| 名称 | 描述 |
| --- | --- |
| setOffsetBottom(value) | 获取或设置底部侧的顶点变换偏移。 |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| 名称 | 描述 |
| --- | --- |
| getOffsetTop() | 获取或设置顶部侧的顶点变换偏移。 |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| 名称 | 描述 |
| --- | --- |
| setOffsetTop(value) | 获取或设置顶部侧的顶点变换偏移。 |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| 名称 | 描述 |
| --- | --- |
| getGenerateFanCylinder() | 获取或设置当 ThetaLength 小于 2π 时是否生成扇形圆柱，否则模型将不会被裁剪。 |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| 名称 | 描述 |
| --- | --- |
| setGenerateFanCylinder(value) | 获取或设置当 ThetaLength 小于 2π 时是否生成扇形圆柱，否则模型将不会被裁剪。 |

 **Result:**



---


### getShearBottom{#getShearBottom}

| 名称 | 描述 |
| --- | --- |
| getShearBottom() | 获取或设置底部的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |

 **Result:**



---


### setShearBottom{#setShearBottom}

| 名称 | 描述 |
| --- | --- |
| setShearBottom(value) | 获取或设置底部的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |

 **Result:**



---


### getShearTop{#getShearTop}

| 名称 | 描述 |
| --- | --- |
| getShearTop() | 获取或设置顶部的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |

 **Result:**



---


### setShearTop{#setShearTop}

| 名称 | 描述 |
| --- | --- |
| setShearTop(value) | 获取或设置顶部的剪切变换，向量存储以弧度测量的 (x 轴, z 轴) 剪切值，默认值为 (0, 0)。 |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| 名称 | 描述 |
| --- | --- |
| getRadiusTop() | 获取或设置圆柱顶部盖的半径。顶部盖的半径。 |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| 名称 | 描述 |
| --- | --- |
| setRadiusTop(value) | 获取或设置圆柱顶部盖的半径。顶部盖的半径。 |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| 名称 | 描述 |
| --- | --- |
| getRadiusBottom() | 获取或设置圆柱底部盖的半径。底部盖的半径。 |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| 名称 | 描述 |
| --- | --- |
| setRadiusBottom(value) | 获取或设置圆柱底部盖的半径。底部盖的半径。 |

 **Result:**



---


### getHeight{#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight() | 获取或设置圆柱的高度。高度。 |

 **Result:**



---


### setHeight{#setHeight}

| 名称 | 描述 |
| --- | --- |
| setHeight(value) | 获取或设置圆柱的高度。高度。 |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| 名称 | 描述 |
| --- | --- |
| getRadialSegments() | 获取或设置径向段数。径向段数。 |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| 名称 | 描述 |
| --- | --- |
| setRadialSegments(value) | 获取或设置径向段数。径向段数。 |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| 名称 | 描述 |
| --- | --- |
| getHeightSegments() | 获取或设置高度段。高度段。 |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| 名称 | 描述 |
| --- | --- |
| setHeightSegments(value) | 获取或设置高度段。高度段。 |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| 名称 | 描述 |
| --- | --- |
| getOpenEnded() | 获取或设置一个值，指示此圆柱是否为开放式。默认值为 false。若为开放式则为 true；否则，顶部/底部盖存在。 |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| 名称 | 描述 |
| --- | --- |
| setOpenEnded(value) | 获取或设置一个值，指示此圆柱是否为开放式。默认值为 false。若为开放式则为 true；否则，顶部/底部盖存在。 |

 **Result:**



---


### getThetaStart{#getThetaStart}

| 名称 | 描述 |
| --- | --- |
| getThetaStart() | 获取或设置 theta 起始角度。默认值为 0。theta 起始角度。 |

 **Result:**



---


### setThetaStart{#setThetaStart}

| 名称 | 描述 |
| --- | --- |
| setThetaStart(value) | 获取或设置 theta 起始角度。默认值为 0。theta 起始角度。 |

 **Result:**



---


### getThetaLength{#getThetaLength}

| 名称 | 描述 |
| --- | --- |
| getThetaLength() | 获取或设置 theta 的长度。默认值为 2π。theta 的长度。 |

 **Result:**



---


### setThetaLength{#setThetaLength}

| 名称 | 描述 |
| --- | --- |
| setThetaLength(value) | 获取或设置 theta 的长度。默认值为 2π。theta 的长度。 |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 名称 | 描述 |
| --- | --- |
| getCastShadows() | 获取或设置此几何体是否可以投射阴影。 |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 名称 | 描述 |
| --- | --- |
| setCastShadows(value) | 获取或设置此几何体是否可以投射阴影。 |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| 名称 | 描述 |
| --- | --- |
| getReceiveShadows() | 获取或设置此几何体是否可以接收阴影。 |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| 名称 | 描述 |
| --- | --- |
| setReceiveShadows(value) | 获取或设置此几何体是否可以接收阴影。 |

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


### toMesh{#toMesh}

| 名称 | 描述 |
| --- | --- |
| toMesh() | 将当前对象转换为网格 |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| 名称 | 描述 |
| --- | --- |
| getBoundingBox() | 获取当前实体在其对象空间坐标系中的边界框。 |

 **Result:**
Mesh


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



