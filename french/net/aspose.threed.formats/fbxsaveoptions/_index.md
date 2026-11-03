---
title: "Classe FbxSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.FbxSaveOptions. Options d'enregistrement pour le fichier Fbx"
type: docs
weight: 1180
url: /fr/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Options d'enregistrement pour le fichier Fbx.

```csharp
public class FbxSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | Initialiser un `FbxSaveOptions` en utilisant la dernière version prise en charge. |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | Initialise un `FbxSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | Obtient ou définit si la texture doit être intégrée au fichier de sortie final. FBX Exporter essaiera de trouver les données brutes de la texture depuis [`FileSystem`](../ioconfig/filesystem/), et intégrera le fichier au fichier FBX final. La valeur par défaut est fausse. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | Compression des grandes données binaires dans le fichier FBX (par ex. données d'animation, points de contrôle, données d'éléments de sommet, indices), la valeur par défaut est vraie. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | Obtient ou définit si l'exportation des propriétés de matériau héritées, utilisées pour la rétrocompatibilité, est activée. Cette option est activée par défaut. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | Obtient ou définit si les données de courbe répétées sont réutilisées en augmentant le compteur de références des dernières données. |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | Obtient ou définit si un [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) est toujours généré pour les géométries si le nœud attaché contient des matériaux. Cette option est désactivée par défaut. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille de la sortie FBX dont la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). La valeur par défaut est false. |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | Obtient ou définit si une instance Video est générée pour [`Texture`](../../aspose.threed.shading/texture/) lors de l'exportation au format FBX. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


