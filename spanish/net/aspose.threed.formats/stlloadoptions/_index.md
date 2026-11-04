---
title: "Clase StlLoadOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.StlLoadOptions. Opciones de carga para STL"
type: docs
weight: 1500
url: /es/net/aspose.threed.formats/stlloadoptions/
---
## StlLoadOptions class

Opciones de carga para STL

```csharp
public class StlLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StlLoadOptions](stlloadoptions/#constructor)() | Inicializa una nueva instancia de `StlLoadOptions`. |
| [StlLoadOptions](stlloadoptions/#constructor_1)(FileContentType) | Inicializa una nueva instancia de `StlLoadOptions`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [RecalculateNormal](../../aspose.threed.formats/stlloadoptions/recalculatenormal/) { get; set; } | Ignora los datos de normales almacenados en el archivo STL y recalcula los datos de normales basándose en la posición de los vértices. El valor predeterminado es false. |

### Ver también

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


