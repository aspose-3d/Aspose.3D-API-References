---
title: "Klasse AnimationNode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Animation.AnimationNode Klasse. Aspose.3D unterstützt eine Animationshierarchie, wobei jede Animation aus mehreren Animationen und einer Schlüsselbilddefinition bestehen kann. AnimationNode definiert die Transformation eines Eigenschaftswerts über die Zeit, zum Beispiel kann ein Animationsknoten verwendet werden, um die Transformation eines Knotens oder andere numerische Eigenschaften von A3DObject-Objekten zu steuern."
type: docs
weight: 40
url: /de/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D unterstützt eine Animationshierarchie, wobei jede Animation aus mehreren Animationen und einer Schlüsselbilddefinition bestehen kann. `AnimationNode` definiert die Transformation eines Eigenschaftswerts über die Zeit, zum Beispiel kann ein Animationsknoten verwendet werden, um die Transformation eines Knotens oder andere numerische Eigenschaften des [`A3DObject`](../../aspose.threed/a3dobject/) Objekts zu steuern.

```csharp
public class AnimationNode : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | Initialisiert eine neue Instanz der `AnimationNode` Klasse. |
| [AnimationNode](animationnode/#constructor_1)(string) | Initialisiert eine neue Instanz der `AnimationNode` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | Ermittelt die aktuellen Property-Bind-Punkte. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | Ermittelt die Unteranimationsknoten unter den aktuellen Animationen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | Erstellt einen BindPoint basierend auf dem Datentyp der Property. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | Findet den BindPoint nach Ziel und Name. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | Ermittelt den Animations-BindPoint für die angegebene Property. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | Ermittelt die Schlüsselbildsequenz für die angegebene Property. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | Ermittelt die Schlüsselbildsequenz für die angegebene Property und den Kanal. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


