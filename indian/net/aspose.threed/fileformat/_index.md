---
title: "Class FileFormat"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.FileFormat class. फ़ाइल फ़ॉर्मेट परिभाषा"
type: docs
weight: 1060
url: /hi/net/aspose.threed/fileformat/
---
## FileFormat class

फ़ाइल फ़ॉर्मेट परिभाषा

```csharp
public class FileFormat
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट में सीन निर्यात का समर्थन करता है या नहीं। |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | जाँचता है कि Aspose.3D वर्तमान फ़ाइल फ़ॉर्मेट से सीन आयात का समर्थन करता है या नहीं। |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | फ़ाइल फ़ॉर्मेट की कंटेंट टाइप प्राप्त करता है |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | इस प्रकार का एक्सटेंशन नाम प्राप्त करता है। |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | इस प्रकार के एक्सटेंशन नाम प्राप्त करता है। |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | फ़ाइल फ़ॉर्मेट टाइप प्राप्त करता है |
| [Version](../../aspose.threed/fileformat/version/) { get; } | फ़ाइल फ़ॉर्मेट संस्करण प्राप्त करता है |
| static [Formats](../../aspose.threed/fileformat/formats/) { get; } | सभी समर्थित फ़ॉर्मेट्स तक पहुँच |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [Detect](../../aspose.threed/fileformat/detect/#detect_1)(string) | फ़ाइल नाम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल पढ़ने योग्य होनी चाहिए ताकि Aspose.3D फ़ाइल हेडर के माध्यम से फ़ॉर्मेट का पता लगा सके। |
| static [Detect](../../aspose.threed/fileformat/detect/#detect)(Stream, string) | डेटा स्ट्रीम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल नाम वैकल्पिक है उन प्रकारों का अनुमान लगाने के लिए जिनमें कोई मैजिक हेडर नहीं है। |
| static [GetFormatByExtension](../../aspose.threed/fileformat/getformatbyextension/)(string) | फ़ाइल एक्सटेंशन नाम से पसंदीदा फ़ाइल फ़ॉर्मेट प्राप्त करता है। एक्सटेंशन नाम को डॉट ('.') से शुरू होना चाहिए। |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट लोड विकल्प बनाएं |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | इस फ़ाइल फ़ॉर्मेट के लिए डिफ़ॉल्ट सहेजने विकल्प बनाएं |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | फ़ॉर्मेट को स्ट्रिंग में बदलें |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [AMF](../../aspose.threed/fileformat/amf/) | एडिटिव मैन्युफैक्चरिंग फ़ाइल फ़ॉर्मेट |
| static readonly [ASE](../../aspose.threed/fileformat/ase/) | 3D Studio Max का ASCII सीन एक्सपोर्टर फ़ॉर्मेट। |
| static readonly [Aspose3DWeb](../../aspose.threed/fileformat/aspose3dweb/) | Aspose.3D वेब फ़ॉर्मेट। |
| static readonly [Blender](../../aspose.threed/fileformat/blender/) | Blender का 3D फ़ाइल फ़ॉर्मेट |
| static readonly [Collada](../../aspose.threed/fileformat/collada/) | Collada फ़ाइल फ़ॉर्मेट |
| static readonly [Discreet3DS](../../aspose.threed/fileformat/discreet3ds/) | 3D Studio का फ़ाइल फ़ॉर्मेट |
| static readonly [DXF](../../aspose.threed/fileformat/dxf/) | AutoCAD DXF |
| static readonly [FBX6100ASCII](../../aspose.threed/fileformat/fbx6100ascii/) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 6.1.0 के साथ |
| static readonly [FBX6100Binary](../../aspose.threed/fileformat/fbx6100binary/) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 6.1.0 के साथ |
| static readonly [FBX7200ASCII](../../aspose.threed/fileformat/fbx7200ascii/) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.2.0 के साथ |
| static readonly [FBX7200Binary](../../aspose.threed/fileformat/fbx7200binary/) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.2.0 के साथ |
| static readonly [FBX7300ASCII](../../aspose.threed/fileformat/fbx7300ascii/) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.3.0 के साथ |
| static readonly [FBX7300Binary](../../aspose.threed/fileformat/fbx7300binary/) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.3.0 के साथ |
| static readonly [FBX7400ASCII](../../aspose.threed/fileformat/fbx7400ascii/) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.4.0 के साथ |
| static readonly [FBX7400Binary](../../aspose.threed/fileformat/fbx7400binary/) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.4.0 के साथ |
| static readonly [FBX7500ASCII](../../aspose.threed/fileformat/fbx7500ascii/) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.5.0 के साथ |
| static readonly [FBX7500Binary](../../aspose.threed/fileformat/fbx7500binary/) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.5.0 के साथ |
| static readonly [FBX7600ASCII](../../aspose.threed/fileformat/fbx7600ascii/) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.6.0 के साथ |
| static readonly [FBX7600Binary](../../aspose.threed/fileformat/fbx7600binary/) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.6.0 के साथ |
| static readonly [FBX7700ASCII](../../aspose.threed/fileformat/fbx7700ascii/) | ASCII FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.7.0 के साथ |
| static readonly [FBX7700Binary](../../aspose.threed/fileformat/fbx7700binary/) | Binary FBX फ़ाइल फ़ॉर्मेट, संस्करण 7.7.0 के साथ |
| static readonly [GLTF](../../aspose.threed/fileformat/gltf/) | Khronos Group का glTF |
| static readonly [GLTF2](../../aspose.threed/fileformat/gltf2/) | Khronos Group का glTF संस्करण 2.0 |
| static readonly [GLTF2_Binary](../../aspose.threed/fileformat/gltf2_binary/) | Khronos Group का glTF संस्करण 2.0 |
| static readonly [GLTF_Binary](../../aspose.threed/fileformat/gltf_binary/) | Khronos Group का glTF बाइनरी फ़ॉर्मेट में |
| static readonly [HTML5](../../aspose.threed/fileformat/html5/) | HTML5 फ़ाइल |
| static readonly [IFC](../../aspose.threed/fileformat/ifc/) | ISO 16739-1 Industry Foundation Classes डेटा मॉडल। |
| static readonly [MayaASCII](../../aspose.threed/fileformat/mayaascii/) | Autodesk Maya ASCII फ़ॉर्मेट में |
| static readonly [MayaBinary](../../aspose.threed/fileformat/mayabinary/) | Autodesk Maya बाइनरी फ़ॉर्मेट में |
| static readonly [Pcd](../../aspose.threed/fileformat/pcd/) | ASCII मोड में PCL पॉइंट क्लाउड डेटा फ़ाइल |
| static readonly [PcdBinary](../../aspose.threed/fileformat/pcdbinary/) | बाइनरी मोड में PCL पॉइंट क्लाउड डेटा फ़ाइल |
| static readonly [SiemensJT8](../../aspose.threed/fileformat/siemensjt8/) | Siemens JT फ़ाइल संस्करण 8 |
| static readonly [SiemensJT9](../../aspose.threed/fileformat/siemensjt9/) | Siemens JT फ़ाइल संस्करण 9 |
| static readonly [STLASCII](../../aspose.threed/fileformat/stlascii/) | ASCII STL फ़ाइल फ़ॉर्मेट |
| static readonly [STLBinary](../../aspose.threed/fileformat/stlbinary/) | बाइनरी STL फ़ाइल फ़ॉर्मेट |
| static readonly [Universal3D](../../aspose.threed/fileformat/universal3d/) | Universal3D फ़ाइल फ़ॉर्मेट |
| static readonly [USD](../../aspose.threed/fileformat/usd/) | यूनिवर्सल सीन डिस्क्रिप्शन |
| static readonly [USDA](../../aspose.threed/fileformat/usda/) | ASCII फ़ॉर्मेट में यूनिवर्सल सीन डिस्क्रिप्शन। |
| static readonly [USDZ](../../aspose.threed/fileformat/usdz/) | कम्प्रेस्ड यूनिवर्सल सीन डिस्क्रिप्शन |
| static readonly [VRML](../../aspose.threed/fileformat/vrml/) | वर्चुअल रियलिटी मॉडलिंग लैंग्वेज |
| static readonly [WavefrontOBJ](../../aspose.threed/fileformat/wavefrontobj/) | Wavefront का Obj फ़ाइल फ़ॉर्मेट |
| static readonly [XBinary](../../aspose.threed/fileformat/xbinary/) | बाइनरी फ़ॉर्मेट में DirectX X फ़ाइल |
| static readonly [XText](../../aspose.threed/fileformat/xtext/) | बाइनरी फ़ॉर्मेट में DirectX X फ़ाइल |
| static readonly [Xyz](../../aspose.threed/fileformat/xyz/) | Xyz पॉइंट क्लाउड फ़ाइल |
| static readonly [Zip](../../aspose.threed/fileformat/zip/) | ज़िप आर्काइव जिसमें अन्य 3D फ़ाइल फ़ॉर्मेट शामिल हैं। |
| static readonly [Draco](../../aspose.threed/fileformat/draco/) | Google Draco मेष |
| static readonly [Microsoft3MF](../../aspose.threed/fileformat/microsoft3mf/) | Microsoft 3D मैन्युफैक्चरिंग फ़ॉर्मेट |
| static readonly [PDF](../../aspose.threed/fileformat/pdf/) | Adobe का पोर्टेबल डॉक्यूमेंट फ़ॉर्मेट |
| static readonly [PLY](../../aspose.threed/fileformat/ply/) | पॉलीगॉन फ़ाइल फ़ॉर्मेट या Stanford ट्रायंगल फ़ॉर्मेट |
| static readonly [RvmBinary](../../aspose.threed/fileformat/rvmbinary/) | बाइनरी फ़ॉर्मेट में AVEVA प्लांट डिज़ाइन मैनेजमेंट सिस्टम मॉडल |
| static readonly [RvmText](../../aspose.threed/fileformat/rvmtext/) | टेक्स्ट फ़ॉर्मेट में AVEVA प्लांट डिज़ाइन मैनेजमेंट सिस्टम मॉडल |

### देखें भी

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


