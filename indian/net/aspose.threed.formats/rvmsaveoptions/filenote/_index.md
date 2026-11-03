---
title: "RvmSaveOptions.FileNote"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "RvmSaveOptions प्रॉपर्टी। फ़ाइल हेडर में फ़ाइल नोट"
type: docs
weight: 70
url: /hi/net/aspose.threed.formats/rvmsaveoptions/filenote/
---
## RvmSaveOptions.FileNote property

फ़ाइल हेडर में फ़ाइल नोट।

```csharp
public string FileNote { get; set; }
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


