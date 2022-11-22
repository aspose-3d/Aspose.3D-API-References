---
title: AnimationNode
second_title: Aspose.3D für .NET-API-Referenz
description: Aspose.3D unterstützt die Animationshierarchie jede Animation kann aus mehreren Animationen und der KeyframeDefinition der Animation bestehen. AnimationNode./animationnode definiert die Transformation eines Eigenschaftswerts im Laufe der Zeit z. B. kann ein Animationsknoten verwendet werden um die Transformation eines Knotens oder anderes zu steuernA3DObject../aspose.threed/a3dobject Numerische Eigenschaften des Objekts.
type: docs
weight: 40
url: /de/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D unterstützt die Animationshierarchie, jede Animation kann aus mehreren Animationen und der Keyframe-Definition der Animation bestehen. [`AnimationNode`](../animationnode) definiert die Transformation eines Eigenschaftswerts im Laufe der Zeit, z. B. kann ein Animationsknoten verwendet werden, um die Transformation eines Knotens oder anderes zu steuern[`A3DObject`](../../aspose.threed/a3dobject) Numerische Eigenschaften des Objekts.

```csharp
public class AnimationNode : A3DObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [AnimationNode](animationnode#constructor)() | Initialisiert eine neue Instanz von[`AnimationNode`](../animationnode) Klasse. |
| [AnimationNode](animationnode#constructor_1)(string) | Initialisiert eine neue Instanz von[`AnimationNode`](../animationnode) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints) { get; } | Ruft die aktuellen Eigenschaftsbindungspunkte ab |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations) { get; } | Ruft die Unteranimationsknoten unter aktuellen Animationen ab |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint)(A3DObject, string) | Erstellt einen BindPoint basierend auf dem Eigenschaftsdatentyp. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint)(string) | Findet den Bindungspunkt anhand des Namens. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint)(A3DObject, string, bool) | Ruft den Bindungspunkt der Animation für die angegebene Eigenschaft ab. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence#getkeyframesequence)(A3DObject, string, bool) | Ruft die Keyframe-Sequenz für die angegebene Eigenschaft ab. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence#getkeyframesequence_1)(A3DObject, string, string, bool) | Ruft die Keyframe-Sequenz für die angegebene Eigenschaft und den angegebenen Kanal ab. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject)
* namensraum [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->