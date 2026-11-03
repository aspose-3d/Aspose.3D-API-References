---
title: "Node.Material"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node प्रॉपर्टी। इस नोड से जुड़ी पहली सामग्री को प्राप्त या सेट करता है; यदि सेट किया जाता है तो अन्य सामग्री साफ़ हो जाएगी"
type: docs
weight: 80
url: /hi/net/aspose.threed/node/material/
---
## Node.Material property

इस नोड से जुड़ा पहला मैटेरियल प्राप्त करता है या सेट करता है; यदि सेट किया जाता है, तो अन्य मैटेरियल्स को साफ़ कर देगा।

```csharp
public Material Material { get; set; }
```

### Property Value

सामग्री।

## उदाहरण

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### देखें भी

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


