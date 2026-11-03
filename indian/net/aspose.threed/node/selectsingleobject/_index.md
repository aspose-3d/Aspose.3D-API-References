---
title: "Node.SelectSingleObject"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node मेथड। XPath जैसे क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के तहत एकल ऑब्जेक्ट चुनें।"
type: docs
weight: 240
url: /hi/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

XPath-समरूप क्वेरी सिंटैक्स का उपयोग करके वर्तमान नोड के अंतर्गत एकल ऑब्जेक्ट चुनें।

```csharp
public object SelectSingleObject(string path)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| path | String | XPath जैसे क्वेरी |

### रिटर्न वैल्यू

XPath जैसे क्वेरी द्वारा स्थित ऑब्जेक्ट।

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
//रूट नोड के तहत 'c' नामक नोड के चाइल्ड नोड्स में एकल कैमरा ऑब्जेक्ट चुनें।
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// रूट नोड के तहत 'a1' नामक नोड चुनें, भले ही 'a1' सीधे चाइल्ड नोड न हो।
var obj = s.RootNode.SelectSingleObject("a1");
//नोड स्वयं को चुनें, क्योंकि '/' को सीधे रूट नोड पर चुना गया है, इसलिए रूट नोड चयनित होता है।
obj = s.RootNode.SelectSingleObject("/");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


