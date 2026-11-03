---
title: "DracoFormat.Encode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode DracoFormat. Encode l'entité dans le flux spécifié"
type: docs
weight: 20
url: /fr/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

Encode l'entité vers le flux spécifié

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité à encoder |
| flux | Flux | Le flux dans lequel les données encodées seront écrites |
| options | DracoSaveOptions | Options supplémentaires pour l'encodage du nuage de points |

### Exceptions

| exception | condition |
| --- | --- |
| IOException | Lancée lorsqu'il n'a pas pu lire le flux |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

Encode l'entité vers le fichier spécifié

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité à encoder |
| fileName | String | Le nom de fichier à écrire |
| options | DracoSaveOptions | Options supplémentaires pour l'encodage du nuage de points |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

Encode l'entité en données brutes Draco

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entité | Entité | L'entité à encoder |
| options | DracoSaveOptions | Options supplémentaires pour l'encodage du nuage de points |

### Valeur de retour

Les données draco encodées représentées en octets

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


