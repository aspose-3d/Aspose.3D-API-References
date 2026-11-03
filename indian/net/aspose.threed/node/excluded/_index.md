---
title: "Node.Excluded"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node प्रॉपर्टी। निर्यात के दौरान इस नोड और सभी चाइल्ड नोड/एंटिटीज़ को बाहर रखने के लिए प्राप्त या सेट करता है"
type: docs
weight: 60
url: /hi/net/aspose.threed/node/excluded/
---
## Node.Excluded property

एक्सपोर्टिंग के दौरान इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखना है या नहीं, प्राप्त करता है या सेट करता है।

```csharp
public bool Excluded { get; set; }
```

## उदाहरण

निम्नलिखित कोड दिखाता है कि निर्यात से निर्दिष्ट नोड को कैसे बाहर रखा जाए

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


