---
title: "Classe KeyframeSequence"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Animation.KeyframeSequence class. La séquence de images-clés décrit la transformation d'une valeur échantillonnée au fil du temps"
type: docs
weight: 100
url: /fr/net/aspose.threed.animation/keyframesequence/
---
## KeyframeSequence class

La séquence d'images clés décrit la transformation d'une valeur échantillonnée au fil du temps.

```csharp
public class KeyframeSequence : A3DObject, IEnumerable<KeyFrame>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [KeyframeSequence](keyframesequence/#constructor)() | Initialise une nouvelle instance de la classe `KeyframeSequence`. |
| [KeyframeSequence](keyframesequence/#constructor_1)(string) | Initialise une nouvelle instance de la classe `KeyframeSequence`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Obtient le point de liaison de propriété qui possède cette courbe |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Obtient les images-clés de cette courbe. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Obtient le comportement postérieur indiquant quelle doit être la valeur échantillonnée après la dernière image-clé. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Obtient le comportement antérieur indiquant quelle doit être la valeur échantillonnée avant la première image-clé. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add)(double, float) | Crée une nouvelle image-clé avec la valeur spécifiée |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add_1)(double, float, Interpolation) | Crée une nouvelle image-clé avec la valeur spécifiée |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Obtient l'énumérateur pour parcourir toutes les images-clés. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Supprime toutes les images-clés et réinitialise les comportements post/pré. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [KeyFrame](../keyframe/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


