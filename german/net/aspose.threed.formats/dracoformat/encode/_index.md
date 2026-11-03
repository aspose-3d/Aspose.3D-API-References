---
title: "DracoFormat.Encode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "DracoFormat-Methode. Kodiert die Entität in den angegebenen Stream."
type: docs
weight: 20
url: /de/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

Kodiert das Objekt in den angegebenen Stream

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| Stream | Stream | Der Stream, in den die kodierten Daten geschrieben werden |
| options | DracoSaveOptions | Zusätzliche Optionen zum Kodieren der Punktwolke |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen aus dem Stream fehlschlägt |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

Kodiert das Objekt in die angegebene Datei

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| fileName | String | Der zu schreibende Dateiname |
| options | DracoSaveOptions | Zusätzliche Optionen zum Kodieren der Punktwolke |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

Kodiert das Objekt in rohe Draco‑Daten

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Entität | Entität | Die zu kodierende Entität |
| options | DracoSaveOptions | Zusätzliche Optionen zum Kodieren der Punktwolke |

### Rückgabewert

Die kodierten Draco-Daten, dargestellt in Bytes

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


