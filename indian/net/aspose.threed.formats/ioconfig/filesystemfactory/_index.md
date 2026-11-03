---
title: "IOConfig.FileSystemFactory"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "IOConfig प्रॉपर्टी। फ़ाइल सिस्टम के लिए फ़ैक्टरी क्लास को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट फ़ैक्टरी LocalFileSystem बनाएगी जो सर्वर पर्यावरण के लिए उपयुक्त नहीं है"
type: docs
weight: 60
url: /hi/net/aspose.threed.formats/ioconfig/filesystemfactory/
---
## IOConfig.FileSystemFactory property

FileSystem के लिए फ़ैक्ट्री क्लास को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट फ़ैक्ट्री LocalFileSystem बनाएगी, जो सर्वर वातावरण के लिए उपयुक्त नहीं है।

```csharp
public static FileSystemFactory FileSystemFactory { get; set; }
```

## उदाहरण

SaveOptions/LoadOptions में डिफ़ॉल्ट फ़ाइल सिस्टम डायरेक्टरी-आधारित फ़ाइल सिस्टम है, आप इसे IOConfig.FileSystemFactory के माध्यम से निर्दिष्ट करके डिफ़ॉल्ट इम्प्लीमेंटेशन को ओवरराइड कर सकते हैं:

```csharp
IOConfig.FileSystemFactory = () => {
    return FileSystem.CreateDummyFileSystem();
};

Scene scene = new Scene();
var material = new PhongMaterial();
var boxNode = scene.RootNode.CreateChildNode(new Box());
boxNode.Material = material;

//opt.FileSystem अब डमी फ़ाइल सिस्टम होगा
var opt = new ObjSaveOptions();
using var output = new MemoryStream();
opt.FileName = "output.obj";
scene.Save(output, opt);
//मैटेरियल फ़ाइल output.mtl किसी भी स्थान पर नहीं लिखी जाएगी क्योंकि हमने डिफ़ॉल्ट इम्प्लीमेंटेशन के रूप में डमी फ़ाइल सिस्टम कॉन्फ़िगर किया है।
```

### देखें भी

* delegate [FileSystemFactory](../../filesystemfactory/)
* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


