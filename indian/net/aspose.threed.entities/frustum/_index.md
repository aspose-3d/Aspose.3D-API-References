---
title: Frustum
second_title: .NET API संदर्भ के लिए Aspose.3D
description: क आधर वर्गCamera./camera/ औरLight./light/
type: docs
weight: 350
url: /hi/net/aspose.threed.entities/frustum/
---
## Frustum class

का आधार वर्ग[`Camera`](../camera/) और[`Light`](../light/)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | frustum का पक्षानुपात प्राप्त या सेट करता है |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | उस दिशा को प्राप्त या सेट करता है जिसे कैमरा देख रहा है। इस संपत्ति में परिवर्तन भी प्रभावित करेगा[`LookAt`](./lookat/) और[`Target`](./target/) . |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | हो जाता है या सेट करता है कि निर्यात के दौरान इस इकाई को बाहर करना है या नहीं। |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | छिन्नक के दूर तल की दूरी प्राप्त या सेट करता है। |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | कैमरे द्वारा देखी जा रही रुचि की स्थिति को प्राप्त या सेट करता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम प्राप्त या सेट करता है। |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | छिन्नक के निकट समतल दूरी को प्राप्त या सेट करता है। |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | ऑर्थोग्राफिक प्रोजेक्शन में फ्रस्टम होने पर ऊंचाई प्राप्त या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहले पैरेंट नोड को प्राप्त या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, ज्यामिति इंस्टेंसिंग के लिए एक इकाई को कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी संपत्तियों का संग्रह प्राप्त करता है। |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | छिन्नक के ओरिएंटेशन मोड को प्राप्त या सेट करता है यह गुण तभी काम करता है जब[`Target`](./target/) शून्य है। यदि मान हैFixedTarget , दिशा की गणना हमेशा गुण द्वारा की जाती है[`LookAt`](./lookat/) अन्यथा[`LookAt`](./lookat/)द्वारा हमेशा गणना की जाती है[`Direction`](./direction/) |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | दृश्य प्राप्त करता है कि यह वस्तु से संबंधित है |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | उस लक्ष्य को प्राप्त या सेट करता है जिसे कैमरा देख रहा है। यदि उपयोगकर्ता इस संपत्ति का समर्थन करता है, तो यह पहले होना चाहिए[`LookAt`](./lookat/) संपत्ति. |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | कैमरे की दिशा प्राप्त करता है या सेट करता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | संपत्ति ढूँढता है। यह एक गतिशील संपत्ति हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल संपत्ति (इसके नाम से पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | अपने ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में वर्तमान इकाई का बाउंडिंग बॉक्स प्राप्त करता है। |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट संपत्ति का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक गतिशील संपत्ति को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट संपत्ति को हटाएं |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट संपत्ति का मान सेट करता है |

### यह सभी देखें

* class [Entity](../../aspose.threed/entity/)
* interface [IOrientable](../iorientable/)
* नाम स्थान [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* सभा [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
