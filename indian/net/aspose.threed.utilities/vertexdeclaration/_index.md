---
title: "क्लास VertexDeclaration"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.VertexDeclaration क्लास। कस्टम परिभाषित वर्टेक्स संरचना की घोषणा"
type: docs
weight: 2910
url: /hi/net/aspose.threed.utilities/vertexdeclaration/
---
## VertexDeclaration class

कस्टम परिभाषित वर्टेक्स संरचना की घोषणा।

```csharp
public sealed class VertexDeclaration : IComparable<VertexDeclaration>, IEnumerable<VertexField>
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [VertexDeclaration](vertexdeclaration/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Count](../../aspose.threed.utilities/vertexdeclaration/count/) { get; } | इस `VertexDeclaration` में परिभाषित सभी फ़ील्डों की गिनती प्राप्त करता है |
| [Item](../../aspose.threed.utilities/vertexdeclaration/item/) { get; } |  |
| [Sealed](../../aspose.threed.utilities/vertexdeclaration/sealed/) { get; } | `VertexDeclaration` को तब सील किया जाएगा जब इसे [`TriMesh`](../../aspose.threed.entities/trimesh-1/) या [`TriMesh`](../../aspose.threed.entities/trimesh/) द्वारा उपयोग किया गया हो, अब कोई संशोधन अनुमति नहीं है। |
| [Size](../../aspose.threed.utilities/vertexdeclaration/size/) { get; } | वर्टेक्स संरचना का बाइट में आकार। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/vertexdeclaration/fromgeometry/)(Geometry, bool) | `VertexDeclaration` बनाएं जो एक [`Geometry`](../../aspose.threed.entities/geometry/) की लेआउट पर आधारित हो। |
| static [FromType&lt;T&gt;](../../aspose.threed.utilities/vertexdeclaration/fromtype/)() |  |
| [AddField](../../aspose.threed.utilities/vertexdeclaration/addfield/)(VertexFieldDataType, VertexFieldSemantic, int, string) | एक नया वर्टेक्स फ़ील्ड जोड़ें |
| [Clear](../../aspose.threed.utilities/vertexdeclaration/clear/)() | सभी फ़ील्ड साफ़ करें। |
| [CompareTo](../../aspose.threed.utilities/vertexdeclaration/compareto/)(VertexDeclaration) | इस इंस्टेंस की निर्दिष्ट ऑब्जेक्ट से तुलना करता है और उनके सापेक्ष मानों का संकेत लौटाता है। |
| override [Equals](../../aspose.threed.utilities/vertexdeclaration/equals/)(object) | निर्धारित करता है कि यह इंस्टेंस और एक निर्दिष्ट ऑब्जेक्ट, जो भी एक `VertexDeclaration` ऑब्जेक्ट होना चाहिए, का मान समान है या नहीं। |
| [GetEnumerator](../../aspose.threed.utilities/vertexdeclaration/getenumerator/)() | इस उदाहरण में सभी वर्टेक्स फ़ील्ड्स के माध्यम से चलने के लिए एक इटरेटर प्राप्त करता है। |
| override [GetHashCode](../../aspose.threed.utilities/vertexdeclaration/gethashcode/)() | इस स्ट्रिंग के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.threed.utilities/vertexdeclaration/tostring/)() | `VertexDeclaration` की स्ट्रिंग प्रतिनिधित्व |

### देखें भी

* class [VertexField](../vertexfield/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


