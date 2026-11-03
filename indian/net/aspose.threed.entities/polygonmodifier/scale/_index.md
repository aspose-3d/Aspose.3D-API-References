---
title: "PolygonModifier.Scale"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PolygonModifier मेथड। सभी ज्योमेट्री को स्केल करें। इस दृश्य में ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें।"
type: docs
weight: 60
url: /hi/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

इस सीन में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)।

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| दृश्य | दृश्य | स्केल करने के लिए दृश्य |
| स्केल | Vector3 | स्केल फ़ैक्टर |

## उदाहरण

निम्नलिखित कोड दिखाता है कि दृश्य में सभी ज्योमेट्री को 10 गुना कैसे स्केल किया जाए।

```csharp
//स्केलिंग के लिए एक टेस्ट फ़ाइल लोड करें
var scene = Scene.FromFile("input.fbx");
//सभी ज्योमेट्री को 10 गुना स्केल करें।
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### देखें भी

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

इस नोड में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)।

```csharp
public static void Scale(Node node, Vector3 scale)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नोड | नोड | स्केल करने के लिए नोड |
| स्केल | Vector3 | स्केल फ़ैक्टर |

## उदाहरण

निम्नलिखित कोड दिखाता है कि दृश्य में सभी ज्योमेट्री को 10 गुना कैसे स्केल किया जाए।

```csharp
//स्केलिंग के लिए एक टेस्ट फ़ाइल लोड करें
var scene = Scene.FromFile("input.fbx");
//सभी ज्योमेट्री को 10 गुना स्केल करें।
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### देखें भी

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


