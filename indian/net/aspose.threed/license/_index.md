---
title: "क्लास License"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.License क्लास। घटक को लाइसेंस करने के लिए मेथड प्रदान करता है।"
type: docs
weight: 1610
url: /hi/net/aspose.threed/license/
---
## License class

कम्पोनेंट को लाइसेंस करने के लिए मेथड्स प्रदान करता है।

```csharp
public class License
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [License](license/)() | इस क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | घटक को लाइसेंस करता है। |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | घटक को लाइसेंस करता है। |

## उदाहरण

इस उदाहरण में, घटक वाली फ़ोल्डर, कॉलिंग असेंबली वाली फ़ोल्डर, एंट्री असेंबली वाली फ़ोल्डर और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्सेज़ में MyLicense.lic नाम की लाइसेंस फ़ाइल खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

घटक जार फ़ाइल:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### देखें भी

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


