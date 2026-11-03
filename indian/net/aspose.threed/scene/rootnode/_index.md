---
title: "Scene.RootNode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene प्रॉपर्टी। सीन का रूट नोड प्राप्त करता है"
type: docs
weight: 90
url: /hi/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

दृश्य का मूल नोड प्राप्त करता है।

```csharp
public Node RootNode { get; }
```

### Property Value

रूट नोड।

## उदाहरण

निम्नलिखित कोड दिखाता है कि रूट नोड से जुड़ी बॉक्स एंटिटी के साथ नोड कैसे बनाएं।

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### देखें भी

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


