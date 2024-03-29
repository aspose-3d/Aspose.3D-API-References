---
title: AnimationChannel
second_title: Riferimento API Aspose.3D per .NET
description: Un canale mappa il campo del componente della proprietà su un insieme di sequenze di fotogrammi chiave
type: docs
weight: 20
url: /it/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Un canale mappa il campo del componente della proprietà su un insieme di sequenze di fotogrammi chiave

```csharp
public class AnimationChannel : IEnumerable<KeyframeSequence>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype) { get; } | Ottiene il tipo del campo del componente |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue) { get; set; } | Ottiene o imposta il valore Default del canale. Se un canale non ha sequenze di fotogrammi chiave collegate, il valore predefinito verrà utilizzato durante la valutazione dell'animazione. Uno scenario reale: l'animazione anima solo la coordinata x di un nodo, la y e la z sono non modificato, il valore predefinito verrà utilizzato durante la valutazione completa della traduzione. |
| [KeyframeSequences](../../aspose.threed.animation/animationchannel/keyframesequences) { get; } | Ottiene tutte le sequenze di fotogrammi chiave all'interno di questo canale |
| [Name](../../aspose.threed.animation/animationchannel/name) { get; } | Ottiene il nome del canale |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddKeyframeSequence](../../aspose.threed.animation/animationchannel/addkeyframesequence)(KeyframeSequence) | Aggiunge la sequenza di fotogrammi chiave a questo canale |
| [GetEnumerator](../../aspose.threed.animation/animationchannel/getenumerator)() | Ottiene un enumeratore per scorrere tutte le sequenze di fotogrammi chiave all'interno di questo canale |

### Guarda anche

* class [KeyframeSequence](../keyframesequence)
* spazio dei nomi [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* assemblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
