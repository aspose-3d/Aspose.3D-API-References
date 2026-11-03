---
title: "Classe CustomObject"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.CustomObject. Les métadonnées ou objets personnalisés utilisés dans les fichiers 3D sont gérés par cette classe. Toutes les propriétés personnalisées sont enregistrées en tant que propriétés dynamiques"
type: docs
weight: 180
url: /fr/net/aspose.threed/customobject/
---
## CustomObject class

Les métadonnées ou objets personnalisés utilisés dans les fichiers 3D sont gérés par cette classe. Toutes les propriétés personnalisées sont enregistrées en tant que propriétés dynamiques.

```csharp
public class CustomObject : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CustomObject](customobject/#constructor)() | Initialise une nouvelle instance de la classe `CustomObject`. |
| [CustomObject](customobject/#constructor_1)(string) | Initialise une nouvelle instance de la classe `CustomObject`. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


