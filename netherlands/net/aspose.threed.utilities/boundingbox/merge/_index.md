---
title: "BoundingBox.Merge"
second_title: "Aspose.3D voor .NET API-referentie"
description: "BoundingBox-methode. Voeg het huidige begrenzingsvak samen met het opgegeven punt"
type: docs
weight: 130
url: /nl/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Voeg het huidige begrenzingsvak samen met het opgegeven punt

```csharp
public void Merge(Vector4 pt)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | Vector4 | Het punt dat in het begrenzingsvak moet worden samengevoegd |

## Voorbeelden

De volgende code laat zien hoe je een punt samenvoegt met een begrenzingsvak.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Zie ook

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Voeg het huidige begrenzingsvak samen met het opgegeven punt

```csharp
public void Merge(Vector3 pt)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | Vector3 | Het punt dat in het begrenzingsvak moet worden samengevoegd |

## Voorbeelden

De volgende code laat zien hoe je een punt samenvoegt met een begrenzingsvak.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Zie ook

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Voeg het huidige begrenzingsvak samen met het opgegeven punt

```csharp
public void Merge(double x, double y, double z)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | Double | Het punt dat in het begrenzingsvak moet worden samengevoegd |
| y | Double | Het punt dat in het begrenzingsvak moet worden samengevoegd |
| z | Double | Het punt dat in het begrenzingsvak moet worden samengevoegd |

## Voorbeelden

De volgende code laat zien hoe je een punt samenvoegt met een begrenzingsvak.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Zie ook

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Voegt het nieuwe vak samen met het huidige begrenzingsvak.

```csharp
public void Merge(BoundingBox bb)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bb | BoundingBox | Het begrenzingsvak om samen te voegen |

### Zie ook

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


