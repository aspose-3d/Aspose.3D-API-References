---
title: "PlyFormat.Decode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PlyFormat. Décode un nuage de points ou un maillage depuis le flux spécifié"
type: docs
weight: 10
url: /fr/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

Décodez un nuage de points ou un maillage depuis le flux spécifié.

```csharp
public Geometry Decode(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Le flux d'entrée |

### Valeur de retour

Une instance de [`Mesh`](../../../aspose.threed.entities/mesh/) ou de [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Exemples

Le code suivant montre comment décoder un maillage depuis un fichier PLY :

```csharp
//Générer un fichier de test pour le décodage
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Décoder le fichier
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Voir aussi

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

Décodez un nuage de points ou un maillage depuis le flux spécifié.

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Le flux d'entrée |
| opt | PlyLoadOptions | L'option de chargement du format PLY |

### Valeur de retour

Une instance de [`Mesh`](../../../aspose.threed.entities/mesh/) ou de [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Exemples

Le code suivant montre comment décoder un maillage depuis un fichier PLY :

```csharp
//Générer un fichier de test pour le décodage
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Décoder le fichier
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Voir aussi

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

Décodez un nuage de points ou un maillage depuis le flux spécifié.

```csharp
public Geometry Decode(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux d'entrée |

### Valeur de retour

Une instance de [`Mesh`](../../../aspose.threed.entities/mesh/) ou de [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Exemples

Le code suivant montre comment décoder un maillage depuis un fichier PLY :

```csharp
//Générer un fichier de test pour le décodage
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Décoder le fichier
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Voir aussi

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

Décodez un nuage de points ou un maillage depuis le flux spécifié.

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux d'entrée |
| opt | PlyLoadOptions | L'option de chargement du format PLY |

### Valeur de retour

Une instance de [`Mesh`](../../../aspose.threed.entities/mesh/) ou de [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Exemples

Le code suivant montre comment décoder un maillage depuis un fichier PLY :

```csharp
//Générer un fichier de test pour le décodage
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Décoder le fichier
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Voir aussi

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


