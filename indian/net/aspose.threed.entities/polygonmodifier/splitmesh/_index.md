---
title: "PolygonModifier.SplitMesh"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PolygonModifier विधि। VertexElementMaterial द्वारा मेष को उप-मेश में विभाजित करें। प्रत्येक उप-मेश केवल एक सामग्री का उपयोग करेगा। एक नोड पर मेष विभाजन करें।"
type: docs
weight: 70
url: /hi/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

[`VertexElementMaterial`](../../vertexelementmaterial/) द्वारा मेष को उप-मेश में विभाजित करें। प्रत्येक उप-मेश केवल एक सामग्री का उपयोग करेगा। एक नोड पर मेष विभाजन करें।

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नोड | नोड |  |
| नीति | SplitMeshPolicy |  |
| createChildNodes | Boolean | प्रत्येक सब‑मेश के लिए चाइल्ड नोड्स बनाएं। |
| removeOldMesh | Boolean | स्प्लिट के बाद पुराना मेष हटाएँ, यदि यह पैरामीटर फ़ॉल्स है, तो पुराना और नया मेष साथ‑साथ मौजूद रहेंगे। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को सब‑मेश में कैसे विभाजित किया जाए।

```csharp
// बॉक्स का एक मेष बनाएं (बॉक्स 6 प्लेनों से बना होता है)
Mesh box = (new Box()).ToMesh();
// इस मेष पर एक मैटेरियल एलिमेंट बनाएं
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// और प्रत्येक प्लेन के लिए अलग मैटेरियल इंडेक्स निर्दिष्ट करें
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// अब इसे 6 सब‑मेश में विभाजित करें, हमने प्रत्येक प्लेन पर 6 अलग-अलग सामग्री निर्दिष्ट की हैं, प्रत्येक प्लेन एक सब‑मेश बन जाएगा।
// हमने CloneData नीति का उपयोग किया, प्रत्येक प्लेन में समान कंट्रोल पॉइंट जानकारी या कंट्रोल पॉइंट‑आधारित वर्टेक्स एलिमेंट जानकारी होगी।
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// अब इसे 2 सब‑मेश में विभाजित करें, पहला मेष 0/1/2 प्लेनों को शामिल करेगा, और दूसरा मेष 3/4/5वें प्लेनों को शामिल करेगा।
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// हमने CompactData नीति का उपयोग किया, प्रत्येक प्लेन की अपनी कंट्रोल पॉइंट जानकारी या कंट्रोल पॉइंट‑आधारित वर्टेक्स एलिमेंट जानकारी होगी।
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### देखें भी

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

[`VertexElementMaterial`](../../vertexelementmaterial/) द्वारा मेष को सब‑मेश में विभाजित करें। प्रत्येक सब‑मेश केवल एक सामग्री का उपयोग करेगा। दृश्य के सभी नोड्स पर मेष विभाजन करें।

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| दृश्य | दृश्य |  |
| नीति | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को सब‑मेश में कैसे विभाजित किया जाए।

```csharp
// बॉक्स का एक मेष बनाएं (बॉक्स 6 प्लेनों से बना होता है)
Mesh box = (new Box()).ToMesh();
// इस मेष पर एक मैटेरियल एलिमेंट बनाएं
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// और प्रत्येक प्लेन के लिए अलग मैटेरियल इंडेक्स निर्दिष्ट करें
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// अब इसे 6 सब‑मेश में विभाजित करें, हमने प्रत्येक प्लेन पर 6 अलग-अलग सामग्री निर्दिष्ट की हैं, प्रत्येक प्लेन एक सब‑मेश बन जाएगा।
// हमने CloneData नीति का उपयोग किया, प्रत्येक प्लेन में समान कंट्रोल पॉइंट जानकारी या कंट्रोल पॉइंट‑आधारित वर्टेक्स एलिमेंट जानकारी होगी।
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// अब इसे 2 सब‑मेश में विभाजित करें, पहला मेष 0/1/2 प्लेनों को शामिल करेगा, और दूसरा मेष 3/4/5वें प्लेनों को शामिल करेगा।
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// हमने CompactData नीति का उपयोग किया, प्रत्येक प्लेन की अपनी कंट्रोल पॉइंट जानकारी या कंट्रोल पॉइंट‑आधारित वर्टेक्स एलिमेंट जानकारी होगी।
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### देखें भी

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

[`VertexElementMaterial`](../../vertexelementmaterial/) द्वारा मेष को सब‑मेश में विभाजित करें। प्रत्येक सब‑मेश केवल एक सामग्री का उपयोग करेगा। मूल मेष में कोई परिवर्तन नहीं होगा।

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### रिटर्न वैल्यू

नए विभाजित मेष

## उदाहरण

निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को सब‑मेश में कैसे विभाजित किया जाए।

```csharp
// बॉक्स का एक मेष बनाएं (बॉक्स 6 प्लेनों से बना होता है)
Mesh box = (new Box()).ToMesh();
// इस मेष पर एक मैटेरियल एलिमेंट बनाएं
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// और प्रत्येक प्लेन के लिए अलग मैटेरियल इंडेक्स निर्दिष्ट करें
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// अब इसे 6 सब‑मेश में विभाजित करें, हमने प्रत्येक प्लेन पर 6 अलग-अलग सामग्री निर्दिष्ट की हैं, प्रत्येक प्लेन एक सब‑मेश बन जाएगा।
// हमने CloneData नीति का उपयोग किया, प्रत्येक प्लेन में समान कंट्रोल पॉइंट जानकारी या कंट्रोल पॉइंट‑आधारित वर्टेक्स एलिमेंट जानकारी होगी।
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// अब इसे 2 सब‑मेश में विभाजित करें, पहला मेष 0/1/2 प्लेनों को शामिल करेगा, और दूसरा मेष 3/4/5वें प्लेनों को शामिल करेगा।
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// हमने CompactData नीति का उपयोग किया, प्रत्येक प्लेन की अपनी कंट्रोल पॉइंट जानकारी या कंट्रोल पॉइंट‑आधारित वर्टेक्स एलिमेंट जानकारी होगी।
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### देखें भी

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


