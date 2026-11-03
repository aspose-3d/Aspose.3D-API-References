---
title: "BoundingBox.Contains"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "BoundingBox method. जाँचें कि बिंदु p बाउंडिंग बॉक्स के भीतर है या नहीं"
type: docs
weight: 100
url: /hi/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

जाँचें कि बिंदु p बाउंडिंग बॉक्स के भीतर है या नहीं

```csharp
public bool Contains(Vector3 p)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| p | Vector3 | परीक्षण के लिए बिंदु |

### रिटर्न वैल्यू

यदि बिंदु बाउंडिंग बॉक्स के भीतर है तो सत्य

## उदाहरण

निम्नलिखित कोड दिखाता है कि बिंदु बाउंडिंग बॉक्स के भीतर है या नहीं।

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### देखें भी

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

वर्तमान बाउंडिंग बॉक्स के भीतर है या नहीं, यह जांचने के लिए बाउंडिंग बॉक्स।

```csharp
public bool Contains(BoundingBox bbox)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bbox | BoundingBox |  |

### देखें भी

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


