---
title: "Scene.AssetInfo"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene प्रॉपर्टी। टॉपलेवल एसेट जानकारी को प्राप्त या सेट करता है।"
type: docs
weight: 50
url: /hi/net/aspose.threed/scene/assetinfo/
---
## Scene.AssetInfo property

शीर्ष-स्तर की संपत्ति जानकारी प्राप्त करता या सेट करता है

```csharp
public AssetInfo AssetInfo { get; set; }
```

### Property Value

दस्तावेज़ जानकारी।

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक FBX फ़ाइल से एप्लिकेशन जानकारी पढ़ी जाए:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The FBX file is created by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion}");
```

### देखें भी

* class [AssetInfo](../../assetinfo/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


