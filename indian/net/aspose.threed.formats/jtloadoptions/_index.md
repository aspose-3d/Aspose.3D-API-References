---
title: "क्लास JtLoadOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.JtLoadOptions क्लास। Siemens JT के लिए लोड विकल्प"
type: docs
weight: 1310
url: /hi/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

Siemens JT के लिए लोड विकल्प

```csharp
public class JtLoadOptions : LoadOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | यदि संभव हो तो JT फ़ाइल से PMI जानकारी लोड करें, डेटा को [`AssetInfo`](../../aspose.threed/scene/assetinfo/) की प्रॉपर्टी "PMI" के रूप में सहेजा जाएगा। डिफ़ॉल्ट मान false है। |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | JT की प्रॉपर्टी टेबल से प्रॉपर्टीज़ को Aspose.3D प्रॉपर्टीज़ के रूप में लोड करें। डिफ़ॉल्ट मान false है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |

### देखें भी

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


