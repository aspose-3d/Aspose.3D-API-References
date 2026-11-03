---
title: "क्लास Shape"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Shape क्लास। यह शेप कंट्रोल पॉइंट्स के सेट पर विकृति का वर्णन करता है जो Maya में क्लस्टर डिफॉर्मर के समान है। उदाहरण के लिए हम एक बनाई गई ज्यामिति में एक शेप जोड़ सकते हैं। और शेप और ज्यामिति के पास समान टोपोलॉजिकल जानकारी होती है लेकिन कंट्रोल पॉइंट्स की स्थिति अलग होती है। विभिन्न प्रभाव की मात्रा के साथ ज्यामिति एक विकृति प्रभाव प्रदर्शित करती है।"
type: docs
weight: 700
url: /hi/net/aspose.threed.entities/shape/
---
## Shape class

आकार नियंत्रण बिंदुओं के सेट पर विकृति का वर्णन करता है, जो Maya में क्लस्टर डिफॉर्मर के समान है। उदाहरण के लिए, हम एक बनाए गए ज्यामिति में एक आकार जोड़ सकते हैं। और आकार तथा ज्यामिति में समान टोपोलॉजिकल जानकारी होती है लेकिन नियंत्रण बिंदुओं की स्थितियाँ अलग होती हैं। प्रभाव की विभिन्न मात्रा के साथ, ज्यामिति एक विकृति प्रभाव प्रदर्शित करती है।

```csharp
public class Shape : Geometry
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Shape](shape/#constructor)() | `Shape` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Shape](shape/#constructor_1)(string) | `Shape` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह ज्योमेट्री शैडो कास्ट कर सकती है या नहीं |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | सभी कंट्रोल पॉइंट प्राप्त करता है |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | इस ज्योमेट्री से जुड़े सभी डिफॉर्मर्स प्राप्त करता है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [Indices](../../aspose.threed.entities/shape/indices/) { get; } | इंडेक्स प्राप्त करता है। |
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
| static [FromControlPoints](../../aspose.threed.entities/shape/fromcontrolpoints/)(params Vector3[]) | निर्दिष्ट कंट्रोल पॉइंट्स के साथ डिफ़ॉल्ट इंडेक्स के साथ एक शेप बनाएं। |
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

### देखें भी

* class [Geometry](../geometry/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


