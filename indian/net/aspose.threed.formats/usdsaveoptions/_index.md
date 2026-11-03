---
title: "Class UsdSaveOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.UsdSaveOptions क्लास। USD/USDZ फ़ॉर्मैट्स के लिए सहेजने के विकल्प"
type: docs
weight: 1540
url: /hi/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

USD/USDZ फ़ॉर्मैट्स के लिए सहेजने के विकल्प।

```csharp
public class UsdSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | `UsdSaveOptions` का एक नया उदाहरण [`USD`](../../aspose.threed/fileformat/usd/) फ़ॉर्मैट के साथ आरंभ करें |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | निर्दिष्ट USD/USDZ फ़ॉर्मैट के साथ नया `UsdSaveOptions` आरंभ करें। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | USD के customData फ़ील्ड के माध्यम से नोड की प्रॉपर्टीज़ निर्यात करें। |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | दृश्य में उपयोग की गई टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | जियोमेट्री की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कनवर्टर। यदि यह असाइन नहीं किया गया है, तो USD एक्सपोर्टर स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान null है। |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | एक्सपोर्ट के दौरान प्रिमिटिव एंटिटीज़ को मेष में बदलें। या प्रिमिटिव्स को सीधे आउटपुट फ़ाइल में एन्कोड करें (डिश, टोरस जैसे अनौपचारिक प्रिमिटिव्स के लिए Aspose की एक्सटेंशन परिभाषा का उपयोग किया जाएगा)। डिफ़ॉल्ट मान true है। |

### देखें भी

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


