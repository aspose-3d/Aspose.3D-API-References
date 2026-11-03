---
title: "क्लास Mesh"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Mesh क्लास। एक मेष कई n-साइड वाले बहुभुजों से बना होता है"
type: docs
weight: 510
url: /hi/net/aspose.threed.entities/mesh/
---
## Mesh class

एक मेष कई n-भुजाओं वाले बहुभुजों से बना होता है।

```csharp
public class Mesh : Geometry, IEnumerable<int[]>, IMeshConvertible
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Mesh](mesh/#constructor)() | `Mesh` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Mesh](mesh/#constructor_4)(string) | `Mesh` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Mesh](mesh/#constructor_1)(TextureData) | निर्दिष्ट हाइट मैप का उपयोग करके एक मेष बनाएं, यदि हाइट मैप के पिक्सेल फ़ॉर्मेट में कई घटक हैं, तो पहला (आमतौर पर लाल) घटक हाइट वैल्यू (z) के रूप में उपयोग किया जाएगा। कंट्रोल पॉइंट के x और y घटक सामान्यीकृत पिक्सेल निर्देशांक होते हैं। |
| [Mesh](mesh/#constructor_2)(TextureData, Matrix4) | निर्दिष्ट हाइट मैप का उपयोग करके एक मेष बनाएं, यदि हाइट मैप के पिक्सेल फ़ॉर्मेट में कई घटक हैं, तो पहला (आमतौर पर लाल) घटक हाइट वैल्यू (z) के रूप में उपयोग किया जाएगा। कंट्रोल पॉइंट के x और y घटक सामान्यीकृत पिक्सेल निर्देशांक होते हैं। |
| [Mesh](mesh/#constructor_3)(TextureData, bool, Matrix4) | निर्दिष्ट हाइट मैप का उपयोग करके एक मेष बनाएं, यदि हाइट मैप के पिक्सेल फ़ॉर्मेट में कई घटक हैं, तो पहला (आमतौर पर लाल) घटक हाइट वैल्यू (z) के रूप में उपयोग किया जाएगा। कंट्रोल पॉइंट के x और y घटक सामान्यीकृत पिक्सेल निर्देशांक होते हैं। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/geometry/castshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह ज्योमेट्री शैडो कास्ट कर सकती है या नहीं |
| [ControlPoints](../../aspose.threed.entities/geometry/controlpoints/) { get; } | सभी कंट्रोल पॉइंट प्राप्त करता है |
| [Deformers](../../aspose.threed.entities/geometry/deformers/) { get; } | इस ज्योमेट्री से जुड़े सभी डिफॉर्मर्स प्राप्त करता है। |
| [Edges](../../aspose.threed.entities/mesh/edges/) { get; } | Mesh के एज प्राप्त करता है। एज मेष में वैकल्पिक होते हैं, इसलिए यह खाली हो सकता है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [PolygonCount](../../aspose.threed.entities/mesh/polygoncount/) { get; } | बहुभुजों की गिनती प्राप्त करता है |
| [Polygons](../../aspose.threed.entities/mesh/polygons/) { get; } | मेश की बहुभुज परिभाषा प्राप्त करता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [ReceiveShadows](../../aspose.threed.entities/geometry/receiveshadows/) { get; set; } | प्राप्त करता है या सेट करता है कि यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [VertexElements](../../aspose.threed.entities/geometry/vertexelements/) { get; } | सभी वर्टेक्स एलिमेंट्स प्राप्त करता है |
| [Visible](../../aspose.threed.entities/geometry/visible/) { get; set; } | प्राप्त करता है या सेट करता है कि जियोमेट्री दृश्यमान है या नहीं |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [DoBoolean](../../aspose.threed.entities/mesh/doboolean/)(BooleanOperation, Mesh, Matrix4?, Mesh, Matrix4?) |  |
| [AddElement](../../aspose.threed.entities/geometry/addelement/)(VertexElement) | एक मौजूदा वर्टेक्स एलिमेंट को वर्तमान जियोमेट्री में जोड़ता है |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है। |
| [CreateElement](../../aspose.threed.entities/geometry/createelement/)(VertexElementType, MappingMode, ReferenceMode) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है। |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) बनाता है। |
| [CreateElementUV](../../aspose.threed.entities/geometry/createelementuv/)(TextureMapping, MappingMode, ReferenceMode) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) बनाता है। |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_2)(int[]) | सभी वर्टेक्स *indices* में परिभाषित नए बहुभुज को बनाता है। बहुभुज को वर्टेक्स दर वर्टेक्स बनाने के लिए, कृपया [`PolygonBuilder`](../polygonbuilder/) का उपयोग करें। |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon)(int, int, int) | 3 वर्टेक्स (त्रिभुज) के साथ एक बहुभुज बनाएं |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_3)(int[], int, int) | सभी वर्टेक्स *indices* में परिभाषित नए बहुभुज को बनाता है। बहुभुज को वर्टेक्स दर वर्टेक्स बनाने के लिए, कृपया [`PolygonBuilder`](../polygonbuilder/) का उपयोग करें। |
| [CreatePolygon](../../aspose.threed.entities/mesh/createpolygon/#createpolygon_1)(int, int, int, int) | 4 वर्टेक्स (चतुर्भुज) के साथ एक बहुभुज बनाएं |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| [GetDeformers&lt;T&gt;](../../aspose.threed.entities/geometry/getdeformers/)() |  |
| [GetElement](../../aspose.threed.entities/geometry/getelement/)(VertexElementType) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट प्राप्त करता है |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetEnumerator](../../aspose.threed.entities/mesh/getenumerator/)() | प्रत्येक आंतरिक बहुभुज के लिए इनेमरेटर प्राप्त करता है। |
| [GetPolygonSize](../../aspose.threed.entities/mesh/getpolygonsize/)(int) | निर्दिष्ट बहुभुज की वर्टेक्स गिनती प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [GetVertexElementOfUV](../../aspose.threed.entities/geometry/getvertexelementofuv/)(TextureMapping) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [`VertexElementUV`](../vertexelementuv/) इंस्टेंस प्राप्त करता है |
| [IsManifold](../../aspose.threed.entities/mesh/ismanifold/)() | जाँचें कि वर्तमान मेश एक मैनिफोल्ड मेश है या नहीं। यह फ़ंक्शन मैनिफोल्ड गणना परिणाम को कैश नहीं करेगा। |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize)(bool) | डुप्लिकेट कंट्रोल पॉइंट्स को हटाकर मेश की मेमोरी उपयोग को अनुकूलित करें |
| [Optimize](../../aspose.threed.entities/mesh/optimize/#optimize_1)(bool, float, float, float) | डुप्लिकेट कंट्रोल पॉइंट्स को हटाकर मेश की मेमोरी उपयोग को अनुकूलित करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [ToMesh](../../aspose.threed.entities/mesh/tomesh/)() | वर्तमान एंटिटी से Mesh इंस्टेंस प्राप्त करता है। |
| [Triangulate](../../aspose.threed.entities/mesh/triangulate/)() | त्रिकोणीय मेश लौटाएं |
| [operator &amp;](../../aspose.threed.entities/mesh/op_bitwiseand/) | दो मेशों का प्रतिच्छेदन गणना करें |
| [operator &#x7C;](../../aspose.threed.entities/mesh/op_bitwiseor/) | दो मेशों का संघ गणना करें |
| [operator -](../../aspose.threed.entities/mesh/op_subtraction/) | दो मेषों का अंतर गणना करें |

## उदाहरण

मेष में एक बहुभुज जोड़ने के लिए:

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

मेष में सभी बहुभुजों के माध्यम से यात्रा करें:

```csharp
Mesh mesh = new Mesh();
foreach(int[] polygon in mesh)
{
    //बहुभुज को संभालें
}
```

### देखें भी

* class [Geometry](../geometry/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


