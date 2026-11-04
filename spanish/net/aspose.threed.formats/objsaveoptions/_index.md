---
title: "Clase ObjSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.ObjSaveOptions. Opciones de guardado para archivo obj wavefront."
type: docs
weight: 1370
url: /es/net/aspose.threed.formats/objsaveoptions/
---
## ObjSaveOptions class

Opciones de guardado para el archivo wavefront obj

```csharp
public class ObjSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ObjSaveOptions](objsaveoptions/)() | Constructor de `ObjSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/objsaveoptions/applyunitscale/) { get; set; } | Aplica [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) a la malla. El valor predeterminado es false. |
| [AxisSystem](../../aspose.threed.formats/objsaveoptions/axissystem/) { get; set; } | Obtiene o establece el sistema de ejes en el archivo exportado. |
| [EnableMaterials](../../aspose.threed.formats/objsaveoptions/enablematerials/) { get; set; } | Obtiene o establece si se importan/exportan materiales para cada objeto |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipCoordinateSystem](../../aspose.threed.formats/objsaveoptions/flipcoordinatesystem/) { get; set; } | Obtiene o establece si se invierte el sistema de coordenadas de los puntos de control/normal durante la importación/exportación. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [PointCloud](../../aspose.threed.formats/objsaveoptions/pointcloud/) { get; set; } | Obtiene o establece la bandera que indica si el exportador debe exportar la escena como nube de puntos (sin estructura topológica), el valor predeterminado es falso. |
| [SerializeW](../../aspose.threed.formats/objsaveoptions/serializew/) { get; set; } | Obtiene o establece si se serializa el componente W en la posición del vértice del modelo. |
| [Verbose](../../aspose.threed.formats/objsaveoptions/verbose/) { get; set; } | Obtiene o establece si se generan comentarios para cada sección. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


