---
title: "क्लास Camera"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.Camera क्लास। कैमरा दृश्य को देख रहे दर्शक के नेत्र बिंदु का वर्णन करता है।"
type: docs
weight: 300
url: /hi/net/aspose.threed.entities/camera/
---
## Camera class

कैमरा दृश्य को देख रहे दर्शक के आँख बिंदु का वर्णन करता है।

```csharp
public class Camera : Frustum
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Camera](camera/#constructor)() | `Camera` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Camera](camera/#constructor_1)(ProjectionType) | `Camera` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Camera](camera/#constructor_2)(string) | `Camera` क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [Camera](camera/#constructor_3)(string, ProjectionType) | `Camera` क्लास का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ApertureMode](../../aspose.threed.entities/camera/aperturemode/) { get; set; } | कैमरा के एपर्चर मोड को प्राप्त करता है या सेट करता है। |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | फ्रस्टम का आस्पेक्ट रेशियो प्राप्त करता है या सेट करता है। |
| [AspectRatio](../../aspose.threed.entities/camera/aspectratio/) { get; set; } | व्यू प्लेन के आस्पेक्ट रेशियो को प्राप्त करता है या सेट करता है। |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | कैमरा जिस दिशा की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। इस प्रॉपर्टी में बदलाव [`LookAt`](../frustum/lookat/) और [`Target`](../frustum/target/) को भी प्रभावित करेंगे। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | फ्रस्टम की दूरस्थ प्लेन दूरी प्राप्त करता है या सेट करता है। |
| [FieldOfView](../../aspose.threed.entities/camera/fieldofview/) { get; set; } | कैमरा के फील्ड ऑफ़ व्यू को डिग्री में प्राप्त करता है या सेट करता है, यह प्रॉपर्टी केवल तब उपयोग होती है जब ApertureMode क्षैतिज या लंबवत हो। |
| [FieldOfViewX](../../aspose.threed.entities/camera/fieldofviewx/) { get; set; } | कैमरा के क्षैतिज फील्ड ऑफ़ व्यू को डिग्री में प्राप्त करता है या सेट करता है, यह प्रॉपर्टी केवल तब उपयोग होती है जब ApertureMode HorizAndVert हो। |
| [FieldOfViewY](../../aspose.threed.entities/camera/fieldofviewy/) { get; set; } | कैमरा के लंबवत फील्ड ऑफ़ व्यू को डिग्री में प्राप्त करता है या सेट करता है, यह प्रॉपर्टी केवल तब उपयोग होती है जब ApertureMode HorizAndVert हो। |
| [Height](../../aspose.threed.entities/camera/height/) { get; set; } | व्यू प्लेन की ऊँचाई को इंच में मापकर प्राप्त करता है या सेट करता है। |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। |
| [Magnification](../../aspose.threed.entities/camera/magnification/) { get; set; } | ऑर्थोग्राफिक कैमरा में उपयोग किए जाने वाले मैग्नीफ़िकेशन को प्राप्त करता है या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | फ्रस्टम की निकट प्लेन दूरी प्राप्त करता है या सेट करता है। |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | ऑर्थोग्राफिक प्रोजेक्शन में फ्रस्टम के लिए ऊँचाई प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [ProjectionType](../../aspose.threed.entities/camera/projectiontype/) { get; set; } | कैमरा के प्रोजेक्शन प्रकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से पर्स्पेक्टिव प्रोजेक्शन उपयोग किया जाता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | फ्रस्टम की अभिविन्यास मोड प्राप्त करता है या सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब [`Target`](../frustum/target/) null हो। यदि मान FixedTarget है, तो दिशा हमेशा प्रॉपर्टी [`LookAt`](../frustum/lookat/) द्वारा गणना की जाती है। अन्यथा [`LookAt`](../frustum/lookat/) हमेशा [`Direction`](../frustum/direction/) द्वारा गणना की जाती है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | कैमरा जिस लक्ष्य की ओर देख रहा है, उसे प्राप्त करता है या सेट करता है। यदि उपयोगकर्ता इस प्रॉपर्टी का समर्थन करता है, तो यह [`LookAt`](../frustum/lookat/) प्रॉपर्टी से पहले होना चाहिए। |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | कैमरा की ऊपर की दिशा प्राप्त करता है या सेट करता है |
| [Width](../../aspose.threed.entities/camera/width/) { get; set; } | व्यू प्लेन की चौड़ाई को इंच में मापकर प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [MoveForward](../../aspose.threed.entities/camera/moveforward/)(double) | कैमरा को उसकी दिशा या लक्ष्य की ओर आगे की ओर ले जाएँ। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


