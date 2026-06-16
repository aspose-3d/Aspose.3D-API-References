---
title: "ITextureDecoder.Decode"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة ITextureDecoder. فك تشفير القوام من الدفق تُعيد null إذا فشل في فك التشفير"
type: docs
weight: 10
url: /ar/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

فك تشفير القوام من الدفق، إرجاع null إذا فشل في فك التشفير.

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | دفق مصدر بيانات القوام |
| reverseY | Boolean | قلب القوام |

### قيمة الإرجاع

بيانات القوام المفكوكة أو null إذا لم يكن مدعومًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| IOException | يُرمى عندما يفشل قراءة البيانات من الدفق |

### انظر أيضًا

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


