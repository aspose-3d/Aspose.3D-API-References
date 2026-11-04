---
title: "Classe Group"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Aspose.ThreeD.Group class. Un Group rappresenta le relazioni logiche di Node"
type: docs
weight: 1570
url: /it/net/aspose.threed/group/
---
## Group class

Un `Group` rappresenta le relazioni logiche di [`Node`](../node/).

```csharp
public class Group : A3DObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Group](group/)(string) | Costruisci una nuova istanza di `Group` |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Sottogruppi |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Ottiene o imposta il nome. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | I nodi in questo gruppo |
| [Parent](../../aspose.threed/group/parent/) { get; } | Gruppo genitore del gruppo corrente |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Ottiene la collezione di tutte le proprietà. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal suo nome) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Ottieni il valore della proprietà specificata |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Rimuove una proprietà dinamica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Rimuove la proprietà specificata identificata per nome |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Imposta il valore della proprietà specificata |
| override [ToString](../../aspose.threed/group/tostring/)() | Restituisce la rappresentazione stringa di `Group` |

### Vedi anche

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


