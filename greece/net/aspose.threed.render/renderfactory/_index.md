---
title: RenderFactory
second_title: Aspose.3D για Αναφορά API .NET
description: Το Το RenderFactory δημιουργεί όλους τους πόρους που αντιπροσωπεύονται στη γραμμή απόδοσης.
type: docs
weight: 2040
url: /el/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

Το Το RenderFactory δημιουργεί όλους τους πόρους που αντιπροσωπεύονται στη γραμμή απόδοσης.

```csharp
public abstract class RenderFactory
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | Δημιουργήστε έναν στόχο απόδοσης που περιέχει 1 κύβο texture |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | Δημιουργήστε το σύνολο περιγραφών για το καθορισμένο πρόγραμμα shader. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | Δημιουργήστε ένα[`IIndexBuffer`](../iindexbuffer/) παράδειγμα για αποθήκευση πληροφοριών προσώπου πολυγώνου. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Δημιουργήστε μια προρυθμισμένη διοχέτευση γραφικών με προρυθμισμένο shader/render State/vertex δήλωση και λειτουργίες σχεδίασης. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | Η δημιουργία ενός στόχου απόδοσης περιέχει 1 στόχους που αποδίδεται στο texture |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | Δημιουργήστε έναν στόχο απόδοσης που αποδίδεται στο texture |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | Δημιουργήστε έναν στόχο απόδοσης που αποδίδεται στο εγγενές παράθυρο. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | Δημιουργία α[`ShaderProgram`](../shaderprogram/) αντικείμενο |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | Δημιουργήστε μια μονάδα υφής 2D στην οποία μπορείτε να έχετε πρόσβαση με shader. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | Δημιουργήστε μια μονάδα υφής στην οποία μπορείτε να έχετε πρόσβαση με shader. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | Δημιουργήστε ένα νέο ομοιόμορφο buffer στην πλευρά της GPU με προκαθορισμένο μέγεθος. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | Δημιουργήστε ένα[`IVertexBuffer`](../ivertexbuffer/) παράδειγμα για την αποθήκευση πληροφοριών κορυφής πολυγώνου. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.ThreeD.Render](../../aspose.threed.render/)
* συνέλευση [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
