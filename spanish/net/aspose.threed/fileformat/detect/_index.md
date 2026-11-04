---
title: "FileFormat.Detect"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método FileFormat. Detecta el formato de archivo a partir del flujo de datos; el nombre del archivo es opcional para adivinar tipos que no tienen encabezado mágico"
type: docs
weight: 460
url: /es/net/aspose.threed/fileformat/detect/
---
## Detect(Stream, string) {#detect}

Detecte el formato de archivo a partir del flujo de datos, el nombre del archivo es opcional para adivinar tipos que no tienen encabezado mágico.

```csharp
public static FileFormat Detect(Stream stream, string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo que contiene datos para detectar |
| fileName | String | Nombre de archivo original de los datos, usado como pista. |

### Valor de retorno

La instancia [`FileFormat`](../) del tipo detectado o null si falla.

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Excepción lanzada cuando falla la lectura de datos. |

## Ejemplos

```csharp
byte[] bytes = new byte[100];//take the bytes from your source
var fmt = FileFormat.Detect(new MemoryStream(bytes), "input-file");
Console.WriteLine($"Input data format: {fmt}");
```

### Ver también

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)

---

## Detect(string) {#detect_1}

Detecte el formato de archivo a partir del nombre del archivo, el archivo debe ser legible para que Aspose.3D pueda detectar el formato mediante el encabezado del archivo.

```csharp
public static FileFormat Detect(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | Ruta al archivo para detectar el formato de archivo. |

### Valor de retorno

La instancia [`FileFormat`](../) del tipo detectado o null si falla.

### Excepciones

| excepción | condición |
| --- | --- |
| IOException | Excepción lanzada cuando falla la lectura de datos. |

## Ejemplos

```csharp
var fmt = FileFormat.Detect("input.fbx");
Console.WriteLine($"Input file format: {fmt}");
```

### Ver también

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


