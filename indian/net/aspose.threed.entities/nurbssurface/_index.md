---
title: "क्लास NurbsSurface"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.NurbsSurface क्लास। NurbsSurface एक सतह है जो NURBS (Non-uniform rational basis spline) द्वारा दर्शाई जाती है। एक NurbsSurface दो NurbsDirectionU और V द्वारा परिभाषित होती है। कंट्रोल पॉइंट में w घटक को कंट्रोल पॉइंट्स के वजन के रूप में उपयोग किया जाता है, चाहे दिशा का प्रकार TwoDimensional हो या ThreeDimensional।"
type: docs
weight: 540
url: /hi/net/aspose.threed.entities/nurbssurface/
---
## NurbsSurface class

`NurbsSurface` एक सतह है जो [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) द्वारा दर्शाई गई है, एक `NurbsSurface` दो [`NurbsDirection`](../nurbsdirection/)[`U`](./u/) और [`V`](./v/) द्वारा परिभाषित होती है। कंट्रोल पॉइंट में w घटक को कंट्रोल पॉइंट के वजन के रूप में उपयोग किया जाता है, चाहे दिशा का प्रकार TwoDimensional या ThreeDimensional हो।

```csharp
public class NurbsSurface : Geometry, IMeshConvertible
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [NurbsSurface](nurbssurface/#constructor)() | `NurbsSurface` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [NurbsSurface](nurbssurface/#constructor_1)(string) | `NurbsSurface` क्लास का एक नया इंस्टेंस प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह ज्योमेट्री शैडो कास्ट कर सकती है या नहीं |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | सभी कंट्रोल पॉइंट प्राप्त करता है |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | इस ज्योमेट्री से जुड़े सभी डिफॉर्मर्स प्राप्त करता है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [U](../../aspose.threed.entities/nurbssurface/u/) { get; } | NURBS सतह की U दिशा प्राप्त करता है |
| [V](../../aspose.threed.entities/nurbssurface/v/) { get; } | NURBS सतह की V दिशा प्राप्त करता है |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | सभी वर्टेक्स एलिमेंट्स प्राप्त करता है |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | प्राप्त करता है या सेट करता है कि जियोमेट्री दृश्यमान है या नहीं |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | एक मौजूदा वर्टेक्स एलिमेंट को वर्तमान जियोमेट्री में जोड़ता है |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है। |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है। |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) बनाता है। |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) बनाता है। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट प्राप्त करता है |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) इंस्टेंस प्राप्त करता है |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [ToMesh](../../aspose.threed.entities/nurbssurface/tomesh/)() | NURBS सतह को मेष में परिवर्तित करें |

### देखें भी

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


