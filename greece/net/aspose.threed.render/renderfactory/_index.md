---
title: "Κλάση RenderFactory"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Η κλάση Aspose.ThreeD.Render.RenderFactory. Η RenderFactory δημιουργεί όλους τους πόρους που αναπαριστώνται στην αλυσίδα απόδοσης."
type: docs
weight: 2280
url: /el/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

Η RenderFactory δημιουργεί όλους τους πόρους που αντιπροσωπεύονται στη γραμμή επεξεργασίας απόδοσης.

```csharp
public abstract class RenderFactory
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | Δημιουργήστε έναν προορισμό απόδοσης που περιέχει 1 κυβική υφή. |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | Δημιουργήστε το σύνολο περιγραφέων για το καθορισμένο πρόγραμμα σκίασης. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | Δημιουργήστε ένα αντικείμενο [`IIndexBuffer`](../iindexbuffer/) για την αποθήκευση των πληροφοριών των προσώπων του πολυγώνου. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Δημιουργήστε μια προρυθμισμένη γραφική γραμμή με προρυθμισμένο shader/κατάσταση απόδοσης/δήλωση κορυφών και λειτουργίες σχεδίασης. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | Δημιουργήστε έναν προορισμό απόδοσης που περιέχει 1 στόχο που αποδίδει στην υφή. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | Δημιουργήστε έναν προορισμό απόδοσης που αποδίδει στην υφή. |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | Δημιουργήστε έναν προορισμό απόδοσης που αποδίδει στο εγγενές παράθυρο. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | Δημιουργήστε ένα αντικείμενο [`ShaderProgram`](../shaderprogram/) |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | Δημιουργήστε μια μονάδα 2Δ υφής που μπορεί να προσπελαστεί από το shader. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | Δημιουργήστε μια μονάδα υφής που μπορεί να προσπελαστεί από το shader. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | Δημιουργήστε ένα νέο ενιαίο buffer στην πλευρά του GPU με προ-καθορισμένο μέγεθος. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | Δημιουργήστε ένα αντικείμενο [`IVertexBuffer`](../ivertexbuffer/) για την αποθήκευση των πληροφοριών των κορυφών του πολυγώνου. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


