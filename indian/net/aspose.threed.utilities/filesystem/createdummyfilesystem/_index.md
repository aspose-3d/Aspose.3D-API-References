---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileSystem मेथड। एक डमी फ़ाइल सिस्टम बनाएं, पढ़ने/लिखने की क्रियाएँ डमी ऑपरेशन हैं।"
type: docs
weight: 10
url: /hi/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

डमी फ़ाइल सिस्टम बनाएं, पढ़ने/लिखने के ऑपरेशन डमी ऑपरेशन हैं।

```csharp
public static FileSystem CreateDummyFileSystem()
```

### रिटर्न वैल्यू

एक डमी फ़ाइल सिस्टम

## उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को मेमोरी में कैसे निर्यात किया जाए, और सभी निर्भर फ़ाइल जनरेशन को अनदेखा किया जाए।

```csharp
//सामग्री के साथ एक दृश्य बनाएं
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//एक सहेजने का विकल्प बनाएं और फ़ाइल सिस्टम निर्दिष्ट करें, ताकि निर्भर फ़ाइल मेमोरी में लिखी जा सके
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//obj की सामग्री फ़ाइल नाम obj की फ़ाइल नाम से जुड़ी है, इसलिए हमें एक स्पष्ट नाम चाहिए।
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### देखें भी

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


