---
title: UsdSaveOptions
second_title: Referencia de API de Aspose.3D para Java
description: Opciones de guardado para formatos USD/USDZ.
type: docs
weight: 200
url: /es/java/com.aspose.threed/usdsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class UsdSaveOptions extends SaveOptions
```

Opciones de guardado para formatos USD/USDZ.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [UsdSaveOptions()](#UsdSaveOptions--) | Inicializa una nueva [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) con el formato [FileFormat.USD](../../com.aspose.threed/fileformat\#USD) |
| [UsdSaveOptions(FileFormat fileFormat)](#UsdSaveOptions-com.aspose.threed.FileFormat-) | Inicializa una nueva [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) con el formato USD/USDZ especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Obtiene la codificación predeterminada para archivos de texto. |
| [getExportMetaData()](#getExportMetaData--) | Exporta las propiedades del nodo a través del campo customData de USD. |
| [getExportTextures()](#getExportTextures--) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [getFileFormat()](#getFileFormat--) | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [getFileName()](#getFileName--) | El nombre de archivo de la escena de exportación/importación. |
| [getFileSystem()](#getFileSystem--) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtiene la clase fábrica para FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [getMaterialConverter()](#getMaterialConverter--) | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador USD convertirá automáticamente el material estándar a material PBR. |
| [getPrimitiveToMesh()](#getPrimitiveToMesh--) | Convierte las entidades primitivas a malla durante la exportación. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Establece la codificación predeterminada para archivos de texto. |
| [setExportMetaData(boolean value)](#setExportMetaData-boolean-) | Exporta las propiedades del nodo a través del campo customData de USD. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [setFileName(String value)](#setFileName-java.lang.String-) | El nombre de archivo de la escena de exportación/importación. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Establece la clase fábrica para FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador USD convertirá automáticamente el material estándar a material PBR. |
| [setPrimitiveToMesh(boolean value)](#setPrimitiveToMesh-boolean-) | Convierte las entidades primitivas a malla durante la exportación. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UsdSaveOptions() {#UsdSaveOptions--}
```
public UsdSaveOptions()
```


Inicializa una nueva [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) con el formato [FileFormat.USD](../../com.aspose.threed/fileformat\#USD)

### UsdSaveOptions(FileFormat fileFormat) {#UsdSaveOptions-com.aspose.threed.FileFormat-}
```
public UsdSaveOptions(FileFormat fileFormat)
```


Inicializa una nueva [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) con el formato USD/USDZ especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileFormat | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Obtiene la codificación predeterminada para archivos de texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.

**Returns:**
java.nio.charset.Charset - la codificación predeterminada para archivos de texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.
### getExportMetaData() {#getExportMetaData--}
```
public boolean getExportMetaData()
```


Exporta las propiedades del nodo a través del campo customData de USD.

**Returns:**
boolean - Exportar las propiedades del nodo a través del campo customData de USD.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Intenta copiar las texturas usadas en la escena al directorio de salida.

**Returns:**
boolean - Intentar copiar las texturas usadas en la escena al directorio de salida.
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


Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador USD convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, USD exporter will automatically convert the standard material to PBR material. Default value is null
### getPrimitiveToMesh() {#getPrimitiveToMesh--}
```
public boolean getPrimitiveToMesh()
```


Convertir las entidades primitivas a malla durante la exportación. O codificar directamente las primitivas en el archivo de salida (se usará la definición de extensión de Aspose para primitivas no oficiales como Dish, Torus). El valor predeterminado es true.

**Returns:**
boolean - Convertir las entidades primitivas a malla durante la exportación. O codificar directamente las primitivas en el archivo de salida (se usará la definición de extensión de Aspose para primitivas no oficiales como Dish, Torus). El valor predeterminado es true.
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




### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset | Nuevo valor |

### setExportMetaData(boolean value) {#setExportMetaData-boolean-}
```
public void setExportMetaData(boolean value)
```


Exporta las propiedades del nodo a través del campo customData de USD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Intenta copiar las texturas usadas en la escena al directorio de salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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


Convertidor personalizado para convertir el material de la geometría a material PBR. Si no está asignado, el exportador USD convertirá automáticamente el material estándar a material PBR. El valor predeterminado es null.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nuevo valor |

### setPrimitiveToMesh(boolean value) {#setPrimitiveToMesh-boolean-}
```
public void setPrimitiveToMesh(boolean value)
```


Convertir las entidades primitivas a malla durante la exportación. O codificar directamente las primitivas en el archivo de salida (se usará la definición de extensión de Aspose para primitivas no oficiales como Dish, Torus). El valor predeterminado es true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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

