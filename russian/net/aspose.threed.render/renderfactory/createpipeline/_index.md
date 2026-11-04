---
title: "RenderFactory.CreatePipeline"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод RenderFactory. Создать предварительно сконфигурированный графический конвейер с предварительно сконфигурированными shader/render state/vertex declaration и операциями отрисовки"
type: docs
weight: 40
url: /ru/net/aspose.threed.render/renderfactory/createpipeline/
---
## RenderFactory.CreatePipeline method

Создайте предварительно настроенный графический конвейер с предустановленными шейдером/состоянием рендеринга/объявлением вершин и операциями отрисовки.

```csharp
public abstract IPipeline CreatePipeline(ShaderProgram shader, RenderState renderState, 
    VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| shader | ShaderProgram | Шейдер, используемый при рендеринге |
| renderState | RenderState | Состояние рендеринга, используемое при рендеринге |
| vertexDeclaration | VertexDeclaration | Объявление вершин входных данных |
| drawOperation | DrawOperation | Операция отрисовки |

### Возвращаемое значение

Новый экземпляр конвейера

### См. также

* interface [IPipeline](../../ipipeline/)
* class [ShaderProgram](../../shaderprogram/)
* class [RenderState](../../renderstate/)
* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* enum [DrawOperation](../../drawoperation/)
* class [RenderFactory](../)
* namespace [Aspose.ThreeD.Render](../../renderfactory/)
* assembly [Aspose.3D](../../../)


