---
title: "Mesh.Triangulate"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Mesh विधि। त्रिकोणीय मेष लौटाता है"
type: docs
weight: 120
url: /hi/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

त्रिकोणीय मेश लौटाएं

```csharp
public Mesh Triangulate()
```

### रिटर्न वैल्यू

वर्तमान मेष यदि पहले से ही त्रिकोणीय है, अन्यथा एक नया त्रिकोणीय मेष गणना किया जाएगा और लौटाया जाएगा

## उदाहरण

निम्नलिखित कोड दर्शाता है कि मेष को कैसे त्रिकोणीय किया जाए:

```csharp
//समतल मेष में केवल एक बहुभुज है जिसमें 4 नियंत्रण बिंदु हैं
var mesh = (new Plane()).ToMesh();
//त्रिकोणीय करने के बाद, नए मेष का आयत 2 त्रिभुजों में बदल जाएगा।
var triangulated = mesh.Triangulate();
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


