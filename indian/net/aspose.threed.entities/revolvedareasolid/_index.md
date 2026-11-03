---
title: "क्लास RevolvedAreaSolid"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.RevolvedAreaSolid क्लास। यह क्लास एक प्रोफ़ाइल द्वारा प्रदान किए गए क्रॉस‑सेक्शन को अक्ष के चारों ओर घुमा कर एक ठोस मॉडल दर्शाती है"
type: docs
weight: 680
url: /hi/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

यह क्लास एक प्रोफ़ाइल द्वारा प्रदान किए गए क्रॉस‑सेक्शन को धुरी के चारों ओर घुमाकर एक ठोस मॉडल का प्रतिनिधित्व करती है।

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | घुमाव प्रक्रिया का अंतिम कोण प्राप्त करता है या सेट करता है, रेडियन में मापा जाता है, डिफ़ॉल्ट मान π है। |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | घुमाव प्रक्रिया का प्रारंभिक कोण प्राप्त करता है या सेट करता है, रेडियन में मापा जाता है, डिफ़ॉल्ट मान 0 है। |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | अक्ष की दिशा प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान (0, 1, 0) है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | घुमाव का मूल बिंदु प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | घुमाने के लिए उपयोग किए जाने वाले बेस प्रोफ़ाइल को प्राप्त करता है या सेट करता है। |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | `RevolvedAreaSolid` को एक मेष में परिवर्तित करें। |

## उदाहरण

निम्नलिखित कोड दिखाता है कि RevolvedAreaSolid का उपयोग करके किसी आकार को ठोस मॉडल में कैसे घुमाया जाए।

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//एक नया 3D दृश्य बनाएं
Scene scene = new Scene();

// घुमाने के लिए बेस प्रोफ़ाइल को प्रारंभ करें
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//एक RevolvedAreaSolid इंस्टेंस बनाएं
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//एक नया 3D दृश्य बनाएं
Scene scene = new Scene();

// एक्सट्रूड करने के लिए बेस प्रोफ़ाइल को प्रारंभ करें
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### देखें भी

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


