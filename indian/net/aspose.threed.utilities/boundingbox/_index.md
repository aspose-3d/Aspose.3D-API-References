---
title: "स्ट्रक्ट BoundingBox"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.BoundingBox स्ट्रक्ट। अक्ष-संरेखित बाउंडिंग बॉक्स।"
type: docs
weight: 2670
url: /hi/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

अक्ष-संरेखित बाउंडिंग बॉक्स

```csharp
public struct BoundingBox
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स प्रारंभ करें |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स प्रारंभ करें |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | अनंत बाउंडिंग बॉक्स |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | शून्य बाउंडिंग बॉक्स |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | बाउंडिंग बॉक्स का केंद्र। |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | बाउंडिंग बॉक्स का विस्तार प्राप्त करता है। |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | बाउंडिंग बॉक्स का अधिकतम कोना |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | बाउंडिंग बॉक्स का न्यूनतम कोना |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | बाउंडिंग बॉक्स का आकार |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | दिए गए ज्यामिति से बाउंडिंग बॉक्स बनाएं |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | वर्तमान बाउंडिंग बॉक्स के भीतर है या नहीं, यह जांचने के लिए बाउंडिंग बॉक्स। |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | जाँचें कि बिंदु p बाउंडिंग बॉक्स के भीतर है या नहीं |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | निर्धारित करता है कि दो वस्तुएँ समान हैं या नहीं |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है। |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | वर्तमान बाउंडिंग बॉक्स को दिए गए बिंदु के साथ मिलाएँ |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | वर्तमान बाउंडिंग बॉक्स को दिए गए बिंदु के साथ मिलाएँ |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | वर्तमान बाउंडिंग बॉक्स को दिए गए बिंदु के साथ मिलाएँ |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | जाँचें कि वर्तमान बाउंडिंग बॉक्स निर्दिष्ट बाउंडिंग बॉक्स के साथ ओवरलैप करता है या नहीं। |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | किसी भी सम्मिलित बिंदु के अधिकतम निरपेक्ष निर्देशांक मान की गणना करता है। |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | गुणा के लिए ऑपरेटर ओवरलोडिंग, नई बाउंडिंग बॉक्स के न्यूनतम और अधिकतम कोने को मैट्रिक्स द्वारा परिवर्तित किया जाएगा। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि एक एंटिटी इंस्टेंस से बाउंडिंग बॉक्स कैसे प्राप्त किया जाए।

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### देखें भी

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


