---
title: "واجهة ICommandList"
second_title: "مرجع Aspose.3D for .NET API"
description: "واجهة Aspose.ThreeD.Render.ICommandList. تشفر تسلسلًا من الأوامر التي ستُرسل إلى وحدة معالجة الرسومات للعرض."
type: docs
weight: 2030
url: /ar/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

يقوم بترميز تسلسل من الأوامر التي سيتم إرسالها إلى GPU للتصوير.

```csharp
public interface ICommandList
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | ربط مجموعة الوصف بالخط الأنابيب الحالي |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | ربط مخزن الفهارس للعرض |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | ربط نسخة الخط الأنابيب للعرض |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | ربط مخزن الرؤوس للعرض |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | ارسم بدون مخزن الفهارس |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | ارسم بدون مخزن الفهارس |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | أصدر رسمًا مفهرسًا إلى قائمة الأوامر |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | أصدر رسمًا مفهرسًا إلى قائمة الأوامر |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | ادفع الثابت إلى الخط الأنابيب |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | ادفع الثابت إلى الخط الأنابيب |

### انظر أيضًا

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


