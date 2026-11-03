---
title: "Watermark.EncodeWatermark"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Watermark मेथड। टेक्स्ट को मेश ब्लाइंड वॉटरमार्क में एन्कोड करें"
type: docs
weight: 20
url: /hi/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें।

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इनपुट | मेश | ब्लाइंड वॉटरमार्क एन्कोड करने के लिए मेश |
| टेक्स्ट | String | मेश में एन्कोड करने के लिए टेक्स्ट |

### रिटर्न वैल्यू

ब्लाइंड वॉटरमार्क एन्कोड के साथ एक नया मेश इंस्टेंस

## टिप्पणियाँ

`EncodeWatermark` और [`DecodeWatermark`](../decodewatermark/) दोनों लाइसेंस जांच करेंगे। ट्रायल उपयोग में अपवाद फेंका जाएगा, आप [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) का उपयोग करके अपवाद को दबा सकते हैं, लेकिन यह यहाँ प्रतिबंध को नहीं हटाएगा। इन सुविधाओं को बिना किसी प्रतिबंध के उपयोग करने के लिए एक वैध लाइसेंस आवश्यक है।

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक ब्लाइंड वॉटरमार्क को मेष में एन्कोड किया जाए और उसे ply फ़ाइल में सहेजा जाए।

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### देखें भी

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें।

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इनपुट | मेश | ब्लाइंड वॉटरमार्क एन्कोड करने के लिए मेश |
| टेक्स्ट | String | मेश में एन्कोड करने के लिए टेक्स्ट |
| पासवर्ड | String | वॉटरमार्क की सुरक्षा के लिए पासवर्ड, यह वैकल्पिक है। |

### रिटर्न वैल्यू

ब्लाइंड वॉटरमार्क एन्कोड के साथ एक नया मेश इंस्टेंस

## टिप्पणियाँ

`EncodeWatermark` और [`DecodeWatermark`](../decodewatermark/) दोनों लाइसेंस जांच करेंगे। ट्रायल उपयोग में अपवाद फेंका जाएगा, आप [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) का उपयोग करके अपवाद को दबा सकते हैं, लेकिन यह यहाँ प्रतिबंध को नहीं हटाएगा। इन सुविधाओं को बिना किसी प्रतिबंध के उपयोग करने के लिए एक वैध लाइसेंस आवश्यक है।

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक ब्लाइंड वॉटरमार्क को मेष में एन्कोड किया जाए और उसे ply फ़ाइल में सहेजा जाए।

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### देखें भी

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें।

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इनपुट | मेश | ब्लाइंड वॉटरमार्क एन्कोड करने के लिए मेश |
| टेक्स्ट | String | मेश में एन्कोड करने के लिए टेक्स्ट |
| पासवर्ड | String | वॉटरमार्क की सुरक्षा के लिए पासवर्ड, यह वैकल्पिक है। |
| स्थायी | Boolean | स्थायी वॉटरमार्क को ओवरराइट या हटाया नहीं जाएगा। |

### रिटर्न वैल्यू

ब्लाइंड वॉटरमार्क एन्कोड के साथ एक नया मेश इंस्टेंस

## टिप्पणियाँ

`EncodeWatermark` और [`DecodeWatermark`](../decodewatermark/) दोनों लाइसेंस जांच करेंगे। ट्रायल उपयोग में अपवाद फेंका जाएगा, आप [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) का उपयोग करके अपवाद को दबा सकते हैं, लेकिन यह यहाँ प्रतिबंध को नहीं हटाएगा। इन सुविधाओं को बिना किसी प्रतिबंध के उपयोग करने के लिए एक वैध लाइसेंस आवश्यक है।

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक ब्लाइंड वॉटरमार्क को मेष में एन्कोड किया जाए और उसे ply फ़ाइल में सहेजा जाए।

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### देखें भी

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


