---
title: "Clase DracoSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.DracoSaveOptions. Opciones de guardado para archivos draco de Google"
type: docs
weight: 1160
url: /es/net/aspose.threed.formats/dracosaveoptions/
---
## DracoSaveOptions class

Opciones de guardado para archivos Google draco

```csharp
public class DracoSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DracoSaveOptions](dracosaveoptions/)() | Construye una configuración predeterminada para guardar archivos draco. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/dracosaveoptions/applyunitscale/) { get; set; } | Aplica [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) a la malla. El valor predeterminado es false. |
| [ColorBits](../../aspose.threed.formats/dracosaveoptions/colorbits/) { get; set; } | Bits de cuantización para el color del vértice, el valor predeterminado es 10 |
| [CompressionLevel](../../aspose.threed.formats/dracosaveoptions/compressionlevel/) { get; set; } | Nivel de compresión, el valor predeterminado es Standard |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [NormalBits](../../aspose.threed.formats/dracosaveoptions/normalbits/) { get; set; } | Bits de cuantización para vectores normales, el valor predeterminado es 10 |
| [PointCloud](../../aspose.threed.formats/dracosaveoptions/pointcloud/) { get; set; } | Exportar la escena como nube de puntos, el valor predeterminado es false. |
| [PositionBits](../../aspose.threed.formats/dracosaveoptions/positionbits/) { get; set; } | Bits de cuantización para la posición, el valor predeterminado es 14 |
| [TextureCoordinateBits](../../aspose.threed.formats/dracosaveoptions/texturecoordinatebits/) { get; set; } | Bits de cuantización para la coordenada de textura, el valor predeterminado es 12 |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


