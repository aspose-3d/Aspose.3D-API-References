---
title: "Clase UsdSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.UsdSaveOptions. Opciones de guardado para los formatos USD/USDZ"
type: docs
weight: 1540
url: /es/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

Opciones de guardado para los formatos USD/USDZ.

```csharp
public class UsdSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | Inicializa una nueva `UsdSaveOptions` con el formato [`USD`](../../aspose.threed/fileformat/usd/) |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | Inicializa una nueva `UsdSaveOptions` con el formato USD/USDZ especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | Exporta las propiedades del nodo a través del campo customData de USD. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador USD convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null. |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | Convierte las entidades primitivas a malla durante la exportación. O codifica directamente las primitivas al archivo de salida (se usará la definición de extensión de Aspose para primitivas no oficiales como Dish, Torus). El valor predeterminado es true. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


