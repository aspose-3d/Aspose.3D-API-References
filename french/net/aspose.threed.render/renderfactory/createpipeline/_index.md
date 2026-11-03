---
title: "RenderFactory.CreatePipeline"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode RenderFactory. Créez un pipeline graphique préconfiguré avec un shader/état de rendu/déclaration de sommet préconfigurés et des opérations de dessin"
type: docs
weight: 40
url: /fr/net/aspose.threed.render/renderfactory/createpipeline/
---
## RenderFactory.CreatePipeline method

Créez un pipeline graphique préconfiguré avec un shader/état de rendu/déclaration de sommet préconfigurés et des opérations de dessin.

```csharp
public abstract IPipeline CreatePipeline(ShaderProgram shader, RenderState renderState, 
    VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| shader | ShaderProgram | Le shader utilisé dans le rendu |
| renderState | RenderState | L'état de rendu utilisé dans le rendu |
| vertexDeclaration | VertexDeclaration | La déclaration de sommet des données de sommet d'entrée |
| drawOperation | DrawOperation | Opération de dessin |

### Valeur de retour

Une nouvelle instance de pipeline

### Voir aussi

* interface [IPipeline](../../ipipeline/)
* class [ShaderProgram](../../shaderprogram/)
* class [RenderState](../../renderstate/)
* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* enum [DrawOperation](../../drawoperation/)
* class [RenderFactory](../)
* namespace [Aspose.ThreeD.Render](../../renderfactory/)
* assembly [Aspose.3D](../../../)


