---
title: "Clase GltfSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.GltfSaveOptions. Opciones de guardado para el formato glTF"
type: docs
weight: 1280
url: /es/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

Opciones de guardado para el formato glTF.

```csharp
public class GltfSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | Constructor de `GltfSaveOptions` |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | Constructor de `GltfSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | Aplica [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) a la malla. El valor predeterminado es false. |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | El nombre de archivo del archivo de búfer externo utilizado para almacenar datos binarios. Si este archivo no se especifica, Aspose.3D generará un nombre para usted. Esto se ignora al exportar glTF en modo binario. |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | Obtiene o establece si se habilita la compresión draco |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | Incrusta todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | Utiliza un codificador draco externo para acelerar la velocidad de compresión draco. |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | Cuando el exportador GLTF2 detecta una normal inválida, esto se usará en lugar de su valor original para omitir la validación. El valor predeterminado es (0, 1, 0). |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | Invierte el componente v(t) de la coordenada de textura, el valor predeterminado es true. |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | El glTF estándar solo admite PNG/JPG como su formato de textura, esta opción guiará cómo Aspose.3D convierte las imágenes no estándar al formato compatible durante la exportación. El valor predeterminado es Png. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador glTF 2.0 convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null. Esta propiedad se usa al exportar una escena a un archivo glTF 2.0. |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false. |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | Guarda las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo glTF generado. Esto es útil para proporcionar datos específicos de la aplicación. El valor predeterminado es false. |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | Serializa materiales usando extensiones de material comunes KHR, el valor predeterminado es false. Establecer esto en false hará que Aspose.3D exporte un conjunto de shaders de vértice/fragmento si ExportShaders |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


