---
title: "PdfFormat.ExtractScene"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PdfFormat. Extrae escenas 3D de un archivo PDF"
type: docs
weight: 20
url: /es/net/aspose.threed.formats/pdfformat/extractscene/
---
## ExtractScene(string) {#extractscene_1}

Extrae escenas 3D del archivo PDF.

```csharp
public List<Scene> ExtractScene(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo del PDF de entrada |

### Valor de retorno

Lista de escenas 3D decodificadas que son compatibles con Aspose.3D

## Ejemplos

El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Ver también

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(string, byte[]) {#extractscene_2}

Extrae escenas 3D del archivo PDF.

```csharp
public List<Scene> ExtractScene(string fileName, byte[] password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo del PDF de entrada |
| contraseña | Byte[] | Contraseña del archivo PDF |

### Valor de retorno

Lista de escenas 3D decodificadas que son compatibles con Aspose.3D

## Ejemplos

El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Ver también

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)

---

## ExtractScene(Stream, byte[]) {#extractscene}

Extrae contenido 3D sin procesar del flujo PDF.

```csharp
public List<Scene> ExtractScene(Stream stream, byte[] password = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Secuencia del archivo PDF de entrada |
| contraseña | Byte[] | Contraseña del archivo PDF |

### Valor de retorno

Lista de escenas 3D decodificadas que son compatibles con Aspose.3D

## Ejemplos

El siguiente código muestra cómo extraer todas las escenas 3D compatibles de un archivo PDF 3D y escribirlas en formato obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Ver también

* class [Scene](../../../aspose.threed/scene/)
* class [PdfFormat](../)
* namespace [Aspose.ThreeD.Formats](../../pdfformat/)
* assembly [Aspose.3D](../../../)


