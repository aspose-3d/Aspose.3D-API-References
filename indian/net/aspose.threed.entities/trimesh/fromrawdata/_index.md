---
title: "TriMesh.FromRawData"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TriMesh मेथड। कच्चे डेटा से TriMesh बनाएं"
type: docs
weight: 40
url: /hi/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

कच्चे डेटा से TriMesh बनाएं

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| vd | VertexDeclaration | Vertex घोषणा, कम से कम एक फ़ील्ड होना चाहिए। |
| vertices | Byte[] | इनपुट वर्टेक्स डेटा, वर्टेक्स की न्यूनतम लंबाई vertex घोषणा के आकार के बराबर या उससे अधिक होनी चाहिए |
| सूचकांक | Int32[] | त्रिभुज सूचकांक |
| generateVertexMapping | Boolean | प्रत्येक वर्टेक्स के लिए [`Vertex`](../../../aspose.threed.utilities/vertex/) उत्पन्न करें, जो केवल सीरियलाइज़ेशन/डिसीरियलाइज़ेशन के लिए आवश्यक नहीं है। |

### रिटर्न वैल्यू

इनपुट बाइट एरे को संलग्न करने वाला [`TriMesh`](../) इंस्टेंस।

## टिप्पणियाँ

रिटर्न किया गया TriMesh प्रदर्शन के लिए इनपुट बाइट एरे को कॉपी नहीं करेगा, एरे में बाहरी परिवर्तन इस इंस्टेंस पर प्रतिबिंबित होंगे।

## उदाहरण

निम्नलिखित कोड दिखाता है कि कच्चे बाइट्स से TriMesh कैसे बनाएं, यह आपके अपने 3D फ़ॉर्मेट बनाने पर उपयोगी है।

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
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### देखें भी

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


