---
title: "क्लास RvmLoadOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.RvmLoadOptions क्लास। AVEVA Plant Design Management Systems RVM फ़ाइल के लिए लोड विकल्प"
type: docs
weight: 1470
url: /hi/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

AVEVA Plant Design Management System की RVM फ़ाइल के लिए लोड विकल्प।

```csharp
public class RvmLoadOptions : LoadOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | `RvmLoadOptions` का एक इंस्टेंस बनाएं |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | `RvmLoadOptions` का एक इंस्टेंस बनाएं |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | बाहरी एट्रिब्यूट फ़ाइलों में परिभाषित एट्रिब्यूट्स के प्रीफ़िक्स को प्राप्त या सेट करता है। प्रीफ़िक्स नाम टकराव से बचने के लिए उपयोग किया जाता है, डिफ़ॉल्ट मान "rvm:" है। |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | लोड होने के बाद सीन को केंद्रित करें। |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | सिलेंडर के रेडियल सेगमेंट्स की संख्या को प्राप्त या सेट करता है, डिफ़ॉल्ट मान 16 है। |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | डिश के लैटिट्यूड सेगमेंट्स की संख्या को प्राप्त या सेट करता है, डिफ़ॉल्ट मान 8 है। |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | डिश के लॉन्गिट्यूड सेगमेंट्स की संख्या को प्राप्त या सेट करता है, डिफ़ॉल्ट मान 12 है। |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | यदि RVM फ़ाइल में कलर टेबल निर्यात नहीं किया गया है, तो सीन में प्रत्येक ऑब्जेक्ट के लिए रैंडम रंगों के साथ सामग्री उत्पन्न करें। डिफ़ॉल्ट मान true है। |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | बाहरी एट्रिब्यूट लिस्ट फ़ाइल (.att/.attrib/.txt) से एट्रिब्यूट्स लोड करने की स्थिति को प्राप्त या सेट करता है, डिफ़ॉल्ट मान true है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | रेक्टेंगलर टोरस के रेडियल सेगमेंट्स की संख्या को प्राप्त या सेट करता है, डिफ़ॉल्ट मान 20 है। |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | टोरस के ट्यूब्यूलर सेगमेंट्स की संख्या प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान 20 है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि RvmLoadOptions का उपयोग करके RVM फ़ाइल से आयातित प्रिमिटिव ज्योमेट्री के टेसलेशन पैरामीटर को कैसे कस्टमाइज़ किया जाए।

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### देखें भी

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


