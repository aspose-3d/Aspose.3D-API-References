---
title: "FileFormat.Detect"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileFormat विधि। डेटा स्ट्रीम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल नाम वैकल्पिक है उन प्रकारों का अनुमान लगाने के लिए जिनमें कोई मैजिक हेडर नहीं है"
type: docs
weight: 460
url: /hi/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

डेटा स्ट्रीम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल नाम वैकल्पिक है उन प्रकारों का अनुमान लगाने के लिए जिनमें कोई मैजिक हेडर नहीं है।

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | पहचानने के लिए डेटा युक्त स्ट्रीम |
| fileName | String | डेटा का मूल फ़ाइल नाम, संकेत के रूप में उपयोग किया जाता है। |

### रिटर्न वैल्यू

पता लगाए गए प्रकार का [`FileFormat`](../) उदाहरण, या यदि विफल हो तो null।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | डेटा पढ़ने में विफल होने पर उत्पन्न अपवाद। |

## उदाहरण

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### देखें भी

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

फ़ाइल नाम से फ़ाइल फ़ॉर्मेट का पता लगाएँ, फ़ाइल पढ़ने योग्य होनी चाहिए ताकि Aspose.3D फ़ाइल हेडर के माध्यम से फ़ॉर्मेट का पता लगा सके।

```csharp
public static FileFormat Detect(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल फ़ॉर्मेट का पता लगाने के लिए फ़ाइल का पथ। |

### रिटर्न वैल्यू

पता लगाए गए प्रकार का [`FileFormat`](../) उदाहरण, या यदि विफल हो तो null।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | डेटा पढ़ने में विफल होने पर उत्पन्न अपवाद। |

## उदाहरण

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### देखें भी

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


