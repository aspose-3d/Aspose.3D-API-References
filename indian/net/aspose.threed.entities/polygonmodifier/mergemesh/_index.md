---
title: "PolygonModifier.MergeMesh"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PolygonModifier मेथड। पूरे दृश्य को एकल ट्रांसफ़ॉर्म्ड मेष में बदलें। सामान्य/टेक्सचर कोऑर्डिनेट जैसे वर्टेक्स एलिमेंट अभी समर्थित नहीं हैं।"
type: docs
weight: 50
url: /hi/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

पूरे सीन को एकल ट्रांसफ़ॉर्म्ड मेष में परिवर्तित करें। सामान्य/टेक्सचर निर्देशांक जैसे वर्टेक्स तत्व अभी समर्थित नहीं हैं।

```csharp
public static Mesh MergeMesh(Scene scene)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| दृश्य | दृश्य | मर्ज करने के लिए दृश्य |

### रिटर्न वैल्यू

मर्ज किया गया मेष

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य से सभी वस्तुओं को एकल मेष में मिलाया जाए।

```csharp
//इनपुट फ़ाइल में कई ऑब्जेक्ट हो सकते हैं
var scene = Scene.FromFile("input.fbx");
//अब उन्हें एकल मेष में मिलाएँ
Mesh merged = PolygonModifier.MergeMesh(scene);
//फिर हम इसे केवल एक मेष वाली फ़ाइल में सहेजते हैं
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### देखें भी

* class [Mesh](../../mesh/)
* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(IList&lt;Node&gt;) {#mergemesh_2}

```csharp
public static Mesh MergeMesh(IList<Node> nodes)
```

### देखें भी

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

पूरे नोड को एकल ट्रांसफ़ॉर्म्ड मेष में परिवर्तित करें। सामान्य/टेक्सचर निर्देशांक जैसे वर्टेक्स तत्व अभी समर्थित नहीं हैं।

```csharp
public static Mesh MergeMesh(Node node)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नोड | नोड | मर्ज करने के लिए नोड |

### रिटर्न वैल्यू

मर्ज किया गया मेष

## उदाहरण

निम्नलिखित कोड दिखाता है कि नोड्स से सभी ऑब्जेक्ट्स को एकल मेष में कैसे मर्ज किया जाए।

```csharp
//इनपुट फ़ाइल में कई ऑब्जेक्ट हो सकते हैं
var scene = Scene.FromFile("input.fbx");
//अब उन्हें एकल मेष में मिलाएँ
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//फिर हम इसे केवल एक मेष वाली फ़ाइल में सहेजते हैं
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### देखें भी

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


