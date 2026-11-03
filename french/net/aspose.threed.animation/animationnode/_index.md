---
title: "Classe AnimationNode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Animation.AnimationNode. Aspose.3Ds prend en charge la hiérarchie d'animation ; chaque animation peut être composée de plusieurs animations et de la définition des images clés d'animation. AnimationNode définit la transformation d'une valeur de propriété au fil du temps, par exemple le nœud d'animation peut être utilisé pour contrôler la transformation d'un nœud ou d'autres propriétés numériques d'objets A3DObject."
type: docs
weight: 40
url: /fr/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D prend en charge la hiérarchie d'animation, chaque animation pouvant être composée de plusieurs animations et de la définition des images clés d'animation. `AnimationNode` définit la transformation d'une valeur de propriété au fil du temps, par exemple, le nœud d'animation peut être utilisé pour contrôler la transformation d'un nœud ou d'autres propriétés numériques d'objets [`A3DObject`](../../aspose.threed/a3dobject/).

```csharp
public class AnimationNode : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | Initialise une nouvelle instance de la classe `AnimationNode`. |
| [AnimationNode](animationnode/#constructor_1)(string) | Initialise une nouvelle instance de la classe `AnimationNode`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | Obtient les points de liaison de propriété actuels |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | Obtient les nœuds de sous-animation sous les animations actuelles |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | Crée un BindPoint basé sur le type de données de la propriété. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | Trouve le point de liaison par cible et nom. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | Obtient le point de liaison d'animation sur la propriété donnée. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | Obtient la séquence d'images clés sur la propriété donnée. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | Obtient la séquence d'images clés sur la propriété et le canal donnés. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


