---
title: "Aspose.ThreeD.Animation"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "L'espace de noms d'animation d'Aspose.3D où toutes les classes liées à l'animation sont définies."
type: docs
weight: 20
url: /fr/net/aspose.threed.animation/
---
L'espace de noms d'animation d'Aspose.3D, toutes les classes liées à l'animation sont définies dans cet espace de noms

## Classes

| Classe | Description |
| --- | --- |
| [AnimationChannel](./animationchannel/) | Un canal associe le champ de composant d'une propriété à un ensemble de séquences d'images clés. |
| [AnimationClip](./animationclip/) | Le clip d'animation est une collection d'animations. La scène peut contenir un ou plusieurs clips d'animation. |
| [AnimationNode](./animationnode/) | Aspose.3D prend en charge la hiérarchie d'animation, chaque animation pouvant être composée de plusieurs animations et de la définition des images clés d'animation. [`AnimationNode`](../aspose.threed.animation/animationnode/) définit la transformation d'une valeur de propriété au fil du temps, par exemple, le nœud d'animation peut être utilisé pour contrôler la transformation d'un nœud ou d'autres propriétés numériques d'un objet [`A3DObject`](../aspose.threed/a3dobject/). |
| [BindPoint](./bindpoint/) | Un [`BindPoint`](../aspose.threed.animation/bindpoint/) est généralement créé sur la propriété d'un objet, certains types de propriétés contenant plusieurs champs de composant (comme un champ Vector3), [`BindPoint`](../aspose.threed.animation/bindpoint/) générera un canal pour chaque champ de composant et connectera le champ à une ou plusieurs instances de séquence d'images clés via les canaux. |
| [Extrapolation](./extrapolation/) | L'extrapolation définit comment procéder lorsque la valeur échantillonnée est hors de la plage définie par les première et dernière images clés. |
| [KeyFrame](./keyframe/) | Une image clé est principalement définie par un temps et une valeur ; pour certains types d'interpolation, la tangente/la tension/le biais/la continuité sont également utilisés pour calculer la valeur échantillonnée finale. Les valeurs échantillonnées à une position temporelle sans image clé sont interpolées par les images clés situées entre les images clés précédentes et suivantes. La valeur avant/après la première/dernière image clé est calculée par la classe [`Extrapolation`](../aspose.threed.animation/extrapolation/). |
| [KeyframeSequence](./keyframesequence/) | La séquence d'images clés décrit la transformation d'une valeur échantillonnée au fil du temps. |
## Énumération

| Énumération | Description |
| --- | --- |
| [ExtrapolationType](./extrapolationtype/) | Type d'extrapolation. |
| [Interpolation](./interpolation/) | Le type d'interpolation de l'image clé. |
| [StepMode](./stepmode/) | Mode d'étape d'interpolation. |
| [WeightedMode](./weightedmode/) | Mode pondéré. |


