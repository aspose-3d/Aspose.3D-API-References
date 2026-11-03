---
title: "Classe RvmSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Formats.RvmSaveOptions classe. Options d'enregistrement pour le fichier Aveva PDMS RVM"
type: docs
weight: 1480
url: /fr/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Options d'enregistrement pour le fichier RVM Aveva PDMS.

```csharp
public class RvmSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | Constructeur de `RvmSaveOptions` |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | Constructeur de `RvmSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | Obtient ou définit le nom de fichier de la liste d'attributs, l'exportateur générera un nom basé sur le nom du fichier .rvm lorsque cette propriété est indéfinie, la valeur par défaut est null. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | Obtient ou définit le préfixe des attributs qui seront exportés, la propriété exportée ne contiendra aucun préfixe, les propriétés personnalisées avec un préfixe différent ne seront pas exportées, la valeur par défaut est 'rvm:'. Par exemple, si une propriété est rvm:Refno=345, l'attribut exporté sera Refno = 345, le préfixe étant supprimé. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | Informations sur l'auteur, la valeur par défaut est '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | L'horodatage qui a exporté ce fichier, la valeur par défaut est l'heure actuelle |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | Obtient ou définit si la liste d'attributs doit être exportée vers un fichier .att externe, la valeur par défaut est false. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | Note de fichier dans l'en-tête du fichier. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |

## Exemples

Le code suivant montre comment exporter un attribut dans RVM.

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//Le nom du nœud est requis pour exporter les attributs
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//Les propriétés avec le préfixe rvm: seront exportées.
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


