---
title: "Classe RvmLoadOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Formats.RvmLoadOptions classe. Options de chargement pour le fichier RVM du système AVEVA Plant Design Management Systems"
type: docs
weight: 1470
url: /fr/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

Options de chargement pour le fichier RVM du système de gestion de conception d'usine AVEVA.

```csharp
public class RvmLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | Construisez une instance de `RvmLoadOptions` |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | Construisez une instance de `RvmLoadOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | Obtient ou définit le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes. Le préfixe est utilisé pour éviter les conflits de noms, valeur par défaut : "rvm:" |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | Centrer la scène après son chargement. |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | Obtient ou définit le nombre de segments radiaux du cylindre, valeur par défaut : 16 |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | Obtient ou définit le nombre de segments de latitude du dish, valeur par défaut : 8 |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | Obtient ou définit le nombre de segments de longitude du dish, valeur par défaut : 12 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | Générez des matériaux avec des couleurs aléatoires pour chaque objet de la scène si la table des couleurs n'est pas exportée dans le fichier RVM. Valeur par défaut : true |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | Obtient ou définit s'il faut charger les attributs à partir d'un fichier de liste d'attributs externe (.att/.attrib/.txt), valeur par défaut : true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | Obtient ou définit le nombre de segments radiaux du torus rectangulaire, valeur par défaut : 20 |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | Obtient ou définit le nombre de segments tubulaires du tore, la valeur par défaut est 20 |

## Exemples

Le code suivant montre comment personnaliser les paramètres de tessellation pour les géométries primitives importées d'un fichier RVM à l'aide de RvmLoadOptions.

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


