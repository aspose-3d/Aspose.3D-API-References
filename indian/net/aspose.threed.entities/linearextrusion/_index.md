---
title: "क्लास LinearExtrusion"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.LinearExtrusion क्लास. रैखिक एक्सट्रूज़न 2D आकार को इनपुट के रूप में लेता है और आकार को तीसरे आयाम में विस्तारित करता है।"
type: docs
weight: 490
url: /hi/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

रैखिक एक्सट्रूज़न 2D आकार को इनपुट के रूप में लेता है और आकार को तीसरे आयाम में विस्तारित करता है।

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | `LinearExtrusion` उदाहरण का कन्स्ट्रक्टर। |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | `LinearExtrusion` उदाहरण का कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | यदि यह मान false है, तो रैखिक एक्सट्रूज़न Z रेंज 0 से ऊँचाई तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी। |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | एक्सट्रूज़न की दिशा, डिफ़ॉल्ट मान (0, 0, 1) है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | एक्सट्रूडेड ज्यामिति की ऊँचाई, डिफ़ॉल्ट मान 1.0 है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | एक्सट्रूड करने के लिए आधार आकार। |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | ट्विस्टेड एक्सट्रूडेड ज्यामिति के स्लाइस, डिफ़ॉल्ट मान 1 है। |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | जिस डिग्री के माध्यम से आकार एक्सट्रूड किया जाता है, उसकी संख्या। |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | ट्विस्टिंग में उपयोग किया गया ऑफ़सेट, डिफ़ॉल्ट मान (0, 0, 0) है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | एक्सट्रूज़न को मेष में परिवर्तित करें। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि LinearExtrusion का उपयोग करके आकार को ठोस मॉडल में कैसे एक्सट्रूड किया जाए।

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//एक नया 3D दृश्य बनाएं
Scene scene = new Scene();

// एक्सट्रूड करने के लिए बेस प्रोफ़ाइल को प्रारंभ करें
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// बायाँ नोड बनाएं
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// दाएँ नोड बनाएं
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//केंद्र और स्लाइस गुण का उपयोग करके बाएँ नोड पर रैखिक एक्सट्रूज़न करें
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// केंद्र और स्लाइस गुण का उपयोग करके बाएँ नोड पर रैखिक एक्सट्रूज़न करें
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### देखें भी

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


