---
title: "Mesh.op_BitwiseOr"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo Mesh. Calcola l'unione di due mesh"
type: docs
weight: 140
url: /it/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Calcola l'unione di due mesh

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | Mesh | Primo mesh |
| b | Mesh | Secondo mesh |

### Valore di ritorno

Mesh risultato

## Esempi

Il codice seguente mostra come unire due mesh in un unico mesh:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Vedi anche

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


