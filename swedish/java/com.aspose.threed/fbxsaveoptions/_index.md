---
title: FbxSaveOptions
second_title: Aspose.3D for Java API-referens
description: Sparaalternativ för Fbx-fil.
type: docs
weight: 63
url: /sv/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Sparaalternativ för Fbx-fil.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | Initierar en [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | Initiera en [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) med den senaste stödda versionen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Hämtar om texturen ska bäddas in i den slutliga utdatafilen. |
| [getEnableCompression()](#getEnableCompression--) | Komprimering av stora binära data i FBX-filen (t.ex. |
| [getEncoding()](#getEncoding--) | Hämtar standardkodningen för textbaserade filer. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | Hämtar om äldre materialegenskaper ska exporteras, används för bakåtkompatibilitet. |
| [getExportTextures()](#getExportTextures--) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [getFileFormat()](#getFileFormat--) | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |
| [getFileName()](#getFileName--) | Filnamnet för den exporterande/importerande scenen. |
| [getFileSystem()](#getFileSystem--) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Hämtar fabriksklassen för FileSystem. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | Hämtar om upprepad kurvdata ska återanvändas genom att öka den sista dataobjektets referensräkning |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | Hämtar om ett [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) alltid ska genereras för geometrier om den bifogade noden innehåller material. |
| [getLookupPaths()](#getLookupPaths--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | Återanvänd meshen för primitiv med samma parametrar, detta kommer avsevärt minska storleken på FBX-utdata när scenen är konstruerad av en stor mängd primitiva former (t.ex. importerade från CAD-filer). |
| [getVideoForTexture()](#getVideoForTexture--) | Hämtar om en Video-instans ska genereras för [Texture](../../com.aspose.threed/texture) vid export som FBX. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Ställer in om texturen ska bäddas in i den slutliga utdatafilen. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | Komprimering av stora binära data i FBX-filen (t.ex. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ställer in standardkodningen för textbaserade filer. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | Ställer in om äldre materialegenskaper ska exporteras, används för bakåtkompatibilitet. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Filnamnet för den exporterande/importerande scenen. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ställer in fabriksklassen för FileSystem. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | Ställer in om upprepad kurvdata ska återanvändas genom att öka den sista dataobjektets referensräkning |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | Ställer in om ett [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) alltid ska genereras för geometrier om den bifogade noden innehåller material. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | Återanvänd meshen för primitiv med samma parametrar, detta kommer avsevärt minska storleken på FBX-utdata när scenen är konstruerad av en stor mängd primitiva former (t.ex. importerade från CAD-filer). |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | Ställer in om en Video-instans ska genereras för [Texture](../../com.aspose.threed/texture) vid export som FBX. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


Initierar en [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Instans av [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat), den bör vara ett giltigt FBX-format. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


Initiera en [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) med den senaste stödda versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | Binär eller ASCII |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmbedTextures() {#getEmbedTextures--}
```
public boolean getEmbedTextures()
```


Hämtar om texturen ska bäddas in i den slutliga utdatafilen. FBX Exporter kommer att försöka hitta texturens rådata från [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) och bädda in filen i den slutliga FBX-filen. Standardvärdet är falskt.

**Returns:**
boolean - om texturen ska bäddas in i den slutliga utdatafilen. FBX Exporter kommer att försöka hitta texturens rådata från [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) och bädda in filen i den slutliga FBX-filen. Standardvärdet är falskt.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


Komprimering av stora binära data i FBX-filen (t.ex. animationsdata, kontrollpunkter, vertex-elementdata, index), standardvärdet är sant.

**Returns:**
boolean - Komprimering av stora binära data i FBX-filen (t.ex. animationsdata, kontrollpunkter, vertex-elementdata, index), standardvärdet är sant.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Hämtar standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.

**Returns:**
java.nio.charset.Charset - standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


Hämtar om äldre materialegenskaper ska exporteras, används för bakåtkompatibilitet. Detta alternativ är aktiverat som standard.

**Returns:**
boolean - om äldre materialegenskaper ska exporteras, används för bakåtkompatibilitet. Detta alternativ är aktiverat som standard.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Försök att kopiera texturer som används i scenen till utmatningskatalogen.

**Returns:**
boolean - Försök att kopiera texturer som används i scenen till utdata katalogen.
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
### getFoldRepeatedCurveData() {#getFoldRepeatedCurveData--}
```
public Boolean getFoldRepeatedCurveData()
```


Hämtar om upprepad kurvdata ska återanvändas genom att öka den sista dataobjektets referensräkning

**Returns:**
java.lang.Boolean - om upprepad kurvdata ska återanvändas genom att öka den sista dataobjektets referensräkning
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


Hämtar om ett [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) alltid ska genereras för geometrier om den bifogade noden innehåller material. Detta är avstängt som standard.

**Returns:**
boolean - om ett [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) alltid ska genereras för geometrier om den bifogade noden innehåller material. Detta är avstängt som standard.
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
### getReusePrimitiveMesh() {#getReusePrimitiveMesh--}
```
public boolean getReusePrimitiveMesh()
```


Återanvänd meshen för primitiv med samma parametrar, detta kommer avsevärt minska storleken på FBX-utdata när scenen är konstruerad av en stor mängd primitiva former (t.ex. importerade från CAD-filer). Standardvärdet är falskt

**Returns:**
boolean - Återanvänd meshen för primitiv med samma parametrar, detta kommer avsevärt minska storleken på FBX-utdata där scenen konstruerades av en stor mängd primitiva former (som importerade från CAD-filer). Standardvärdet är false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


Hämtar om en Video-instans ska genereras för [Texture](../../com.aspose.threed/texture) vid export som FBX.

**Returns:**
boolean - huruvida en Video-instans ska genereras för [Texture](../../com.aspose.threed/texture) vid export som FBX.
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




### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


Anger om texturen ska bäddas in i den slutliga utdatafilen. FBX Exporter kommer att försöka hitta texturens rådata från [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) och bädda in filen i den slutliga FBX-filen. Standardvärdet är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


Komprimering av stora binära data i FBX-filen (t.ex. animationsdata, kontrollpunkter, vertex-elementdata, index), standardvärdet är sant.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Ställer in standardkodning för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset | Nytt värde |

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


Anger om äldre materialegenskaper ska exporteras, används för bakåtkompatibilitet. Detta alternativ är aktiverat som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Försök att kopiera texturer som används i scenen till utmatningskatalogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

### setFoldRepeatedCurveData(Boolean value) {#setFoldRepeatedCurveData-java.lang.Boolean-}
```
public void setFoldRepeatedCurveData(Boolean value)
```


Ställer in om upprepad kurvdata ska återanvändas genom att öka den sista dataobjektets referensräkning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Boolean | Nytt värde |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


Anger om ett [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) alltid ska genereras för geometrier om den bifogade noden innehåller material. Detta är avstängt som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

### setReusePrimitiveMesh(boolean value) {#setReusePrimitiveMesh-boolean-}
```
public void setReusePrimitiveMesh(boolean value)
```


Återanvänd meshen för primitiv med samma parametrar, detta kommer avsevärt minska storleken på FBX-utdata när scenen är konstruerad av en stor mängd primitiva former (t.ex. importerade från CAD-filer). Standardvärdet är falskt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


Ställer in om en Video-instans ska genereras för [Texture](../../com.aspose.threed/texture) vid export som FBX.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

