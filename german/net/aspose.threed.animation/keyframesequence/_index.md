---
title: "Klasse KeyframeSequence"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Animation.KeyframeSequence Klasse. Die Sequenz von Keyframes beschreibt die Transformation eines abgetasteten Wertes über die Zeit"
type: docs
weight: 100
url: /de/net/aspose.threed.animation/keyframesequence/
---
## KeyframeSequence class

Die Sequenz von Keyframes beschreibt die Transformation eines abgetasteten Wertes über die Zeit.

```csharp
public class KeyframeSequence : A3DObject, IEnumerable<KeyFrame>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [KeyframeSequence](keyframesequence/#constructor)() | Initialisiert eine neue Instanz der `KeyframeSequence` Klasse. |
| [KeyframeSequence](keyframesequence/#constructor_1)(string) | Initialisiert eine neue Instanz der `KeyframeSequence` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Gibt den Property-Bind-Punkt zurück, dem diese Kurve gehört |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Gibt die Keyframes dieser Kurve zurück. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Gibt das Nachverhalten zurück, das angibt, welchen Wert die Abtastung nach dem letzten Keyframe haben soll. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Gibt das Vorverhalten zurück, das angibt, welchen Wert die Abtastung vor dem ersten Keyframe haben soll. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add)(double, float) | Erstelle ein neues Keyframe mit angegebenem Wert |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add_1)(double, float, Interpolation) | Erstelle ein neues Keyframe mit angegebenem Wert |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Gibt den Enumerator zurück, um alle Keyframes zu durchlaufen. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Entfernt alle Keyframes und setzt das Nach- und Vorverhalten zurück. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [KeyFrame](../keyframe/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


