---
title: FbxSaveOptions
second_title: Aspose.3D for Java API-referentie
description: Opslagopties voor een Fbx-bestand.
type: docs
weight: 63
url: /nl/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Opslagopties voor een Fbx-bestand.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | Initialiseert een [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | Initialiseer een [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) met de nieuwste ondersteunde versie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Bepaalt of de textuur in het uiteindelijke uitvoerbestand moet worden ingebed. |
| [getEnableCompression()](#getEnableCompression--) | Compressie van grote binaire gegevens in het FBX‑bestand (bijv. |
| [getEncoding()](#getEncoding--) | Haalt de standaardcodering op voor tekstgebaseerde bestanden. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | Bepaalt of verouderde materiaaleigenschappen moeten worden geëxporteerd, gebruikt voor achterwaartse compatibiliteit. |
| [getExportTextures()](#getExportTextures--) | Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [getFileFormat()](#getFileFormat--) | Haalt het bestandsformaat op dat is gespecificeerd in de huidige opslaan/laden-optie. |
| [getFileName()](#getFileName--) | De bestandsnaam van de exporterende/importerende scène. |
| [getFileSystem()](#getFileSystem--) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Haalt de fabrieksklasse op voor FileSystem. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | Bepaalt of herhaalde curve‑gegevens opnieuw moeten worden gebruikt door de referentietelling van de laatste gegevens te verhogen |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | Bepaalt of er altijd een [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) moet worden gegenereerd voor geometrieën als het gekoppelde knooppunt materialen bevat. |
| [getLookupPaths()](#getLookupPaths--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | Herbruik het mesh voor de primitives met dezelfde parameters; dit zal de grootte van de FBX‑output aanzienlijk verkleinen wanneer de scène is opgebouwd uit een grote set primitieve vormen (zoals geïmporteerd uit CAD‑bestanden). |
| [getVideoForTexture()](#getVideoForTexture--) | Bepaalt of er een Video‑instantie wordt gegenereerd voor [Texture](../../com.aspose.threed/texture) bij het exporteren als FBX. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Stelt in of de textuur in het uiteindelijke uitvoerbestand moet worden ingebed. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | Compressie van grote binaire gegevens in het FBX‑bestand (bijv. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Stelt de standaardcodering in voor tekstgebaseerde bestanden. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | Stelt in of verouderde materiaaleigenschappen moeten worden geëxporteerd, gebruikt voor achterwaartse compatibiliteit. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [setFileName(String value)](#setFileName-java.lang.String-) | De bestandsnaam van de exporterende/importerende scène. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Stelt de fabrieksklasse in voor FileSystem. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | Stelt in of herhaalde curve‑gegevens opnieuw moeten worden gebruikt door de referentietelling van de laatste gegevens te verhogen |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | Stelt in of er altijd een [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) moet worden gegenereerd voor geometrieën als het gekoppelde knooppunt materialen bevat. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | Herbruik het mesh voor de primitives met dezelfde parameters; dit zal de grootte van de FBX‑output aanzienlijk verkleinen wanneer de scène is opgebouwd uit een grote set primitieve vormen (zoals geïmporteerd uit CAD‑bestanden). |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | Stelt in of er een Video‑instantie wordt gegenereerd voor [Texture](../../com.aspose.threed/texture) bij het exporteren als FBX. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


Initialiseert een [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Instantie van [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat), dit moet een geldig FBX‑formaat zijn. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


Initialiseer een [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) met de nieuwste ondersteunde versie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | Binair of ASCII |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Bepaalt of de textuur in het uiteindelijke uitvoerbestand moet worden ingebed. De FBX‑exporteur probeert de ruwe gegevens van de textuur te vinden via [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) en embedde het bestand in het uiteindelijke FBX‑bestand. Standaardwaarde is false.

**Returns:**
boolean - of de textuur in het uiteindelijke uitvoerbestand moet worden ingebed. De FBX‑exporteur probeert de ruwe gegevens van de textuur te vinden via [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) en embedde het bestand in het uiteindelijke FBX‑bestand. Standaardwaarde is false.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


Compressie van grote binaire gegevens in het FBX‑bestand (bijv. animatiegegevens, controlepunten, vertex‑elementgegevens, indexen), standaardwaarde is true.

**Returns:**
boolean - Compressie van grote binaire gegevens in het FBX‑bestand (bijv. animatiegegevens, controlepunten, vertex‑elementgegevens, indexen), standaardwaarde is true.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Haalt de standaardcodering op voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.

**Returns:**
java.nio.charset.Charset - de standaardcodering voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


Bepaalt of verouderde materiaaleigenschappen moeten worden geëxporteerd, gebruikt voor achterwaartse compatibiliteit. Deze optie is standaard ingeschakeld.

**Returns:**
boolean - of verouderde materiaaleigenschappen moeten worden geëxporteerd, gebruikt voor achterwaartse compatibiliteit. Deze optie is standaard ingeschakeld.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Returns:**
boolean - Probeer texturen die in de scène worden gebruikt naar de uitvoermap te kopiëren.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Haalt het bestandsformaat op dat is gespecificeerd in de huidige opslaan/laden-optie.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


De bestandsnaam van de export‑/importscene. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ.

**Returns:**
java.lang.String - De bestandsnaam van de export‑/importscene. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

En je kunt ook je eigen implementatie gebruiken.

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


Haalt de fabrieksklasse voor FileSystem op. De standaardfabriek maakt com.aspose.threed.LocalFileSystem aan, wat niet geschikt is voor een serveromgeving.

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


Bepaalt of herhaalde curve‑gegevens opnieuw moeten worden gebruikt door de referentietelling van de laatste gegevens te verhogen

**Returns:**
java.lang.Boolean - of herhaalde curve‑gegevens opnieuw moeten worden gebruikt door de referentietelling van de laatste gegevens te verhogen
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


Bepaalt of er altijd een [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) moet worden gegenereerd voor geometrieën als het gekoppelde knooppunt materialen bevat. Dit is standaard uitgeschakeld.

**Returns:**
boolean - of er altijd een [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) moet worden gegenereerd voor geometrieën als het gekoppelde knooppunt materialen bevat. Dit is standaard uitgeschakeld.
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden.

**Returns:**
java.util.ArrayList<java.lang.String> - Sommige bestanden, zoals OBJ, zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te vinden om te laden. **Example:** De volgende code laat zien hoe je handmatig de te zoeken textures opgeeft, zodat de importeur ze kan vinden

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


Herbruik het mesh voor de primitives met dezelfde parameters; dit zal de grootte van de FBX‑output aanzienlijk verkleinen wanneer de scène is opgebouwd uit een grote set primitieve vormen (zoals geïmporteerd uit CAD‑bestanden). Standaardwaarde is false

**Returns:**
boolean - Hergebruik het mesh voor de primitives met dezelfde parameters, dit zal de grootte van de FBX‑uitvoer aanzienlijk verkleinen, aangezien de scène is opgebouwd uit een grote set primitieve vormen (zoals geïmporteerd uit CAD‑bestanden). Standaardwaarde is false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


Bepaalt of er een Video‑instantie wordt gegenereerd voor [Texture](../../com.aspose.threed/texture) bij het exporteren als FBX.

**Returns:**
boolean - of er een Video‑instantie wordt gegenereerd voor [Texture](../../com.aspose.threed/texture) bij het exporteren als FBX.
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


Stelt in of de texture moet worden ingebed in het uiteindelijke uitvoerbestand. De FBX‑Exporter probeert de ruwe data van de texture te vinden via [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) en embed het bestand in het definitieve FBX‑bestand. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


Compressie van grote binaire gegevens in het FBX‑bestand (bijv. animatiegegevens, controlepunten, vertex‑elementgegevens, indexen), standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Stelt de standaardcodering in voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset | Nieuwe waarde |

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


Stelt in of legacy‑materiaal‑eigenschappen worden geëxporteerd, gebruikt voor achterwaartse compatibiliteit. Deze optie is standaard ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


De bestandsnaam van de export‑/importscene. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nieuwe waarde **Example:** De standaard FileSystem is LocalFileSystem, dit is niet veilig in een omgeving zoals server-side, maar je kunt de bestandsysteemtoegang overschrijven door een andere implementatie op te geven. Aspose.3D biedt verschillende FileSystem-implementaties, zoals: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

En je kunt ook je eigen implementatie gebruiken.

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


Stelt de fabrieksklasse voor FileSystem in. De standaardfabriek maakt com.aspose.threed.LocalFileSystem aan, wat niet geschikt is voor een serveromgeving.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nieuwe waarde **Example:** Het standaard FileSystem in SaveOptions/LoadOptions is een mapgebaseerd bestandssysteem. Je kunt de standaardimplementatie overschrijven door deze op te geven via IOConfig.FileSystemFactory: |

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


Stelt in of herhaalde curve‑gegevens opnieuw moeten worden gebruikt door de referentietelling van de laatste gegevens te verhogen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Boolean | Nieuwe waarde |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


Stelt in of er altijd een [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) wordt gegenereerd voor geometrieën als het gekoppelde knooppunt materialen bevat. Dit is standaard uitgeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.ArrayList<java.lang.String> | Nieuwe waarde **Example:** De volgende code laat zien hoe je handmatig de te zoeken textures opgeeft, zodat de importeur ze kan vinden |

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


Herbruik het mesh voor de primitives met dezelfde parameters; dit zal de grootte van de FBX‑output aanzienlijk verkleinen wanneer de scène is opgebouwd uit een grote set primitieve vormen (zoals geïmporteerd uit CAD‑bestanden). Standaardwaarde is false

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


Stelt in of er een Video‑instantie wordt gegenereerd voor [Texture](../../com.aspose.threed/texture) bij het exporteren als FBX.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

