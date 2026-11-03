---
title: "FontFile.FromFile"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FontFile मेथड। फ़ाइल नाम से FontFile लोड करें"
type: docs
weight: 10
url: /hi/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

फ़ाइल नाम से FontFile लोड करें

```csharp
public static FontFile FromFile(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ॉन्ट फ़ाइल का पथ |

### रिटर्न वैल्यू

FontFile उदाहरण

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | फ़ाइल से पढ़ने में विफल होने पर थ्रो किया जाता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि निर्दिष्ट फ़ॉन्ट फ़ाइल का उपयोग करके पाठ से 3D मेष कैसे बनाया जाए।

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### देखें भी

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


