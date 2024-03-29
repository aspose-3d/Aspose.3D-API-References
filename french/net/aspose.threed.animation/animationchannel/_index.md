---
title: AnimationChannel
second_title: Référence de l'API Aspose.3D pour .NET
description: Un canal mappe le champ de composant de la propriété à un ensemble de séquences dimages clés
type: docs
weight: 20
url: /fr/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Un canal mappe le champ de composant de la propriété à un ensemble de séquences d'images clés

```csharp
public class AnimationChannel : IEnumerable<KeyframeSequence>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype) { get; } | Récupère le type du champ composant |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue) { get; set; } | Obtient ou définit la valeur par défaut du canal. Si un canal n'a pas de séquences d'images clés connectées, la valeur par défaut sera utilisée lors de l'évaluation de l'animation. Un scénario réel : l'animation n'anime que la coordonnée x d'un nœud, le y et le z sont pas changé, alors la valeur par défaut sera utilisée lors de l'évaluation complète de la traduction. |
| [KeyframeSequences](../../aspose.threed.animation/animationchannel/keyframesequences) { get; } | Obtient toutes les séquences d'images clés à l'intérieur de ce canal |
| [Name](../../aspose.threed.animation/animationchannel/name) { get; } | Obtient le nom du canal |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddKeyframeSequence](../../aspose.threed.animation/animationchannel/addkeyframesequence)(KeyframeSequence) | Ajoute une séquence d'images clés à ce canal |
| [GetEnumerator](../../aspose.threed.animation/animationchannel/getenumerator)() | Obtient un énumérateur pour parcourir toutes les séquences d'images clés à l'intérieur de ce canal |

### Voir également

* class [KeyframeSequence](../keyframesequence)
* espace de noms [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
