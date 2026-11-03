---
title: "Class Watermark"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.Watermark class. ब्लाइंड वॉटरमार्क को मेष में एन्कोड/डिकोड करने के लिए उपयोगिता"
type: docs
weight: 2950
url: /hi/net/aspose.threed.utilities/watermark/
---
## Watermark class

मेश से/तक ब्लाइंड वॉटरमार्क को एन्कोड/डिकोड करने के लिए उपयोगिता।

```csharp
public class Watermark
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | मेश से वॉटरमार्क को डिकोड करें |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | मेश से वॉटरमार्क को डिकोड करें |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें। |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें। |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | पाठ को मेष के ब्लाइंड वॉटरमार्क में एन्कोड करें। |

## टिप्पणियाँ

Both [`EncodeWatermark`](./encodewatermark/) and [`DecodeWatermark`](./decodewatermark/) लाइसेंस जांच करेंगे। ट्रायल उपयोग में अपवाद फेंका जाएगा, आप अपवाद को दबाने के लिए [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) का उपयोग कर सकते हैं, लेकिन यह यहाँ प्रतिबंध को नहीं हटाएगा। इन सुविधाओं का बिना किसी प्रतिबंध के उपयोग करने के लिए एक वैध लाइसेंस आवश्यक है।

## उदाहरण

निम्नलिखित कोड दिखाता है कि ब्लाइंड वॉटरमार्क को मेष में कैसे एन्कोड किया जाए और उसे डिकोड किया जाए।

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### देखें भी

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


