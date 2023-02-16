---
title: AnimationNode
second_title: .NET API संदर्भ के लिए Aspose.3D
description: Aspose.3D एनमेशन पदनुक्रम क समर्थन करत है प्रत्येक एनमेशन क कई एनमेशन और एनमेशन क कफ्रेम परभष द्वर बनय ज सकत है AnimationNode./animationnode/ समय के सथ संपत्त मूल्य के परवर्तन क परभषत करत है उदहरण के लए नड के परवर्तन य अन्य क नयंत्रत करने के लए एनमेशन नड क उपयग कय ज सकत हैA3DObject../aspose.threed/a3dobject/ वस्तु के संख्यत्मक गुण
type: docs
weight: 40
url: /hi/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D एनीमेशन पदानुक्रम का समर्थन करता है, प्रत्येक एनीमेशन को कई एनिमेशन और एनीमेशन की की-फ्रेम परिभाषा द्वारा बनाया जा सकता है। `AnimationNode` समय के साथ संपत्ति मूल्य के परिवर्तन को परिभाषित करता है, उदाहरण के लिए, नोड के परिवर्तन या अन्य को नियंत्रित करने के लिए एनीमेशन नोड का उपयोग किया जा सकता है[`A3DObject`](../../aspose.threed/a3dobject/) वस्तु के संख्यात्मक गुण।

```csharp
public class AnimationNode : A3DObject
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`AnimationNode` वर्ग. |
| [AnimationNode](animationnode/#constructor_1)(string) | का एक नया उदाहरण प्रारंभ करता है`AnimationNode` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | वर्तमान गुण बाइंड पॉइंट प्राप्त करता है |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम प्राप्त या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी संपत्तियों का संग्रह प्राप्त करता है। |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | वर्तमान एनिमेशन के अंतर्गत उप-एनीमेशन नोड प्राप्त करता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | गुण डेटा प्रकार के आधार पर एक BindPoint बनाता है। |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(string) | नाम से बाइंड पॉइंट ढूँढता है। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | संपत्ति ढूँढता है। यह एक गतिशील संपत्ति हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल संपत्ति (इसके नाम से पहचानी गई) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | दी गई संपत्ति पर एनीमेशन बाइंड पॉइंट प्राप्त करता है। |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | दिए गए गुण पर कीफ्रेम अनुक्रम प्राप्त करता है। |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | दिए गए गुण और चैनल पर मुख्य-फ़्रेम अनुक्रम प्राप्त करता है. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट संपत्ति का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक गतिशील संपत्ति को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट संपत्ति को हटाएं |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट संपत्ति का मान सेट करता है |

### यह सभी देखें

* class [A3DObject](../../aspose.threed/a3dobject/)
* नाम स्थान [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* सभा [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->