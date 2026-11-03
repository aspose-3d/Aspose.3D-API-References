---
title: "Node.Visible"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node प्रॉपर्टी। नोड को दिखाने के लिए प्राप्त या सेट करता है"
type: docs
weight: 130
url: /hi/net/aspose.threed/node/visible/
---
## Node.Visible property

नोड को दिखाने के लिए प्राप्त या सेट करता है

```csharp
public bool Visible { get; set; }
```

## उदाहरण

निम्नलिखित कोड दिखाता है कि एक अदृश्य नोड कैसे बनाया जाए

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


