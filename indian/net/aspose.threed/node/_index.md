---
title: "क्लास Node"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Node क्लास। सीन ग्राफ में एक तत्व का प्रतिनिधित्व करता है। सीन ग्राफ Node ऑब्जेक्ट्स का एक ट्री है। ट्री प्रबंधन सेवाएँ इस क्लास में स्वयं समाहित हैं। ध्यान दें कि Aspose.3D SDK निर्मित सीन ग्राफ की वैधता का परीक्षण नहीं करता। यह कॉलर की जिम्मेदारी है कि वह सुनिश्चित करे कि नोड पदानुक्रम में चक्रीय ग्राफ न बनें। ट्री प्रबंधन के अलावा, यह क्लास उन सभी प्रॉपर्टीज़ को परिभाषित करता है जो सीन में ऑब्जेक्ट की स्थिति का वर्णन करने के लिए आवश्यक हैं। इस जानकारी में मूलभूत Translation Rotation और Scaling प्रॉपर्टीज़ तथा पिवट्स, लिमिट्स और IK जॉइंट्स एट्रिब्यूट्स जैसे उन्नत विकल्प शामिल हैं, जैसे कि stiffness और damping। जब पहली बार बनाया जाता है, Node ऑब्जेक्ट खाली होता है, अर्थात यह कोई ग्राफिकल प्रतिनिधित्व नहीं रखता और केवल स्थिति जानकारी रखता है। इस अवस्था में इसे नोड ट्री संरचना में पैरेंट्स को दर्शाने के लिए उपयोग किया जा सकता है, लेकिन अधिक नहीं। इस प्रकार के ऑब्जेक्ट्स का सामान्य उपयोग उन्हें एक entity जोड़ना है जो नोड को विशेष बनाता है; देखें Entity। Entity स्वयं में एक ऑब्जेक्ट है और Node से जुड़ा होता है। इसका अर्थ यह भी है कि वही entity कई नोड्स के बीच साझा की जा सकती है। Camera, Light, Mesh आदि सभी entities हैं और वे सभी बेस क्लास Entity से व्युत्पन्न हैं।"
type: docs
weight: 1630
url: /hi/net/aspose.threed/node/
---
## Node class

सीन ग्राफ में एक तत्व का प्रतिनिधित्व करता है। सीन ग्राफ Node ऑब्जेक्ट्स का एक ट्री है। ट्री मैनेजमेंट सर्विसेज इस क्लास में स्वयं-contained हैं। ध्यान दें कि Aspose.3D SDK निर्मित सीन ग्राफ की वैधता की जाँच नहीं करता। यह कॉलर की ज़िम्मेदारी है कि वह सुनिश्चित करे कि वह नोड हायरार्की में साइक्लिक ग्राफ न बनाये। ट्री मैनेजमेंट के अलावा, यह क्लास उन सभी प्रॉपर्टीज़ को परिभाषित करती है जो सीन में ऑब्जेक्ट की स्थिति का वर्णन करने के लिए आवश्यक हैं। इस जानकारी में बेसिक ट्रांसलेशन, रोटेशन और स्केलिंग प्रॉपर्टीज़ तथा पिवट्स, लिमिट्स और IK जॉइंट्स के उन्नत विकल्प जैसे स्टिफनेस और डैम्पनिंग शामिल हैं। जब पहली बार बनाया जाता है, तो Node ऑब्जेक्ट "empty" (अर्थात: यह एक ऑब्जेक्ट है जिसमें कोई ग्राफिकल प्रतिनिधित्व नहीं है और केवल स्थिति जानकारी रखता है) होता है। इस स्थिति में, इसे नोड ट्री स्ट्रक्चर में पैरेंट्स को दर्शाने के लिए उपयोग किया जा सकता है लेकिन अधिक नहीं। इस प्रकार के ऑब्जेक्ट्स का सामान्य उपयोग उन्हें एक एंटिटी जोड़ना है जो नोड को विशेष बनाता है ("Entity" देखें)। एंटिटी स्वयं में एक ऑब्जेक्ट है और Node से जुड़ी होती है। इसका मतलब यह भी है कि वही एंटिटी कई नोड्स में साझा की जा सकती है। Camera, Light, Mesh आदि सभी एंटिटी हैं और वे सभी बेस क्लास Entity से व्युत्पन्न हैं।

