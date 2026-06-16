---
title: "Text.Font"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Text. الخط الخاص بالنص"
type: docs
weight: 30
url: /ar/net/aspose.threed.profiles/text/font/
---
## Text.Font property

خط النص.

```csharp
public FontFile Font { get; set; }
```

## أمثلة

الكود التالي يوضح كيفية إنشاء شبكة ثلاثية الأبعاد من النص باستخدام ملف الخط المحدد.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### انظر أيضًا

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


