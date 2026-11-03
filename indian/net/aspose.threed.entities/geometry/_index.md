---
title: "क्लास Geometry"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Geometry class. सभी रेंडरेबल ज्यामितीय वस्तुओं जैसे Mesh, NurbsSurface, Patch आदि की बेस क्लास।"
type: docs
weight: 410
url: /hi/net/aspose.threed.entities/geometry/
---
## Geometry class

सभी रेंडर करने योग्य ज्यामितीय वस्तुओं की बेस क्लास (जैसे [`Mesh`](../mesh/), [`NurbsSurface`](../nurbssurface/), [`Patch`](../patch/) आदि)।

`Geometry` बेस क्लास समर्थन करता है: **Control point management**, कंट्रोल पॉइंट्स ज्यामिति की बेस 3D स्पैशियल स्ट्रक्चर को परिभाषित करते हैं, विभिन्न ज्यामितीय प्रकारों के पास ठोस 3D मॉडल को परिभाषित करने का अलग तरीका होता है। **Vertex element definition**, वर्टेक्स एलिमेंट्स अतिरिक्त जानकारी जैसे नॉर्मल्स/UV कॉर्डिनेट्स/वर्टेक्स कलर्स को ज्यामिति में लागू करते हैं, अधिक विवरण के लिए देखें [`VertexElement`](../vertexelement/)।**Object deforming**, [`Deformer`](../../aspose.threed.deformers/deformer/) को बंधित करके ज्यामिति के आकार को एनीमेट किया जा सकता है।

```csharp
public class Geometry : Entity
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Geometry](geometry/)(string) | `Geometry` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

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
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | सभी वर्टेक्स एलिमेंट्स प्राप्त करता है |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | प्राप्त करता है या सेट करता है कि जियोमेट्री दृश्यमान है या नहीं |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | एक मौजूदा वर्टेक्स एलिमेंट को वर्तमान जियोमेट्री में जोड़ता है |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement)(VertexElementType) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है। |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/#createelement_1)(VertexElementType, MappingMode, ReferenceMode) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है। |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv)(TextureMapping) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) बनाता है। |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/#createelementuv_1)(TextureMapping, MappingMode, ReferenceMode) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) बनाता है। |
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

### देखें भी

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


