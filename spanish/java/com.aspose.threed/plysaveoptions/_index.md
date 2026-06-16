---
title: PlySaveOptions
second_title: Referencia de API de Aspose.3D para Java
description: Opciones de guardado para exportar la escena como archivo PLY.
type: docs
weight: 131
url: /es/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

Opciones de guardado para exportar la escena como archivo PLY.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | Constructor de [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | Constructor de [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | Obtiene el sistema de ejes en el archivo stl exportado. |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | Los nombres de los componentes para el color del vértice, el valor predeterminado es ("red", "green", "blue") |
| [getEncoding()](#getEncoding--) | Obtiene la codificación predeterminada para archivos de texto. |
| [getExportTextures()](#getExportTextures--) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [getFaceElement()](#getFaceElement--) | El nombre del elemento para los datos de la cara, el valor predeterminado es "face" |
| [getFaceProperty()](#getFaceProperty--) | El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex\_index" |
| [getFileFormat()](#getFileFormat--) | Obtiene el formato de archivo especificado en la opción actual de Guardar/Cargar. |
| [getFileName()](#getFileName--) | El nombre de archivo de la escena de exportación/importación. |
| [getFileSystem()](#getFileSystem--) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtiene la clase fábrica para FileSystem. |
| [getFlipCoordinate()](#getFlipCoordinate--) | Invertir la coordenada al guardar la escena, el valor predeterminado es true |
| [getLookupPaths()](#getLookupPaths--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [getNormalComponents()](#getNormalComponents--) | Los nombres de los componentes para los datos normales, el valor predeterminado es ("nx", "ny", "nz") |
| [getPointCloud()](#getPointCloud--) | Exportar la escena como nube de puntos, el valor predeterminado es false. |
| [getPositionComponents()](#getPositionComponents--) | Los nombres de los componentes para los datos de posición, el valor predeterminado es ("x", "y", "z") |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | Los nombres de los componentes para los datos de coordenadas de textura, el valor predeterminado es ("u", "v") |
| [getVertexElement()](#getVertexElement--) | El nombre del elemento para los datos del v\u00e9rtice, el valor predeterminado es "vertex" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Establece el sistema de ejes en el archivo STL exportado. |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Los nombres de los componentes para el color del vértice, el valor predeterminado es ("red", "green", "blue") |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Establece la codificación predeterminada para archivos de texto. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Intenta copiar las texturas usadas en la escena al directorio de salida. |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | El nombre del elemento para los datos de la cara, el valor predeterminado es "face" |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex\_index" |
| [setFileName(String value)](#setFileName-java.lang.String-) | El nombre de archivo de la escena de exportación/importación. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Permite al usuario manejar cómo gestionar las dependencias externas durante la carga/guardado. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Establece la clase fábrica para FileSystem. |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | Invertir la coordenada al guardar la escena, el valor predeterminado es true |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Algunos archivos como OBJ dependen de archivos externos; las rutas de búsqueda permitirán a Aspose.3D buscar el archivo externo para cargarlo. |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Los nombres de los componentes para los datos normales, el valor predeterminado es ("nx", "ny", "nz") |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | Exportar la escena como nube de puntos, el valor predeterminado es false. |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Los nombres de los componentes para los datos de posición, el valor predeterminado es ("x", "y", "z") |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | Los nombres de los componentes para los datos de coordenadas de textura, el valor predeterminado es ("u", "v") |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | El nombre del elemento para los datos del v\u00e9rtice, el valor predeterminado es "vertex" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


Constructor de [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


Constructor de [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Obtiene el sistema de ejes en el archivo stl exportado.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported stl file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponents() {#getColorComponents--}
```
public Tuple_3<String,String,String> getColorComponents()
```


Los nombres de los componentes para el color del vértice, el valor predeterminado es ("red", "green", "blue")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Los nombres de los componentes para el color del v\u00e9rtice, el valor predeterminado es ("red", "green", "blue")
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
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


El nombre del elemento para los datos de la cara, el valor predeterminado es "face"

**Returns:**
java.lang.String - El nombre del elemento para los datos de la cara, el valor predeterminado es "face"
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex\_index"

**Returns:**
java.lang.String - El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex\_index"
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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


Invertir la coordenada al guardar la escena, el valor predeterminado es true

**Returns:**
boolean - Invertir la coordenada al guardar la escena, el valor predeterminado es true
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
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


Los nombres de los componentes para los datos normales, el valor predeterminado es ("nx", "ny", "nz")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Los nombres de los componentes para los datos normales, el valor predeterminado es ("nx", "ny", "nz")
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


Exportar la escena como nube de puntos, el valor predeterminado es false.

**Returns:**
boolean - Exportar la escena como nube de puntos, el valor predeterminado es false.
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


Los nombres de los componentes para los datos de posición, el valor predeterminado es ("x", "y", "z")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Los nombres de los componentes para los datos de posici\u00f3n, el valor predeterminado es ("x", "y", "z")
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


Los nombres de los componentes para los datos de coordenadas de textura, el valor predeterminado es ("u", "v")

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - Los nombres de los componentes para los datos de coordenadas de textura, el valor predeterminado es ("u", "v")
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


El nombre del elemento para los datos del v\u00e9rtice, el valor predeterminado es "vertex"

**Returns:**
java.lang.String - El nombre del elemento para los datos del v\u00e9rtice, el valor predeterminado es "vertex"
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




### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Establece el sistema de ejes en el archivo STL exportado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nuevo valor **Observaciones:** FlipCoordinateSystem debe estar habilitado para utilizar esta funci\u00f3n. |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


Los nombres de los componentes para el color del vértice, el valor predeterminado es ("red", "green", "blue")

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nuevo valor |

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

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


El nombre del elemento para los datos de la cara, el valor predeterminado es "face"

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


El nombre de la propiedad para los datos de la cara, el valor predeterminado es "vertex\_index"

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


Invertir la coordenada al guardar la escena, el valor predeterminado es true

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


Los nombres de los componentes para los datos normales, el valor predeterminado es ("nx", "ny", "nz")

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nuevo valor |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


Exportar la escena como nube de puntos, el valor predeterminado es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


Los nombres de los componentes para los datos de posición, el valor predeterminado es ("x", "y", "z")

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nuevo valor |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


Los nombres de los componentes para los datos de coordenadas de textura, el valor predeterminado es ("u", "v")

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | Nuevo valor |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


El nombre del elemento para los datos del v\u00e9rtice, el valor predeterminado es "vertex"

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

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

