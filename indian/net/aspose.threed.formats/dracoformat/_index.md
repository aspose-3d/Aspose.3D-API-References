---
title: "क्लास DracoFormat"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.DracoFormat क्लास। Google Draco फ़ॉर्मेट"
type: docs
weight: 1150
url: /hi/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

Google Draco फ़ॉर्मेट

```csharp
public class DracoFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | मेमोरी डेटा से पॉइंट क्लाउड या मेष को डिकोड करें |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | निर्दिष्ट फ़ाइल नाम से पॉइंट क्लाउड या मेष को डिकोड करें |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | एंटिटी को Draco कच्चे डेटा में एन्कोड करें |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | एंटिटी को निर्दिष्ट स्ट्रीम में एन्कोड करें |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | एंटिटी को निर्दिष्ट फ़ाइल में एन्कोड करें |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | फ़ॉर्मेट को स्ट्रिंग में बदलें |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को बाइट एरे में/से एन्कोड और डिकोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//मेश को Draco फ़ॉर्मेट में एन्कोड करें
byte[] draco = FileFormat.Draco.Encode(mesh);
//मेश को Draco फ़ॉर्मेट से डिकोड करें
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### देखें भी

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


