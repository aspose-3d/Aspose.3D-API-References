---
title: "क्लास FbxSaveOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.FbxSaveOptions क्लास। Fbx फ़ाइल के लिए सहेजने के विकल्प।"
type: docs
weight: 1180
url: /hi/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Fbx फ़ाइल के लिए सहेजने के विकल्प।

```csharp
public class FbxSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | नवीनतम समर्थित संस्करण का उपयोग करके `FbxSaveOptions` को प्रारंभ करें। |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | `FbxSaveOptions` को प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | टेक्सचर को अंतिम आउटपुट फ़ाइल में एम्बेड करने के लिए प्राप्त या सेट करता है। FBX एक्सपोर्टर टेक्सचर के कच्चे डेटा को [`FileSystem`](../ioconfig/filesystem/) से खोजने की कोशिश करेगा, और फ़ाइल को अंतिम FBX फ़ाइल में एम्बेड करेगा। डिफ़ॉल्ट मान असत्य है। |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | FBX फ़ाइल में बड़े बाइनरी डेटा (जैसे एनीमेशन डेटा, कंट्रोल पॉइंट्स, वर्टेक्स एलिमेंट डेटा, इंडेक्स) का संपीड़न, डिफ़ॉल्ट मान सत्य है। |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | निर्यात लेगेसी सामग्री गुणों को सेट या प्राप्त करता है, जो बैक संगतता के लिए उपयोग होते हैं। यह विकल्प डिफ़ॉल्ट रूप से चालू रहता है। |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | दृश्य में उपयोग की गई टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | पिछले डेटा की रेफ़रेंस काउंट बढ़ाकर दोहराए गए कर्व डेटा को पुनः उपयोग करना सेट या प्राप्त करता है। |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | यदि संलग्न नोड में सामग्री मौजूद हैं तो ज्यामितियों के लिए हमेशा एक [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) उत्पन्न करना सेट या प्राप्त करता है। यह डिफ़ॉल्ट रूप से बंद रहता है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | एक ही पैरामीटर वाले प्रिमिटिव्स के लिए मेष को पुनः उपयोग करें, इससे FBX आउटपुट का आकार काफी घटेगा क्योंकि दृश्य बड़े प्रिमिटिव आकारों (जैसे CAD फ़ाइलों से आयातित) के सेट से बना है। डिफ़ॉल्ट मान false है। |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | FBX के रूप में निर्यात करते समय [`Texture`](../../aspose.threed.shading/texture/) के लिए एक Video इंस्टेंस उत्पन्न करना सेट या प्राप्त करता है। |

### देखें भी

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


