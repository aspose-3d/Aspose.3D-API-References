---
title: "FileFormat.CanImport"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileFormat प्रॉपर्टी। यह प्राप्त करता है कि क्या Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट से सीन आयात करने का समर्थन करता है।"
type: docs
weight: 490
url: /hi/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट से सीन आयात का समर्थन करता है या नहीं।

```csharp
public bool CanImport { get; }
```

## उदाहरण

निम्नलिखित कोड दिखाता है कि निर्दिष्ट फ़ॉर्मेट से आयात का समर्थन है या नहीं, कैसे जांचें।

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### देखें भी

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


