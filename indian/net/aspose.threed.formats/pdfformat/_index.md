---
title: "क्लास PdfFormat"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.PdfFormat क्लास। Adobe का पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट"
type: docs
weight: 1380
url: /hi/net/aspose.threed.formats/pdfformat/
---
## PdfFormat class

Adobe का पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट

```csharp
public class PdfFormat : FileFormat
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
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract)(Stream, byte[]) | PDF स्ट्रीम से कच्ची 3D सामग्री निकालें। |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract_1)(string, byte[]) | PDF फ़ाइल से कच्ची 3D सामग्री निकालें। |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_1)(string) | PDF फ़ाइल से 3D सीन निकालें। |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene)(Stream, byte[]) | PDF स्ट्रीम से कच्ची 3D सामग्री निकालें। |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_2)(string, byte[]) | PDF फ़ाइल से 3D सीन निकालें। |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | फ़ॉर्मेट को स्ट्रिंग में बदलें |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक 3D PDF फ़ाइल से सभी समर्थित 3D सीन निकाले जाएँ और उन्हें obj फ़ॉर्मेट में लिखा जाए।

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### देखें भी

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


