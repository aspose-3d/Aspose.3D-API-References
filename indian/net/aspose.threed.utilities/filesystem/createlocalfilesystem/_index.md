---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileSystem मेथड। केवल स्थानीय डायरेक्टरी तक पहुँचने वाला नया FileSystem प्रारंभ करें। इस FileSystem इंस्टेंस पर सभी फ़ाइल पढ़ने/लिखने को निर्दिष्ट डायरेक्टरी में मैप किया जाएगा"
type: docs
weight: 20
url: /hi/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

एक नया [`FileSystem`](../) प्रारंभ करें जो केवल स्थानीय डायरेक्टरी तक पहुँचता है। इस FileSystem इंस्टेंस पर सभी फ़ाइल पढ़ने/लिखने को निर्दिष्ट डायरेक्टरी में मैप किया जाएगा।

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डायरेक्टरी | String | आपके भौतिक फ़ाइल सिस्टम में वह डायरेक्टरी जो वर्चुअल रूट डायरेक्टरी के रूप में कार्य करती है। |

### रिटर्न वैल्यू

स्थानीय फ़ाइल पहुँच प्रदान करने के लिए फ़ाइल सिस्टम का एक नया उदाहरण

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| FileNotFoundException | जब निर्देशिका नहीं मिल पाती है तो फेंका जाता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को कैसे आयात किया जाए, और दिए गए डायरेक्टरी में निर्भर फ़ाइलें कैसे प्रदान की जाएँ।

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//लोड विकल्पों का एक उदाहरण बनाएं और स्थानीय फ़ाइल सिस्टम निर्दिष्ट करें
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//फ़ाइल लोड करें
var scene = Scene.FromFile(inputFile, opt);
```

### देखें भी

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


