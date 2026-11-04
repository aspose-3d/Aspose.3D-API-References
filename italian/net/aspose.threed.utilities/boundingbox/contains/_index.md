---
title: "BoundingBox.Contains"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo BoundingBox. Verifica se il punto p è all'interno del BoundingBox"
type: docs
weight: 100
url: /it/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Verifica se il punto p è all'interno del BoundingBox

```csharp
public bool Contains(Vector3 p)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | Vector3 | Il punto da testare |

### Valore di ritorno

True se il punto è all'interno del BoundingBox

## Esempi

Il codice seguente mostra come verificare se un punto è all'interno del BoundingBox.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Vedi anche

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Il BoundingBox da verificare se è all'interno del BoundingBox corrente.

```csharp
public bool Contains(BoundingBox bbox)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Vedi anche

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


