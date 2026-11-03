---
title: "BoundingBox.Merge"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode BoundingBox. Fusionner la boîte englobante actuelle avec le point donné"
type: docs
weight: 130
url: /fr/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Fusionner la boîte englobante actuelle avec le point donné

```csharp
public void Merge(Vector4 pt)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pt | Vector4 | Le point à fusionner dans la boîte englobante |

## Exemples

Le code suivant montre comment fusionner un point à la boîte englobante.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Voir aussi

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Fusionner la boîte englobante actuelle avec le point donné

```csharp
public void Merge(Vector3 pt)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pt | Vector3 | Le point à fusionner dans la boîte englobante |

## Exemples

Le code suivant montre comment fusionner un point à la boîte englobante.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Voir aussi

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Fusionner la boîte englobante actuelle avec le point donné

```csharp
public void Merge(double x, double y, double z)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Double | Le point à fusionner dans la boîte englobante |
| y | Double | Le point à fusionner dans la boîte englobante |
| z | Double | Le point à fusionner dans la boîte englobante |

## Exemples

Le code suivant montre comment fusionner un point à la boîte englobante.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Voir aussi

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Fusionne la nouvelle boîte dans la boîte englobante actuelle.

```csharp
public void Merge(BoundingBox bb)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bb | BoundingBox | La boîte englobante à fusionner |

### Voir aussi

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


