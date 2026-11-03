---
title: "IOConfig.LookupPaths"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية IOConfig. بعض الملفات مثل OBJ تعتمد على ملفات خارجية، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل"
type: docs
weight: 50
url: /ar/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

بعض الملفات مثل OBJ تعتمد على ملفات خارجية، مسارات البحث ستسمح لـ Aspose.3D بالبحث عن الملف الخارجي للتحميل.

```csharp
public List<string> LookupPaths { get; set; }
```

## أمثلة

الكود التالي يوضح كيفية تحديد مسارات البحث عن القوام يدويًا، حتى يتمكن المستورد من العثور عليها

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


