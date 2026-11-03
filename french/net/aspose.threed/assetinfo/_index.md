---
title: "Classe AssetInfo"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.AssetInfo. Information de l'actif. Les informations d'actif peuvent être attachées à une Scène. Une Scène enfant peut avoir son propre AssetInfo pour remplacer la définition du parent."
type: docs
weight: 130
url: /fr/net/aspose.threed/assetinfo/
---
## AssetInfo class

Information de l'actif. Les informations d'actif peuvent être attachées à un [`Scene`](../scene/). Une [`Scene`](../scene/) enfant peut avoir son propre `AssetInfo` pour remplacer la définition du parent.

```csharp
public class AssetInfo : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AssetInfo](assetinfo/#constructor)() | Initialise une nouvelle instance de la classe `AssetInfo`. |
| [AssetInfo](assetinfo/#constructor_1)(string) | Initialise une nouvelle instance de la classe `AssetInfo`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Ambient](../../aspose.threed/assetinfo/ambient/) { get; set; } | Obtient ou définit la couleur ambiante par défaut de cet actif |
| [ApplicationName](../../aspose.threed/assetinfo/applicationname/) { get; set; } | Obtient ou définit l'application qui a créé cet actif |
| [ApplicationVendor](../../aspose.threed/assetinfo/applicationvendor/) { get; set; } | Obtient ou définit le nom du fournisseur de l'application |
| [ApplicationVersion](../../aspose.threed/assetinfo/applicationversion/) { get; set; } | Obtient ou définit la version de l'application qui a créé cet actif. |
| [Author](../../aspose.threed/assetinfo/author/) { get; set; } | Obtient ou définit l'auteur de cet actif |
| [AxisSystem](../../aspose.threed/assetinfo/axissystem/) { get; set; } | Obtient ou définit le système de coordonnées/up vector/front vector des informations de l'actif. |
| [Comment](../../aspose.threed/assetinfo/comment/) { get; set; } | Obtient ou définit le commentaire de cet actif. |
| [CoordinateSystem](../../aspose.threed/assetinfo/coordinatesystem/) { get; set; } | Obtient ou définit le système de coordonnées utilisé dans cet actif. |
| [Copyright](../../aspose.threed/assetinfo/copyright/) { get; set; } | Obtient ou définit le droit d'auteur du document |
| [CreationTime](../../aspose.threed/assetinfo/creationtime/) { get; set; } | Obtient ou définit l'heure de création de cet actif |
| [FrontVector](../../aspose.threed/assetinfo/frontvector/) { get; set; } | Obtient ou définit le front-vector utilisé dans cet actif. |
| [Keywords](../../aspose.threed/assetinfo/keywords/) { get; set; } | Obtient ou définit les mots-clés de cet actif |
| [ModificationTime](../../aspose.threed/assetinfo/modificationtime/) { get; set; } | Obtient ou définit l'heure de modification de cet actif |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Revision](../../aspose.threed/assetinfo/revision/) { get; set; } | Obtient ou définit le numéro de révision de cet actif, généralement utilisé dans le système de contrôle de version. |
| [Subject](../../aspose.threed/assetinfo/subject/) { get; set; } | Obtient ou définit le sujet de cet actif |
| [Title](../../aspose.threed/assetinfo/title/) { get; set; } | Obtient ou définit le titre de cet actif |
| [UnitName](../../aspose.threed/assetinfo/unitname/) { get; set; } | Obtient ou définit l'unité de longueur utilisée dans cet actif. p. ex. cm/m/km/pouce/pieds |
| [UnitScaleFactor](../../aspose.threed/assetinfo/unitscalefactor/) { get; set; } | Obtient ou définit le facteur d'échelle en mètres du monde réel. |
| [UpVector](../../aspose.threed/assetinfo/upvector/) { get; set; } | Obtient ou définit le up-vector utilisé dans cet actif. |
| [Url](../../aspose.threed/assetinfo/url/) { get; set; } | Obtient ou définit l'URL de cet actif. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

## Exemples

Le code suivant montre comment lire les informations d'actif à partir d'un fichier fbx :

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The file is created at {scene.AssetInfo.CreationTime} by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion} ");
```

### Voir aussi

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


