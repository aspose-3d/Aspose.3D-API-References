---
title: "Class RvmSaveOptions"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Formats.RvmSaveOptions class. Aveka PDMS RVM फ़ाइल के लिए सहेजने विकल्प।"
type: docs
weight: 1480
url: /hi/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Aveva PDMS RVM फ़ाइल के लिए सहेजने के विकल्प।

```csharp
public class RvmSaveOptions : SaveOptions
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | `RvmSaveOptions` का कंस्ट्रक्टर |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | `RvmSaveOptions` का कंस्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | एट्रिब्यूट सूची फ़ाइल का फ़ाइल नाम प्राप्त या सेट करता है, निर्यातक इस प्रॉपर्टी के अनिर्धारित होने पर .rvm फ़ाइल नाम के आधार पर एक नाम उत्पन्न करेगा, डिफ़ॉल्ट मान null है। |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | निर्यात किए जाने वाले एट्रिब्यूट्स के प्रीफ़िक्स को प्राप्त या सेट करता है, निर्यातित प्रॉपर्टी में कोई प्रीफ़िक्स नहीं होगा, विभिन्न प्रीफ़िक्स वाली कस्टम प्रॉपर्टी निर्यात नहीं होंगी, डिफ़ॉल्ट मान 'rvm:' है। उदाहरण के लिए यदि प्रॉपर्टी rvm:Refno=345 है, तो निर्यातित एट्रिब्यूट Refno = 345 होगा, प्रीफ़िक्स हटा दिया जाएगा। |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | लेखक जानकारी, डिफ़ॉल्ट मान '3d@aspose' है। |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | इस फ़ाइल को निर्यात करने वाला टाइमस्टैम्प, डिफ़ॉल्ट मान वर्तमान समय है। |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सा एन्कोडिंग उपयोग किया जाए। |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात करने के लिए प्राप्त या सेट करता है, डिफ़ॉल्ट मान false है। |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | दृश्य में उपयोग की गई टेक्सचर को आउटपुट डायरेक्टरी में कॉपी करने का प्रयास करें। |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान Save/Load विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | एक्सपोर्ट/इम्पोर्ट दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करने पर उपयोगी होता है। |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | फ़ाइल हेडर में फ़ाइल नोट। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को उपयोगकर्ता को संभालने की अनुमति देता है। |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि RVM में एट्रिब्यूट कैसे निर्यात करें।

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//एट्रिब्यूट निर्यात करने के लिए नोड का नाम आवश्यक है।
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//rvm: प्रीफ़िक्स वाली प्रॉपर्टीज़ निर्यात की जाएँगी।
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### देखें भी

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


