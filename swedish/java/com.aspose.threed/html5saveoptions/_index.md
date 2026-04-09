---
title: Html5SaveOptions
second_title: Aspose.3D for Java API-referens
description: Spara alternativ för HTML5
type: docs
weight: 80
url: /sv/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

Spara alternativ för HTML5
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | Konstruktor för [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) med alla standardinställningar. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Hämtar kamerans initiala position, standardvärdet är (10, 10, 10) |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Hämtar standardkodningen för textbaserade filer. |
| [getExportTextures()](#getExportTextures--) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [getFarPlane()](#getFarPlane--) | Hämtar kamerans fjärrplan, standardvärdet är 1000. |
| [getFieldOfView()](#getFieldOfView--) | Hämtar synfältet, standardvärdet är 45, mätt i grader. |
| [getFileFormat()](#getFileFormat--) | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |
| [getFileName()](#getFileName--) | Filnamnet för den exporterande/importerande scenen. |
| [getFileSystem()](#getFileSystem--) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Hämtar fabriksklassen för FileSystem. |
| [getLookAt()](#getLookAt--) | Hämtar standard‑blickposition, standardvärdet är (0, 0, 0) |
| [getLookupPaths()](#getLookupPaths--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [getNearPlane()](#getNearPlane--) | Hämtar kamerans närplan, standardvärdet är 1 |
| [getOrientationBox()](#getOrientationBox--) | Visa en orienteringsruta. |
| [getShowGrid()](#getShowGrid--) | Visa ett rutnät i scenen. |
| [getShowRulers()](#getShowRulers--) | Visa linjaler för x/y/z-axlar i scenen för att mäta modellen. |
| [getShowUI()](#getShowUI--) | Visa ett enkelt användargränssnitt i scenen. |
| [getUpVector()](#getUpVector--) | Hämtar uppvektorn, värdet kan vara "x"/"y"/"z", standardvärdet är "y" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | Ställer in den initiala positionen för kameran, standardvärdet är (10, 10, 10) |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ställer in standardkodningen för textbaserade filer. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [setFarPlane(double value)](#setFarPlane-double-) | Ställer in den avlägsna planet för kameran, standardvärdet är 1000. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Ställer in synfältet, standardvärdet är 45, mätt i grader. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Filnamnet för den exporterande/importerande scenen. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ställer in fabriksklassen för FileSystem. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Ställer in standardpositionen för blick, standardvärdet är (0, 0, 0) |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [setNearPlane(double value)](#setNearPlane-double-) | Ställer in den närliggande planet för kameran, standardvärdet är 1 |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | Visa en orienteringsruta. |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | Visa ett rutnät i scenen. |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | Visa linjaler för x/y/z-axlar i scenen för att mäta modellen. |
| [setShowUI(boolean value)](#setShowUI-boolean-) | Visa ett enkelt användargränssnitt i scenen. |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | Ställer in uppvektorn, värdet kan vara "x"/"y"/"z", standardvärdet är "y" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


Konstruktor för [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) med alla standardinställningar.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


Hämtar kamerans initiala position, standardvärdet är (10, 10, 10)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the initial position of the camera, default value is (10, 10, 10)
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


Hämtar standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.

**Returns:**
java.nio.charset.Charset - standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Försök att kopiera texturer som används i scenen till utmatningskatalogen.

**Returns:**
boolean - Försök att kopiera texturer som används i scenen till utdata katalogen.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Hämtar kamerans fjärrplan, standardvärdet är 1000.

**Returns:**
double - den avlägsna planet för kameran, standardvärdet är 1000.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Hämtar synfältet, standardvärdet är 45, mätt i grader.

**Returns:**
double - synfältet, standardvärdet är 45, mätt i grader.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material.

**Returns:**
java.lang.String - Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Och du kan också använda din egen implementation.

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


Hämtar fabriks‑klassen för FileSystem. Standardfabriken kommer att skapa com.aspose.threed.LocalFileSystem som inte är lämplig för servermiljö.

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
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Hämtar standard‑blickposition, standardvärdet är (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda.

**Returns:**
java.util.ArrayList<java.lang.String> - Vissa filer som OBJ beror på externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. **Example:** Följande kod visar hur man manuellt specificerar uppslagnings‑texturer, så att importören kan hitta

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Hämtar kamerans närplan, standardvärdet är 1

**Returns:**
double - den närliggande planet för kameran, standardvärdet är 1
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


Visa en orienteringsruta. Standardvärdet är true.

**Returns:**
boolean - Visa en orienteringsruta. Standardvärdet är true.
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


Visa ett rutnät i scenen. Standardvärdet är true.

**Returns:**
boolean - Visa ett rutnät i scenen. Standardvärdet är true.
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


Visa linjaler för x/y/z-axlar i scenen för att mäta modellen. Standardvärdet är false.

**Returns:**
boolean - Visa linjaler för x/y/z-axlar i scenen för att mäta modellen. Standardvärdet är false.
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


Visa ett enkelt UI i scenen. Standardvärdet är true.

**Returns:**
boolean - Visa ett enkelt UI i scenen. Standardvärdet är true.
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


Hämtar uppvektorn, värdet kan vara "x"/"y"/"z", standardvärdet är "y"

**Returns:**
java.lang.String - uppvektorn, värdet kan vara "x"/"y"/"z", standardvärdet är "y"
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




### setCameraPosition(Vector3 value) {#setCameraPosition-com.aspose.threed.Vector3-}
```
public void setCameraPosition(Vector3 value)
```


Ställer in den initiala positionen för kameran, standardvärdet är (10, 10, 10)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Ställer in standardkodning för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset | Nytt värde |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Försök att kopiera texturer som används i scenen till utmatningskatalogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Ställer in den avlägsna planet för kameran, standardvärdet är 1000.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Ställer in synfältet, standardvärdet är 45, mätt i grader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | New value **Example:** Standard‑FileSystem är LocalFileSystem, den är inte säker i miljöer som server‑sidan, men du kan åsidosätta filsystem‑åtkomsten genom att ange en annan implementation. Aspose.3D tillhandahåller olika FileSystem‑implementationer såsom: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Och du kan också använda din egen implementation.

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


Ställer in fabriks‑klassen för FileSystem. Standardfabriken kommer att skapa com.aspose.threed.LocalFileSystem som inte är lämplig för servermiljö.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | New value **Example:** Standard‑FileSystem i SaveOptions/LoadOptions är ett katalogbaserat filsystem, du kan åsidosätta standardimplementationen genom att specificera den via IOConfig.FileSystemFactory: |

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

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Ställer in standardpositionen för blick, standardvärdet är (0, 0, 0)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.util.ArrayList<java.lang.String> | New value **Example:** Följande kod visar hur man manuellt specificerar uppslagnings‑texturer, så att importören kan hitta |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Ställer in den närliggande planet för kameran, standardvärdet är 1

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


Visa en orienteringsruta. Standardvärdet är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


Visa ett rutnät i scenen. Standardvärdet är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


Visa linjaler för x/y/z-axlar i scenen för att mäta modellen. Standardvärdet är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


Visa ett enkelt UI i scenen. Standardvärdet är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


Ställer in uppvektorn, värdet kan vara "x"/"y"/"z", standardvärdet är "y"

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

