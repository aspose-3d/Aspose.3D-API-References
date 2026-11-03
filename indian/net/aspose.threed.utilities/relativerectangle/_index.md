---
title: "Struct RelativeRectangle"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.RelativeRectangle struct. Relative rectangle सापेक्ष घटक से निरपेक्ष मान के बीच का सूत्र है Scale  Reference Width  offset। इसलिए यदि हम इसे निरपेक्ष मान के रूप में प्रदर्शित करना चाहते हैं तो सभी स्केल फ़ील्ड को शून्य रखें और इसके बजाय ऑफ़सेट फ़ील्ड का उपयोग करें।"
type: docs
weight: 2830
url: /hi/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

रिलेटिव आयत। रिलेटिव घटक से एब्सोल्यूट वैल्यू के बीच का सूत्र है: Scale * (Reference Width) + offset। इसलिए यदि हम इसे एब्सोल्यूट वैल्यू के रूप में प्रदर्शित करना चाहते हैं, तो सभी स्केल फ़ील्ड को शून्य रखें, और इसके बजाय ऑफ़सेट फ़ील्ड का उपयोग करें।

```csharp
public struct RelativeRectangle
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | एक `RelativeRectangle` बनाएं |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | ऊँचाई के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | चौड़ाई के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | निर्देशांक X के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | निर्देशांक Y के लिए ऑफ़सेट प्राप्त करता है या सेट करता है |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | सापेक्ष ऊँचाई |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | सापेक्ष चौड़ाई |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | सापेक्ष निर्देशांक X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | सापेक्ष निर्देशांक Y |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | सभी ऑफ़सेट फ़ील्ड शून्य और दिए गए पैरामीटरों से स्केल फ़ील्ड के साथ एक `RelativeRectangle` बनाएं। |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | सापेक्ष आयत को निरपेक्ष आयत में परिवर्तित करें |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | इस उदाहरण का मान एक स्ट्रिंग में परिवर्तित करता है। |

### देखें भी

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


