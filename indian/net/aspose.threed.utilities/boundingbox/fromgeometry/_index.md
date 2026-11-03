---
title: "BoundingBox.FromGeometry"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "BoundingBox मेथड। दिए गए ज्योमेट्री से बाउंडिंग बॉक्स बनाता है।"
type: docs
weight: 40
url: /hi/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

दिए गए ज्यामिति से बाउंडिंग बॉक्स बनाएं

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ज्यामिति | ज्यामिति | बाउंडिंग बॉक्स की गणना करने के लिए ज्यामिति |

### रिटर्न वैल्यू

दिए गए ज्यामिति का बाउंडिंग बॉक्स

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक ज्यामिति इंस्टेंस से बाउंडिंग बॉक्स बनाया जाए।

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### देखें भी

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


