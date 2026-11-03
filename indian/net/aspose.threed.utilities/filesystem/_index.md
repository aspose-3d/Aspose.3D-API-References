---
title: "क्लास FileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.FileSystem क्लास। फ़ाइल सिस्टम एन्कैप्सुलेशन। Aspose.3D इसका उपयोग निर्भरताओं को पढ़ने/लिखने के लिए करेगा।"
type: docs
weight: 2750
url: /hi/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

फ़ाइल सिस्टम एन्कैप्सुलेशन। Aspose.3D इसका उपयोग निर्भरताओं को पढ़ने/लिखने के लिए करेगा।

```csharp
public abstract class FileSystem : IDisposable
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | डमी फ़ाइल सिस्टम बनाएं, पढ़ने/लिखने के ऑपरेशन डमी ऑपरेशन हैं। |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | नया `FileSystem` इनिशियलाइज़ करें जो केवल स्थानीय डायरेक्टरी तक पहुंचता है। इस FileSystem इंस्टेंस पर सभी फ़ाइल पढ़ने/लिखने को निर्दिष्ट डायरेक्टरी में मैप किया जाएगा। |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-रीड एक्सेस प्रदान करने के लिए फ़ाइल सिस्टम। फ़ाइल सिस्टम को खोलने/सहेजने के ऑपरेशन के बाद नष्ट किया जाएगा। |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | फ़ाइल सिस्टम बनाएं जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-रीड एक्सेस प्रदान करे। फ़ाइल सिस्टम को ओपन/सेव ऑपरेशन के बाद डिस्पोज़ किया जाएगा। |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | फ़ाइल सिस्टम को नष्ट करें और उसके संसाधनों को मुक्त करें। |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | निर्भरताओं को पढ़ने के लिए एक स्ट्रीम बनाएं। |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | निर्भरताओं को लिखने के लिए एक स्ट्रीम बनाएं। |

## उदाहरण

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

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


