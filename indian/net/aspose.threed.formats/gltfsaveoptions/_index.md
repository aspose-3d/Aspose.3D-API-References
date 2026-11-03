---
title: "क्लास GltfSaveOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.GltfSaveOptions क्लास। glTF फ़ॉर्मेट के लिए सहेजने के विकल्प"
type: docs
weight: 1280
url: /hi/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

glTF फ़ॉर्मेट के लिए सहेजने के विकल्प।

```csharp
public class GltfSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | `GltfSaveOptions` का कन्स्ट्रक्टर |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | `GltfSaveOptions` का कन्स्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) को मेष पर लागू करें। डिफ़ॉल्ट मान false है। |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | बाइनरी डेटा को संग्रहीत करने के लिए उपयोग की जाने वाली बाहरी बफ़र फ़ाइल का फ़ाइल नाम। यदि यह फ़ाइल निर्दिष्ट नहीं की गई है, तो Aspose.3D आपके लिए एक नाम उत्पन्न करेगा। यह glTF को बाइनरी मोड में निर्यात करने पर अनदेखा किया जाता है। |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | ड्रैको संपीड़न को सक्षम करने के लिए प्राप्त या सेट करता है |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | ASCII मोड में सभी बाहरी एसेट्स को base64 के रूप में एकल फ़ाइल में एम्बेड करें, डिफ़ॉल्ट मान false है। |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | दृश्य में उपयोग की गई टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | ड्रैको संपीड़न गति को तेज करने के लिए बाहरी ड्रैको एन्कोडर का उपयोग करें। |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | जब GLTF2 एक्सपोर्टर ने एक अमान्य नॉर्मल का पता लगाया, तो वैधता को बायपास करने के लिए इसका मूल मान के बजाय यह उपयोग किया जाएगा। डिफ़ॉल्ट मान (0, 1, 0) है। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | टेक्सचर कोऑर्डिनेट v(t) घटक को फ़्लिप करें, डिफ़ॉल्ट मान true है। |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | मानक glTF केवल PNG/JPG को अपने टेक्सचर फ़ॉर्मेट के रूप में समर्थन करता है, यह विकल्प निर्यात के दौरान Aspose.3D को गैर-मानक छवियों को समर्थित फ़ॉर्मेट में परिवर्तित करने के तरीके को निर्देशित करेगा। डिफ़ॉल्ट मान Png है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | जियोमेट्री के मटेरियल को PBR मटेरियल में बदलने के लिए कस्टम कनवर्टर। यदि यह असाइन नहीं किया गया है, तो glTF 2.0 एक्सपोर्टर स्वचालित रूप से मानक मटेरियल को PBR मटेरियल में बदल देगा। डिफ़ॉल्ट मान null है। यह प्रॉपर्टी glTF 2.0 फ़ाइल में सीन को निर्यात करते समय उपयोग की जाती है। |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | GLTF फ़ाइल की JSON सामग्री को मानव पढ़ने के लिए इंडेंट किया गया है, डिफ़ॉल्ट मान false है। |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | जेनरेटेड glTF फ़ाइल में सीन ऑब्जेक्ट की डायनेमिक प्रॉपर्टीज़ को 'extra' फ़ील्ड्स में सहेजें। यह एप्लिकेशन-विशिष्ट डेटा प्रदान करने में उपयोगी है। डिफ़ॉल्ट मान false है। |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | KHR सामान्य मटेरियल एक्सटेंशन का उपयोग करके मटेरियल्स को सीरियलाइज़ करें, डिफ़ॉल्ट मान false है। इसे false सेट करने से Aspose.3D ExportShaders होने पर वर्टेक्स/फ़्रैगमेंट शेडर का सेट निर्यात करेगा। |

### देखें भी

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


