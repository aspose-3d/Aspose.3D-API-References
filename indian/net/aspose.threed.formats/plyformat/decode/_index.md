---
title: "PlyFormat.Decode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PlyFormat मेथड। निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें"
type: docs
weight: 10
url: /hi/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

```csharp
public Geometry Decode(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | इनपुट स्ट्रीम |

### रिटर्न वैल्यू

एक [`Mesh`](../../../aspose.threed.entities/mesh/) या [`PointCloud`](../../../aspose.threed.entities/pointcloud/) का इंस्टेंस

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल से डिकोड किया जाता है:

```csharp
//डिकोडिंग के लिए एक टेस्ट फ़ाइल जनरेट करें
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//फ़ाइल को डिकोड करें
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### देखें भी

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | इनपुट स्ट्रीम |
| विकल्प | PlyLoadOptions | PLY फ़ॉर्मेट का लोड विकल्प |

### रिटर्न वैल्यू

एक [`Mesh`](../../../aspose.threed.entities/mesh/) या [`PointCloud`](../../../aspose.threed.entities/pointcloud/) का इंस्टेंस

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल से डिकोड किया जाता है:

```csharp
//डिकोडिंग के लिए एक टेस्ट फ़ाइल जनरेट करें
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//फ़ाइल को डिकोड करें
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### देखें भी

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

```csharp
public Geometry Decode(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम |

### रिटर्न वैल्यू

एक [`Mesh`](../../../aspose.threed.entities/mesh/) या [`PointCloud`](../../../aspose.threed.entities/pointcloud/) का इंस्टेंस

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल से डिकोड किया जाता है:

```csharp
//डिकोडिंग के लिए एक टेस्ट फ़ाइल जनरेट करें
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//फ़ाइल को डिकोड करें
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### देखें भी

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

निर्दिष्ट स्ट्रीम से पॉइंट क्लाउड या मेष को डिकोड करें।

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम |
| विकल्प | PlyLoadOptions | PLY फ़ॉर्मेट का लोड विकल्प |

### रिटर्न वैल्यू

एक [`Mesh`](../../../aspose.threed.entities/mesh/) या [`PointCloud`](../../../aspose.threed.entities/pointcloud/) का इंस्टेंस

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल से डिकोड किया जाता है:

```csharp
//डिकोडिंग के लिए एक टेस्ट फ़ाइल जनरेट करें
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//फ़ाइल को डिकोड करें
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### देखें भी

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


