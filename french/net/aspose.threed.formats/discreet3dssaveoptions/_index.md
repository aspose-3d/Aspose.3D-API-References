---
title: "Classe Discreet3dsSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.Discreet3dsSaveOptions. Options d'enregistrement pour le fichier 3DS"
type: docs
weight: 1130
url: /fr/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Options d'enregistrement pour le fichier 3DS.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | Constructeur de `Discreet3dsSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | Le compteur utilisé pour générer un nouveau nom pour les noms dupliqués, la valeur par défaut est 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | Le format du compteur dupliqué, la valeur par défaut est une chaîne vide. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "_". Lorsque la scène contient des objets qui utilisent le même nom, l'exportateur 3DS d'Aspose.3D générera un nom différent pour l'objet. Par exemple, il y a deux nœuds nommés "Box", le premier nœud aura le nom "Box", et le deuxième nœud recevra un nouveau nom "Box_2" en utilisant la configuration par défaut. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | Obtient ou définit si toutes les caméras de la scène sont exportées. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | Obtient ou définit si toutes les lumières de la scène sont exportées. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | Obtient ou définit le retournement du système de coordonnées des points de contrôle/normales lors de l'importation/exportation. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | Un fichier 3ds peut contenir la couleur originale et la couleur corrigée gamma pour le même attribut. Le définir sur true utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | Si cette valeur est true, le fichier 3ds généré utilisera une couleur haute précision, ce qui signifie que chaque canal rouge/vert/bleu est en flottant 32 bits. Sinon, le fichier généré utilisera une couleur 24 bits, chaque canal étant un octet de 8 bits. La valeur par défaut est false, car toutes les applications ne prennent pas en charge la couleur haute précision. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | Obtient ou définit l'échelle principale utilisée lors de l'exportation. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


