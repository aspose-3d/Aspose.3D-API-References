---
title: "FileFormat.Detect"
second_title: "Aspose.3D für .NET API-Referenz"
description: "FileFormat Methode. Ermittelt das Dateiformat aus dem Datenstrom, Dateiname ist optional zum Erraten von Typen, die keinen Magic-Header haben"
type: docs
weight: 460
url: /de/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

Erkennen Sie das Dateiformat aus dem Datenstrom, der Dateiname ist optional, um Typen zu erraten, die keinen Magic-Header haben.

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Stream, der zu erkennende Daten enthält |
| fileName | String | Ursprünglicher Dateiname der Daten, als Hinweis verwendet. |

### Rückgabewert

Die [`FileFormat`](../)-Instanz des erkannten Typs oder null bei Fehlschlag.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Ausnahme, die ausgelöst wird, wenn das Lesen von Daten fehlschlägt. |

## Beispiele

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### Siehe auch

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

Erkennen Sie das Dateiformat anhand des Dateinamens, die Datei muss lesbar sein, damit Aspose.3D das Dateiformat über den Dateikopf erkennen kann.

```csharp
public static FileFormat Detect(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Pfad zur Datei, um das Dateiformat zu erkennen. |

### Rückgabewert

Die [`FileFormat`](../)-Instanz des erkannten Typs oder null bei Fehlschlag.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Ausnahme, die ausgelöst wird, wenn das Lesen von Daten fehlschlägt. |

## Beispiele

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### Siehe auch

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


