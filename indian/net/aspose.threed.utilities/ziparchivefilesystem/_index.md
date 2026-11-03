---
title: "क्लास ZipArchiveFileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.ZipArchiveFileSystem क्लास। निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-रीड एक्सेस प्रदान करने के लिए फ़ाइल सिस्टम। फ़ाइल सिस्टम को खोलने/सहेजने के ऑपरेशन के बाद नष्ट किया जाएगा।"
type: docs
weight: 2830
url: /hi/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-रीड एक्सेस प्रदान करने के लिए फ़ाइल सिस्टम। फ़ाइल सिस्टम को खोलने/सहेजने के ऑपरेशन के बाद नष्ट किया जाएगा।

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | ZipArchiveFileSystem को नष्ट करें और उसकी आंतरिक संसाधनों को मुक्त करें। |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | फ़ाइल को पढ़ने के लिए खोलें |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | फ़ाइल को लिखने के लिए खोलें, इस क्लास में लागू नहीं है। |

### उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को कैसे आयात किया जाए, और ज़िप आर्काइव फ़ाइल में निर्भर फ़ाइलें कैसे प्रदान की जाएँ।

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//लोड विकल्पों का एक इंस्टेंस बनाएं और ज़िप फ़ाइल सिस्टम निर्दिष्ट करें
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//फ़ाइल लोड करें
var scene = Scene.FromFile(inputFile, opt);
```

### देखें भी

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


