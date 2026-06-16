---
title: "Scene.AssetInfo"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية Scene. تحصل أو تعين معلومات الأصل ذات المستوى الأعلى."
type: docs
weight: 50
url: /ar/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

يحصل أو يعيّن معلومات الأصل ذات المستوى الأعلى

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


