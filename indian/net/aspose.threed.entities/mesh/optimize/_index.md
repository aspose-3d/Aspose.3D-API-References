---
title: "Mesh.Optimize"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Mesh विधि। दोहराए गए नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करता है"
type: docs
weight: 100
url: /hi/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

डुप्लिकेट कंट्रोल पॉइंट्स को हटाकर मेश की मेमोरी उपयोग को अनुकूलित करें

```csharp
public Mesh Optimize(bool vertexElements)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| वर्टेक्स तत्व | Boolean | दोहराए गए वर्टेक्स तत्व डेटा को अनुकूलित करें |

### रिटर्न वैल्यू

संकुचित मेमोरी उपयोग के साथ नया मेष इंस्टेंस

## उदाहरण

निम्नलिखित कोड दिखाता है कि अनऑप्टिमाइज़्ड मेष से दोहराए गए कंट्रोल पॉइंट्स को कैसे हटाया जाए:

```csharp
//Sphere.ToMesh 117 कंट्रोल पॉइंट्स उत्पन्न करता है
var mesh = (new Sphere()).ToMesh();
//ऑप्टिमाइज़ करने के बाद, केवल 86 कंट्रोल पॉइंट्स बचे हैं, पॉलीगॉन इंडेक्स भी पुनः मैप किए गए हैं।
var optimized = mesh.Optimize(true);
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

डुप्लिकेट कंट्रोल पॉइंट्स को हटाकर मेश की मेमोरी उपयोग को अनुकूलित करें

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| वर्टेक्स तत्व | Boolean | दोहराए गए वर्टेक्स तत्व डेटा को अनुकूलित करें |
| toleranceControlPoint | Single | कंट्रोल पॉइंट के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |
| toleranceNormal | Single | नॉर्मल/टैन्जेंट/बिनॉर्मल के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |
| toleranceUV | Single | UV के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |

### रिटर्न वैल्यू

संकुचित मेमोरी उपयोग के साथ नया मेष इंस्टेंस

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


