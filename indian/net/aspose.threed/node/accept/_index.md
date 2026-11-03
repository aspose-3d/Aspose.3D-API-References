---
title: "Node.Accept"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node मेथड। सभी वंशज नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और नोड के साथ विज़िटर को कॉल करता है। विज़िटर false लौटाकर वॉकथ्रू को रोक सकता है।"
type: docs
weight: 140
url: /hi/net/aspose.threed/node/accept/
---
## Node.Accept method

सभी अवनति नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और नोड के साथ विज़िटर को कॉल करता है। विज़िटर false लौटाकर वॉक-थ्रू को रोक सकता है।

```csharp
public bool Accept(NodeVisitor visitor)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| विज़िटर | NodeVisitor | विज़िटर कॉलबैक नोड को विज़िट करने के लिए |

### रिटर्न वैल्यू

true का अर्थ है विज़िटर ने वॉकथ्रू को तोड़ दिया है।

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन से सभी मेषेज़ कैसे प्राप्त करें

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //खोज जारी रखें
    return true;
});
```

### देखें भी

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


