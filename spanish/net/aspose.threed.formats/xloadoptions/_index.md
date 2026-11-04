---
title: "Clase XLoadOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.XLoadOptions. Las opciones de carga para archivos DirectX X"
type: docs
weight: 1550
url: /es/net/aspose.threed.formats/xloadoptions/
---
## XLoadOptions class

Las opciones de carga para archivos DirectX X.

```csharp
public class XLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XLoadOptions](xloadoptions/)(FileContentType) | Constructor de `XLoadOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/xloadoptions/flipcoordinatesystem/) { get; set; } | Invierte el sistema de coordenadas, esto es verdadero por defecto |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |

### Ver también

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


