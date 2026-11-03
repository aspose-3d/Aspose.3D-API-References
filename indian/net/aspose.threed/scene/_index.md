---
title: "क्लास Scene"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Scene क्लास। एक सीन एक टॉप-लेवल ऑब्जेक्ट है जो नोड्स, ज्योमेट्रीज़, मैटेरियल्स, टेक्सचर, एनीमेशन, पोज़, सबसीन्स आदि को शामिल करता है। सीन में सबसीन्स हो सकते हैं और यह collada/blender/fbx जैसी फ़ाइलों में मल्टी-डॉक्यूमेंट समर्थन के रूप में कार्य करता है। नोड पदानुक्रम को RootNodeLibrary के माध्यम से एक्सेस किया जा सकता है। यह सीरियलाइज़ेशन के दौरान अनअटैच्ड ऑब्जेक्ट्स (जैसे मेटा डेटा या कस्टम ऑब्जेक्ट्स) का रेफ़रेंस रखने के लिए उपयोग किया जाता है, इसलिए इसे लाइब्रेरी के रूप में इस्तेमाल किया जा सकता है।"
type: docs
weight: 2500
url: /hi/net/aspose.threed/scene/
---
## Scene class

एक सीन एक टॉप-लेवल ऑब्जेक्ट है जो नोड्स, ज्योमेट्रीज़, मैटेरियल्स, टेक्सचर, एनीमेशन, पोज़, सब-सीन्स आदि को शामिल करता है। सीन में सब-सीन्स हो सकते हैं, और यह collada/blender/fbx जैसी फ़ाइलों में मल्टीपल-डॉक्यूमेंट समर्थन के रूप में कार्य करता है। नोड पदानुक्रम को [`RootNode`](./rootnode/)[`Library`](./library/) के माध्यम से एक्सेस किया जा सकता है। यह अनअटैच्ड ऑब्जेक्ट्स (जैसे मेटा डेटा या कस्टम ऑब्जेक्ट्स) का रेफ़रेंस रखने के लिए सीरियलाइज़ेशन के दौरान उपयोग किया जाता है, इसलिए इसे लाइब्रेरी के रूप में इस्तेमाल किया जा सकता है।

```csharp
public class Scene : SceneObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Scene](scene/#constructor)() | `Scene` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Scene](scene/#constructor_1)(Entity) | `Scene` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है जिसमें एक नई नोड से एंटिटी संलग्न है। |
| [Scene](scene/#constructor_2)(Scene, string) | एक नई उप-दृश्य के रूप में `Scene` वर्ग का नया उदाहरण आरंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | दृश्य में परिभाषित सभी [`AnimationClip`](../../aspose.threed.animation/animationclip/) प्राप्त करता है। |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | शीर्ष-स्तर की संपत्ति जानकारी प्राप्त करता या सेट करता है |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | सक्रिय [`AnimationClip`](../../aspose.threed.animation/animationclip/) प्राप्त करता या सेट करता है |
| [Library](../../aspose.threed/scene/library/) { get; } | वे वस्तुएँ जो दृश्य पदानुक्रम में सीधे उपयोग नहीं होतीं, लाइब्रेरी में परिभाषित की जा सकती हैं। यह तब उपयोगी है जब आप उप-दृश्यों का उपयोग करते हैं और पुन: उपयोग योग्य घटकों को उप-दृश्यों के तहत रखते हैं। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Poses](../../aspose.threed/scene/poses/) { get; } | इस दृश्य में उपयोग किए गए सभी [`Pose`](../pose/) प्राप्त करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | दृश्य का मूल नोड प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | सभी उप-दृश्य प्राप्त करता है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | दिए गए पथ से दृश्य खोलता है |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | दिए गए पथ से दृश्य खोलता है |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | दिए गए स्ट्रीम से दृश्य खोलता है |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [Clear](../../aspose.threed/scene/clear/)() | दृश्य की सामग्री साफ़ करता है और डिफ़ॉल्ट सेटिंग्स को पुनर्स्थापित करता है। |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | [`AnimationClip`](../../aspose.threed.animation/animationclip/) बनाने और पंजीकृत करने के लिए एक संक्षिप्त फ़ंक्शन। पहला [`AnimationClip`](../../aspose.threed.animation/animationclip/) को [`CurrentAnimationClip`](./currentanimationclip/) को सौंपा जाएगा। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | नामित [`AnimationClip`](../../aspose.threed.animation/animationclip/) प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | दिए गए पथ से दृश्य खोलता है |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | दिए गए पथ से दृश्य खोलता है |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है। डिफ़ॉल्ट आउटपुट आकार 1024x768 है और आउटपुट स्वरूप png है। |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है। |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है। |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है। |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है। |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है। |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है। |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | वर्तमान रिलीज़ संस्करण प्राप्त करता है |

### देखें भी

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


