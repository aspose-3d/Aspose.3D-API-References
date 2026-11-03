---
title: "RvmSaveOptions.ExportAttributes"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "RvmSaveOptions प्रॉपर्टी। एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात करने की स्थिति प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान false है"
type: docs
weight: 60
url: /hi/net/aspose.threed.formats/rvmsaveoptions/exportattributes/
---
## RvmSaveOptions.ExportAttributes property

एट्रिब्यूट सूची को बाहरी .att फ़ाइल में निर्यात करने के लिए प्राप्त या सेट करता है, डिफ़ॉल्ट मान false है।

```csharp
public bool ExportAttributes { get; set; }
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


