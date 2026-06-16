---
title: "节点"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/node/
---
## Node class

表示场景图中的一个元素。场景图是由 Node 对象组成的树。树的管理服务封装在此类中。注意，Aspose.3D SDK 不会检查构建的场景图的有效性。调用者有责任确保在节点层次结构中不生成循环图。除了树管理外，此类还定义了描述对象在场景中位置所需的所有属性。这些信息包括基本的 Translation、Rotation 和 Scaling 属性，以及用于枢轴、限制和 IK 关节的更高级选项，如刚度和阻尼。首次创建时，Node 对象是\"empty\"（即：它是一个仅包含位置信息且没有任何图形表示的对象）。在此状态下，它可用于表示节点树结构中的父节点，但功能有限。此类对象的常规用法是为其添加一个实体以专化节点（参见\"Entity\"）。实体本身是一个对象，并连接到 Node。这也意味着同一实体可以在多个节点之间共享。Camera、Light、Mesh 等都是实体，并且它们都派生自基类 Entity。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 Node 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(name, entity) | 初始化 Node 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |
| 实体 | 实体 | 默认实体。 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(name) | 初始化 Node 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| 名称 | 描述 |
| --- | --- |
| getAssetInfo() | 每个节点的资产信息 |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| 名称 | 描述 |
| --- | --- |
| setAssetInfo(value) | 每个节点的资产信息 |

 **Result:**



---


### getVisible{#getVisible}

| 名称 | 描述 |
| --- | --- |
| getVisible() | 获取或设置以显示节点 |

 **Result:**



---


### setVisible{#setVisible}

| 名称 | 描述 |
| --- | --- |
| setVisible(value) | 获取或设置以显示节点 |

 **Result:**



---


### getChildNodes{#getChildNodes}

| 名称 | 描述 |
| --- | --- |
| getChildNodes() | 获取子节点。节点。 |

 **Result:**



---


### getEntity{#getEntity}

| 名称 | 描述 |
| --- | --- |
| getEntity() | 获取或设置附加到此节点的第一个实体，如果设置，将清除其他实体。节点实体。 |

 **Result:**



---


### setEntity{#setEntity}

| 名称 | 描述 |
| --- | --- |
| setEntity(value) | 获取或设置附加到此节点的第一个实体，如果设置，将清除其他实体。节点实体。 |

 **Result:**



---


### getExcluded{#getExcluded}

| 名称 | 描述 |
| --- | --- |
| getExcluded() | 获取或设置是否在导出时排除此节点及所有子节点/实体。 |

 **Result:**



---


### setExcluded{#setExcluded}

| 名称 | 描述 |
| --- | --- |
| setExcluded(value) | 获取或设置是否在导出时排除此节点及所有子节点/实体。 |

 **Result:**



---


### getEntities{#getEntities}

| 名称 | 描述 |
| --- | --- |
| getEntities() | 获取所有节点实体。节点实体。 |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| 名称 | 描述 |
| --- | --- |
| getMetaDatas() | 获取此节点中定义的元数据。元数据。 |

 **Result:**



---


### getMaterials{#getMaterials}

| 名称 | 描述 |
| --- | --- |
| getMaterials() | 获取与此节点关联的材料。材料。 |

 **Result:**



---


### getMaterial{#getMaterial}

| 名称 | 描述 |
| --- | --- |
| getMaterial() | 获取或设置与此节点关联的第一个材料，如果设置，将清除其他材料。材料。 |

 **Result:**



---


### setMaterial{#setMaterial}

| 名称 | 描述 |
| --- | --- |
| setMaterial(value) | 获取或设置与此节点关联的第一个材料，如果设置，将清除其他材料。材料。 |

 **Result:**



---


### getParentNode{#getParentNode}

| 名称 | 描述 |
| --- | --- |
| getParentNode() | 获取或设置父节点。父节点。 |

 **Result:**



---


### setParentNode{#setParentNode}

| 名称 | 描述 |
| --- | --- |
| setParentNode(value) | 获取或设置父节点。父节点。 |

 **Result:**



---


### getTransform{#getTransform}

| 名称 | 描述 |
| --- | --- |
| getTransform() | 获取本地变换。该变换。 |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| 名称 | 描述 |
| --- | --- |
| getGlobalTransform() | 获取全局变换。该全局变换。 |

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


### createChildNode{#createChildNode}

| 名称 | 描述 |
| --- | --- |
| createChildNode() | 创建子节点 |

 **Result:**
节点


---


### merge{#merge}

| 名称 | 描述 |
| --- | --- |
| merge(node) | 分离节点下的所有内容并将它们附加到当前节点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nod | 节点 | null |

 **Result:**
节点


---


### createChildNode{#createChildNode}

| 名称 | 描述 |
| --- | --- |
| createChildNode(nodeName) | 使用给定的节点名称创建一个新的子节点 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 新子节点的名称 |

 **Result:**
节点


---


### createChildNode{#createChildNode}

| 名称 | 描述 |
| --- | --- |
| createChildNode(entity) | 创建一个附带给定实体的新子节点 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 默认附加到节点的实体 |

 **Result:**
节点


---


### createChildNode{#createChildNode}

| 名称 | 描述 |
| --- | --- |
| createChildNode(nodeName, entity) | 使用给定的节点名称创建一个新的子节点 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 新子节点的名称 |
| 实体 | 实体 | 默认附加到节点的实体 |

 **Result:**
节点


---


### createChildNode{#createChildNode}

| 名称 | 描述 |
| --- | --- |
| createChildNode(nodeName, entity, material) | 使用给定的节点名称创建一个新子节点，并附加指定的实体和材质 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 新子节点的名称 |
| 实体 | 实体 | 默认附加到节点的实体 |
| material | 材质 | 附加到节点的材质 |

 **Result:**
节点


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| 名称 | 描述 |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | 评估全局变换，是否包括几何变换。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| withGeometricTransform | boolean | 是否需要几何变换。 |

 **Result:**
Matrix4


---


### getChild{#getChild}

| 名称 | 描述 |
| --- | --- |
| getChild(index) | 获取指定索引处的子节点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | 数字 | 索引。 |

 **Result:**
节点


---


### getChild{#getChild}

| 名称 | 描述 |
| --- | --- |
| getChild(nodeName) | 获取具有指定名称的子节点 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| nodeName | 字符串 | 要查找的子节点名称。 |

 **Result:**
节点


---


### accept{#accept}

| 名称 | 描述 |
| --- | --- |
| accept(visitor) | 遍历所有后代节点（包括当前节点），并使用该节点调用访问者。访问者可以通过返回 false 来中断遍历。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| visitor | NodeVisitor | 访问者回调，用于访问节点 |

 **Result:**
boolean


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 获取此节点的字符串表示。 |

 **Result:**
字符串


---


### getBoundingBox{#getBoundingBox}

| 名称 | 描述 |
| --- | --- |
| getBoundingBox() | 计算节点的边界框 |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| 名称 | 描述 |
| --- | --- |
| addEntity(entity) | 向节点添加实体。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 要附加到节点的实体 |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| 名称 | 描述 |
| --- | --- |
| addChildNode(node) | 向此节点添加子节点 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 要附加的子节点 |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| 名称 | 描述 |
| --- | --- |
| selectSingleObject(path) | 使用类似 XPath 的查询语法在当前节点下选择单个对象。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pat | 字符串 | null |

 **Result:**
对象


---


### selectObjects{#selectObjects}

| 名称 | 描述 |
| --- | --- |
| selectObjects(path) | 使用类似 XPath 的查询语法在当前节点下选择多个对象。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pat | 字符串 | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



