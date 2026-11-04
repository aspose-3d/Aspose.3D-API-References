---
title: "Clase StlSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.StlSaveOptions. Opciones de guardado para STL"
type: docs
weight: 1510
url: /es/net/aspose.threed.formats/stlsaveoptions/
---
## StlSaveOptions class

Opciones de guardado para STL

```csharp
public class StlSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StlSaveOptions](stlsaveoptions/#constructor)() | Inicializa una nueva instancia de `StlSaveOptions`. |
| [StlSaveOptions](stlsaveoptions/#constructor_1)(FileContentType) | Inicializa una nueva instancia de `StlSaveOptions`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/stlsaveoptions/axissystem/) { get; set; } | Obtiene o establece el sistema de ejes en el archivo stl exportado. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/stlsaveoptions/flipcoordinatesystem/) { get; set; } | Obtiene o establece si se invierte el sistema de coordenadas de los puntos de control/normal durante la exportación. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


