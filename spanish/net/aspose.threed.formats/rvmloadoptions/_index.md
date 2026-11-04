---
title: "Clase RvmLoadOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.RvmLoadOptions. Opciones de carga para el archivo RVM de AVEVA Plant Design Management Systems."
type: docs
weight: 1470
url: /es/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

Opciones de carga para el archivo RVM del Sistema de Gestión de Diseño de Planta AVEVA.

```csharp
public class RvmLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | Construye una instancia de `RvmLoadOptions` |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | Construye una instancia de `RvmLoadOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | Obtiene o establece el prefijo de los atributos que fueron definidos en archivos de atributos externos. El prefijo se usa para evitar conflictos de nombres, el valor predeterminado es "rvm:". |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | Centra la escena después de cargarla. |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | Obtiene o establece el número de segmentos radiales del cilindro, el valor predeterminado es 16. |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | Obtiene o establece el número de segmentos de latitud del dish, el valor predeterminado es 8. |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | Obtiene o establece el número de segmentos de longitud del dish, el valor predeterminado es 12. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | Genera materiales con colores aleatorios para cada objeto en la escena si la tabla de colores no se exporta dentro del archivo RVM. El valor predeterminado es true. |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | Obtiene o establece si se deben cargar los atributos desde un archivo de lista de atributos externo (.att/.attrib/.txt), el valor predeterminado es true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | Obtiene o establece el número de segmentos radiales del toro rectangular, el valor predeterminado es 20. |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | Obtiene o establece el número de segmentos tubulares del toro, el valor predeterminado es 20 |

## Ejemplos

El siguiente código muestra cómo personalizar los parámetros de teselado para geometrías primitivas importadas de un archivo RVM usando RvmLoadOptions.

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### Ver también

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


