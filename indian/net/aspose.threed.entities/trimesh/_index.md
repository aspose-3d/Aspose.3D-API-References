---
title: "क्लास TriMesh"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.TriMesh क्लास। एक TriMesh में कच्चा डेटा होता है जिसे GPU सीधे उपयोग कर सकता है। यह क्लास एक उपयोगिता है जो केवल प्रति-वर्टेक्स डेटा वाले मेष को बनाने में मदद करती है।"
type: docs
weight: 790
url: /hi/net/aspose.threed.entities/trimesh/
---
## TriMesh class

एक TriMesh कच्चा डेटा रखता है जिसे GPU सीधे उपयोग कर सकता है। यह क्लास एक उपयोगिता है जो केवल प्रति-वर्टेक्स डेटा वाले मेष को बनाने में मदद करती है।

```csharp
public class TriMesh : Entity, IEnumerable<Vertex>
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TriMesh](trimesh/)(string, VertexDeclaration) | एक `TriMesh` का उदाहरण प्रारंभ करें |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Capacity](../../aspose.threed.entities/trimesh/capacity/) { get; } | प्री-एलोकेटेड वर्टेक्स की क्षमता। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [IndicesCount](../../aspose.threed.entities/trimesh/indicescount/) { get; } | इस `TriMesh` में सूचकांकों की गिनती। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [UnmergedVerticesCount](../../aspose.threed.entities/trimesh/unmergedverticescount/) { get; } | [`BeginVertex`](./beginvertex/) और [`EndVertex`](./endvertex/) द्वारा पास किए गए अनमर्ज्ड वर्टेक्स की गिनती। |
| [VertexDeclaration](../../aspose.threed.entities/trimesh/vertexdeclaration/) { get; } | `TriMesh` का वर्टेक्स लेआउट। |
| [VerticesCount](../../aspose.threed.entities/trimesh/verticescount/) { get; } | इस `TriMesh` में वर्टेक्स की गिनती। |
| [VerticesSizeInBytes](../../aspose.threed.entities/trimesh/verticessizeinbytes/) { get; } | सभी वर्टेक्स का कुल आकार बाइट्स में |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [CopyFrom](../../aspose.threed.entities/trimesh/copyfrom/)(TriMesh, VertexDeclaration) | इनपुट से `TriMesh` को नई वर्टेक्स लेआउट के साथ कॉपी करें |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh)(Mesh, bool) | दिए गए मेष ऑब्जेक्ट से एक TriMesh बनाएं, वर्टेक्स घोषणा इनपुट मेष की संरचना पर आधारित है। |
| static [FromMesh](../../aspose.threed.entities/trimesh/frommesh/#frommesh_1)(VertexDeclaration, Mesh) | दिए गए मेष ऑब्जेक्ट से दिए गए वर्टेक्स लेआउट के साथ एक TriMesh बनाएं। |
| static [FromRawData](../../aspose.threed.entities/trimesh/fromrawdata/)(VertexDeclaration, byte[], int[], bool) | कच्चे डेटा से TriMesh बनाएं |
| [AddTriangle](../../aspose.threed.entities/trimesh/addtriangle/)(int, int, int) | एक नया त्रिभुज जोड़ें |
| [BeginVertex](../../aspose.threed.entities/trimesh/beginvertex/)() | वर्टेक्स जोड़ना शुरू करें |
| [EndVertex](../../aspose.threed.entities/trimesh/endvertex/)() | वर्टेक्स जोड़ना समाप्त करें |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetEnumerator](../../aspose.threed.entities/trimesh/getenumerator/)() | [`Vertex`](../../aspose.threed.utilities/vertex/) को क्रमबद्ध करने के लिए एन्यूमरेटर प्राप्त करें |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray)(out int[]) |  |
| [IndicesToArray](../../aspose.threed.entities/trimesh/indicestoarray/#indicestoarray_1)(out ushort[]) |  |
| [LoadVerticesFromBytes](../../aspose.threed.entities/trimesh/loadverticesfrombytes/)(byte[]) | बाइट्स से वर्टेक्स लोड करें, बाइट्स की लंबाई वर्टेक्स आकार का पूर्णांक गुणज होना चाहिए। |
| [ReadDouble](../../aspose.threed.entities/trimesh/readdouble/)(int, VertexField) | डबल फ़ील्ड पढ़ें |
| [ReadFloat](../../aspose.threed.entities/trimesh/readfloat/)(int, VertexField) | फ़्लोट फ़ील्ड पढ़ें |
| [ReadFVector2](../../aspose.threed.entities/trimesh/readfvector2/)(int, VertexField) | vector2 फ़ील्ड पढ़ें |
| [ReadFVector3](../../aspose.threed.entities/trimesh/readfvector3/)(int, VertexField) | vector3 फ़ील्ड पढ़ें |
| [ReadFVector4](../../aspose.threed.entities/trimesh/readfvector4/)(int, VertexField) | vector4 फ़ील्ड पढ़ें |
| [ReadVector2](../../aspose.threed.entities/trimesh/readvector2/)(int, VertexField) | vector2 फ़ील्ड पढ़ें |
| [ReadVector3](../../aspose.threed.entities/trimesh/readvector3/)(int, VertexField) | vector3 फ़ील्ड पढ़ें |
| [ReadVector4](../../aspose.threed.entities/trimesh/readvector4/)(int, VertexField) | vector4 फ़ील्ड पढ़ें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| override [ToString](../../aspose.threed.entities/trimesh/tostring/)() | `TriMesh` का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है |
| [VerticesToArray](../../aspose.threed.entities/trimesh/verticestoarray/)() | वर्टेक्स डेटा को बाइट एरे में परिवर्तित करें |
| [Write16bIndicesTo](../../aspose.threed.entities/trimesh/write16bindicesto/)(Stream) | इंडेक्स डेटा को 16-बिट पूर्णांक के रूप में स्ट्रीम में लिखें |
| [Write32bIndicesTo](../../aspose.threed.entities/trimesh/write32bindicesto/)(Stream) | इंडेक्स डेटा को 32‑बिट पूर्णांक के रूप में स्ट्रीम में लिखें |
| [WriteVerticesTo](../../aspose.threed.entities/trimesh/writeverticesto/)(Stream) | निर्दिष्ट स्ट्रीम में वर्टिस डेटा लिखें |

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

* class [Entity](../../aspose.threed/entity/)
* class [Vertex](../../aspose.threed.utilities/vertex/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


