---
title: "Clase U3dSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.U3dSaveOptions. Opciones de guardado para 3D universal"
type: docs
weight: 1530
url: /es/net/aspose.threed.formats/u3dsaveoptions/
---
## U3dSaveOptions class

Opciones de guardado para universal 3d

```csharp
public class U3dSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [U3dSaveOptions](u3dsaveoptions/)() | Constructor de `U3dSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/u3dsaveoptions/embedtextures/) { get; set; } | Incrusta las texturas externas en el archivo U3D, el valor predeterminado es false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportNormals](../../aspose.threed.formats/u3dsaveoptions/exportnormals/) { get; set; } | Obtiene o establece si exportar datos de normales. |
| [ExportTextureCoordinates](../../aspose.threed.formats/u3dsaveoptions/exporttexturecoordinates/) { get; set; } | Obtiene o establece si exportar coordenadas de textura. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [ExportVertexDiffuse](../../aspose.threed.formats/u3dsaveoptions/exportvertexdiffuse/) { get; set; } | Obtiene o establece si exportar el color difuso del vértice. |
| [ExportVertexSpecular](../../aspose.threed.formats/u3dsaveoptions/exportvertexspecular/) { get; set; } | Obtiene o establece si exportar el color especular del vértice. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/u3dsaveoptions/flipcoordinatesystem/) { get; set; } | Obtiene o establece si se invierte el sistema de coordenadas de los puntos de control/normal durante la importación/exportación. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [MeshCompression](../../aspose.threed.formats/u3dsaveoptions/meshcompression/) { get; set; } | Obtiene o establece si habilitar la compresión de datos de malla. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


