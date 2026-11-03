---
title: "Classe BindPoint"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Animation.BindPoint. Un BindPoint est généralement créé sur la propriété d'un objet ; certains types de propriétés contiennent plusieurs champs composants, comme un champ Vector3. BindPoint générera un canal pour chaque champ composant et connectera le champ à une ou plusieurs instances de séquence d'images clés via les canaux."
type: docs
weight: 50
url: /fr/net/aspose.threed.animation/bindpoint/
---
## BindPoint class

Un `BindPoint` est généralement créé sur la propriété d'un objet, certains types de propriétés contiennent plusieurs champs composants (comme un champ Vector3), `BindPoint` générera un canal pour chaque champ composant et connectera le champ à une ou plusieurs instance(s) de séquence d'images clés via les canaux.

```csharp
public class BindPoint : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | Initialise une nouvelle instance de la classe `BindPoint`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | Obtient le nombre total de canaux de propriété définis dans ce mappage de courbe d'animation. |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | Obtient la propriété associée au CurveMapping |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | Ajoute la propriété de canal spécifiée. |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | Ajoute la propriété de canal spécifiée. |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | Lie la séquence d'images clés au canal spécifié |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | Crée une nouvelle courbe et la connecte au premier canal du mappage de courbe |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | Obtient le canal par le nom donné |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | Obtient la première séquence d'images clés dans le canal spécifié |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | Vide les canaux de propriété de ce mappage de courbe d'animation. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | Formate l'objet en chaîne |

### Voir aussi

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


