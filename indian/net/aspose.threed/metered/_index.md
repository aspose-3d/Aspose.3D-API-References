---
title: "क्लास Metered"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Metered क्लास। मीटर की सेट करने के लिए मेथड्स प्रदान करती है।"
type: docs
weight: 1620
url: /hi/net/aspose.threed/metered/
---
## Metered class

मीटर की कुंजी सेट करने के लिए मेथड्स प्रदान करता है।

```csharp
public class Metered
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Metered](metered/)() | इस क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey/)(string, string) | मीटर सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटर लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफलता होती है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट कर दिया जाएगा; ऐसे मामले से बचने के लिए, आपको नियमित रूप से लाइसेंस स्थिति जांचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें। |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit/)() | उपभोग क्रेडिट प्राप्त करता है |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity/)() | उपभोग फ़ाइल आकार प्राप्त करता है |

## उदाहरण

इस उदाहरण में, मीटर किए गए सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

घटक जार फ़ाइल:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### देखें भी

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


