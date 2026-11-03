---
title: "क्लास AnimationNode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Animation.AnimationNode क्लास। Aspose.3Ds एनीमेशन पदानुक्रम का समर्थन करता है, प्रत्येक एनीमेशन कई एनीमेशन और एनीमेशन की-फ़्रेम परिभाषा द्वारा निर्मित हो सकता है। AnimationNode समय के साथ एक प्रॉपर्टी वैल्यू के ट्रांसफ़ॉर्मेशन को परिभाषित करता है, उदाहरण के लिए एनीमेशन नोड का उपयोग नोड के ट्रांसफ़ॉर्मेशन या अन्य A3DObject ऑब्जेक्ट्स की संख्यात्मक प्रॉपर्टीज़ को नियंत्रित करने के लिए किया जा सकता है।"
type: docs
weight: 40
url: /hi/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D एनीमेशन पदानुक्रम का समर्थन करता है, प्रत्येक एनीमेशन कई एनीमेशन और एनीमेशन की-फ़्रेम परिभाषा द्वारा निर्मित हो सकता है। `AnimationNode` समय के साथ एक प्रॉपर्टी वैल्यू के ट्रांसफ़ॉर्मेशन को परिभाषित करता है, उदाहरण के लिए, एनीमेशन नोड का उपयोग नोड के ट्रांसफ़ॉर्मेशन या अन्य [`A3DObject`](../../aspose.threed/a3dobject/) ऑब्जेक्ट की संख्यात्मक प्रॉपर्टीज़ को नियंत्रित करने के लिए किया जा सकता है।

```csharp
public class AnimationNode : A3DObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | `AnimationNode` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [AnimationNode](animationnode/#constructor_1)(string) | `AnimationNode` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | वर्तमान प्रॉपर्टी बाइंड पॉइंट्स प्राप्त करता है |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | वर्तमान एनीमेशन के तहत सब-एनीमेशन नोड्स प्राप्त करता है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | प्रॉपर्टी डेटा टाइप के आधार पर एक BindPoint बनाता है। |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | टारगेट और नाम द्वारा बाइंड पॉइंट खोजता है। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | दिए गए प्रॉपर्टी पर एनीमेशन बाइंड पॉइंट प्राप्त करता है। |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | दिए गए प्रॉपर्टी पर कीफ़्रेम अनुक्रम प्राप्त करता है। |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | दिए गए प्रॉपर्टी और चैनल पर कीफ़्रेम अनुक्रम प्राप्त करता है। |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


