---
title: "क्लास AnimationChannel"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Animation.AnimationChannel क्लास। एक चैनल प्रॉपर्टी के घटक फ़ील्ड को कीफ़्रेम अनुक्रमों के सेट से मैप करता है"
type: docs
weight: 20
url: /hi/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

एक चैनल प्रॉपर्टी के घटक फ़ील्ड को कीफ़्रेम अनुक्रमों के सेट से मैप करता है

```csharp
public class AnimationChannel : KeyframeSequence
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | उस प्रॉपर्टी बाइंड पॉइंट को प्राप्त करता है जो इस कर्व का स्वामित्व रखता है। |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype/) { get; } | घटक फ़ील्ड का प्रकार प्राप्त करता है |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue/) { get; set; } | चैनल का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। यदि किसी चैनल से कोई कीफ़्रेम अनुक्रम जुड़ा नहीं है, तो एनीमेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा। एक वास्तविक परिदृश्य: एनीमेशन केवल एक नोड के x निर्देशांक को एनिमेट करता है, y और z नहीं बदलते, तब पूर्ण ट्रांसलेशन मूल्यांकन के दौरान डिफ़ॉल्ट मान उपयोग किया जाएगा। |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | इस कर्व के कीफ़्रेम्स को प्राप्त करता है। |
| [KeyframeSequence](../../aspose.threed.animation/animationchannel/keyframesequence/) { get; set; } | इस चैनल के भीतर संबंधित कीफ़्रेम अनुक्रम प्राप्त करता है |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | पोस्ट बिहेवियर को प्राप्त करता है जो दर्शाता है कि अंतिम कीफ़्रेम के बाद सैंपल किया गया मान क्या होना चाहिए। |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | प्रि बिहेवियर को प्राप्त करता है जो दर्शाता है कि पहले कीफ़्रेम से पहले सैंपल किया गया मान क्या होना चाहिए। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float) | निर्दिष्ट मान के साथ एक नया कीफ़्रेम बनाएं |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float, Interpolation) | निर्दिष्ट मान के साथ एक नया कीफ़्रेम बनाएं |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | सभी कीफ़्रेम्स को पार करने के लिए एनेमरेटर प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | सभी कीफ़्रेम्स को हटाता है और पोस्ट/प्रि बिहेवियर्स को रीसेट करता है। |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [KeyframeSequence](../keyframesequence/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


