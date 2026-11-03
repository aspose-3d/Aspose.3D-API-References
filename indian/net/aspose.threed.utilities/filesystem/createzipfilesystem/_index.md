---
title: "FileSystem.CreateZipFileSystem"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileSystem मेथड। निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-रीड पहुँच प्रदान करने के लिए फ़ाइल सिस्टम बनाएं। फ़ाइल सिस्टम को खोलने/सहेजने के बाद नष्ट कर दिया जाएगा।"
type: docs
weight: 40
url: /hi/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

फ़ाइल सिस्टम बनाएं जो निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-रीड एक्सेस प्रदान करे। फ़ाइल सिस्टम को ओपन/सेव ऑपरेशन के बाद डिस्पोज़ किया जाएगा।

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | ज़िप फ़ाइल तक पहुँचने के लिए स्ट्रीम |
| baseDir | String | ज़िप फ़ाइल के भीतर बेस डायरेक्टरी। |

### रिटर्न वैल्यू

एक ज़िप फ़ाइल सिस्टम

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | स्ट्रीम से पढ़ने में विफल होने पर फेंका जाता है। |

## टिप्पणियाँ

यह एक केवल-रीड फ़ाइल सिस्टम है, इसलिए कोई लिखने की क्रियाएँ समर्थित नहीं हैं।

## उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को कैसे आयात किया जाए, और ज़िप आर्काइव फ़ाइल में निर्भर फ़ाइलें कैसे प्रदान की जाएँ।

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//लोड विकल्पों का एक इंस्टेंस बनाएं और ज़िप फ़ाइल सिस्टम निर्दिष्ट करें
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//फ़ाइल लोड करें
var scene = Scene.FromFile(inputFile, opt);
```

### देखें भी

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

निर्दिष्ट ज़िप फ़ाइल या ज़िप स्ट्रीम तक केवल-रीड एक्सेस प्रदान करने के लिए फ़ाइल सिस्टम। फ़ाइल सिस्टम को खोलने/सहेजने के ऑपरेशन के बाद नष्ट किया जाएगा।

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | ज़िप फ़ाइल का फ़ाइल नाम। |

### रिटर्न वैल्यू

एक ज़िप फ़ाइल सिस्टम

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | स्ट्रीम से पढ़ने में विफल होने पर फेंका जाता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल को कैसे आयात किया जाए, और ज़िप आर्काइव फ़ाइल में निर्भर फ़ाइलें कैसे प्रदान की जाएँ।

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//लोड विकल्पों का एक इंस्टेंस बनाएं और ज़िप फ़ाइल सिस्टम निर्दिष्ट करें
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//फ़ाइल लोड करें
var scene = Scene.FromFile(inputFile, opt);
```

### देखें भी

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


