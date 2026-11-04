---
title: "Mesh.Triangulate"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo Mesh. Restituisce la mesh triangolata"
type: docs
weight: 120
url: /it/net/aspose.threed.entities/mesh/triangulate/
---
## Mesh.Triangulate method

Restituisci la mesh triangolata

```csharp
public Mesh Triangulate()
```

### Valore di ritorno

Mesh corrente se la mesh corrente è già triangolata, altrimenti verrà calcolata e restituita una nuova mesh triangolata

## Esempi

Il codice seguente mostra come triangolare una mesh:

```csharp
//La mesh del piano ha un solo poligono con 4 punti di controllo
var mesh = (new Plane()).ToMesh();
//Dopo la triangolazione, il rettangolo della nuova mesh diventerà 2 triangoli.
var triangulated = mesh.Triangulate();
```

### Vedi anche

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


