---
title: "Klasse KeyFrame"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Animation.KeyFrame Klasse. Ein Keyframe wird hauptsächlich durch eine Zeit und einen Wert definiert; für einige Interpolationstypen werden Tangente/Spannung/Bias/Kontinuität ebenfalls zur Berechnung des endgültigen abgetasteten Wertes verwendet. Abgetastete Werte an einer Zeitposition ohne Keyframe werden durch Keyframes zwischen dem vorherigen und dem nächsten Keyframe interpoliert. Werte vor/nach dem ersten/letzten Keyframe werden von der Extrapolation Klasse berechnet."
type: docs
weight: 90
url: /de/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

Ein Keyframe wird hauptsächlich durch eine Zeit und einen Wert definiert; für einige Interpolationstypen werden Tangente/Spannung/Bias/Kontinuität ebenfalls zur Berechnung des endgültigen abgetasteten Wertes verwendet. Abgetastete Werte an einer Zeitposition ohne Keyframe werden durch Keyframes zwischen dem vorherigen und dem nächsten Keyframe interpoliert. Werte vor/nach dem ersten/letzten Keyframe werden von der [`Extrapolation`](../extrapolation/) Klasse berechnet.

```csharp
public class KeyFrame
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | Erstelle ein neues Keyframe auf der angegebenen Kurve |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | Liest oder setzt den Bias, der im TCB-Spline verwendet wird |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | Liest oder setzt die Kontinuität, die im TCB spline verwendet wird |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | Liest oder setzt, ob das Schlüsselbild flach ist. Das Schlüsselbild sollte flach sein, wenn das nächste oder vorherige Schlüsselbild denselben Wert hat. Ein flaches Schlüsselbild hat flache Tangenten und feste Interpolation. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | Liest oder setzt, ob die Ausgangs‑ und nächsten Eingabetangenten unabhängig sind. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | Liest oder setzt den Interpolationstyp des Schlüssels, list.data[index] definiert den Algorithmus, wie der abgetastete Wert berechnet wird. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | Liest oder setzt die nächste Eingabetangente (links) dieses Schlüsselbildes. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | Liest oder setzt das nächste Eingabegewicht (links) dieses Schlüsselbildes. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | Liest oder setzt die Ausgangstangente (rechts) dieses Schlüsselbildes. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | Liest oder setzt das Ausgangsgewicht (rechts) dieses Schlüsselbildes. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | Liest oder setzt den Schrittmodus des Schlüssels. Wenn der Interpolationstyp Konstant ist, entscheidet list.data[index], welcher Schlüsselbildwert während der Interpolation verwendet wird. Ein PreviousValue bedeutet, dass der Wert des linken Schlüsselbildes verwendet wird. Ein NextValue bedeutet, dass der Wert des nächsten rechten Schlüsselbildes verwendet wird. |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | Liest oder setzt den Tangenten‑Gewichtsmodus des Schlüssels. Die Ausgangstangente oder die nächste Eingabetangente kann durch Auswahl des richtigen [`WeightedMode`](../weightedmode/) angepasst werden. |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | Liest oder setzt die Spannung, die im TCB spline verwendet wird. |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | Liest oder setzt die Zeitposition des Schlüsselbildes list.data[index], gemessen in Sekunden. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | Liest oder setzt, dass die Tangente zeitunabhängig ist. |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | Liest oder setzt den Wert des Schlüsselbildes. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | Liest die Zeichenkettenrepräsentation des Schlüsselbildes. |

### Siehe auch

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


