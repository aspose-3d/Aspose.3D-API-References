---
title: "DracoFormat.Decode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode DracoFormat. Décode le nuage de points ou le maillage à partir du nom de fichier spécifié"
type: docs
weight: 10
url: /fr/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

Décode le nuage de points ou le maillage à partir du nom de fichier spécifié

```csharp
public Geometry Decode(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Le nom de fichier contient le fichier drc |

### Valeur de retour

Une instance de [`Mesh`](../../../aspose.threed.entities/mesh/) ou de [`PointCloud`](../../../aspose.threed.entities/pointcloud/) dépend du contenu du fichier

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancée lorsqu'il n'a pas pu lire le fichier |

## Exemples

Le code suivant montre comment encoder et décoder un Mesh vers/de tableau d'octets :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//décoder le maillage depuis le format Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Voir aussi

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

Décode le nuage de points ou le maillage à partir des données en mémoire

```csharp
public Geometry Decode(byte[] data)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| données | Byte[] | Les octets bruts du drc |

### Valeur de retour

Une instance de [`Mesh`](../../../aspose.threed.entities/mesh/) ou de [`PointCloud`](../../../aspose.threed.entities/pointcloud/) dépend du contenu

### Exceptions

| exception | condition |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | Lancée lorsque les données sont malformées. |

## Exemples

Le code suivant montre comment encoder et décoder un Mesh vers/de tableau d'octets :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//décoder le maillage depuis le format Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Voir aussi

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


