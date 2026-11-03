---
title: "BoundingBox.Merge"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "BoundingBox मेथड। वर्तमान बाउंडिंग बॉक्स को दिए गए बिंदु के साथ मिलाएँ"
type: docs
weight: 130
url: /hi/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

वर्तमान बाउंडिंग बॉक्स को दिए गए बिंदु के साथ मिलाएँ

```csharp
public void Merge(Vector4 pt)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pt | Vector4 | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु |

## उदाहरण

निम्नलिखित कोड दिखाता है कि बिंदु को बाउंडिंग बॉक्स में कैसे मिलाया जाए।

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### देखें भी

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

वर्तमान बाउंडिंग बॉक्स को दिए गए बिंदु के साथ मिलाएँ

```csharp
public void Merge(Vector3 pt)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pt | Vector3 | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु |

## उदाहरण

निम्नलिखित कोड दिखाता है कि बिंदु को बाउंडिंग बॉक्स में कैसे मिलाया जाए।

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### देखें भी

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

वर्तमान बाउंडिंग बॉक्स को दिए गए बिंदु के साथ मिलाएँ

```csharp
public void Merge(double x, double y, double z)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | डबल | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु |
| y | डबल | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु |
| z | डबल | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु |

## उदाहरण

निम्नलिखित कोड दिखाता है कि बिंदु को बाउंडिंग बॉक्स में कैसे मिलाया जाए।

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### देखें भी

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है।

```csharp
public void Merge(BoundingBox bb)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| bb | BoundingBox | मर्ज करने के लिए बाउंडिंग बॉक्स |

### देखें भी

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


