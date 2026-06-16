---
title: "Scene"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/scene/
---
## Scene class

场景是一个顶层对象，包含节点、几何体、材质、纹理、动画、姿态、子场景等。 场景可以拥有子场景，在 collada/blender/fbx 等文件中充当多文档支持。 可以通过 RootNodeLibrary 访问节点层次结构，RootNodeLibrary 用于在序列化期间保存未关联对象的引用（如元数据或自定义对象），以便将其用作库。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 Scene 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(entity) | 初始化 Scene 类的新实例，并将实体附加到新节点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 实体 | 实体 | 附加到场景的初始实体 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(parentScene, name) | 初始化 Scene 类的新实例作为子场景。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| parentScene | Scene | 父场景。 |
| name | 字符串 | Scene 的名称。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名称 | 描述 |
| --- | --- |
| constructor_overload3(fileName) | 初始化 Scene 类的新实例并立即打开文件。此构造函数已过时，请使用 #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken)。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 要打开的 File 名称。 |

 **Result:**



---


### getSubScenes{#getSubScenes}

| 名称 | 描述 |
| --- | --- |
| getSubScenes() | 获取所有子场景 |

 **Result:**



---


### getLibrary{#getLibrary}

| 名称 | 描述 |
| --- | --- |
| getLibrary() | 未直接在场景层次结构中使用的对象可以在 Library 中定义。当使用子场景并将可重用组件放在子场景下时，这非常有用。 |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| 名称 | 描述 |
| --- | --- |
| getAnimationClips() | 获取场景中定义的所有 AnimationClip。 |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| 名称 | 描述 |
| --- | --- |
| getCurrentAnimationClip() | 获取或设置活动的 AnimationClip |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| 名称 | 描述 |
| --- | --- |
| setCurrentAnimationClip(value) | 获取或设置活动的 AnimationClip |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| 名称 | 描述 |
| --- | --- |
| getAssetInfo() | 获取或设置顶层资产信息（文档信息）。 |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| 名称 | 描述 |
| --- | --- |
| setAssetInfo(value) | 获取或设置顶层资产信息（文档信息）。 |

 **Result:**



---


### getPoses{#getPoses}

| 名称 | 描述 |
| --- | --- |
| getPoses() | 获取此场景中使用的所有 Pose。Pose。 |

 **Result:**



---


### getRootNode{#getRootNode}

| 名称 | 描述 |
| --- | --- |
| getRootNode() | 获取场景的根节点。根节点。 |

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


### getAnimationClip{#getAnimationClip}

| 名称 | 描述 |
| --- | --- |
| getAnimationClip(name) | 获取已命名的 AnimationClip |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 该 |

 **Result:**
AnimationClip


---


### clear{#clear}

| 名称 | 描述 |
| --- | --- |
| clear() | 清除场景内容并恢复默认设置。 |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| 名称 | 描述 |
| --- | --- |
| createAnimationClip(name) | 一个用于创建和注册 AnimationClip 的简写函数，第一个 AnimationClip 将被分配给 CurrentAnimationClip。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | Animation clip 的名称 |

 **Result:**
AnimationClip


---


### open{#open}

| 名称 | 描述 |
| --- | --- |
| open(fileName, options) | 使用指定的文件格式从给定路径打开场景。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| options | LoadOptions | 打开流的更详细配置。 |

 **Result:**
AnimationClip


---


### open{#open}

| 名称 | 描述 |
| --- | --- |
| open(fileName) | 从给定路径打开场景 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| 名称 | 描述 |
| --- | --- |
| fromFile(fileName) | 从给定路径打开场景 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |

 **Result:**
AnimationClip


---


### save{#save}

| 名称 | 描述 |
| --- | --- |
| save(fileName) | 使用指定的文件格式将场景保存到指定路径。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |

 **Result:**
AnimationClip


---


### save{#save}

| 名称 | 描述 |
| --- | --- |
| save(fileName, format) | 使用指定的文件格式将场景保存到指定路径。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| format | 文件格式 | 格式。 |

 **Result:**
AnimationClip


---


### save{#save}

| 名称 | 描述 |
| --- | --- |
| save(fileName, options) | 使用指定的文件格式将场景保存到指定路径。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| options | SaveOptions | 保存流的更详细配置。 |

 **Result:**
AnimationClip


---


### render{#render}

| 名称 | 描述 |
| --- | --- |
| render(camera, fileName) | 从给定 camera 的视角将场景渲染到外部文件。默认输出尺寸为 1024x768，输出格式为 png。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| camera | Camera | 从哪个 camera 的视角渲染场景 |
| fileName | 字符串 | 输出文件的文件名 |

 **Result:**
AnimationClip


---


### render{#render}

| 名称 | 描述 |
| --- | --- |
| render(camera, fileName, size, format) | 从给定 camera 的视角将场景渲染到外部文件。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| camera | Camera | 从哪个 camera 的视角渲染场景 |
| fileName | 字符串 | 输出文件的文件名 |
| size | Vector2 | 最终渲染图像的尺寸 |
| format | 字符串 | 输出文件的图像格式 |

 **Result:**
AnimationClip


---


### render{#render}

| 名称 | 描述 |
| --- | --- |
| render(camera, fileName, size, format, options) | 从给定 camera 的视角将场景渲染到外部文件。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| camera | Camera | 从哪个 camera 的视角渲染场景 |
| fileName | 字符串 | 输出文件的文件名 |
| size | Vector2 | 最终渲染图像的尺寸 |
| format | 字符串 | 输出文件的图像格式 |
| options | ImageRenderOptions | 用于自定义某些内部设置的选项。 |

 **Result:**
AnimationClip


---


### render{#render}

| 名称 | 描述 |
| --- | --- |
| render(camera, bitmap) | 从给定相机的视角将场景渲染为位图。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| camera | Camera | 从哪个 camera 的视角渲染场景 |
| bitmap | TextureData | 渲染结果的目标 |

 **Result:**
AnimationClip


---


### render{#render}

| 名称 | 描述 |
| --- | --- |
| render(camera, bitmap, options) | 从给定相机的视角将场景渲染为位图。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| camera | Camera | 从哪个 camera 的视角渲染场景 |
| bitmap | TextureData | 渲染结果的目标 |
| options | ImageRenderOptions | 用于自定义某些内部设置的选项。 |

 **Result:**
AnimationClip


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



