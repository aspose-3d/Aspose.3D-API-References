---
title: "Geometry.CreateElement"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Geometry मेथड। निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे ज्योमेट्री में जोड़ता है"
type: docs
weight: 90
url: /hi/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है।

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | VertexElementType | वर्टेक्स एलिमेंट प्रकार |

### रिटर्न वैल्यू

एलिमेंट बनाया गया।

## टिप्पणियाँ

यदि प्रकार UV है, तो एक [`VertexElementUV`](../../vertexelementuv/) टेक्टचर मैपिंग प्रकार Diffuse के साथ बनाया जाएगा।

### देखें भी

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

निर्दिष्ट प्रकार के साथ एक वर्टेक्स एलिमेंट बनाता है और उसे जियोमेट्री में जोड़ता है।

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | VertexElementType | वर्टेक्स एलिमेंट प्रकार |
| mappingMode | MappingMode | डिफ़ॉल्ट मैपिंग मोड |
| referenceMode | ReferenceMode | डिफ़ॉल्ट रेफ़रेंस मोड |

### रिटर्न वैल्यू

एलिमेंट बनाया गया।

## टिप्पणियाँ

यदि प्रकार UV है, तो एक [`VertexElementUV`](../../vertexelementuv/) टेक्टचर मैपिंग प्रकार Diffuse के साथ बनाया जाएगा।

### देखें भी

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)


