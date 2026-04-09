---
title: RvmSaveOptions
second_title: Referencia de API de Aspose.3D para Java
description: Opciones de guardado para el archivo RVM de Aveva PDMS.
type: docs
weight: 158
url: /es/java/com.aspose.threed/rvmsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class RvmSaveOptions extends SaveOptions
```

Opciones de guardado para el archivo Aveva PDMS RVM. **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RvmSaveOptions()](#RvmSaveOptions--) | Constructor de [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) |
| [RvmSaveOptions(FileContentType contentType)](#RvmSaveOptions-com.aspose.threed.FileContentType-) | Constructor de [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributeListFile()](#getAttributeListFile--) | Obtiene el nombre de archivo de la lista de atributos; el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null. |
| [getAttributePrefix()](#getAttributePrefix--) | Obtiene el prefijo de los atributos que se exportarán; la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. |
| [getAuthor()](#getAuthor--) | Información del autor, el valor predeterminado es '3d@aspose' |
| [getClass()](#getClass--) |  |
| [getCreationTime()](#getCreationTime--) | La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual |
| [getEncoding()](#getEncoding--) | Obtiene la codificación predeterminada para archivos de texto. |
| [getExportAttributes()](#getExportAttributes--) | Obtiene si se debe exportar la lista de atributos a un archivo .att externo, el valor predeterminado es false. |
| [getExportTextures()](#getExportTextures--) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [getFileFormat()](#getFileFormat--) | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [getFileName()](#getFileName--) | El nombre de archivo de la escena de exportación/importación. |
| [getFileNote()](#getFileNote--) | Nota del archivo en el encabezado del archivo. |
| [getFileSystem()](#getFileSystem--) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtiene la clase fábrica para FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributeListFile(String value)](#setAttributeListFile-java.lang.String-) | Establece el nombre de archivo de la lista de atributos, el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null. |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Establece el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Información del autor, el valor predeterminado es '3d@aspose' |
| [setCreationTime(String value)](#setCreationTime-java.lang.String-) | La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Establece la codificación predeterminada para archivos de texto. |
| [setExportAttributes(boolean value)](#setExportAttributes-boolean-) | Establece si se debe exportar la lista de atributos a un archivo .att externo, el valor predeterminado es false. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [setFileName(String value)](#setFileName-java.lang.String-) | El nombre de archivo de la escena de exportación/importación. |
| [setFileNote(String value)](#setFileNote-java.lang.String-) | Nota del archivo en el encabezado del archivo. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Establece la clase fábrica para FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmSaveOptions() {#RvmSaveOptions--}
```
public RvmSaveOptions()
```


Constructor de [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions)

### RvmSaveOptions(FileContentType contentType) {#RvmSaveOptions-com.aspose.threed.FileContentType-}
```
public RvmSaveOptions(FileContentType contentType)
```


Constructor de [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | ¿Archivo RVM de texto o binario? |

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
### getAttributeListFile() {#getAttributeListFile--}
```
public String getAttributeListFile()
```


Obtiene el nombre de archivo de la lista de atributos; el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null.

**Returns:**
java.lang.String - el nombre de archivo de la lista de atributos, el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null. **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


Obtiene el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. Por ejemplo, si una propiedad es rvm:Refno=345, el atributo exportado será Refno = 345, el prefijo se elimina.

**Returns:**
java.lang.String - el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. Por ejemplo, si una propiedad es rvm:Refno=345, el atributo exportado será Refno = 345, el prefijo se elimina. **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Información del autor, el valor predeterminado es '3d@aspose'

**Returns:**
java.lang.String - Información del autor, el valor predeterminado es '3d@aspose' **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationTime() {#getCreationTime--}
```
public String getCreationTime()
```


La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual

**Returns:**
java.lang.String - La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Obtiene la codificación predeterminada para archivos de texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.

**Returns:**
java.nio.charset.Charset - la codificación predeterminada para archivos de texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.
### getExportAttributes() {#getExportAttributes--}
```
public boolean getExportAttributes()
```


Obtiene si se debe exportar la lista de atributos a un archivo .att externo, el valor predeterminado es false.

**Returns:**
boolean - si se debe exportar la lista de atributos a un archivo .att externo, el valor predeterminado es false. **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
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
### getFileNote() {#getFileNote--}
```
public String getFileNote()
```


Nota del archivo en el encabezado del archivo.

**Returns:**
java.lang.String - Nota del archivo en el encabezado del archivo. **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
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




### setAttributeListFile(String value) {#setAttributeListFile-java.lang.String-}
```
public void setAttributeListFile(String value)
```


Establece el nombre de archivo de la lista de atributos, el exportador generará un nombre basado en el nombre del archivo .rvm cuando esta propiedad no esté definida, el valor predeterminado es null.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Nuevo valor **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


Establece el prefijo de los atributos que se exportarán, la propiedad exportada no contendrá prefijo, las propiedades personalizadas con un prefijo diferente no se exportarán, el valor predeterminado es 'rvm:'. Por ejemplo, si una propiedad es rvm:Refno=345, el atributo exportado será Refno = 345, el prefijo se elimina.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Nuevo valor **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Información del autor, el valor predeterminado es '3d@aspose'

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Nuevo valor **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setCreationTime(String value) {#setCreationTime-java.lang.String-}
```
public void setCreationTime(String value)
```


La marca de tiempo que exportó este archivo, el valor predeterminado es la hora actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es null, lo que significa que el importador/exportador decidirá qué codificación usar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset | Nuevo valor |

### setExportAttributes(boolean value) {#setExportAttributes-boolean-}
```
public void setExportAttributes(boolean value)
```


Establece si se debe exportar la lista de atributos a un archivo .att externo, el valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Nuevo valor **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

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

### setFileNote(String value) {#setFileNote-java.lang.String-}
```
public void setFileNote(String value)
```


Nota del archivo en el encabezado del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Nuevo valor **Ejemplo:** El siguiente código muestra cómo exportar atributos en RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

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

