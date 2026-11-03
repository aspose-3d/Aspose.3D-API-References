---
title: "Node.GlobalTransform"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node property. ग्लोबल ट्रांसफ़ॉर्म प्राप्त करता है"
type: docs
weight: 70
url: /hi/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

ग्लोबल ट्रांसफ़ॉर्म प्राप्त करता है।

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

ग्लोबल ट्रांसफ़ॉर्म।

## उदाहरण

निम्नलिखित कोड दिखाता है कि नोड के ग्लोबल ट्रांसफ़ॉर्म को कैसे पढ़ा जाए

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//बॉक्स को (10, 0, 0) पर रखें
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### देखें भी

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


