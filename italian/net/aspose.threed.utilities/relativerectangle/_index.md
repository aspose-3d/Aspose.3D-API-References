---
title: RelativeRectangle
second_title: Riferimento API Aspose.3D per .NET
description: Rettangolo relativo La formula tra il componente relativo e il valore assoluto è Scala  larghezza di riferimento  offset Quindi se vogliamo che rappresenti un valore assoluto lascia tutti i campi della scala zero e usa invece i campi offset.
type: docs
weight: 2600
url: /it/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Rettangolo relativo La formula tra il componente relativo e il valore assoluto è: Scala * (larghezza di riferimento) + offset Quindi, se vogliamo che rappresenti un valore assoluto, lascia tutti i campi della scala zero e usa invece i campi offset.

```csharp
public struct RelativeRectangle
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight) { get; set; } | Ottiene o imposta l'offset per height |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth) { get; set; } | Ottiene o imposta l'offset per width |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx) { get; set; } | Ottiene o imposta l'offset per la coordinata X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety) { get; set; } | Ottiene o imposta l'offset per la coordinata Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight) { get; set; } | Altezza relativa |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth) { get; set; } | Larghezza relativa |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex) { get; set; } | Coordinata relativa X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley) { get; set; } | Coordinata relativa Y |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale)(float, float, float, float) | Costruisci a[`RelativeRectangle`](../relativerectangle) con tutti i campi di offset zero e scala campi da parametri dati. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute#toabsolute)(Rectangle) | Converti il rettangolo relativo in rettangolo assoluto |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute#toabsolute_1)(Size) | Converti il rettangolo relativo in rettangolo assoluto |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring)() | Converte il valore di questa istanza in aString. |

### Guarda anche

* spazio dei nomi [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assemblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
