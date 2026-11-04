---
title: "Clase Discreet3dsSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.Discreet3dsSaveOptions. Opciones de guardado para archivos 3DS"
type: docs
weight: 1130
url: /es/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Opciones de guardado para archivo 3DS.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | Constructor de `Discreet3dsSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | El contador usado para generar nuevos nombres para nombres duplicados, el valor predeterminado es 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | El formato del contador duplicado, el valor predeterminado es una cadena vacía. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | El separador entre el nombre del objeto y el contador duplicado, el valor predeterminado es "_". Cuando la escena contiene objetos que usan el mismo nombre, el exportador 3DS de Aspose.3D generará un nombre diferente para el objeto. Por ejemplo, hay dos nodos llamados "Box", el primer nodo tendrá el nombre "Box", y el segundo nodo obtendrá un nuevo nombre "Box_2" usando la configuración predeterminada. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | Obtiene o establece si se exportan todas las cámaras en la escena. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | Obtiene o establece si se exportan todas las luces en la escena. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | Obtiene o establece la inversión del sistema de coordenadas de los puntos de control/normal durante la importación/exportación. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | Un archivo 3ds puede contener el color original y el color corregido por gamma para el mismo atributo; al establecer esto en true se usará el color corregido por gamma si es posible, de lo contrario Aspose.3D intentará usar el color original. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | Si esto es true, el archivo 3ds generado usará color de alta precisión, lo que significa que cada canal de rojo/verde/azul está en punto flotante de 32 bits. De lo contrario, el archivo generado usará color de 24 bits, cada canal usa un byte de 8 bits. El valor predeterminado es false, porque no todas las aplicaciones admiten el color de alta precisión. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | Obtiene o establece la escala maestra utilizada al exportar. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


