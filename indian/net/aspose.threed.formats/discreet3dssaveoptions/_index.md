---
title: "क्लास Discreet3dsSaveOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.Discreet3dsSaveOptions क्लास। 3DS फ़ाइल के लिए सेव विकल्प"
type: docs
weight: 1130
url: /hi/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

3DS फ़ाइल के लिए सहेजने विकल्प।

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | `Discreet3dsSaveOptions` का कन्स्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | डुप्लिकेट नामों के लिए नया नाम उत्पन्न करने में उपयोग किया जाने वाला काउंटर, डिफ़ॉल्ट मान 2 है। |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | डुप्लिकेट काउंटर का फ़ॉर्मेट, डिफ़ॉल्ट मान खाली स्ट्रिंग है। |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | ऑब्जेक्ट के नाम और डुप्लिकेट काउंटर के बीच विभाजक, डिफ़ॉल्ट मान "_" है। जब दृश्य में समान नाम वाले ऑब्जेक्ट होते हैं, तो Aspose.3D 3DS एक्सपोर्टर ऑब्जेक्ट के लिए एक अलग नाम उत्पन्न करेगा। उदाहरण के लिए, दो नोड्स "Box" नाम के हैं, पहला नोड "Box" नाम रखेगा, और दूसरा नोड डिफ़ॉल्ट कॉन्फ़िगरेशन का उपयोग करके नया नाम "Box_2" प्राप्त करेगा। |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | दृश्य में सभी कैमरों को एक्सपोर्ट करने की स्थिति प्राप्त करता है या सेट करता है। |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | दृश्य में सभी लाइट्स को एक्सपोर्ट करने की स्थिति प्राप्त करता है या सेट करता है। |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | दृश्य में उपयोग की गई टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | इम्पोर्ट/एक्सपोर्ट के दौरान नियंत्रण बिंदुओं/नॉर्मल के फ़्लिप कोऑर्डिनेट सिस्टम को प्राप्त करता है या सेट करता है। |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | एक 3ds फ़ाइल में समान गुण के लिए मूल रंग और गामा-सुधारित रंग दोनों हो सकते हैं, इसे true सेट करने पर संभव होने पर गामा-सुधारित रंग उपयोग किया जाएगा, अन्यथा Aspose.3D मूल रंग का उपयोग करने की कोशिश करेगा। |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | यदि यह true है, तो उत्पन्न 3ds फ़ाइल उच्च सटीकता वाला रंग उपयोग करेगी, अर्थात् लाल/हरा/नीला प्रत्येक चैनल 32 बिट फ़्लोट में होगा। अन्यथा उत्पन्न फ़ाइल 24 बिट रंग उपयोग करेगी, प्रत्येक चैनल 8 बिट बाइट में होगा। डिफ़ॉल्ट मान false है, क्योंकि सभी एप्लिकेशन उच्च-सटीकता वाले रंग का समर्थन नहीं करते। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | निर्यात में उपयोग किए जाने वाले मुख्य स्केल को प्राप्त करता है या सेट करता है। |

### देखें भी

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


