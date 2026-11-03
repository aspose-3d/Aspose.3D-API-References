---
title: "PdfFormat.ExtractScene"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PdfFormat मेथड। PDF फ़ाइल से 3D दृश्यों को निकालें"
type: docs
weight: 20
url: /hi/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

PDF फ़ाइल से 3D सीन निकालें।

```csharp
public List<Scene> ExtractScene(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | इनपुट PDF फ़ाइल का फ़ाइल नाम। |

### रिटर्न वैल्यू

Aspose.3D द्वारा समर्थित डिकोडेड 3D दृश्यों की सूची

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

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

PDF फ़ाइल से 3D सीन निकालें।

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | इनपुट PDF फ़ाइल का फ़ाइल नाम। |
| पासवर्ड | Byte[] | PDF फ़ाइल का पासवर्ड। |

### रिटर्न वैल्यू

Aspose.3D द्वारा समर्थित डिकोडेड 3D दृश्यों की सूची

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

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

PDF स्ट्रीम से कच्ची 3D सामग्री निकालें।

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट PDF फ़ाइल की स्ट्रीम |
| पासवर्ड | Byte[] | PDF फ़ाइल का पासवर्ड। |

### रिटर्न वैल्यू

Aspose.3D द्वारा समर्थित डिकोडेड 3D दृश्यों की सूची

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

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


