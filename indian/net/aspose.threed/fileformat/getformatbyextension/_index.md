---
title: "FileFormat.GetFormatByExtension"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "FileFormat मेथड। फ़ाइल एक्सटेंशन नाम से पसंदीदा फ़ाइल फ़ॉर्मेट प्राप्त करता है। एक्सटेंशन नाम को डॉट से शुरू होना चाहिए।"
type: docs
weight: 470
url: /hi/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

फ़ाइल एक्सटेंशन नाम से पसंदीदा फ़ाइल फ़ॉर्मेट प्राप्त करता है। एक्सटेंशन नाम को डॉट ('.') से शुरू होना चाहिए।

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| extensionName | String | एक्सटेंशन नाम क्वेरी के लिए '.' से शुरू किया गया था। |

### रिटर्न वैल्यू

[`FileFormat`](../) का इंस्टेंस, अन्यथा null लौटाया जाता है।

## उदाहरण

निम्नलिखित कोड दिखाता है कि निर्दिष्ट फ़ॉर्मेट का उपयोग करके सीन को मेमोरी में कैसे सहेजा जाए।

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### देखें भी

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


