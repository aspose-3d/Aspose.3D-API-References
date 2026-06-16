---
title: "الفئة RenderFactory"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Render.RenderFactory. يقوم RenderFactory بإنشاء جميع الموارد التي تم تمثيلها في خط أنابيب العرض"
type: docs
weight: 2280
url: /ar/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory تنشئ جميع الموارد التي تم تمثيلها في خط أنابيب العرض.

```csharp
public abstract class RenderFactory
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | إنشاء هدف عرض يحتوي على نسيج مكعب واحد |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | إنشاء مجموعة الوصف للبرنامج الظلي المحدد. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | إنشاء مثيل [`IIndexBuffer`](../iindexbuffer/) لتخزين معلومات وجوه المضلع. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | إنشاء خط أنابيب رسومي مُكوَّن مسبقًا مع ظل/حالة عرض/إعلان رأس مُكوَّن مسبقًا وعمليات رسم. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | إنشاء هدف عرض يحتوي على هدف واحد يُرسم إلى النسيج |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | إنشاء هدف عرض يُرسم إلى النسيج |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | إنشاء هدف عرض يُرسم إلى النافذة الأصلية. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | إنشاء كائن [`ShaderProgram`](../shaderprogram/) |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | إنشاء وحدة نسيج ثنائية الأبعاد يمكن للظل الوصول إليها. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | إنشاء وحدة نسيج يمكن للظل الوصول إليها. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | إنشاء مخزن موحد جديد على جانب وحدة معالجة الرسوميات بحجم مُخصص مسبقًا. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | إنشاء مثيل [`IVertexBuffer`](../ivertexbuffer/) لتخزين معلومات رؤوس المضلع. |

### انظر أيضًا

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


