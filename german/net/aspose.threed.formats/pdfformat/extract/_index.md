---
title: "PdfFormat.Extract"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PdfFormat-Methode. Extrahiert rohen 3D-Inhalt aus einer PDF-Datei"
type: docs
weight: 10
url: /de/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

Roh-3D-Inhalt aus PDF-Datei extrahieren.

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname der Eingabe-PDF-Datei |
| Passwort | Byte[] | Passwort der PDF-Datei |

### Rückgabewert

Eine Liste aller 3D-Inhalte in Bytes, einschließlich der Formate, die Aspose.3D nicht unterstützt.

## Beispiele

Der folgende Code zeigt, wie man alle rohen 3D-Inhalte aus einer 3D-PDF-Datei extrahiert und sie in Dateien schreibt.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Siehe auch

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

Roh-3D-Inhalt aus PDF-Stream extrahieren.

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Stream der Eingabe-PDF-Datei |
| Passwort | Byte[] | Passwort der PDF-Datei |

### Rückgabewert

Eine Liste aller 3D-Inhalte in Bytes, einschließlich der Formate, die Aspose.3D nicht unterstützt.

## Beispiele

Der folgende Code zeigt, wie man alle rohen 3D-Inhalte aus einer 3D-PDF-Datei extrahiert und sie in Dateien schreibt.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Siehe auch

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


