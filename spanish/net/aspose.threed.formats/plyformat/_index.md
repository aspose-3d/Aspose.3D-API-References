---
title: "Clase PlyFormat"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.PlyFormat. El formato PLY"
type: docs
weight: 1430
url: /es/net/aspose.threed.formats/plyformat/
---
## PlyFormat class

El formato PLY.

```csharp
public class PlyFormat : FileFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Obtiene si Aspose.3D admite la exportación de la escena al formato de archivo actual. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Obtiene si Aspose.3D admite la importación de la escena desde el formato de archivo actual. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Obtiene el tipo de contenido del formato de archivo |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Obtiene el nombre de la extensión de este tipo. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Obtiene los nombres de las extensiones de este tipo. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Obtiene el tipo de formato de archivo |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Obtiene la versión del formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Crea opciones de carga predeterminadas para este formato de archivo |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Crea opciones de guardado predeterminadas para este formato de archivo |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode)(Stream) | Decodifica una nube de puntos o malla del flujo especificado. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_2)(string) | Decodifica una nube de puntos o malla del flujo especificado. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_1)(Stream, PlyLoadOptions) | Decodifica una nube de puntos o malla del flujo especificado. |
| [Decode](../../aspose.threed.formats/plyformat/decode/#decode_3)(string, PlyLoadOptions) | Decodifica una nube de puntos o malla del flujo especificado. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode)(Entity, Stream) | Codifica la entidad y guarda el resultado en el flujo. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_2)(Entity, string) | Codifica la entidad y guarda el resultado en un archivo externo. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_1)(Entity, Stream, PlySaveOptions) | Codifica la entidad y guarda el resultado en el flujo. |
| [Encode](../../aspose.threed.formats/plyformat/encode/#encode_3)(Entity, string, PlySaveOptions) | Codifica la entidad y guarda el resultado en un archivo externo. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatea a cadena |

## Ejemplos

El siguiente código muestra cómo codificar una malla en un archivo PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

El siguiente código muestra cómo decodificar una malla de un archivo PLY:

```csharp
//Generar un archivo de prueba para decodificación
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Decodificar el archivo
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Ver también

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


