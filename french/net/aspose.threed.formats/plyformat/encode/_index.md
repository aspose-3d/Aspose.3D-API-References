---
title: "PlyFormat.Encode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PlyFormat. Encode l'entité et enregistre le résultat dans le flux"
type: docs
weight: 20
url: /fr/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

Encodez l'entité et enregistrez le résultat dans le flux.

```csharp
public void Encode(Entity entity, Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité à encoder |
| flux | Flux | Le flux d'écriture, cette méthode ne fermera pas ce flux |

## Exemples

Le code suivant montre comment encoder un maillage dans un fichier PLY :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Voir aussi

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

Encodez l'entité et enregistrez le résultat dans le flux.

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité à encoder |
| flux | Flux | Le flux d'écriture, cette méthode ne fermera pas ce flux |
| opt | PlySaveOptions | Options d'enregistrement |

## Exemples

Le code suivant montre comment encoder un maillage dans un fichier PLY :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Voir aussi

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

Encodez l'entité et enregistrez le résultat dans un fichier externe.

```csharp
public void Encode(Entity entity, string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité à encoder |
| fileName | String | Le fichier dans lequel écrire |

## Exemples

Le code suivant montre comment encoder un maillage dans un fichier PLY :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Voir aussi

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

Encodez l'entité et enregistrez le résultat dans un fichier externe.

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité à encoder |
| fileName | String | Le fichier dans lequel écrire |
| opt | PlySaveOptions | Options d'enregistrement |

## Exemples

Le code suivant montre comment encoder un maillage dans un fichier PLY :

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//encoder le maillage au format PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Voir aussi

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


