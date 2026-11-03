---
title: "Classe AnimationChannel"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "classe Aspose.ThreeD.Animation.AnimationChannel. Un canal mappe le champ de composant des propriétés à un ensemble de séquences d'images clés"
type: docs
weight: 20
url: /fr/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Un canal associe le champ de composant d'une propriété à un ensemble de séquences d'images clés.

```csharp
public class AnimationChannel : KeyframeSequence
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Obtient le point de liaison de propriété qui possède cette courbe |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype/) { get; } | Obtient le type du champ du composant |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue/) { get; set; } | Obtient ou définit la valeur par défaut du canal. Si un canal n'a aucune séquence d'images clés connectée, la valeur par défaut sera utilisée pendant l'évaluation de l'animation. Un scénario réel : l'animation ne modifie que la coordonnée x d'un nœud, les y et z ne sont pas changés, alors la valeur par défaut sera utilisée pendant l'évaluation complète de la translation. |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Obtient les images-clés de cette courbe. |
| [KeyframeSequence](../../aspose.threed.animation/animationchannel/keyframesequence/) { get; set; } | Obtient la séquence d'images clés associée dans ce canal |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Obtient le comportement postérieur indiquant quelle doit être la valeur échantillonnée après la dernière image-clé. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Obtient le comportement antérieur indiquant quelle doit être la valeur échantillonnée avant la première image-clé. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float) | Crée une nouvelle image-clé avec la valeur spécifiée |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float, Interpolation) | Crée une nouvelle image-clé avec la valeur spécifiée |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Obtient l'énumérateur pour parcourir toutes les images-clés. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Supprime toutes les images-clés et réinitialise les comportements post/pré. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [KeyframeSequence](../keyframesequence/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


