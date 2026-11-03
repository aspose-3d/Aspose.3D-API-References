---
title: "DracoFormat.Decode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "DracoFormat मेथड। निर्दिष्ट फ़ाइल नाम से पॉइंट क्लाउड या मेष को डिकोड करें।"
type: docs
weight: 10
url: /hi/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

निर्दिष्ट फ़ाइल नाम से पॉइंट क्लाउड या मेष को डिकोड करें

```csharp
public Geometry Decode(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम में drc फ़ाइल शामिल है। |

### रिटर्न वैल्यू

फ़ाइल सामग्री के आधार पर एक [`Mesh`](../../../aspose.threed.entities/mesh/) या [`PointCloud`](../../../aspose.threed.entities/pointcloud/) इंस्टेंस होता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | फ़ाइल से पढ़ने में विफल होने पर फेंका जाता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को बाइट एरे में/से एन्कोड और डिकोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//मेश को Draco फ़ॉर्मेट में एन्कोड करें
byte[] draco = FileFormat.Draco.Encode(mesh);
//मेश को Draco फ़ॉर्मेट से डिकोड करें
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### देखें भी

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

मेमोरी डेटा से पॉइंट क्लाउड या मेष को डिकोड करें

```csharp
public Geometry Decode(byte[] data)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| डेटा | Byte[] | कच्चे drc बाइट्स। |

### रिटर्न वैल्यू

सामग्री के आधार पर एक [`Mesh`](../../../aspose.threed.entities/mesh/) या [`PointCloud`](../../../aspose.threed.entities/pointcloud/) इंस्टेंस होता है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | डेटा खराब होने पर फेंका जाता है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को बाइट एरे में/से एन्कोड और डिकोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//मेश को Draco फ़ॉर्मेट में एन्कोड करें
byte[] draco = FileFormat.Draco.Encode(mesh);
//मेश को Draco फ़ॉर्मेट से डिकोड करें
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### देखें भी

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


