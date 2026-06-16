---
title: "RenderFactory.CreatePipeline"
second_title: "Aspose.3D for .NET API 参考"
description: "RenderFactory 方法。创建一个预配置的图形管线，包含预配置的着色器/渲染状态/顶点声明和绘制操作"
type: docs
weight: 40
url: /zh/net/aspose.threed.render/renderfactory/createpipeline/
---
## RenderFactory.CreatePipeline method

创建一个预配置的图形管线，包含预配置的着色器/渲染状态/顶点声明和绘制操作。

```csharp
public abstract IPipeline CreatePipeline(ShaderProgram shader, RenderState renderState, 
    VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 着色器 | ShaderProgram | 渲染中使用的着色器 |
| 渲染状态 | RenderState | 渲染中使用的渲染状态 |
| 顶点声明 | VertexDeclaration | 输入顶点数据的顶点声明 |
| 绘制操作 | DrawOperation | 绘制操作 |

### 返回值

新的管线实例

### 另请参见

* interface [IPipeline](../../ipipeline/)
* class [ShaderProgram](../../shaderprogram/)
* class [RenderState](../../renderstate/)
* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* enum [DrawOperation](../../drawoperation/)
* class [RenderFactory](../)
* namespace [Aspose.ThreeD.Render](../../renderfactory/)
* assembly [Aspose.3D](../../../)


