---
title: "Clase ObjLoadOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.ObjLoadOptions. Opciones de carga para wavefront obj"
type: docs
weight: 1360
url: /es/net/aspose.threed.formats/objloadoptions/
---
## ObjLoadOptions class

Opciones de carga para wavefront obj

```csharp
public class ObjLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ObjLoadOptions](objloadoptions/)() | Constructor de `ObjLoadOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EnableMaterials](../../aspose.threed.formats/objloadoptions/enablematerials/) { get; set; } | Obtiene o establece si se importan materiales para cada objeto |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objloadoptions/flipcoordinatesystem/) { get; set; } | Obtiene o establece si se invierte el sistema de coordenadas de los puntos de control/normal durante la importación |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [NormalizeNormal](../../aspose.threed.formats/objloadoptions/normalizenormal/) { get; set; } | Obtiene o establece si se normaliza el vector normal durante la carga. El valor predeterminado es verdadero. |
| [Scale](../../aspose.threed.formats/objloadoptions/scale/) { get; set; } | Escalas en los ejes x/y/z, el valor predeterminado es 1.0 |

### Ver también

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


