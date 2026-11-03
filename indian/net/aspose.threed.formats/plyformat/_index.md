---
title: "क्लास PlyFormat"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.PlyFormat क्लास। PLY फ़ॉर्मेट"
type: docs
weight: 1430
url: /hi/net/aspose.threed.formats/plyformat/
---
## PlyFormat class

PLY फ़ॉर्मेट।

```csharp
public class PlyFormat : FileFormat
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट में सीन निर्यात का समर्थन करता है या नहीं। |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट से सीन आयात का समर्थन करता है या नहीं। |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | फ़ाइल फ़ॉर्मेट की कंटेंट टाइप प्राप्त करता है |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | इस प्रकार का एक्सटेंशन नाम प्राप्त करता है। |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | इस प्रकार के एक्सटेंशन नाम प्राप्त करता है। |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | फ़ाइल फ़ॉर्मेट टाइप प्राप्त करता है |
| [Version](../../aspose.threed/fileformat/version/) { get; } | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट लोड विकल्प बनाएं |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट सहेजने विकल्प बनाएं |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode)(Stream) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_2)(string) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_1)(Stream, PlyLoadOptions) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_3)(string, PlyLoadOptions) | निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें। |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode)(Entity, Stream) | एंटिटी को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें। |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_2)(Entity, string) | एंटिटी को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें। |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_1)(Entity, Stream, PlySaveOptions) | एंटिटी को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें। |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_3)(Entity, string, PlySaveOptions) | एंटिटी को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें। |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | फ़ॉर्मेट को स्ट्रिंग में बदलें |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल में एन्कोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//PLY फ़ॉर्मेट में मेष को एन्कोड करें
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल से डिकोड किया जाता है:

```csharp
//डिकोडिंग के लिए एक टेस्ट फ़ाइल जनरेट करें
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//फ़ाइल को डिकोड करें
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### देखें भी

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


