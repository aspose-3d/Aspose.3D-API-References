---
title: "Node.EvaluateGlobalTransform"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node मेथड। ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करें, जिसमें ज्यामितीय ट्रांसफ़ॉर्म शामिल है या नहीं।"
type: docs
weight: 180
url: /hi/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करें, ज्यामितीय ट्रांसफ़ॉर्म शामिल करें या नहीं।

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| withGeometricTransform | Boolean | क्या ज्यामितीय रूपांतरण आवश्यक है। |

### रिटर्न वैल्यू

वैश्विक रूपांतरण मैट्रिक्स।

## उदाहरण

निम्नलिखित कोड दिखाता है कि नोड के वैश्विक रूपांतरण मैट्रिक्स को कैसे पढ़ा जाए।

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//बॉक्स को (10, 0, 0) पर रखें
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### देखें भी

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


