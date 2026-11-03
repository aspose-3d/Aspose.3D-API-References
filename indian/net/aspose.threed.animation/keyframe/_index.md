---
title: "क्लास KeyFrame"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Animation.KeyFrame class. एक कुंजी फ्रेम मुख्यतः समय और मान द्वारा परिभाषित होती है; कुछ इंटरपोलेशन प्रकारों के लिए टैंजेंट/तनाव/पक्षपात/सततता का उपयोग अंतिम सैंपल्ड मान की गणना में भी किया जाता है। गैर-कीफ़्रेम समय स्थिति में सैंपल्ड मान पिछले और अगले कीफ़्रेम के बीच इंटरपोलेट किए जाते हैं। पहले/अंतिम कीफ़्रेम से पहले/बाद का मान Extrapolation class द्वारा गणना किया जाता है।"
type: docs
weight: 90
url: /hi/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

एक कुंजी फ्रेम मुख्यतः समय और मान द्वारा परिभाषित होती है, कुछ इंटरपोलेशन प्रकारों के लिए टैंजेंट/तनाव/पक्षपात/सततता का उपयोग अंतिम सैंपल्ड मान की गणना में भी किया जाता है। गैर-कीफ़्रेम समय स्थिति में सैंपल्ड मान पिछले और अगले कीफ़्रेम के बीच इंटरपोलेट किए जाते हैं। पहले/अंतिम कीफ़्रेम से पहले/बाद का मान [`Extrapolation`](../extrapolation/) क्लास द्वारा गणना किया जाता है।

```csharp
public class KeyFrame
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | निर्दिष्ट वक्र पर एक नया कीफ़्रेम बनाएं |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | TCB स्प्लाइन में उपयोग किए जाने वाले पक्षपात को प्राप्त करता है या सेट करता है |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | TCB स्प्लाइन में उपयोग की जाने वाली सततता को प्राप्त करता है या सेट करता है |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | यदि कीफ़्रेम सपाट है तो प्राप्त करें या सेट करें। यदि अगला या पिछला कीफ़्रेम समान मान रखता है तो कीफ़्रेम सपाट होना चाहिए। सपाट कीफ़्रेम की टैंजेंट्स सपाट होती हैं और इंटरपोलेशन स्थिर रहता है। |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | आउट और अगले इन टैंजेंट्स को स्वतंत्र होने के रूप में प्राप्त करता है या सेट करता है। |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | की का इंटरपोलेशन प्रकार प्राप्त करता है या सेट करता है, list.data[index] निर्धारित करता है कि सैंपल्ड मान कैसे गणना किया जाता है। |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | इस कीफ़्रेम पर अगले इन (बाएँ) टैंजेंट को प्राप्त करता है या सेट करता है। |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | इस कीफ़्रेम पर अगले इन (बाएँ) वजन को प्राप्त करता है या सेट करता है। |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | इस कीफ़्रेम पर आउट (दाएँ) टैंजेंट को प्राप्त करता है या सेट करता है। |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | इस कीफ़्रेम पर आउट (दाएँ) वजन को प्राप्त करता है या सेट करता है। |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | की का स्टेप मोड प्राप्त करता है या सेट करता है। यदि इंटरपोलेशन प्रकार स्थिर है, तो list.data[index] तय करता है कि इंटरपोलेशन के दौरान कौन से कीफ़्रेम का मान उपयोग किया जाएगा। एक PreviousValue का अर्थ है कि बाएँ कीफ़्रेम का मान उपयोग होगा। एक NextValue का अर्थ है कि अगला दाएँ कीफ़्रेम का मान उपयोग होगा। |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | की का टैंजेंट वजन मोड प्राप्त करता है या सेट करता है। आउट टैंजेंट या अगले इन टैंजेंट को सही [`WeightedMode`](../weightedmode/) चुनकर अनुकूलित किया जा सकता है। |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | TCB स्प्लाइन में उपयोग किए जाने वाले तनाव को प्राप्त करता है या सेट करता है |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | list.data[index] कीफ़्रेम की समय स्थिति को सेकंड में मापते हुए प्राप्त करता है या सेट करता है। |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | टैंजेंट को समय-स्वतंत्र होने के रूप में प्राप्त करता है या सेट करता है |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | की-फ़्रेम का मान प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | की फ्रेम का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है |

### देखें भी

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


