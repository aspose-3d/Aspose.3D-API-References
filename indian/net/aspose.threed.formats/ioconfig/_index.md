---
title: "क्लास IOConfig"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.IOConfig क्लास। सीरियलाइज़ेशन/डिसीरियलाइज़ेशन के लिए IO कॉन्फ़िग। उपयोगकर्ता यहाँ निर्भरता लुकअप पथ या फ़ॉर्मेट-संबंधित कॉन्फ़िगरेशन जैसी विस्तृत सेटिंग्स निर्दिष्ट कर सकता है।"
type: docs
weight: 1300
url: /hi/net/aspose.threed.formats/ioconfig/
---
## IOConfig class

सीरियलाइज़ेशन/डिसीरियलाइज़ेशन के लिए IO कॉन्फ़िग। उपयोगकर्ता यहाँ निर्भरता लुक-अप पाथ या फ़ॉर्मेट-संबंधित कॉन्फ़िगरेशन जैसी विस्तृत सेटिंग्स निर्दिष्ट कर सकता है।

```csharp
public class IOConfig
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| static [FileSystemFactory](../../aspose.threed.formats/ioconfig/filesystemfactory/) { get; set; } | FileSystem के लिए फ़ैक्ट्री क्लास को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट फ़ैक्ट्री LocalFileSystem बनाएगी, जो सर्वर वातावरण के लिए उपयुक्त नहीं है। |

### देखें भी

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


