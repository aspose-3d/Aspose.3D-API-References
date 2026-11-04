---
title: "Clase PlySaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.PlySaveOptions. Opciones de guardado para exportar la escena como archivo PLY"
type: docs
weight: 1450
url: /es/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

Opciones de guardado para exportar la escena como archivo PLY.

```csharp
public class PlySaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | Constructor de `PlySaveOptions` |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | Constructor de `PlySaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/plysaveoptions/axissystem/) { get; set; } | Obtiene o establece el sistema de ejes en el archivo stl exportado. |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | Los nombres de los componentes para el color del vértice, el valor predeterminado es ("red", "green", "blue") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | El nombre del elemento para los datos de la cara, el valor predeterminado es "face" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex_index" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | Invierte la coordenada al guardar la escena, el valor predeterminado es true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | Los nombres de los componentes para los datos normales, el valor predeterminado es ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | Exporta la escena como nube de puntos, el valor predeterminado es false. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | Los nombres de los componentes para los datos de posición, el valor predeterminado es ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | Los nombres de los componentes para los datos de coordenadas de textura, el valor predeterminado es ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | El nombre del elemento para los datos del vértice, el valor predeterminado es "vertex" |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


