---
title: "IOConfig.LookupPaths"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "IOConfig प्रॉपर्टी। कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को बाहरी फ़ाइल लोड करने के लिए खोजने की अनुमति देंगे"
type: docs
weight: 50
url: /hi/net/aspose.threed.formats/ioconfig/lookuppaths/
---
## IOConfig.LookupPaths property

कुछ फ़ाइलें जैसे OBJ बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

```csharp
public List<string> LookupPaths { get; set; }
```

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मैन्युअल रूप से लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें खोज सके

```csharp
var opt = new ObjLoadOptions();
//लुकअप पाथ्स निर्दिष्ट करें, ताकि टेक्सचर स्थित हो सकें।
opt.LookupPaths.Add("textures");
var scene = Scene.FromFile("input.obj", opt);
scene.Save("output.glb");
```

### देखें भी

* class [IOConfig](../)
* namespace [Aspose.ThreeD.Formats](../../ioconfig/)
* assembly [Aspose.3D](../../../)


