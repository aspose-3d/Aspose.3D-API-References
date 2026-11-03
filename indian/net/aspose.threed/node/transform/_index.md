---
title: "Node.Transform"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node property. स्थानीय रूपांतरण प्राप्त करता है।"
type: docs
weight: 120
url: /hi/net/aspose.threed/node/transform/
---
## Node.Transform property

लोकल ट्रांसफ़ॉर्म प्राप्त करता है।

```csharp
public Transform Transform { get; }
```

### Property Value

रूपांतरण।

## उदाहरण

निम्नलिखित कोड दिखाता है कि नोड का ट्रांसफ़ॉर्म कैसे बदलें:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//बॉक्स को (10, 0, 0) पर रखें
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### देखें भी

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


