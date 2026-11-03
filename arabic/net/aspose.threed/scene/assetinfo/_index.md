---
title: "Scene.AssetInfo"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "خاصية Scene. تحصل أو تعين معلومات الأصل المستوى الأعلى"
type: docs
weight: 50
url: /ar/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

تحصل أو تعين معلومات الأصل المستوى الأعلى

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

معلومات المستند.

## أمثلة

الكود التالي يوضح كيفية قراءة معلومات التطبيق من ملف FBX:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### انظر أيضًا

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


