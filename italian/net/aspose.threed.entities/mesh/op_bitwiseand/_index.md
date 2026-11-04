---
title: "Mesh.op_BitwiseAnd"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo Mesh. Calcola l'intersezione tra due mesh"
type: docs
weight: 130
url: /it/net/aspose.threed.entities/mesh/op_bitwiseand/
---
## Mesh BitwiseAnd operator

Calcola l'intersezione tra due mesh

```csharp
public static Mesh operator &(Mesh a, Mesh b)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | Mesh | Primo mesh |
| b | Mesh | Secondo mesh |

### Valore di ritorno

Mesh risultato

## Esempi

Il codice seguente mostra come calcolare la differenza tra due mesh:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 & box2;
```

### Vedi anche

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


