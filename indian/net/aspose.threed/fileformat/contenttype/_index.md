---
title: "FileFormat.ContentType"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileFormat प्रॉपर्टी। फ़ाइल फ़ॉर्मेट कंटेंट टाइप प्राप्त करता है"
type: docs
weight: 500
url: /hi/net/aspose.threed/fileformat/contenttype/
---
## FileFormat.ContentType property

फ़ाइल फ़ॉर्मेट की कंटेंट टाइप प्राप्त करता है

```csharp
public FileContentType ContentType { get; }
```

## उदाहरण

```csharp
var format = FileFormat.MayaBinary;
if (format.ContentType == FileContentType.Binary)
    Console.WriteLine($"{format} is binary format");
else
    Console.WriteLine($"{format} is text-based format");
```

### देखें भी

* enum [FileContentType](../../filecontenttype/)
* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


