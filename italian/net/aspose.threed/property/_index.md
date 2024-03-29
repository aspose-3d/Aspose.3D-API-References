---
title: Property
second_title: Riferimento API Aspose.3D per .NET
description: Classe per contenere le proprietà definite dallutente.
type: docs
weight: 1670
url: /it/net/aspose.threed/property/
---
## Property class

Classe per contenere le proprietà definite dall'utente.

```csharp
public abstract class Property : A3DObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Name](../../aspose.threed/property/name) { set; } |  |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ottiene la raccolta di tutte le proprietà. |
| abstract [Value](../../aspose.threed/property/value) { get; set; } | Ottiene o imposta il valore. |
| abstract [ValueType](../../aspose.threed/property/valuetype) { get; } | Ottiene il tipo del valore della proprietà. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal nome) |
| [GetBindPoint](../../aspose.threed/property/getbindpoint)(AnimationNode, bool) | Ottiene il punto di collegamento della proprietà sull'istanza di animazione specificata. |
| [GetKeyframeSequence](../../aspose.threed/property/getkeyframesequence)(AnimationNode, bool) | Ottiene la sequenza di fotogrammi chiave sull'istanza di animazione specificata. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Ottieni il valore della proprietà specificata |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Rimuove una proprietà dinamica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Rimuove la proprietà specificata identificata da nome |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Imposta il valore della proprietà specificata |
| override [ToString](../../aspose.threed/property/tostring)() | Restituisce una stringa che rappresenta la corrente[`Property`](../property) . |

### Guarda anche

* class [A3DObject](../a3dobject)
* spazio dei nomi [Aspose.ThreeD](../../aspose.threed)
* assemblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
