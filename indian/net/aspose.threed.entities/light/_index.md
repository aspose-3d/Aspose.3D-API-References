---
title: "क्लास Light"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Light क्लास। प्रकाश दृश्य को प्रकाशित करता है"
type: docs
weight: 460
url: /hi/net/aspose.threed.entities/light/
---
## Light class

रोशनी दृश्य को प्रकाशित करती है।

प्रकाश के कुल क्षीणन की गणना करने का सूत्र है: `A = ConstantAttenuation + (Dist * LinearAttenuation) + ((Dist^2) * QuadraticAttenuation)`

```csharp
public class Light : Frustum
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Light](light/#constructor)() | `Light` क्लास का नया उदाहरण प्रारंभ करता है। |
| [Light](light/#constructor_1)(string) | `Light` क्लास का नया उदाहरण प्रारंभ करता है। |
| [Light](light/#constructor_2)(string, LightType) | `Light` क्लास का नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | फ्रस्टम का आस्पेक्ट रेशियो प्राप्त करता है या सेट करता है। |
| [CastLight](../../aspose.threed.entities/light/castlight/) { get; set; } | वर्तमान प्रकाश उदाहरण अन्य वस्तुओं को प्रकाशित कर सकता है या नहीं, यह निर्धारित करता है या सेट करता है। |
| [CastShadows](../../aspose.threed.entities/light/castshadows/) { get; set; } | प्रकाश अन्य वस्तुओं पर छाया डाल सकता है या नहीं, यह निर्धारित करता है या सेट करता है। |
| [Color](../../aspose.threed.entities/light/color/) { get; set; } | प्रकाश का रंग प्राप्त करता है या सेट करता है |
| [ConstantAttenuation](../../aspose.threed.entities/light/constantattenuation/) { get; set; } | प्रकाश के कुल क्षीणन की गणना करने के लिए स्थिर क्षीणन प्राप्त करता है या सेट करता है |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | कैमरा जिस दिशा की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। इस प्रॉपर्टी में बदलाव [`LookAt`](../frustum/lookat/) और [`Target`](../frustum/target/) को भी प्रभावित करेंगे। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [Falloff](../../aspose.threed.entities/light/falloff/) { get; set; } | फ़ॉलऑफ़ कोन कोण (डिग्री में) प्राप्त करता है या सेट करता है। |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | फ्रस्टम की दूरस्थ प्लेन दूरी प्राप्त करता है या सेट करता है। |
| [HotSpot](../../aspose.threed.entities/light/hotspot/) { get; set; } | हॉट स्पॉट कोन कोण (डिग्री में) प्राप्त करता है या सेट करता है। |
| [Intensity](../../aspose.threed.entities/light/intensity/) { get; set; } | प्रकाश की तीव्रता प्राप्त करता है या सेट करता है, डिफ़ॉल्ट मान 100 है |
| [LightType](../../aspose.threed.entities/light/lighttype/) { get; set; } | प्रकाश का प्रकार प्राप्त करता है या सेट करता है |
| [LinearAttenuation](../../aspose.threed.entities/light/linearattenuation/) { get; set; } | प्रकाश के कुल क्षीणन की गणना करने के लिए रैखिक क्षीणन प्राप्त करता है या सेट करता है |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | फ्रस्टम की निकट प्लेन दूरी प्राप्त करता है या सेट करता है। |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | ऑर्थोग्राफिक प्रोजेक्शन में फ्रस्टम के लिए ऊँचाई प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [QuadraticAttenuation](../../aspose.threed.entities/light/quadraticattenuation/) { get; set; } | प्रकाश के कुल क्षीणन की गणना करने के लिए द्विघातीय क्षीणन प्राप्त करता है या सेट करता है |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | फ्रस्टम की अभिविन्यास मोड प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब [`Target`](../frustum/target/) null हो। यदि मान FixedTarget है, तो दिशा हमेशा प्रॉपर्टी [`LookAt`](../frustum/lookat/) द्वारा गणना की जाती है। अन्यथा [`LookAt`](../frustum/lookat/) हमेशा [`Direction`](../frustum/direction/) द्वारा गणना की जाती है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [ShadowColor](../../aspose.threed.entities/light/shadowcolor/) { get; set; } | छाया का रंग प्राप्त करता है या सेट करता है। |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | कैमरा जिस लक्ष्य की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। यदि उपयोगकर्ता इस प्रॉपर्टी का समर्थन करता है, तो यह [`LookAt`](../frustum/lookat/) प्रॉपर्टी से पहले होना चाहिए। |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | कैमरा की ऊपर की दिशा प्राप्त करता है या सेट करता है |

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

### देखें भी

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


