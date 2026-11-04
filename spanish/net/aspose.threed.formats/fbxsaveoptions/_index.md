---
title: "Clase FbxSaveOptions"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Formats.FbxSaveOptions. Opciones de guardado para archivo Fbx"
type: docs
weight: 1180
url: /es/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Opciones de guardado para el archivo Fbx.

```csharp
public class FbxSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | Inicializa un `FbxSaveOptions` usando la última versión compatible. |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | Inicializa un `FbxSaveOptions` |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | Obtiene o establece si incrustar la textura en el archivo de salida final. FBX Exporter intentará encontrar los datos sin procesar de la textura desde [`FileSystem`](../ioconfig/filesystem/), y incrustará el archivo en el archivo FBX final. El valor predeterminado es falso. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | Compresión de datos binarios grandes en el archivo FBX (p. ej., datos de animación, puntos de control, datos de elementos de v\u00e9rtice, índices), el valor predeterminado es verdadero. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | Obtiene o establece si se exportan propiedades de material heredadas, usadas para compatibilidad retroactiva. Esta opción está activada por defecto. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | El nombre de archivo de la escena exportada/importada. Es opcional, pero útil al serializar recursos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permite al usuario gestionar cómo manejar las dependencias externas durante la carga/guardado. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | Obtiene o establece si se reutiliza datos de curva repetidos incrementando el recuento de referencias del último dato |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | Obtiene o establece si siempre se genera un [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/) para geometrías si el nodo adjunto contiene materiales. Esto está desactivado por defecto. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Algunos archivos, como OBJ, dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | Reutiliza la malla para los primitivas con los mismos parámetros, lo que reducirá significativamente el tamaño del output FBX cuya escena fue construida por un gran conjunto de formas primitivas (como importadas de archivos CAD). El valor predeterminado es falso |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | Obtiene o establece si se genera una instancia de Video para [`Texture`](../../aspose.threed.shading/texture/) al exportar como FBX. |

### Ver también

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


