---
title: "क्लास FbxLoadOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.FbxLoadOptions क्लास। Fbx फ़ॉर्मेट के लिए लोड विकल्प"
type: docs
weight: 1170
url: /hi/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Fbx फ़ॉर्मेट के लिए लोड विकल्प।

```csharp
public class FbxLoadOptions : LoadOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | `FbxLoadOptions` का कन्स्ट्रक्टर |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | `FbxLoadOptions` का कन्स्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | संगत मोड को सक्षम करना है या नहीं, इसे प्राप्त या सेट करता है। संगत मोड Blender द्वारा निर्यात किए गए PBR सामग्री जैसे गैर-मानक FBX परिभाषाओं को समर्थन देने का प्रयास करेगा। डिफ़ॉल्ट मान false है। |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | GlobalSettings में अंतर्निहित प्रॉपर्टीज़ को रखने हैं या नहीं, जिसे [`AssetInfo`](../../aspose.threed/assetinfo/) में मूल प्रॉपर्टी प्रतिस्थापन है, इसे प्राप्त या सेट करता है। यदि आप GlobalSettings में सभी प्रॉपर्टीज़ चाहते हैं तो इसे true सेट करें। डिफ़ॉल्ट मान false है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |

### देखें भी

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


