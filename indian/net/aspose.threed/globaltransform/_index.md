---
title: "क्लास GlobalTransform"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.GlobalTransform क्लास। ग्लोबल ट्रांसफ़ॉर्म Transform के समान है लेकिन यह अपरिवर्तनीय है जबकि यह अंतिम मूल्यांकित परिवर्तन का प्रतिनिधित्व करता है। ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करते समय राइटहैंड कोऑर्डिनेट सिस्टम का उपयोग किया जाता है।"
type: docs
weight: 1560
url: /hi/net/aspose.threed/globaltransform/
---
## GlobalTransform class

ग्लोबल ट्रांसफ़ॉर्म [`Transform`](../transform/) के समान है लेकिन यह अपरिवर्तनीय है जबकि यह अंतिम मूल्यांकित परिवर्तन का प्रतिनिधित्व करता है। ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करते समय राइट-हैंड कोऑर्डिनेट सिस्टम का उपयोग किया जाता है।

```csharp
public class GlobalTransform
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | Euler कोणों में दर्शाए गए घूर्णन को प्राप्त करता है, डिग्री में मापा गया |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | क्वाटरनियन में दर्शाए गए घूर्णन को प्राप्त करता है। |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | स्केल प्राप्त करता है |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है। |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | अनुवाद प्राप्त करता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि नोड के ग्लोबल ट्रांसफ़ॉर्म को कैसे पढ़ा जाए

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//बॉक्स को (10, 0, 0) पर रखें
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### देखें भी

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


