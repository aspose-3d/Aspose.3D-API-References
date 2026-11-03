---
title: "Klasse AnimationChannel"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Animation.AnimationChannel Klasse. Ein Kanal ordnet das Komponentenfeld einer Eigenschaft einer Menge von Keyframe‑Sequenzen zu"
type: docs
weight: 20
url: /de/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Ein Kanal ordnet das Komponentenfeld einer Eigenschaft einer Menge von Keyframe‑Sequenzen zu

```csharp
public class AnimationChannel : KeyframeSequence
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Gibt den Property-Bind-Punkt zurück, dem diese Kurve gehört |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype/) { get; } | Ruft den Typ des Komponentenfeldes ab |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue/) { get; set; } | Liest oder setzt den Standardwert des Kanals. Wenn ein Kanal keine verbundenen Keyframe‑Sequenzen hat, wird der Standardwert während der Animationsauswertung verwendet. Ein realistisches Szenario: Die Animation animiert nur die x‑Koordinate eines Knotens, y und z werden nicht geändert, dann wird der Standardwert während der vollständigen Übersetzungsauswertung verwendet. |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Gibt die Keyframes dieser Kurve zurück. |
| [KeyframeSequence](../../aspose.threed.animation/animationchannel/keyframesequence/) { get; set; } | Ruft die zugehörige Keyframe‑Sequenz in diesem Kanal ab |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Gibt das Nachverhalten zurück, das angibt, welchen Wert die Abtastung nach dem letzten Keyframe haben soll. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Gibt das Vorverhalten zurück, das angibt, welchen Wert die Abtastung vor dem ersten Keyframe haben soll. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float) | Erstelle ein neues Keyframe mit angegebenem Wert |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float, Interpolation) | Erstelle ein neues Keyframe mit angegebenem Wert |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Gibt den Enumerator zurück, um alle Keyframes zu durchlaufen. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Entfernt alle Keyframes und setzt das Nach- und Vorverhalten zurück. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [KeyframeSequence](../keyframesequence/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


