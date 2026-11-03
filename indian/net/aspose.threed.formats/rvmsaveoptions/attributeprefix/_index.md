---
title: "RvmSaveOptions.AttributePrefix"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "RvmSaveOptions प्रॉपर्टी। निर्यात की जाने वाली एट्रिब्यूट्स का प्रीफ़िक्स प्राप्त करता है या सेट करता है। निर्यातित प्रॉपर्टी में कोई प्रीफ़िक्स नहीं होगा; अलग प्रीफ़िक्स वाले कस्टम प्रॉपर्टी निर्यात नहीं होंगे। डिफ़ॉल्ट मान rvm है। उदाहरण के लिए यदि प्रॉपर्टी rvmRefno345 है, तो निर्यातित एट्रिब्यूट Refno 345 होगा, प्रीफ़िक्स हटाया जाएगा"
type: docs
weight: 30
url: /hi/net/aspose.threed.formats/rvmsaveoptions/attributeprefix/
---
## RvmSaveOptions.AttributePrefix property

निर्यात किए जाने वाले एट्रिब्यूट्स के प्रीफ़िक्स को प्राप्त या सेट करता है, निर्यातित प्रॉपर्टी में कोई प्रीफ़िक्स नहीं होगा, विभिन्न प्रीफ़िक्स वाली कस्टम प्रॉपर्टी निर्यात नहीं होंगी, डिफ़ॉल्ट मान 'rvm:' है। उदाहरण के लिए यदि प्रॉपर्टी rvm:Refno=345 है, तो निर्यातित एट्रिब्यूट Refno = 345 होगा, प्रीफ़िक्स हटा दिया जाएगा।

```csharp
public string AttributePrefix { get; set; }
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


