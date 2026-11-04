---
title: "BoundingBox.OverlapsWith"
second_title: "Riferimento API Aspose.3D per .NET"
description: "BoundingBox metodo. Verifica se il riquadro corrente si sovrappone al riquadro specificato"
type: docs
weight: 140
url: /it/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Verifica se il riquadro corrente si sovrappone al riquadro specificato.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scatola | BoundingBox | L'altro BoundingBox da testare |

### Valore di ritorno

True se il BoundingBox corrente si sovrappone a quello fornito.

## Esempi

Il codice seguente mostra come verificare se due BoundingBox si sovrappongono tra loro.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Vedi anche

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


