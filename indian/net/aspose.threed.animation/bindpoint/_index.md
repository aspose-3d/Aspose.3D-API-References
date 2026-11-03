---
title: "क्लास BindPoint"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Animation.BindPoint क्लास। एक BindPoint आमतौर पर किसी ऑब्जेक्ट की प्रॉपर्टी पर बनाया जाता है; कुछ प्रॉपर्टी प्रकारों में कई घटक फ़ील्ड होते हैं (जैसे Vector3 फ़ील्ड)। BindPoint प्रत्येक घटक फ़ील्ड के लिए एक चैनल उत्पन्न करेगा और फ़ील्ड को एक या अधिक कीफ़्रेम अनुक्रम इंस्टेंस के साथ चैनलों के माध्यम से जोड़ता है।"
type: docs
weight: 50
url: /hi/net/aspose.threed.animation/bindpoint/
---
## BindPoint class

`BindPoint` आमतौर पर किसी ऑब्जेक्ट की प्रॉपर्टी पर बनाया जाता है, कुछ प्रॉपर्टी प्रकारों में कई घटक फ़ील्ड होते हैं (जैसे Vector3 फ़ील्ड), `BindPoint` प्रत्येक घटक फ़ील्ड के लिए एक चैनल उत्पन्न करेगा और फ़ील्ड को एक या अधिक कीफ़्रेम अनुक्रम इंस्टेंस (इंस्टेंस) के साथ चैनलों के माध्यम से जोड़ता है।

```csharp
public class BindPoint : A3DObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | `BindPoint` क्लास का नया इंस्टेंस आरंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | इस एनीमेशन कर्व मैपिंग में परिभाषित प्रॉपर्टी चैनलों की कुल संख्या प्राप्त करता है। |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | CurveMapping से जुड़ी प्रॉपर्टी प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है। |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | निर्दिष्ट चैनल प्रॉपर्टी जोड़ता है। |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | कीफ़्रेम अनुक्रम को निर्दिष्ट चैनल से बाइंड करें। |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | एक नया कर्व बनाता है और इसे कर्व मैपिंग के पहले चैनल से जोड़ता है। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | दिए गए नाम से चैनल प्राप्त करता है। |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | निर्दिष्ट चैनल में पहला कीफ़्रेम अनुक्रम प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | इस एनीमेशन कर्व मैपिंग के प्रॉपर्टी चैनलों को खाली करता है। |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | ऑब्जेक्ट को स्ट्रिंग में फॉर्मेट करता है |

### देखें भी

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


