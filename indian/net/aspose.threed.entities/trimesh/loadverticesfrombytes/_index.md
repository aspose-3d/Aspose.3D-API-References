---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TriMesh विधि। बाइट्स से वर्टेक्स लोड करें, बाइट्स की लंबाई वर्टेक्स आकार का पूर्णांक गुणज होना चाहिए"
type: docs
weight: 160
url: /hi/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

बाइट्स से वर्टेक्स लोड करें, बाइट्स की लंबाई वर्टेक्स आकार का पूर्णांक गुणज होना चाहिए।

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक खाली TriMesh बनाएं और मैन्युअल रूप से कच्चे बाइट्स से वर्टेक्स लोड करें।

```csharp
var indices = new int[] { 0,  1,  2 };
var vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
//निर्दिष्ट वर्टेक्स घोषणा के साथ एक खाली TriMesh बनाएं
var triMesh = new TriMesh("", vd);
//बाइट्स से सीधे वर्टेक्स लोड करें
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//निर्दिष्ट वर्टेक्स घोषणा के साथ एक खाली TriMesh बनाएं
var triMesh = new TriMesh("", vd);
//बाइट्स से सीधे वर्टेक्स लोड करें
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### देखें भी

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


