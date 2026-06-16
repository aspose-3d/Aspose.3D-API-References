---
title: GltfSaveOptions
second_title: Referencia de API de Aspose.3D para Java
description: Opciones de guardado para el formato glTF.
type: docs
weight: 74
url: /es/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Opciones de guardado para el formato glTF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Constructor de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Constructor de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Aplicar [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) a la malla. |
| [getBufferFile()](#getBufferFile--) | El nombre de archivo del archivo de búfer externo utilizado para almacenar datos binarios. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Obtiene si se debe habilitar la compresión draco |
| [getEmbedAssets()](#getEmbedAssets--) | Incrusta todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false. |
| [getEncoding()](#getEncoding--) | Obtiene la codificación predeterminada para archivos de texto. |
| [getExportTextures()](#getExportTextures--) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Utiliza un codificador draco externo para acelerar la velocidad de compresión draco. |
| [getFallbackNormal()](#getFallbackNormal--) | Cuando el exportador GLTF2 detecta una normal inválida, esto se usará en lugar de su valor original para eludir la validación. |
| [getFileFormat()](#getFileFormat--) | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [getFileName()](#getFileName--) | El nombre de archivo de la escena de exportación/importación. |
| [getFileSystem()](#getFileSystem--) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtiene la clase fábrica para FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Invierte el componente v(t) de la coordenada de textura, el valor predeterminado es true. |
| [getImageFormat()](#getImageFormat--) | El glTF estándar solo admite PNG/JPG como su formato de textura, esta opción guiará cómo Aspose.3D convierte las imágenes no estándar al formato compatible durante la exportación. |
| [getLookupPaths()](#getLookupPaths--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [getMaterialConverter()](#getMaterialConverter--) | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no se asigna, el exportador glTF 2.0 convertirá automáticamente el material estándar a material PBR. |
| [getPrettyPrint()](#getPrettyPrint--) | El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false. |
| [getSaveExtras()](#getSaveExtras--) | Guarde las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo glTF generado. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Serialice los materiales usando extensiones de material comunes KHR, el valor predeterminado es false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Aplicar [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) a la malla. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | El nombre de archivo del archivo de búfer externo utilizado para almacenar datos binarios. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Establece si se habilita la compresión draco. |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Incrusta todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Establece la codificación predeterminada para archivos de texto. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Utiliza un codificador draco externo para acelerar la velocidad de compresión draco. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | Cuando el exportador GLTF2 detecta una normal inválida, esto se usará en lugar de su valor original para eludir la validación. |
| [setFileName(String value)](#setFileName-java.lang.String-) | El nombre de archivo de la escena de exportación/importación. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Establece la clase fábrica para FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Invierte el componente v(t) de la coordenada de textura, el valor predeterminado es true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | El glTF estándar solo admite PNG/JPG como su formato de textura, esta opción guiará cómo Aspose.3D convierte las imágenes no estándar al formato compatible durante la exportación. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no se asigna, el exportador glTF 2.0 convertirá automáticamente el material estándar a material PBR. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false. |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Guarde las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo glTF generado. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Serialice los materiales usando extensiones de material comunes KHR, el valor predeterminado es false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Constructor de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Constructor de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Aplicar [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) a la malla. El valor predeterminado es false.

**Returns:**
boolean - Aplicar [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) a la malla. El valor predeterminado es false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


El nombre de archivo del búfer externo utilizado para almacenar datos binarios. Si no se especifica este archivo, Aspose.3D generará un nombre para usted. Esto se ignora al exportar glTF en modo binario.

**Returns:**
java.lang.String - El nombre de archivo del búfer externo utilizado para almacenar datos binarios. Si no se especifica este archivo, Aspose.3D generará un nombre para usted. Esto se ignora al exportar glTF en modo binario.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDracoCompression() {#getDracoCompression--}
```
public boolean getDracoCompression()
```


Obtiene si se debe habilitar la compresión draco

**Returns:**
boolean - si se habilita la compresión draco
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Incrusta todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false.

**Returns:**
boolean - Incruste todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Obtiene la codificación predeterminada para archivos de texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.

**Returns:**
java.nio.charset.Charset - la codificación predeterminada para archivos de texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Intenta copiar las texturas usadas en la escena al directorio de salida.

**Returns:**
boolean - Intentar copiar las texturas usadas en la escena al directorio de salida.
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Utiliza un codificador draco externo para acelerar la velocidad de compresión draco.

**Returns:**
java.lang.String - Use un codificador draco externo para acelerar la velocidad de compresión draco. **Remarks:** Aspose.3D creará un nuevo subproceso para codificar la malla al formato draco, úselo bajo su propio riesgo.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


Cuando el exportador GLTF2 detecta una normal inválida, esto se usará en lugar de su valor original para evitar la validación. El valor predeterminado es (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


El nombre de archivo de la escena de exportación/importación. Esto es opcional, pero útil al serializar recursos externos como el material de OBJ.

**Returns:**
java.lang.String - El nombre de archivo de la escena de exportación/importación. Esto es opcional, pero útil al serializar recursos externos como el material de OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Y también puedes usar tu propia implementación.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


Obtiene la clase de fábrica para FileSystem. La fábrica predeterminada creará com.aspose.threed.LocalFileSystem, que no es adecuada para entornos de servidor.

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


Invierte el componente v(t) de la coordenada de textura, el valor predeterminado es true.

**Returns:**
boolean - Invierta el componente v(t) de la coordenada de textura, el valor predeterminado es true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


El glTF estándar solo admite PNG/JPG como su formato de textura, esta opción guiará cómo Aspose.3D convierte las imágenes no estándar al formato compatible durante la exportación. El valor predeterminado es [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo.

**Returns:**
java.util.ArrayList<java.lang.String> - Algunos archivos como OBJ dependen de archivos externos, las rutas de búsqueda permitirán a Aspose.3D buscar archivos externos para cargar. **Ejemplo:** El siguiente código muestra cómo especificar manualmente las texturas de búsqueda, para que el importador pueda encontrarlas

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


Convertidor personalizado para convertir el material de la geometría a material PBR. Si no se asigna, el exportador glTF 2.0 convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null. Esta propiedad se usa al exportar una escena a un archivo glTF 2.0.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false.

**Returns:**
boolean - El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false.
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Guarde las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo glTF generado. Esto es útil para proporcionar datos específicos de la aplicación. El valor predeterminado es false.

**Returns:**
boolean - Guarde las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo GLTF generado. Esto es útil para proporcionar datos específicos de la aplicación. El valor predeterminado es false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Serialice los materiales usando extensiones de material comunes KHR, el valor predeterminado es false. Establecer esto en false hará que Aspose.3D exporte un conjunto de sombreadores de vértice/fragmento si [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - Serialice los materiales usando extensiones de material comunes KHR, el valor predeterminado es false. Establecer esto en false hará que Aspose.3D exporte un conjunto de sombreadores de vértice/fragmento si [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** Esta propiedad solo funciona para glTF 1.0
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setApplyUnitScale(boolean value) {#setApplyUnitScale-boolean-}
```
public void setApplyUnitScale(boolean value)
```


Aplicar [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) a la malla. El valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


El nombre de archivo del búfer externo utilizado para almacenar datos binarios. Si no se especifica este archivo, Aspose.3D generará un nombre para usted. Esto se ignora al exportar glTF en modo binario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Establece si se habilita la compresión draco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Incrusta todos los recursos externos como base64 en un solo archivo en modo ASCII, el valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset | Nuevo valor |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Intenta copiar las texturas usadas en la escena al directorio de salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Utiliza un codificador draco externo para acelerar la velocidad de compresión draco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor **Remarks:** Aspose.3D creará un nuevo subproceso para codificar la malla al formato draco, úselo bajo su propio riesgo. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


Cuando el exportador GLTF2 detecta una normal inválida, esto se usará en lugar de su valor original para evitar la validación. El valor predeterminado es (0, 1, 0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


El nombre de archivo de la escena de exportación/importación. Esto es opcional, pero útil al serializar recursos externos como el material de OBJ.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nuevo valor **Ejemplo:** El FileSystem predeterminado es LocalFileSystem, no es seguro en entornos como el lado del servidor, pero puedes sobrescribir el acceso al sistema de archivos especificando una implementación diferente. Aspose.3D proporciona diferentes implementaciones de FileSystem como: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Y también puedes usar tu propia implementación.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


Establece la clase de fábrica para FileSystem. La fábrica predeterminada creará com.aspose.threed.LocalFileSystem, que no es adecuada para entornos de servidor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nuevo valor **Ejemplo:** El FileSystem predeterminado en SaveOptions/LoadOptions es un sistema de archivos basado en directorios. Puedes sobrescribir la implementación predeterminada especificándolo a través de IOConfig.FileSystemFactory: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


Invierte el componente v(t) de la coordenada de textura, el valor predeterminado es true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


El glTF estándar solo admite PNG/JPG como su formato de textura, esta opción guiará cómo Aspose.3D convierte las imágenes no estándar al formato compatible durante la exportación. El valor predeterminado es [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Nuevo valor |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.util.ArrayList<java.lang.String> | Nuevo valor **Ejemplo:** El siguiente código muestra cómo especificar manualmente las texturas de búsqueda, para que el importador pueda encontrarlas |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


Convertidor personalizado para convertir el material de la geometría a material PBR. Si no se asigna, el exportador glTF 2.0 convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null. Esta propiedad se usa al exportar una escena a un archivo glTF 2.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nuevo valor |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


El contenido JSON del archivo GLTF está indentado para la lectura humana, el valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Guarde las propiedades dinámicas del objeto de escena en campos 'extra' en el archivo glTF generado. Esto es útil para proporcionar datos específicos de la aplicación. El valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Serialice los materiales usando extensiones de material comunes KHR, el valor predeterminado es false. Establecer esto en false hará que Aspose.3D exporte un conjunto de sombreadores de vértice/fragmento si [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor **Remarks:** Esta propiedad solo funciona para glTF 1.0 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