```csharp
public class Node : SceneObject
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Node](node/#constructor)() | `Node` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Node](node/#constructor_1)(string) | `Node` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Node](node/#constructor_2)(string, Entity) | `Node` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo/) { get; set; } | प्रति-नोड एसेट जानकारी |
| [ChildNodes](../../aspose.threed/node/childnodes/) { get; } | चाइल्ड नोड्स प्राप्त करता है। |
| [Entities](../../aspose.threed/node/entities/) { get; } | सभी नोड एंटिटीज़ प्राप्त करता है। |
| [Entity](../../aspose.threed/node/entity/) { get; set; } | इस नोड से जुड़ी पहली entity को प्राप्त करता है या सेट करता है; यदि सेट किया जाता है, तो अन्य entities को साफ़ कर देगा। |
| [Excluded](../../aspose.threed/node/excluded/) { get; set; } | एक्सपोर्टिंग के दौरान इस नोड और सभी चाइल्ड नोड्स/एंटिटीज़ को बाहर रखना है या नहीं, प्राप्त करता है या सेट करता है। |
| [GlobalTransform](../../aspose.threed/node/globaltransform/) { get; } | ग्लोबल ट्रांसफ़ॉर्म प्राप्त करता है। |
| [Material](../../aspose.threed/node/material/) { get; set; } | इस नोड से जुड़ा पहला मैटेरियल प्राप्त करता है या सेट करता है; यदि सेट किया जाता है, तो अन्य मैटेरियल्स को साफ़ कर देगा। |
| [Materials](../../aspose.threed/node/materials/) { get; } | इस नोड से जुड़े मैटेरियल्स प्राप्त करता है। |
| [MetaDatas](../../aspose.threed/node/metadatas/) { get; } | इस नोड में परिभाषित मेटा डेटा प्राप्त करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/node/parentnode/) { get; set; } | पैरेंट नोड प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Transform](../../aspose.threed/node/transform/) { get; } | लोकल ट्रांसफ़ॉर्म प्राप्त करता है। |
| [Visible](../../aspose.threed/node/visible/) { get; set; } | नोड को दिखाने के लिए प्राप्त या सेट करता है |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Accept](../../aspose.threed/node/accept/)(NodeVisitor) | सभी अवनति नोड्स (वर्तमान नोड सहित) के माध्यम से चलता है और नोड के साथ विज़िटर को कॉल करता है। विज़िटर false लौटाकर वॉक-थ्रू को रोक सकता है। |
| [AddChildNode](../../aspose.threed/node/addchildnode/)(Node) | इस नोड में एक चाइल्ड नोड जोड़ें |
| [AddEntity](../../aspose.threed/node/addentity/)(Entity) | नोड में एक एंटिटी जोड़ें। |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode)() | एक चाइल्ड नोड बनाता है |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_1)(Entity) | दिए गए एंटिटी संलग्न के साथ एक नया चाइल्ड नोड बनाएं |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_2)(string) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_3)(string, Entity) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_4)(string, Entity, Material) | दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं, और निर्दिष्ट एंटिटी तथा एक सामग्री संलग्न करें |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform/)(bool) | ग्लोबल ट्रांसफ़ॉर्म का मूल्यांकन करें, ज्यामितीय ट्रांसफ़ॉर्म शामिल करें या नहीं। |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox/)() | नोड का बाउंडिंग बॉक्स गणना करें |
| [GetChild](../../aspose.threed/node/getchild/#getchild)(int) | निर्दिष्ट इंडेक्स पर चाइल्ड नोड प्राप्त करता है। |
| [GetChild](../../aspose.threed/node/getchild/#getchild_1)(string) | निर्दिष्ट नाम वाले चाइल्ड नोड को प्राप्त करता है |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity/)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [Merge](../../aspose.threed/node/merge/)(Node) | नोड के अंतर्गत सभी चीज़ों को अलग करें और उन्हें वर्तमान नोड से संलग्न करें। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SelectObjects](../../aspose.threed/node/selectobjects/)(string) | XPath-समरूप क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के अंतर्गत कई ऑब्जेक्ट चुनें। |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject/)(string) | XPath-समरूप क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के अंतर्गत एकल ऑब्जेक्ट चुनें। |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| override [ToString](../../aspose.threed/node/tostring/)() | इस नोड का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |

### देखें भी

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


