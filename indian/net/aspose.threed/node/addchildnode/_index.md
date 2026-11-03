---
title: "Node.AddChildNode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node मेथड। इस नोड में एक चाइल्ड नोड जोड़ें"
type: docs
weight: 150
url: /hi/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

इस नोड में एक चाइल्ड नोड जोड़ें

```csharp
public void AddChildNode(Node node)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नोड | नोड | संलग्न करने के लिए चाइल्ड नोड |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन से सभी मेषेज़ कैसे प्राप्त करें

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//नए नोड को मैन्युअल रूप से जोड़ें
scene.RootNode.AddChildNode(newNode);
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


