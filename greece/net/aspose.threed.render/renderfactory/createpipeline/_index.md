---
title: "RenderFactory.CreatePipeline"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος RenderFactory. Δημιουργήστε ένα προρυθμισμένο graphics pipeline με προρυθμισμένο shader/render state/vertex declaration και λειτουργίες σχεδίασης"
type: docs
weight: 40
url: /el/net/aspose.threed.render/renderfactory/createpipeline/
---
## RenderFactory.CreatePipeline method

Δημιουργήστε μια προρυθμισμένη γραφική γραμμή με προρυθμισμένο shader/κατάσταση απόδοσης/δήλωση κορυφών και λειτουργίες σχεδίασης.

```csharp
public abstract IPipeline CreatePipeline(ShaderProgram shader, RenderState renderState, 
    VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shader | ShaderProgram | Ο shader που χρησιμοποιείται στην απόδοση |
| renderState | RenderState | Η κατάσταση render state που χρησιμοποιείται στην απόδοση |
| vertexDeclaration | VertexDeclaration | Η δήλωση vertex των εισερχόμενων δεδομένων vertex |
| drawOperation | DrawOperation | Λειτουργία σχεδίασης |

### Τιμή επιστροφής

Μια νέα παρουσία του pipeline

### Δείτε επίσης

* interface [IPipeline](../../ipipeline/)
* class [ShaderProgram](../../shaderprogram/)
* class [RenderState](../../renderstate/)
* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* enum [DrawOperation](../../drawoperation/)
* class [RenderFactory](../)
* namespace [Aspose.ThreeD.Render](../../renderfactory/)
* assembly [Aspose.3D](../../../)


