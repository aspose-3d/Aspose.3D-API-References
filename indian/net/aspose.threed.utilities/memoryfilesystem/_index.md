---
title: "MemoryFileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: 
type: docs
weight: 2680
url: /hi/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

यह [`MemoryFileSystem`](../memoryfilesystem) पढ़ने/लिखने के संचालन को मेमोरी में मैप करेगा।

```csharp
public class MemoryFileSystem : FileSystem
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | इस मेमोरी फ़ाइल सिस्टम में फ़ाइल नाम। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें। |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | निर्दिष्ट फ़ाइल की कच्ची सामग्री लौटाता है। यदि निर्दिष्ट फ़ाइल मौजूद नहीं है तो FileNotFoundException फेंकेगा। |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं। |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं। |

### उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को मेमोरी में कैसे निर्यात किया जाए, जिसमें MemoryFileSystem का उपयोग करके निर्भर फ़ाइल शामिल है।

```csharp
//सामग्री के साथ एक दृश्य बनाएं
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//एक सहेजने का विकल्प बनाएं और फ़ाइल सिस्टम निर्दिष्ट करें, ताकि निर्भर फ़ाइल मेमोरी में लिखी जा सके
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//obj की सामग्री फ़ाइल नाम obj की फ़ाइल नाम से जुड़ी है, इसलिए हमें एक स्पष्ट नाम चाहिए।
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//test.obj को वेरिएबल ms में लिखा गया था, और हम test.mtl फ़ाइल की सामग्री भी प्राप्त कर सकते हैं द्वारा
var materialFile = mfs.GetFileContent("test.mtl");
```

### देखें भी

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- संपादित न करें: xmldocmd द्वारा Aspose.3D.dll के लिए उत्पन्न किया गया -->
