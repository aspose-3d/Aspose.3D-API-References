---
title: "PlyFormat.Encode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PlyFormat-Methode. Kodieren Sie die Entität und speichern Sie das Ergebnis im Stream"
type: docs
weight: 20
url: /de/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

Kodieren Sie das Objekt und speichern Sie das Ergebnis in den Stream.

```csharp
public void Encode(Entity entity, Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| Stream | Stream | Der Stream, in den geschrieben wird; diese Methode schließt den Stream nicht |

## Beispiele

Der folgende Code zeigt, wie ein Mesh in eine PLY-Datei kodiert wird:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in PLY-Format kodieren
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Siehe auch

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

Kodieren Sie das Objekt und speichern Sie das Ergebnis in den Stream.

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| Stream | Stream | Der Stream, in den geschrieben wird; diese Methode schließt den Stream nicht |
| opt | PlySaveOptions | Speicheroptionen |

## Beispiele

Der folgende Code zeigt, wie ein Mesh in eine PLY-Datei kodiert wird:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in PLY-Format kodieren
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Siehe auch

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

Kodieren Sie das Objekt und speichern Sie das Ergebnis in einer externen Datei.

```csharp
public void Encode(Entity entity, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| fileName | String | Die Datei, in die geschrieben wird |

## Beispiele

Der folgende Code zeigt, wie ein Mesh in eine PLY-Datei kodiert wird:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in PLY-Format kodieren
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Siehe auch

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

Kodieren Sie das Objekt und speichern Sie das Ergebnis in einer externen Datei.

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| fileName | String | Die Datei, in die geschrieben wird |
| opt | PlySaveOptions | Speicheroptionen |

## Beispiele

Der folgende Code zeigt, wie ein Mesh in eine PLY-Datei kodiert wird:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in PLY-Format kodieren
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### Siehe auch

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


