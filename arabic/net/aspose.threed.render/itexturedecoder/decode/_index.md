---
title: ITextureDecoder.Decode
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة ITextureDecoder. فك تشفير النسيج من الدفق وإرجاع null إذا فشل الفك
type: docs
weight: 10
url: /ar/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

فك تشفير القوام من الدفق، إرجاع null إذا فشل فك التشفير.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تيار مصدر بيانات القوام |
| reverseY | Boolean | قلب القوام |

### قيمة الإرجاع

بيانات النسيج المفكوكة أو null إذا لم يكن مدعومًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل قراءة البيانات من الدفق |

### انظر أيضًا

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


