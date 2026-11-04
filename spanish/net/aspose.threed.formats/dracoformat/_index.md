---
title: "Clase DracoFormat"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.DracoFormat. Formato Google Draco"
type: docs
weight: 1150
url: /es/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

Formato Google Draco

```csharp
public class DracoFormat : FileFormat
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
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | Decodifica la nube de puntos o malla desde datos en memoria |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | Decodifica la nube de puntos o malla desde el nombre de archivo especificado |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | Codifica la entidad a datos sin procesar Draco |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | Codifica la entidad al flujo especificado |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | Codifica la entidad al archivo especificado |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formatea a cadena |

## Ejemplos

El siguiente código muestra cómo codificar y decodificar una Mesh a/de una matriz de bytes:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//codificar malla en formato Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//decodificar malla del formato Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### Ver también

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


