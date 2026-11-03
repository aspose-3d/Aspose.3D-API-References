---
title: "क्लास VertexElementMaterial"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.VertexElementMaterial क्लास। निर्दिष्ट घटकों के लिए मैटेरियल इंडेक्स परिभाषित करता है। एक नोड के पास कई मैटेरियल हो सकते हैं, VertexElementMaterial का उपयोग ज्यामिति के विभिन्न भागों को विभिन्न मैटेरियल में रेंडर करने के लिए किया जाता है"
type: docs
weight: 880
url: /hi/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

निर्दिष्ट घटकों के लिए मैटेरियल इंडेक्स परिभाषित करता है। एक नोड के पास कई मैटेरियल हो सकते हैं, `VertexElementMaterial` का उपयोग ज्यामिति के विभिन्न भागों को विभिन्न मैटेरियल में रेंडर करने के लिए किया जाता है।

```csharp
public class VertexElementMaterial : VertexElement
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | `VertexElementMaterial` क्लास का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | इंडेक्स डेटा प्राप्त करता है |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | तत्व कैसे मैप किया गया है, इसे प्राप्त या सेट करता है। |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | तत्व कैसे संदर्भित किया गया है, इसे प्राप्त या सेट करता है। |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | [`VertexElement`](../vertexelement/) का प्रकार प्राप्त करता है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | डायरेक्ट और इंडेक्स एरेज़ से सभी तत्वों को हटा देता है। |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | इंडेक्स लोड करें |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | वर्टेक्स तत्व का स्ट्रिंग प्रतिनिधित्व। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि बॉक्स के विभिन्न फेस को विभिन्न मैटेरियल कैसे असाइन करें।

```csharp
// बॉक्स का एक मेष बनाएं (बॉक्स 6 प्लेनों से बना होता है)
Mesh box = (new Box()).ToMesh();
// इस मेष पर एक मैटेरियल एलिमेंट बनाएं
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// और प्रत्येक प्लेन के लिए अलग मैटेरियल इंडेक्स निर्दिष्ट करें
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### देखें भी

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


