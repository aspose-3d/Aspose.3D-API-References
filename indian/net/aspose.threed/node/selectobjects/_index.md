---
title: "Node.SelectObjects"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node method. वर्तमान नोड के तहत XPath जैसे क्वेरी सिंटैक्स का उपयोग करके कई वस्तुओं का चयन करता है।"
type: docs
weight: 230
url: /hi/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

XPath-समरूप क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के अंतर्गत कई ऑब्जेक्ट चुनें।

```csharp
public List<object> SelectObjects(string path)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | String | XPath जैसे क्वेरी |

### रिटर्न वैल्यू

कई वस्तुएँ XPath- जैसे क्वेरी से मेल खाती हैं।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | यदि पाथ में खराब क्वेरी है तो ParseException फेंका जाएगा। |

## उदाहरण

XPath जैसे अभिव्यक्ति का उपयोग करके एकल नोड चुनें।

```csharp
//परीक्षण के लिए एक सीन बनाएं।
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//ऐसी वस्तुओं का चयन करें जिनका प्रकार Camera हो या नाम 'light' हो, चाहे वे कहीं भी स्थित हों।
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


