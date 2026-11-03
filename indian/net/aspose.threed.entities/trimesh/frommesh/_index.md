---
title: "TriMesh.FromMesh"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TriMesh विधि। दिए गए mesh ऑब्जेक्ट और दिए गए vertex लेआउट से एक TriMesh बनाएं"
type: docs
weight: 30
url: /hi/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

दिए गए मेष ऑब्जेक्ट से दिए गए वर्टेक्स लेआउट के साथ एक TriMesh बनाएं।

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| घोषणा | VertexDeclaration | Vertex का प्रकार परिभाषा, या मेमोरी लेआउट |
| mesh | मेश | स्रोत mesh |

### रिटर्न वैल्यू

इनपुट mesh से परिवर्तित TriMesh का उदाहरण, जिसमें निर्दिष्ट vertex की मेमोरी लेआउट है

## उदाहरण

निम्नलिखित कोड दिखाता है कि कस्टम मेमोरी लेआउट के साथ TriMesh कैसे बनाएं, और इसे फ़ाइल में निर्यात करें।

```csharp
//वर्टेक्स घोषणा को इस प्रकार परिभाषित करें: {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//निर्दिष्ट मेमोरी लेआउट का उपयोग करके मेष को ट्राई‑मेश में बदलें
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//इसे स्ट्रीम में सहेजें, 115 वर्टिस * प्रति वर्टिस 32 बाइट
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //इंडेक्स को ushort के रूप में स्ट्रीम में सहेजें, 504 इंडेक्स * प्रति इंडेक्स 2 बाइट
    triMesh.Write16bIndicesTo(stream);
}
```

### देखें भी

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

दिए गए मेष ऑब्जेक्ट से एक TriMesh बनाएं, वर्टेक्स घोषणा इनपुट मेष की संरचना पर आधारित है।

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mesh | मेश |  |
| useFloat | Boolean | प्रत्येक vertex तत्व घटक के लिए double प्रकार के बजाय float प्रकार का उपयोग करें। |

### रिटर्न वैल्यू

दिए गए [`Mesh`](../../mesh/) से उत्पन्न [`TriMesh`](../)

## उदाहरण

निम्नलिखित कोड दिखाता है कि कस्टम मेमोरी लेआउट के साथ TriMesh कैसे बनाएं, और इसे फ़ाइल में निर्यात करें।

```csharp
//वर्टेक्स घोषणा को इस प्रकार परिभाषित करें: {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//निर्दिष्ट मेमोरी लेआउट का उपयोग करके मेष को ट्राई‑मेश में बदलें
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//इसे स्ट्रीम में सहेजें, 115 वर्टिस * प्रति वर्टिस 32 बाइट
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //इंडेक्स को ushort के रूप में स्ट्रीम में सहेजें, 504 इंडेक्स * प्रति इंडेक्स 2 बाइट
    triMesh.Write16bIndicesTo(stream);
}
```

### देखें भी

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


