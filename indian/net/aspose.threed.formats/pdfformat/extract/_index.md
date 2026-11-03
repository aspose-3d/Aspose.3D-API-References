---
title: "PdfFormat.Extract"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PdfFormat मेथड। PDF फ़ाइल से कच्ची 3D सामग्री निकालें।"
type: docs
weight: 10
url: /hi/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

PDF फ़ाइल से कच्ची 3D सामग्री निकालें।

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | इनपुट PDF फ़ाइल का फ़ाइल नाम। |
| पासवर्ड | Byte[] | PDF फ़ाइल का पासवर्ड। |

### रिटर्न वैल्यू

बाइट्स में सभी 3D सामग्री की एक सूची, जिसमें वे फ़ॉर्मेट शामिल हैं जिन्हें Aspose.3D समर्थन नहीं करता।

## उदाहरण

निम्नलिखित कोड दिखाता है कि 3D PDF फ़ाइल से सभी कच्ची 3D सामग्री कैसे निकाली जाएँ, और उन्हें फ़ाइलों में लिखा जाए।

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### देखें भी

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

PDF स्ट्रीम से कच्ची 3D सामग्री निकालें।

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट PDF फ़ाइल की स्ट्रीम |
| पासवर्ड | Byte[] | PDF फ़ाइल का पासवर्ड। |

### रिटर्न वैल्यू

बाइट्स में सभी 3D सामग्री की एक सूची, जिसमें वे फ़ॉर्मेट शामिल हैं जिन्हें Aspose.3D समर्थन नहीं करता।

## उदाहरण

निम्नलिखित कोड दिखाता है कि 3D PDF फ़ाइल से सभी कच्ची 3D सामग्री कैसे निकाली जाएँ, और उन्हें फ़ाइलों में लिखा जाए।

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### देखें भी

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


