---
title: "क्लास PolygonModifier"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.PolygonModifier क्लास। पॉलीगॉन को संशोधित करने के लिए उपयोगिताएँ"
type: docs
weight: 620
url: /hi/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

बहुभुजों को संशोधित करने के लिए उपयोगिताएँ

```csharp
public class PolygonModifier
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | सभी ज्यामितियों के कंट्रोल पॉइंट्स पर ट्रांसफ़ॉर्म मैट्रिक्स लागू करें |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | यह मेष पर टैन्जेंट और बाइनॉर्मल बनाएगा। सामान्य (Normal) आवश्यक है; यदि मेष पर सामान्य मौजूद नहीं है, तो यह स्थिति से सामान्य डेटा भी बनाएगा। UV भी आवश्यक है, यदि कोई UV नहीं मिला तो एक अपवाद उत्पन्न होगा। |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | यह सीन की सभी मेषों पर टैन्जेंट और बाइनॉर्मल बनाएगा। सामान्य (Normal) आवश्यक है; यदि मेष पर सामान्य मौजूद नहीं है, तो यह स्थिति से सामान्य डेटा भी बनाएगा। UV भी आवश्यक है, यदि कोई UV परिभाषित नहीं है तो मेष को अनदेखा किया जाएगा। |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | Mesh परिभाषा से सामान्य डेटा उत्पन्न करें |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | दिए गए इनपुट मेष से UV डेटा उत्पन्न करें |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | दिए गए इनपुट मेष और निर्दिष्ट सामान्य डेटा से UV डेटा उत्पन्न करें। |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | पूरे नोड को एकल ट्रांसफ़ॉर्म्ड मेष में परिवर्तित करें। सामान्य/टेक्सचर निर्देशांक जैसे वर्टेक्स तत्व अभी समर्थित नहीं हैं। |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | पूरे सीन को एकल ट्रांसफ़ॉर्म्ड मेष में परिवर्तित करें। सामान्य/टेक्सचर निर्देशांक जैसे वर्टेक्स तत्व अभी समर्थित नहीं हैं। |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | इस नोड में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)। |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | इस सीन में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)। |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | `[`VertexElementMaterial`](../vertexelementmaterial/)` द्वारा मेष को उप-मे़श में विभाजित करें। प्रत्येक उप-मे़श केवल एक सामग्री का उपयोग करेगा। मूल मे़श में कोई परिवर्तन नहीं होगा। |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | `[`VertexElementMaterial`](../vertexelementmaterial/)` द्वारा मेष को उप-मे़श में विभाजित करें। प्रत्येक उप-मे़श केवल एक सामग्री का उपयोग करेगा। दृश्य के सभी नोड्स पर मेष विभाजन करें। |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | `[`VertexElementMaterial`](../vertexelementmaterial/)` द्वारा मेष को उप-मे़श में विभाजित करें। प्रत्येक उप-मे़श केवल एक सामग्री का उपयोग करेगा। एक नोड पर मेष विभाजन करें। |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | बहुभुज-आधारित मेष को पूर्ण त्रिकोण मेष में परिवर्तित करें। |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | सभी बहुभुज-आधारित मेषों को पूर्ण त्रिकोण मेष में परिवर्तित करें। |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### देखें भी

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


