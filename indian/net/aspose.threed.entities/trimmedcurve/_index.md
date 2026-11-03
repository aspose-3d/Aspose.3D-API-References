---
title: "क्लास TrimmedCurve"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Entities.TrimmedCurve क्लास। एक सीमित वक्र जो दोनों सिरों पर बेसिस कर्व को ट्रिम करता है।"
type: docs
weight: 810
url: /hi/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

एक सीमित वक्र जो दोनों सिरों पर आधार वक्र को ट्रिम करता है।

```csharp
public class TrimmedCurve : Curve
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TrimmedCurve](trimmedcurve/)() | `TrimmedCurve` का कंस्ट्रक्टर |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve/) { get; set; } | ट्रिम किया जाने वाला बेसिस कर्व। |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | लाइन का रंग प्राप्त या सेट करता है, डिफ़ॉल्ट मान सफेद (1, 1, 1) है। |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | निर्यात के दौरान इस एंटिटी को बाहर रखने के लिए प्राप्त करता है या सेट करता है। |
| [First](../../aspose.threed.entities/trimmedcurve/first/) { get; set; } | ट्रिम करने के लिए पहला अंत बिंदु, यह एक कार्टेशियन बिंदु या वास्तविक पैरामीटर हो सकता है। |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | पहला पैरेंट नोड प्राप्त करता है या सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी को जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection/) { get; set; } | प्राप्त करता या सेट करता है कि क्या ट्रिम्ड परिणाम बेसिस कर्व की वही दिशा उपयोग करता है। |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [Second](../../aspose.threed.entities/trimmedcurve/second/) { get; set; } | ट्रिम करने के लिए दूसरा अंत बिंदु, यह एक कार्टेशियन बिंदु या वास्तविक पैरामीटर हो सकता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

### देखें भी

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


