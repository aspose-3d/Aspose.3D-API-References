---
title: "DracoFormat.Encode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "DracoFormat मेथड। निर्दिष्ट स्ट्रीम में एंटिटी को एन्कोड करें।"
type: docs
weight: 20
url: /hi/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

एंटिटी को निर्दिष्ट स्ट्रीम में एन्कोड करें

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड की जाने वाली एंटिटी। |
| stream | Stream | स्ट्रीम जिसमें एन्कोड किया गया डेटा लिखा जाएगा। |
| options | DracoSaveOptions | पॉइंट क्लाउड को एन्कोड करने के अतिरिक्त विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | स्ट्रीम से पढ़ने में विफल होने पर फेंका जाता है। |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

एंटिटी को निर्दिष्ट फ़ाइल में एन्कोड करें

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड की जाने वाली एंटिटी। |
| fileName | String | लिखी जाने वाली फ़ाइल नाम। |
| options | DracoSaveOptions | पॉइंट क्लाउड को एन्कोड करने के अतिरिक्त विकल्प। |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

एंटिटी को Draco कच्चे डेटा में एन्कोड करें

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | एन्कोड की जाने वाली एंटिटी। |
| options | DracoSaveOptions | पॉइंट क्लाउड को एन्कोड करने के अतिरिक्त विकल्प। |

### रिटर्न वैल्यू

बाइट्स में दर्शाए गए एन्कोडेड draco डेटा।

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


