---
title: "PdfFormat.Extract"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PdfFormat. Extrae contenido 3D sin procesar del archivo PDF"
type: docs
weight: 10
url: /es/net/aspose.threed.formats/pdfformat/extract/
---
## Extract(string, byte[]) {#extract_1}

Extrae contenido 3D sin procesar del archivo PDF.

```csharp
public List<byte[]> Extract(string fileName, byte[] password = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo del PDF de entrada |
| contraseña | Byte[] | Contraseña del archivo PDF |

### Valor de retorno

Una lista de todos los contenidos 3D en bytes, incluidos los formatos que Aspose.3D no soporta.

## Ejemplos

El siguiente código muestra cómo extraer todo el contenido 3D sin procesar de un archivo PDF 3D y escribirlo en archivos.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Ver también

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## Extract(Stream, byte[]) {#extract}

Extrae contenido 3D sin procesar del flujo PDF.

```csharp
public List<byte[]> Extract(Stream stream, byte[] password = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Secuencia del archivo PDF de entrada |
| contraseña | Byte[] | Contraseña del archivo PDF |

### Valor de retorno

Una lista de todos los contenidos 3D en bytes, incluidos los formatos que Aspose.3D no soporta.

## Ejemplos

El siguiente código muestra cómo extraer todo el contenido 3D sin procesar de un archivo PDF 3D y escribirlo en archivos.

```csharp
var raw3DContents = FileFormat.PDF.Extract("input.pdf");
for (int i = 0; i < raw3DContents.Count; i++)
{
    File.WriteAllBytes("raw-3d-" + i, raw3DContents[i]);
}
```

### Ver también

* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


