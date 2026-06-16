---
title: "ShaderTechnique"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/shadertechnique/
---
## ShaderTechnique class

Shader technique 表示具体的渲染实现。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 ShaderTechnique 类的新实例。 |

 **Result:**



---


### getDescription{#getDescription}

| 名称 | 描述 |
| --- | --- |
| getDescription() | 获取或设置此技术的描述 |

 **Result:**



---


### setDescription{#setDescription}

| 名称 | 描述 |
| --- | --- |
| setDescription(value) | 获取或设置此技术的描述 |

 **Result:**



---


### getShaderLanguage{#getShaderLanguage}

| 名称 | 描述 |
| --- | --- |
| getShaderLanguage() | 获取或设置此技术使用的着色器语言。 |

 **Result:**



---


### setShaderLanguage{#setShaderLanguage}

| 名称 | 描述 |
| --- | --- |
| setShaderLanguage(value) | 获取或设置此技术使用的着色器语言。 |

 **Result:**



---


### getShaderVersion{#getShaderVersion}

| 名称 | 描述 |
| --- | --- |
| getShaderVersion() | 获取或设置此技术使用的着色器版本。 |

 **Result:**



---


### setShaderVersion{#setShaderVersion}

| 名称 | 描述 |
| --- | --- |
| setShaderVersion(value) | 获取或设置此技术使用的着色器版本。 |

 **Result:**



---


### getShaderFile{#getShaderFile}

| 名称 | 描述 |
| --- | --- |
| getShaderFile() | 获取或设置外部着色器文件的文件名。 |

 **Result:**



---


### setShaderFile{#setShaderFile}

| 名称 | 描述 |
| --- | --- |
| setShaderFile(value) | 获取或设置外部着色器文件的文件名。 |

 **Result:**



---


### getShaderContent{#getShaderContent}

| 名称 | 描述 |
| --- | --- |
| getShaderContent() | 获取或设置嵌入式着色器脚本的内容。它可以是 HLSL/GLSL 着色器源文件。 |

 **Result:**



---


### setShaderContent{#setShaderContent}

| 名称 | 描述 |
| --- | --- |
| setShaderContent(value) | 获取或设置嵌入式着色器脚本的内容。它可以是 HLSL/GLSL 着色器源文件。 |

 **Result:**



---


### getShaderEntry{#getShaderEntry}

| 名称 | 描述 |
| --- | --- |
| getShaderEntry() | 获取或设置着色器的入口点，某些着色器如 HLSL 可以有自定义的着色器入口。 |

 **Result:**



---


### setShaderEntry{#setShaderEntry}

| 名称 | 描述 |
| --- | --- |
| setShaderEntry(value) | 获取或设置着色器的入口点，某些着色器如 HLSL 可以有自定义的着色器入口。 |

 **Result:**



---


### getRenderAPI{#getRenderAPI}

| 名称 | 描述 |
| --- | --- |
| getRenderAPI() | 获取或设置此技术使用的渲染 API |

 **Result:**



---


### setRenderAPI{#setRenderAPI}

| 名称 | 描述 |
| --- | --- |
| setRenderAPI(value) | 获取或设置此技术使用的渲染 API |

 **Result:**



---


### getRenderAPIVersion{#getRenderAPIVersion}

| 名称 | 描述 |
| --- | --- |
| getRenderAPIVersion() | 获取或设置渲染 API 的版本。 |

 **Result:**



---


### setRenderAPIVersion{#setRenderAPIVersion}

| 名称 | 描述 |
| --- | --- |
| setRenderAPIVersion(value) | 获取或设置渲染 API 的版本。 |

 **Result:**



---


### getShaderParameters{#getShaderParameters}

| 名称 | 描述 |
| --- | --- |
| getShaderParameters() | 获取着色器参数定义。键是动态属性的名称，值是该属性所连接的着色器参数名称。 |

 **Result:**



---


### addBinding{#addBinding}

| 名称 | 描述 |
| --- | --- |
| addBinding(property, shaderParameter) | 将动态属性绑定到着色器参数。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| property | 字符串 | 动态属性的名称。 |
| shaderParameter | 字符串 | 着色器参数的名称。 |

 **Result:**



---



