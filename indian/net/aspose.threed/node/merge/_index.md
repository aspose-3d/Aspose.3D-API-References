---
title: "Node.Merge"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node मेथड। नोड के नीचे की सभी चीज़ों को अलग करता है और उन्हें वर्तमान नोड से जोड़ता है"
type: docs
weight: 220
url: /hi/net/aspose.threed/node/merge/
---
## Node.Merge method

नोड के अंतर्गत सभी चीज़ों को अलग करें और उन्हें वर्तमान नोड से संलग्न करें।

```csharp
public void Merge(Node node)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नोड | नोड |  |

## उदाहरण

निम्नलिखित कोड दिखाता है कि दो 3D फ़ाइलों को एक फ़ाइल में कैसे मर्ज किया जाए

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


