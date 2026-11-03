---
title: "BoundingBox.OverlapsWith"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "BoundingBox method. जाँचें कि वर्तमान बाउंडिंग बॉक्स निर्दिष्ट बाउंडिंग बॉक्स के साथ ओवरलैप करता है या नहीं"
type: docs
weight: 140
url: /hi/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

जाँचें कि वर्तमान बाउंडिंग बॉक्स निर्दिष्ट बाउंडिंग बॉक्स के साथ ओवरलैप करता है या नहीं।

```csharp
public bool OverlapsWith(BoundingBox box)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| बॉक्स | BoundingBox | परीक्षण के लिए अन्य बाउंडिंग बॉक्स |

### रिटर्न वैल्यू

यदि वर्तमान बाउंडिंग बॉक्स दिए गए बॉक्स के साथ ओवरलैप करता है तो सत्य।

## उदाहरण

निम्नलिखित कोड दिखाता है कि दो बाउंडिंग बॉक्स एक-दूसरे के साथ कैसे ओवरलैप करते हैं।

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### देखें भी

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


