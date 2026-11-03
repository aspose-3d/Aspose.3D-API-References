---
title: "PlyFormat.Decode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PlyFormat-Methode. Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream"
type: docs
weight: 10
url: /de/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream.

```csharp
public Geometry Decode(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Eingabestream |

### Rückgabewert

Ein [`Mesh`](../../../aspose.threed.entities/mesh/) oder [`PointCloud`](../../../aspose.threed.entities/pointcloud/) Instanz

## Beispiele

Der folgende Code zeigt, wie ein Mesh aus einer PLY-Datei dekodiert wird:

```csharp
//Eine Testdatei zum Dekodieren erzeugen
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Datei dekodieren
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Siehe auch

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream.

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Eingabestream |
| opt | PlyLoadOptions | Die Ladeoption des PLY-Formats |

### Rückgabewert

Ein [`Mesh`](../../../aspose.threed.entities/mesh/) oder [`PointCloud`](../../../aspose.threed.entities/pointcloud/) Instanz

## Beispiele

Der folgende Code zeigt, wie ein Mesh aus einer PLY-Datei dekodiert wird:

```csharp
//Eine Testdatei zum Dekodieren erzeugen
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Datei dekodieren
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Siehe auch

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream.

```csharp
public Geometry Decode(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Eingabestream |

### Rückgabewert

Ein [`Mesh`](../../../aspose.threed.entities/mesh/) oder [`PointCloud`](../../../aspose.threed.entities/pointcloud/) Instanz

## Beispiele

Der folgende Code zeigt, wie ein Mesh aus einer PLY-Datei dekodiert wird:

```csharp
//Eine Testdatei zum Dekodieren erzeugen
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Datei dekodieren
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Siehe auch

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

Dekodieren Sie eine Punktwolke oder ein Mesh aus dem angegebenen Stream.

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Eingabestream |
| opt | PlyLoadOptions | Die Ladeoption des PLY-Formats |

### Rückgabewert

Ein [`Mesh`](../../../aspose.threed.entities/mesh/) oder [`PointCloud`](../../../aspose.threed.entities/pointcloud/) Instanz

## Beispiele

Der folgende Code zeigt, wie ein Mesh aus einer PLY-Datei dekodiert wird:

```csharp
//Eine Testdatei zum Dekodieren erzeugen
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Datei dekodieren
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Siehe auch

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


