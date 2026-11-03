---
title: "PlyFormat.Encode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PlyFormat मेथड। एंटिटी को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें"
type: docs
weight: 20
url: /hi/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

एंटिटी को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें।

```csharp
public void Encode(Entity entity, Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड करने के लिए एंटिटी |
| stream | Stream | लिखने के लिए स्ट्रीम, यह मेथड इस स्ट्रीम को बंद नहीं करेगा |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल में एन्कोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//PLY फ़ॉर्मेट में मेष को एन्कोड करें
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### देखें भी

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

एंटिटी को एन्कोड करें और परिणाम को स्ट्रीम में सहेजें।

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड करने के लिए एंटिटी |
| stream | Stream | लिखने के लिए स्ट्रीम, यह मेथड इस स्ट्रीम को बंद नहीं करेगा |
| विकल्प | PlySaveOptions | सेव विकल्प |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल में एन्कोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//PLY फ़ॉर्मेट में मेष को एन्कोड करें
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### देखें भी

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

एंटिटी को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें।

```csharp
public void Encode(Entity entity, string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड करने के लिए एंटिटी |
| fileName | String | लिखने के लिए फ़ाइल |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल में एन्कोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//PLY फ़ॉर्मेट में मेष को एन्कोड करें
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### देखें भी

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

एंटिटी को एन्कोड करें और परिणाम को बाहरी फ़ाइल में सहेजें।

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड करने के लिए एंटिटी |
| fileName | String | लिखने के लिए फ़ाइल |
| विकल्प | PlySaveOptions | सेव विकल्प |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे मेष को PLY फ़ाइल में एन्कोड किया जाता है:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//PLY फ़ॉर्मेट में मेष को एन्कोड करें
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### देखें भी

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


