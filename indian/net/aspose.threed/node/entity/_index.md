---
title: "Node.Entity"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node property. इस नोड से जुड़ी पहली इकाई को प्राप्त करता है या सेट करता है; सेट करने पर अन्य इकाइयाँ साफ़ हो जाएँगी।"
type: docs
weight: 50
url: /hi/net/aspose.threed/node/entity/
---
## Node.Entity property

इस नोड से जुड़ी पहली entity को प्राप्त करता है या सेट करता है; यदि सेट किया जाता है, तो अन्य entities को साफ़ कर देगा।

```csharp
public Entity Entity { get; set; }
```

### Property Value

नोड इकाई।

## उदाहरण

निम्नलिखित कोड दिखाता है कि रूट नोड के तहत नया चाइल्ड नोड कैसे बनाया जाए।

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### देखें भी

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


