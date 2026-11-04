---
title: "Clase FbxLoadOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.FbxLoadOptions. Opciones de carga para el formato Fbx"
type: docs
weight: 1170
url: /es/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Opciones de carga para el formato Fbx.

```csharp
public class FbxLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | Constructor de `FbxLoadOptions` |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | Constructor de `FbxLoadOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | Obtiene o establece si se habilita el modo compatible. El modo compatible intentará soportar definiciones FBX no estándar como materiales PBR exportados por Blender. El valor predeterminado es false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | Obtiene o establece si se conservan las propiedades incorporadas en GlobalSettings que tienen un reemplazo de propiedad nativa en [`AssetInfo`](../../aspose.threed/assetinfo/). Establezca esto en true si desea todas las propiedades en GlobalSettings. El valor predeterminado es false |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |

### Ver también

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


