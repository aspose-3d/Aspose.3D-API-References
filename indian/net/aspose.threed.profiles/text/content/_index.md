---
title: "Text.Content"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Text गुण. पाठ की सामग्री"
type: docs
weight: 20
url: /hi/net/aspose.threed.profiles/text/content/
---
## Text.Content property

पाठ की सामग्री

```csharp
public string Content { get; set; }
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

* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


