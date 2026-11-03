---
title: "Node.GetChild"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node method. निर्दिष्ट इंडेक्स पर चाइल्ड नोड प्राप्त करता है"
type: docs
weight: 200
url: /hi/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

निर्दिष्ट इंडेक्स पर चाइल्ड नोड प्राप्त करता है।

```csharp
public Node GetChild(int index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इंडेक्स | Int32 | इंडेक्स। |

### रिटर्न वैल्यू

बच्चा।

## उदाहरण

निम्नलिखित कोड दिखाता है कि निर्दिष्ट अनुक्रमांक पर एक चाइल्ड नोड कैसे प्राप्त करें।

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

निर्दिष्ट नाम वाले चाइल्ड नोड को प्राप्त करता है

```csharp
public Node GetChild(string nodeName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| nodeName | String | खोजने के लिए चाइल्ड का नाम। |

### रिटर्न वैल्यू

बच्चा।

## उदाहरण

निम्नलिखित कोड दिखाता है कि निर्दिष्ट नाम वाले चाइल्ड नोड को कैसे प्राप्त करें।

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


