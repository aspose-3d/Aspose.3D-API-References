---
title: "DracoFormat.Decode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "DracoFormat-Methode. Dekodiert die Punktwolke oder das Mesh aus dem angegebenen Dateinamen."
type: docs
weight: 10
url: /de/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

Dekodiert die Punktwolke oder das Mesh aus dem angegebenen Dateinamen

```csharp
public Geometry Decode(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Dateiname enthält die drc-Datei. |

### Rückgabewert

Eine [`Mesh`](../../../aspose.threed.entities/mesh/) oder [`PointCloud`](../../../aspose.threed.entities/pointcloud/) Instanz, abhängig vom Dateiinhalt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen aus der Datei fehlschlägt. |

## Beispiele

Der folgende Code zeigt, wie man ein Mesh in ein Byte-Array kodiert und daraus dekodiert:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in Draco-Format kodieren
byte[] draco = FileFormat.Draco.Encode(mesh);
//Mesh aus Draco-Format dekodieren
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Siehe auch

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

Dekodiert die Punktwolke oder das Mesh aus Speicher­daten

```csharp
public Geometry Decode(byte[] data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | Byte[] | Die rohen drc-Bytes |

### Rückgabewert

Eine [`Mesh`](../../../aspose.threed.entities/mesh/) oder [`PointCloud`](../../../aspose.threed.entities/pointcloud/) Instanz, abhängig vom Inhalt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | Wird ausgelöst, wenn Daten fehlerhaft sind. |

## Beispiele

Der folgende Code zeigt, wie man ein Mesh in ein Byte-Array kodiert und daraus dekodiert:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//Mesh in Draco-Format kodieren
byte[] draco = FileFormat.Draco.Encode(mesh);
//Mesh aus Draco-Format dekodieren
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Siehe auch

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


