---
title: "Scene.Save"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Methode. Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats"
type: docs
weight: 160
url: /de/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(Stream stream, FileFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |
| Format | FileFormat | Format. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |
| Format | FileFormat | Format. |
| cancellationToken | CancellationToken | Abbruch-Token für die Speicheraufgabe |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(Stream stream, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |
| options | SaveOptions | Detailliertere Konfiguration zum Speichern des Streams. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Siehe auch

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Eingabestream, der Benutzer ist für das Schließen des Streams verantwortlich. |
| options | SaveOptions | Detailliertere Konfiguration zum Speichern des Streams. |
| cancellationToken | CancellationToken | Abbruch-Token für die Speicheraufgabe |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### Siehe auch

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### Siehe auch

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(string fileName, FileFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| Format | FileFormat | Format. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| Format | FileFormat | Format. |
| cancellationToken | CancellationToken | Abbruch-Token für die Speicheraufgabe |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### Siehe auch

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(string fileName, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| options | SaveOptions | Detailliertere Konfiguration zum Speichern des Streams. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### Siehe auch

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats.

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname. |
| options | SaveOptions | Detailliertere Konfiguration zum Speichern des Streams. |
| cancellationToken | CancellationToken | Abbruch-Token für die Speicheraufgabe |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IOException | Wird ausgelöst, wenn das Lesen der Eingabe fehlschlägt |
| [ExportException](../../exportexception/) | Wird ausgelöst, wenn das Exportieren der Szene in das angegebene 3D-Format fehlschlägt |

## Beispiele

Der folgende Code zeigt, wie man die Szene speichert

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### Siehe auch

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


