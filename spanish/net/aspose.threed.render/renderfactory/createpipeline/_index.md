---
title: "RenderFactory.CreatePipeline"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método RenderFactory. Crear una canalización gráfica preconfigurada con shader, estado de renderizado y declaración de vértices preconfigurados y operaciones de dibujo"
type: docs
weight: 40
url: /es/net/aspose.threed.render/renderfactory/createpipeline/
---
## RenderFactory.CreatePipeline method

Cree una canalización gráfica preconfigurada con sombreado/estado de renderizado/declaración de vértices preconfigurados y operaciones de dibujo.

```csharp
public abstract IPipeline CreatePipeline(ShaderProgram shader, RenderState renderState, 
    VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shader | ShaderProgram | El shader usado en el renderizado |
| renderState | RenderState | El estado de renderizado usado en el renderizado |
| vertexDeclaration | VertexDeclaration | La declaración de vértices de los datos de vértices de entrada |
| drawOperation | DrawOperation | Operación de dibujo |

### Valor de retorno

Una nueva instancia de pipeline

### Ver también

* interface [IPipeline](../../ipipeline/)
* class [ShaderProgram](../../shaderprogram/)
* class [RenderState](../../renderstate/)
* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* enum [DrawOperation](../../drawoperation/)
* class [RenderFactory](../)
* namespace [Aspose.ThreeD.Render](../../renderfactory/)
* assembly [Aspose.3D](../../../)


