---
title: "क्लास FontFile"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Profiles.FontFile क्लास। फ़ॉन्ट फ़ाइल में ग्लिफ़्स की परिभाषाएँ होती हैं, जिसका उपयोग टेक्स्ट प्रोफ़ाइल बनाने के लिए किया जाता है"
type: docs
weight: 1720
url: /hi/net/aspose.threed.profiles/fontfile/
---
## FontFile class

फ़ॉन्ट फ़ाइल में ग्लिफ़ की परिभाषाएँ होती हैं, इसका उपयोग टेक्स्ट प्रोफ़ाइल बनाने के लिए किया जाता है।

```csharp
public abstract class FontFile : A3DObject
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | नाम को प्राप्त करता है या सेट करता है। |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | फ़ाइल नाम से FontFile लोड करें |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | बाइट्स से FontFile पार्स करें |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | प्रॉपर्टी को खोजता है। यह एक डायनेमिक प्रॉपर्टी हो सकती है (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (इसके नाम द्वारा पहचानी गई) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | एक डायनेमिक प्रॉपर्टी को हटाता है। |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि निर्दिष्ट फ़ॉन्ट फ़ाइल का उपयोग करके पाठ से 3D मेष कैसे बनाया जाए।

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### देखें भी

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


