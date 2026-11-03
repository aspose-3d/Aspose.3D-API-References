---
title: "Node.ChildNodes"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node property. चाइल्ड नोड्स प्राप्त करता है"
type: docs
weight: 30
url: /hi/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

चाइल्ड नोड्स प्राप्त करता है।

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

नोड्स।

## उदाहरण

निम्नलिखित कोड दिखाता है कि रूट नोड के चाइल्ड नोड को कैसे सूचीबद्ध किया जाए

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //अपना काम करें
}
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


