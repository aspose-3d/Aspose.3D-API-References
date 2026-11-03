---
title: "FileFormat.CanExport"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileFormat property. प्राप्त करता है कि Aspose.3D वर्तमान फ़ाइल स्वरूप में सीन निर्यात का समर्थन करता है या नहीं"
type: docs
weight: 480
url: /hi/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट में सीन निर्यात का समर्थन करता है या नहीं।

```csharp
public bool CanExport { get; }
```

## उदाहरण

निम्नलिखित कोड दर्शाता है कि निर्दिष्ट स्वरूप में निर्यात समर्थित है या नहीं, इसे कैसे जांचें।

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### देखें भी

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


