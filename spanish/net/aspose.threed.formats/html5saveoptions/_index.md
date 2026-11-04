---
title: "Clase Html5SaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.Html5SaveOptions. Opciones de guardado para HTML5"
type: docs
weight: 1290
url: /es/net/aspose.threed.formats/html5saveoptions/
---
## Html5SaveOptions class

Opciones de guardado para HTML5

```csharp
public class Html5SaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Html5SaveOptions](html5saveoptions/)() | Constructor de `Html5SaveOptions` con todos los ajustes predeterminados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CameraPosition](../../aspose.threed.formats/html5saveoptions/cameraposition/) { get; set; } | Obtiene o establece la posición inicial de la cámara, el valor predeterminado es (10, 10, 10) |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FarPlane](../../aspose.threed.formats/html5saveoptions/farplane/) { get; set; } | Obtiene o establece el plano lejano de la cámara, el valor predeterminado es 1000. |
| [FieldOfView](../../aspose.threed.formats/html5saveoptions/fieldofview/) { get; set; } | Obtiene o establece el campo de visión, el valor predeterminado es 45, medido en grados. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [LookAt](../../aspose.threed.formats/html5saveoptions/lookat/) { get; set; } | Obtiene o establece la posición de mirada predeterminada, el valor predeterminado es (0, 0, 0) |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [NearPlane](../../aspose.threed.formats/html5saveoptions/nearplane/) { get; set; } | Obtiene o establece el plano cercano de la cámara, el valor predeterminado es 1 |
| [OrientationBox](../../aspose.threed.formats/html5saveoptions/orientationbox/) { get; set; } | Muestra una caja de orientación. El valor predeterminado es verdadero. |
| [ShowGrid](../../aspose.threed.formats/html5saveoptions/showgrid/) { get; set; } | Muestra una cuadrícula en la escena. El valor predeterminado es verdadero. |
| [ShowRulers](../../aspose.threed.formats/html5saveoptions/showrulers/) { get; set; } | Muestra reglas de los ejes x/y/z en la escena para medir el modelo. El valor predeterminado es falso. |
| [ShowUI](../../aspose.threed.formats/html5saveoptions/showui/) { get; set; } | Muestra una interfaz simple en la escena. El valor predeterminado es verdadero. |
| [UpVector](../../aspose.threed.formats/html5saveoptions/upvector/) { get; set; } | Obtiene o establece el vector ascendente, el valor puede ser "x"/"y"/"z", el valor predeterminado es "y" |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


