---
title: "LocalFileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: 
type: docs
weight: 2650
url: /hi/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

यह [`LocalFileSystem`](../localfilesystem) पढ़ने/लिखने के ऑपरेशनों को स्थानीय निर्देशिका में मैप करेगा।

```csharp
public class LocalFileSystem : FileSystem
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | निर्दिष्ट बेस डायरेक्टरी के साथ एक नया [`LocalFileSystem`](../localfilesystem) प्रारंभ करें। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें। |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं। |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं। |

### उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को कैसे आयात किया जाए, और दिए गए डायरेक्टरी में निर्भर फ़ाइलें कैसे प्रदान की जाएँ।

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//लोड विकल्पों का एक इंस्टेंस बनाएं और ज़िप फ़ाइल सिस्टम निर्दिष्ट करें
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//फ़ाइल लोड करें
var scene = Scene.FromFile(inputFile, opt);
```

### देखें भी

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- संपादित न करें: xmldocmd द्वारा Aspose.3D.dll के लिए उत्पन्न किया गया -->
