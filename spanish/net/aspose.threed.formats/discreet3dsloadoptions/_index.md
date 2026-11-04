---
title: "Clase Discreet3dsLoadOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.Discreet3dsLoadOptions. Opciones de carga para archivo 3DS"
type: docs
weight: 1120
url: /es/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

Opciones de carga para archivo 3DS.

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions/)() | Constructor de `Discreet3dsLoadOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform/) { get; set; } | Obtiene o establece si se debe usar la transformación definida en el primer fotograma de la pista de animación. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem/) { get; set; } | Obtiene o establece la inversión del sistema de coordenadas de los puntos de control/normal durante la importación/exportación. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor/) { get; set; } | Un archivo 3ds puede contener el color original y el color corregido por gamma para el mismo atributo; al establecer esto en true se usará el color corregido por gamma si es posible, de lo contrario Aspose.3D intentará usar el color original. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |

### Ver también

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


