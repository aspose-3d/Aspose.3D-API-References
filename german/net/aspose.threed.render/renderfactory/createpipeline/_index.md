---
title: CreatePipeline
second_title: Aspose.3D für .NET-API-Referenz
description: Erstellen Sie eine vorkonfigurierte Grafikpipeline mit vorkonfigurierten Shader/Renderstatus/Scheitelpunktdeklarationen und Zeichenoperationen.
type: docs
weight: 40
url: /de/net/aspose.threed.render/renderfactory/createpipeline/
---
## RenderFactory.CreatePipeline method

Erstellen Sie eine vorkonfigurierte Grafikpipeline mit vorkonfigurierten Shader-/Renderstatus-/Scheitelpunktdeklarationen und Zeichenoperationen.

```csharp
public abstract IPipeline CreatePipeline(ShaderProgram shader, RenderState renderState, 
    VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shader | ShaderProgram | Der beim Rendern verwendete Shader |
| renderState | RenderState | Der beim Rendern verwendete Renderstatus |
| vertexDeclaration | VertexDeclaration | Die Vertex-Deklaration von Eingabe-Vertex-Daten |
| drawOperation | DrawOperation | Draw-Operation |

### Rückgabewert

Eine neue Pipelineinstanz

### Siehe auch

* interface [IPipeline](../../ipipeline)
* class [ShaderProgram](../../shaderprogram)
* class [RenderState](../../renderstate)
* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration)
* enum [DrawOperation](../../drawoperation)
* class [RenderFactory](../../renderfactory)
* namensraum [Aspose.ThreeD.Render](../../renderfactory)
* Montage [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->