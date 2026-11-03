---
title: "Watermark.DecodeWatermark"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Watermark मेथड। एक मेश से वॉटरमार्क डिकोड करें"
type: docs
weight: 10
url: /hi/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

मेश से वॉटरमार्क को डिकोड करें

```csharp
public static string DecodeWatermark(Mesh input)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इनपुट | मेश | वॉटरमार्क निकालने के लिए मेश |

### रिटर्न वैल्यू

ब्लाइंड वॉटरमार्क या null यदि कोई वॉटरमार्क डिकोड नहीं हुआ।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| UnauthorizedAccessException | मेश पासवर्ड द्वारा संरक्षित है, और दिया गया पासवर्ड गलत है। |

## टिप्पणियाँ

दोनों [`EncodeWatermark`](../encodewatermark/) और `DecodeWatermark` लाइसेंस जाँच करेंगे। ट्रायल उपयोग में अपवाद फेंका जाएगा, आप [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) का उपयोग करके अपवाद को दबा सकते हैं, लेकिन यह यहाँ प्रतिबंध को नहीं हटाएगा। इन सुविधाओं को बिना किसी प्रतिबंध के उपयोग करने के लिए एक वैध लाइसेंस आवश्यक है।

## उदाहरण

निम्नलिखित कोड दिखाता है कि 3D फ़ाइल में सहेजे गए मेश से ब्लाइंड वॉटरमार्क को कैसे डिकोड किया जाए।

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### देखें भी

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

मेश से वॉटरमार्क को डिकोड करें

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इनपुट | मेश | वॉटरमार्क निकालने के लिए मेश |
| पासवर्ड | String | वॉटरमार्क को डिक्रिप्ट करने के लिए पासवर्ड |

### रिटर्न वैल्यू

ब्लाइंड वॉटरमार्क या null यदि कोई वॉटरमार्क डिकोड नहीं हुआ।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| UnauthorizedAccessException | मेश पासवर्ड द्वारा संरक्षित है, और दिया गया पासवर्ड गलत है। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि 3D फ़ाइल में सहेजे गए मेश से ब्लाइंड वॉटरमार्क को कैसे डिकोड किया जाए।

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### देखें भी

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


