---
title: "IOConfig.LookupPaths"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية IOConfig. بعض الملفات مثل OBJ تعتمد على ملفات خارجية، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل."
type: docs
weight: 50
url: /ar/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

بعض الملفات مثل OBJ تعتمد على ملف خارجي، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل.

```csharp
public List<string> LookupPaths { get; set; }
```

## أمثلة

يعرض الشيفرة التالية كيفية تحديد قوام البحث يدوياً، حتى يتمكن المستورد من العثور عليها.

```csharp
var opt = new ObjLoadOptions();
//حدد مسارات البحث، حتى يمكن العثور على القوام.
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### انظر أيضًا

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


