---
title: Property
second_title: Référence de l'API Aspose.3D pour .NET
description: Classe pour contenir les propriétés définies par lutilisateur.
type: docs
weight: 1670
url: /fr/net/aspose.threed/property/
---
## Property class

Classe pour contenir les propriétés définies par l'utilisateur.

```csharp
public abstract class Property : A3DObject
```

## Propriétés

| Nom | La description |
| --- | --- |
| override [Name](../../aspose.threed/property/name) { set; } |  |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtient la collection de toutes les propriétés. |
| abstract [Value](../../aspose.threed/property/value) { get; set; } | Obtient ou définit la valeur. |
| abstract [ValueType](../../aspose.threed/property/valuetype) { get; } | Obtient le type de la valeur de la propriété. |

## Méthodes

| Nom | La description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Trouve la propriété. Il peut s'agir d'une propriété dynamique (créée par CreateDynamicProperty/SetProperty) ou d'une propriété native (identifiée par son nom) |
| [GetBindPoint](../../aspose.threed/property/getbindpoint)(AnimationNode, bool) | Obtient le point de liaison de la propriété sur l'instance d'animation spécifiée. |
| [GetKeyframeSequence](../../aspose.threed/property/getkeyframesequence)(AnimationNode, bool) | Obtient la séquence d'images clés sur l'instance d'animation spécifiée. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Supprimer la propriété spécifiée identifiée par name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Définit la valeur de la propriété spécifiée |
| override [ToString](../../aspose.threed/property/tostring)() | Renvoie une chaîne qui représente le courant[`Property`](../property) . |

### Voir également

* class [A3DObject](../a3dobject)
* espace de noms [Aspose.ThreeD](../../aspose.threed)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
