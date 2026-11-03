---
title: "TriMesh.CopyFrom"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TriMesh विधि। इनपुट से TriMesh को नई वर्टेक्स लेआउट के साथ कॉपी करें"
type: docs
weight: 20
url: /hi/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

इनपुट से नई वर्टेक्स लेआउट के साथ [`TriMesh`](../) को कॉपी करें

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इनपुट | TriMesh | कॉपी करने के लिए इनपुट TriMesh |
| vd | VertexDeclaration | आउटपुट TriMesh की नई वर्टेक्स घोषणा |

### रिटर्न वैल्यू

नई वर्टेक्स घोषणा के साथ एक नया TriMesh इंस्टेंस।

## उदाहरण

```csharp
//वर्टेक्स घोषणा को इस प्रकार परिभाषित करें: {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//एक mesh को TriMesh में परिवर्तित करें, लेआउट इनपुट mesh से स्वचालित रूप से अनुमानित किया जाता है
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//अब स्पष्ट मेमोरी लेआउट जो vd द्वारा परिभाषित है, का उपयोग करके पुराने TriMesh से नया TriMesh बनाएं
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### देखें भी

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


