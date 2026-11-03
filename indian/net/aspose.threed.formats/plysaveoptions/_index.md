---
title: "क्लास PlySaveOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.PlySaveOptions क्लास। दृश्य को PLY फ़ाइल के रूप में निर्यात करने के लिए सहेजने विकल्प"
type: docs
weight: 1450
url: /hi/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

सीन को PLY फ़ाइल के रूप में निर्यात करने के लिए सहेजने के विकल्प।

```csharp
public class PlySaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | `PlySaveOptions` का कंस्ट्रक्टर |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | `PlySaveOptions` का कंस्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/plysaveoptions/axissystem/) { get; set; } | निर्यात किए गए stl फ़ाइल में अक्ष प्रणाली को प्राप्त करता है या सेट करता है। |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | वर्टेक्स रंग के घटक नाम, डिफ़ॉल्ट मान (\"red\", \"green\", \"blue\") है |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | दृश्य में उपयोग की गई टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | फ़ेस डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान \"face\" है |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | फ़ेस डेटा के लिए प्रॉपर्टी नाम, डिफ़ॉल्ट मान \"vertex_index\" है |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | दृश्य को सहेजते समय निर्देशांक को उलटें, डिफ़ॉल्ट मान true है |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | नॉर्मल डेटा के घटक नाम, डिफ़ॉल्ट मान (\"nx\", \"ny\", \"nz\") है |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | दृश्य को पॉइंट क्लाउड के रूप में निर्यात करें, डिफ़ॉल्ट मान false है। |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | स्थिति डेटा के घटक नाम, डिफ़ॉल्ट मान (\"x\", \"y\", \"z\") है |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | टेक्सचर कोऑर्डिनेट डेटा के घटक नाम, डिफ़ॉल्ट मान (\"u\", \"v\") है |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | वर्टेक्स डेटा के लिए तत्व नाम, डिफ़ॉल्ट मान \"vertex\" है |

### देखें भी

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


