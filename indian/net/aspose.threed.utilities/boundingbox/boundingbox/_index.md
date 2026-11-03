---
title: "BoundingBox.BoundingBox"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "BoundingBox कन्स्ट्रक्टर। दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स को प्रारंभ करें"
type: docs
weight: 10
url: /hi/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स प्रारंभ करें

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| minimum | Vector3 | न्यूनतम कोना |
| maximum | Vector3 | अधिकतम कोना |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे न्यूनतम और अधिकतम कोनों से बाउंडिंग बॉक्स बनाया जाए।

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### देखें भी

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स प्रारंभ करें

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| minX | डबल | न्यूनतम कोने का X |
| minY | डबल | न्यूनतम कोने का Y |
| minZ | डबल | न्यूनतम कोने का Z |
| maxX | डबल | अधिकतम कोने का X |
| maxY | डबल | अधिकतम कोने का Y |
| maxZ | डबल | अधिकतम कोने का Z |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे न्यूनतम और अधिकतम कोनों से बाउंडिंग बॉक्स बनाया जाए।

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### देखें भी

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


