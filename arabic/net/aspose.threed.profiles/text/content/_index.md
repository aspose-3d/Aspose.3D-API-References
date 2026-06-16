---
title: "Text.Content"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Text. محتوى النص"
type: docs
weight: 20
url: /ar/net/aspose.threed.profiles/text/content/
---
## Text.Content property

محتوى النص

```csharp
public string Content { get; set; }
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

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


