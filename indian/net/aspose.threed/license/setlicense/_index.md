---
title: "License.SetLicense"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "License मेथड. घटक को लाइसेंस देता है"
type: docs
weight: 20
url: /hi/net/aspose.threed/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

घटक को लाइसेंस करता है।

```csharp
public void SetLicense(string licenseName)
```

## टिप्पणियाँ

लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. वह फ़ोल्डर जिसमें Aspose घटक असेंबली शामिल है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग असेंबली शामिल है।

4. वह फ़ोल्डर जिसमें एंट्री (स्टार्टअप) असेंबली शामिल है।

5. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

2. वह फ़ोल्डर जिसमें Aspose घटक JAR फ़ाइल शामिल है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग JAR फ़ाइल शामिल है।

## उदाहरण

इस उदाहरण में, घटक वाली फ़ोल्डर, कॉलिंग असेंबली वाली फ़ोल्डर, एंट्री असेंबली वाली फ़ोल्डर और फिर कॉलिंग असेंबली के एम्बेडेड रिसोर्सेज़ में MyLicense.lic नाम की लाइसेंस फ़ाइल खोजने का प्रयास किया जाएगा।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

घटक जार फ़ाइल:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

पूरा या छोटा फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें।

### देखें भी

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)

---

## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस करता है।

```csharp
public void SetLicense(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

## टिप्पणियाँ

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।

## उदाहरण

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)

License license = new License();
license.setLicense(myStream);
```

### देखें भी

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


