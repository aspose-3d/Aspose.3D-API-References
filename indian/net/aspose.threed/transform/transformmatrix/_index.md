---
title: "Transform.TransformMatrix"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Transform प्रॉपर्टी। ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है"
type: docs
weight: 130
url: /hi/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है।

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## टिप्पणियाँ

इस पर असाइन करने से [`Translation`](../translation/), [`Scaling`](../scaling/) और [`Rotation`](../rotation/) रीसेट हो जाएंगे, जबकि [`GeometricRotation`](../geometricrotation/), [`GeometricScaling`](../geometricscaling/) और [`GeometricTranslation`](../geometrictranslation/) प्रभावित नहीं होंगे।

## उदाहरण

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### देखें भी

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


