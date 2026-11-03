---
title: "ITextureDecoder.Decode"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة ITextureDecoder. فك تشفير الملمس من الدفق إرجاع null إذا فشل فك التشفير"
type: docs
weight: 10
url: /ar/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

فك تشفير الملمس من الدفق، إرجاع null إذا فشل فك التشفير.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | دفق مصدر بيانات الملمس |
| reverseY | Boolean | قلب الملمس |

### قيمة الإرجاع

بيانات الملمس المفكوكة أو null إذا لم يكن مدعومًا.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل قراءة البيانات من الدفق |

### انظر أيضًا

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


