---
title: "IOConfig.FileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "IOConfig प्रॉपर्टी। उपयोगकर्ता को लोड/सेव के दौरान बाहरी निर्भरताओं को कैसे प्रबंधित करें, इसे संभालने की अनुमति देती है"
type: docs
weight: 40
url: /hi/net/aspose.threed.formats/ioconfig/filesystem/
---
## IOConfig.FileSystem property

लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है।

```csharp
public FileSystem FileSystem { get; set; }
```

## उदाहरण

डिफ़ॉल्ट फ़ाइल सिस्टम LocalFileSystem है, यह सर्वर-साइड जैसे पर्यावरण में सुरक्षित नहीं है, लेकिन आप अलग इम्प्लीमेंटेशन निर्दिष्ट करके फ़ाइल सिस्टम एक्सेस को ओवरराइड कर सकते हैं। Aspose.3D विभिन्न फ़ाइल सिस्टम इम्प्लीमेंटेशन प्रदान करता है जैसे: मेमोरी-आधारित फ़ाइल सिस्टम, डायरेक्टरी-आधारित फ़ाइल सिस्टम, डमी फ़ाइल सिस्टम, ज़िप फ़ाइल सिस्टम और आप अपनी स्वयं की इम्प्लीमेंटेशन भी उपयोग कर सकते हैं।

```csharp
Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

var opt = new ObjSaveOptions();
var memFs = new Dictionary<string, MemoryStream>();
opt.FileSystem = FileSystem.CreateMemoryFileSystem(memFs);
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//मैटेरियल को memFs नामक वेरिएबल में output.mtl के रूप में लिखा जाएगा
var materialInBytes = memFs["output.mtl"].ToArray();
```

### देखें भी

* class [FileSystem](../../../aspose.threed.utilities/filesystem/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


