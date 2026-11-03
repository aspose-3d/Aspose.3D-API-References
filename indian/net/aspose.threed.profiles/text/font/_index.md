---
title: "Text.Font"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Text गुण. पाठ का फ़ॉन्ट"
type: docs
weight: 30
url: /hi/net/aspose.threed.profiles/text/font/
---
## Text.Font property

पाठ का फ़ॉन्ट।

```csharp
public FontFile Font { get; set; }
```

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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


