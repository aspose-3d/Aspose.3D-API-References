---
title: "Delegate FileSystemFactory"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "SaveOptions और LoadOptions डिफ़ॉल्ट रूप से एक LocalFileSystem बनाएंगे। यह सर्वर वातावरण में सुरक्षा समस्या हो सकती है। सर्वर पक्ष की सुरक्षा सुधारने के लिए अपने स्वयं के FileSystemFactory का उपयोग करें।"
type: docs
weight: 1190
url: /hi/net/aspose.threed.formats/filesystemfactory/
---
## FileSystemFactory delegate

[`SaveOptions`](../saveoptions/) and [`LoadOptions`](../loadoptions/) will create a LocalFileSystem for default. This can be a security issue in server environment. Use your own `FileSystemFactory` to [`FileSystemFactory`](../ioconfig/filesystemfactory/) to improve server side security.

```csharp
public delegate FileSystem FileSystemFactory();
```

### देखें भी

* class [FileSystem](../../aspose.threed.utilities/filesystem/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


