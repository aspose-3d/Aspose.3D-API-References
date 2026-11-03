---
title: "TriMesh.Write16bIndicesTo"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TriMesh विधि। इंडेक्स डेटा को 16‑bit पूर्णांक के रूप में स्ट्रीम में लिखें"
type: docs
weight: 270
url: /hi/net/aspose.threed.entities/trimesh/write16bindicesto/
---
## TriMesh.Write16bIndicesTo method

इंडेक्स डेटा को 16-बिट पूर्णांक के रूप में स्ट्रीम में लिखें

```csharp
public void Write16bIndicesTo(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream |  |

## उदाहरण

```csharp
//एक mesh को TriMesh में परिवर्तित करें, लेआउट इनपुट mesh से स्वचालित रूप से अनुमानित किया जाता है
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//इसे स्ट्रीम में सहेजें, 115 वर्टिस * प्रति वर्टिस 32 बाइट
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//इंडेक्स को ushort के रूप में स्ट्रीम में सहेजें, 504 इंडेक्स * प्रति इंडेक्स 2 बाइट
triMesh.Write16bIndicesTo(stream);
```

### देखें भी

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)


