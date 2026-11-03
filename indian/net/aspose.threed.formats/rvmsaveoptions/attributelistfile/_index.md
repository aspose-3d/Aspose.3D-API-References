---
title: "RvmSaveOptions.AttributeListFile"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "RvmSaveOptions प्रॉपर्टी। फ़ाइल नाम प्राप्त करता है या सेट करता है जो एट्रिब्यूट सूची फ़ाइल निर्यातकर्ता .rvm फ़ाइल नाम के आधार पर उत्पन्न करेगा जब यह प्रॉपर्टी अपरिभाषित हो, डिफ़ॉल्ट मान null है।"
type: docs
weight: 20
url: /hi/net/aspose.threed.formats/rvmsaveoptions/attributelistfile/
---
## RvmSaveOptions.AttributeListFile property

एट्रिब्यूट सूची फ़ाइल का फ़ाइल नाम प्राप्त या सेट करता है, निर्यातक इस प्रॉपर्टी के अनिर्धारित होने पर .rvm फ़ाइल नाम के आधार पर एक नाम उत्पन्न करेगा, डिफ़ॉल्ट मान null है।

```csharp
public string AttributeListFile { get; set; }
```

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

* class [RvmSaveOptions](../)
* namespace [Aspose.ThreeD.Formats](../../rvmsaveoptions/)
* assembly [Aspose.3D](../../../)


