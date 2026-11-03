---
title: "DummyFileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: 
type: docs
weight: 2570
url: /hi/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

पढ़ने/लिखने के ऑपरेशन डमी ऑपरेशन हैं।

```csharp
public class DummyFileSystem : FileSystem
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें। |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं। |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं। |

### उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को मेमोरी में कैसे निर्यात किया जाए, और सभी निर्भर फ़ाइल जनरेशन को अनदेखा किया जाए।

```csharp
//सामग्री के साथ एक दृश्य बनाएं
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//एक सहेजने का विकल्प बनाएं और फ़ाइल सिस्टम निर्दिष्ट करें, ताकि निर्भर फ़ाइल मेमोरी में लिखी जा सके
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//obj की सामग्री फ़ाइल नाम obj की फ़ाइल नाम से जुड़ी है, इसलिए हमें एक स्पष्ट नाम चाहिए।
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### देखें भी

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- संपादित न करें: xmldocmd द्वारा Aspose.3D.dll के लिए उत्पन्न किया गया -->
