---
title: Discreet3dsSaveOptions
second_title: Référence de l'API Aspose.3D pour .NET
description: Enregistrer les options pour le fichier 3DS.
type: docs
weight: 1070
url: /fr/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Enregistrer les options pour le fichier 3DS.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions)() | Constructeur de[`Discreet3dsSaveOptions`](../discreet3dssaveoptions) |

## Propriétés

| Nom | La description |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase) { get; set; } | Le compteur utilisé en générant un nouveau nom pour les noms en double, la valeur par défaut est 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat) { get; set; } | Le format du compteur dupliqué, la valeur par défaut est une chaîne vide. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator) { get; set; } | Le séparateur entre le nom de l'objet et le compteur dupliqué, la valeur par défaut est "_". Lorsque la scène contient des objets qui utilisent le même nom, l'exportateur Aspose.3D 3DS générera un nom différent pour l'objet. Par exemple, il y a deux nœuds nommé "Box", le premier nœud aura un nom "Box", et le deuxième nœud recevra un nouveau nom "Box_2" en utilisant la configuration par défaut. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est nulle, ce qui signifie que l'importateur/exportateur décidera quel encodage utiliser. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera) { get; set; } | Obtient ou définit si toutes les caméras de la scène sont exportées. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight) { get; set; } | Obtient ou définit si toutes les lumières de la scène sont exportées. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrer/Charger actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Le nom de fichier de la scène d'exportation/importation. Ceci est facultatif, mais utile lors de la sérialisation de ressources externes comme le matériel d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Autoriser l'utilisateur à gérer la gestion des dépendances externes lors du chargement/sauvegarde. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem) { get; set; } | Obtient ou définit le système de coordonnées d'inversion des points de contrôle/de la normale lors de l'importation/exportation. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor) { get; set; } | Un fichier 3ds peut contenir la couleur d'origine et la couleur corrigée gamma pour le même attribut, Définir ceci sur vrai utilisera la couleur corrigée gamma si possible, sinon Aspose.3D essaiera d'utiliser la couleur originale. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor) { get; set; } | Si cela est vrai, le fichier 3ds généré utilisera une couleur très précise, ce qui signifie que chaque canal de rouge/vert/bleu est en flottant 32 bits. Sinon, le fichier généré utilisera une couleur 24 bits, chaque canal utilisera un octet 8 bits. La valeur par défaut est faux, car toutes les applications ne prennent pas en charge la couleur haute précision. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher un fichier externe à charger. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale) { get; set; } | Obtient ou définit l'échelle principale utilisée lors de l'exportation. |

### Voir également

* class [SaveOptions](../saveoptions)
* espace de noms [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
