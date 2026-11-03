---
title: "TriMesh.WriteVerticesTo"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "TriMesh विधि। निर्दिष्ट स्ट्रीम में vertices डेटा लिखें"
type: docs
weight: 290
url: /hi/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

निर्दिष्ट स्ट्रीम में वर्टिस डेटा लिखें

```csharp
public void WriteVerticesTo(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | वह स्ट्रीम जिसमें vertices डेटा लिखा जाएगा |

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


