---
title: SplitMesh
second_title: .NET API संदर्भ के लिए Aspose.3D
description: मेश क सबमेश में वभजत करेंVertexElementMaterialaspose.threed.entities/vertexelementmaterial/ . प्रत्येक सबमेश केवल एक समग्र क उपयग करेग नड पर मेश स्प्लटंग करें
type: docs
weight: 60
url: /hi/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

मेश को सब-मेश में विभाजित करें[`VertexElementMaterial`](../../vertexelementmaterial/) . प्रत्येक सब-मेश केवल एक सामग्री का उपयोग करेगा। नोड पर मेश स्प्लिटिंग करें

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| node | Node |  |
| policy | SplitMeshPolicy |  |
| createChildNodes | Boolean | प्रत्येक सब-मेश के लिए चाइल्ड नोड बनाएँ। |
| removeOldMesh | Boolean | विभाजन के बाद पुराने जाल को हटा दें, यदि यह पैरामीटर गलत है, तो पुराना और नया जाल सह-अस्तित्व में रहेगा। |

### यह सभी देखें

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* नाम स्थान [Aspose.ThreeD.Entities](../../polygonmodifier/)
* सभा [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

मेश को सब-मेश में विभाजित करें[`VertexElementMaterial`](../../vertexelementmaterial/) . प्रत्येक उप-जाल केवल एक सामग्री का उपयोग करेगा। दृश्य के सभी नोड्स पर जाल विभाजन करें।

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scene | Scene |  |
| policy | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

### यह सभी देखें

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* नाम स्थान [Aspose.ThreeD.Entities](../../polygonmodifier/)
* सभा [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

मेश को सब-मेश में विभाजित करें[`VertexElementMaterial`](../../vertexelementmaterial/) . प्रत्येक उप-जाल केवल एक सामग्री का उपयोग करेगा। मूल जाल नहीं बदलेगा।

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### यह सभी देखें

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* नाम स्थान [Aspose.ThreeD.Entities](../../polygonmodifier/)
* सभा [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
