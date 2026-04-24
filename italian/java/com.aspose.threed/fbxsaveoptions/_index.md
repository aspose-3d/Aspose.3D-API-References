---
title: FbxSaveOptions
second_title: Aspose.3D for Java API Reference
description: Opzioni di salvataggio per il file Fbx.
type: docs
weight: 63
url: /it/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Opzioni di salvataggio per il file Fbx.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | Inizializza un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | Inizializza un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) utilizzando l'ultima versione supportata. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Restituisce se incorporare la texture nel file di output finale. |
| [getEnableCompression()](#getEnableCompression--) | Compressione di grandi dati binari nel file FBX (ad es. |
| [getEncoding()](#getEncoding--) | Restituisce la codifica predefinita per i file di testo. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | Restituisce se esportare le proprietà dei materiali legacy, utilizzate per la retrocompatibilità. |
| [getExportTextures()](#getExportTextures--) | Prova a copiare le texture usate nella scena nella directory di output. |
| [getFileFormat()](#getFileFormat--) | Restituisce il formato file specificato nell'opzione Salva/Carica corrente. |
| [getFileName()](#getFileName--) | Il nome file della scena di esportazione/importazione. |
| [getFileSystem()](#getFileSystem--) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Restituisce la classe factory per FileSystem. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | Restituisce se riutilizzare i dati delle curve ripetute aumentando il conteggio di riferimento dell'ultimo dato. |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | Restituisce se generare sempre un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) per le geometrie se il nodo collegato contiene materiali. |
| [getLookupPaths()](#getLookupPaths--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | Riutilizza la mesh per le primitive con gli stessi parametri, questo ridurrà significativamente le dimensioni dell'output FBX quando la scena è stata costruita con un ampio set di forme primitive (come importate da file CAD). |
| [getVideoForTexture()](#getVideoForTexture--) | Restituisce se generare un'istanza Video per [Texture](../../com.aspose.threed/texture) durante l'esportazione come FBX. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Imposta se incorporare la texture nel file di output finale. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | Compressione di grandi dati binari nel file FBX (ad es. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica predefinita per i file di testo. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | Imposta se esportare le proprietà dei materiali legacy, utilizzate per la retrocompatibilità. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Prova a copiare le texture usate nella scena nella directory di output. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Il nome file della scena di esportazione/importazione. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Imposta la classe factory per FileSystem. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | Imposta se riutilizzare i dati delle curve ripetute aumentando il conteggio di riferimento dell'ultimo dato. |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | Imposta se generare sempre un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) per le geometrie se il nodo collegato contiene materiali. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | Riutilizza la mesh per le primitive con gli stessi parametri, questo ridurrà significativamente le dimensioni dell'output FBX quando la scena è stata costruita con un ampio set di forme primitive (come importate da file CAD). |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | Imposta se generare un'istanza Video per [Texture](../../com.aspose.threed/texture) durante l'esportazione come FBX. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


Inizializza un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Istanza di [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat), dovrebbe essere un formato FBX valido. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


Inizializza un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) utilizzando l'ultima versione supportata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | Binario o ASCII |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Restituisce se incorporare la texture nel file di output finale. L'exporter FBX cercherà i dati grezzi della texture da [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) e incorporerà il file nel file FBX finale. Il valore predefinito è false.

**Returns:**
boolean - se incorporare la texture nel file di output finale. L'exporter FBX cercherà i dati grezzi della texture da [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) e incorporerà il file nel file FBX finale. Il valore predefinito è false.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


Compressione di grandi dati binari nel file FBX (ad es. dati di animazione, punti di controllo, dati degli elementi vertex, indici), il valore predefinito è true.

**Returns:**
boolean - Compressione di grandi dati binari nel file FBX (ad es. dati di animazione, punti di controllo, dati degli elementi vertex, indici), il valore predefinito è true.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Restituisce la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Returns:**
java.nio.charset.Charset - la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


Restituisce se esportare le proprietà dei materiali legacy, utilizzate per la retrocompatibilità. Questa opzione è attiva per impostazione predefinita.

**Returns:**
boolean - se esportare le proprietà dei materiali legacy, utilizzate per la retrocompatibilità. Questa opzione è attiva per impostazione predefinita.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Prova a copiare le texture usate nella scena nella directory di output.

**Returns:**
boolean - Prova a copiare le texture usate nella scena nella directory di output.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Restituisce il formato file specificato nell'opzione Salva/Carica corrente.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.

**Returns:**
java.lang.String - Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

E puoi anche utilizzare la tua implementazione.

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


Ottiene la classe factory per FileSystem. La factory predefinita creerà com.aspose.threed.LocalFileSystem, che non è adatta per l'ambiente server.

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


Restituisce se riutilizzare i dati delle curve ripetute aumentando il conteggio di riferimento dell'ultimo dato.

**Returns:**
java.lang.Boolean - se riutilizzare i dati delle curve ripetute aumentando il conteggio di riferimento dell'ultimo dato
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


Restituisce se generare sempre un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) per le geometrie se il nodo collegato contiene materiali. Questa opzione è disattivata per impostazione predefinita.

**Returns:**
boolean - se generare sempre un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) per le geometrie se il nodo collegato contiene materiali. Questa opzione è disattivata per impostazione predefinita.
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare.

**Returns:**
java.util.ArrayList<java.lang.String> - Alcuni file come OBJ dipendono da file esterni; i percorsi di ricerca consentiranno ad Aspose.3D di cercare i file esterni da caricare. **Esempio:** Il codice seguente mostra come specificare manualmente le texture di ricerca, così l'importatore può trovarle

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


Riutilizza la mesh per le primitive con gli stessi parametri, questo ridurrà significativamente le dimensioni dell'output FBX quando la scena è stata costruita con un ampio set di forme primitive (come importate da file CAD). Il valore predefinito è false

**Returns:**
boolean - Riutilizza la mesh per le primitive con gli stessi parametri, questo ridurrà significativamente le dimensioni dell'output FBX quando la scena è stata costruita con un grande insieme di forme primitive (come importate da file CAD). Il valore predefinito è false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


Restituisce se generare un'istanza Video per [Texture](../../com.aspose.threed/texture) durante l'esportazione come FBX.

**Returns:**
boolean - se generare un'istanza Video per [Texture](../../com.aspose.threed/texture) durante l'esportazione come FBX.
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


Imposta se incorporare la texture nel file di output finale. L'FBX Exporter cercherà i dati grezzi della texture da [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) e incorporerà il file nel FBX finale. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


Compressione di grandi dati binari nel file FBX (ad es. dati di animazione, punti di controllo, dati degli elementi vertex, indici), il valore predefinito è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset | Nuovo valore |

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


Imposta se esportare le proprietà dei materiali legacy, utilizzate per la retrocompatibilità. Questa opzione è attiva per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Prova a copiare le texture usate nella scena nella directory di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nuovo valore **Esempio:** Il FileSystem predefinito è LocalFileSystem, non è sicuro in ambienti come il lato server, ma è possibile sovrascrivere l'accesso al file system specificando un'implementazione diversa. Aspose.3D fornisce diverse implementazioni di FileSystem come: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

E puoi anche utilizzare la tua implementazione.

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


Imposta la classe factory per FileSystem. La factory predefinita creerà com.aspose.threed.LocalFileSystem, che non è adatta per l'ambiente server.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nuovo valore **Esempio:** Il FileSystem predefinito in SaveOptions/LoadOptions è un file system basato su directory; è possibile sovrascrivere l'implementazione predefinita specificandola tramite IOConfig.FileSystemFactory: |

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


Imposta se riutilizzare i dati delle curve ripetute aumentando il conteggio di riferimento dell'ultimo dato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Boolean | Nuovo valore |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


Imposta se generare sempre un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) per le geometrie se il nodo collegato contiene materiali. Questa opzione è disattivata per impostazione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.ArrayList<java.lang.String> | Nuovo valore **Esempio:** Il codice seguente mostra come specificare manualmente le texture di ricerca, così l'importatore può trovarle |

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


Riutilizza la mesh per le primitive con gli stessi parametri, questo ridurrà significativamente le dimensioni dell'output FBX quando la scena è stata costruita con un ampio set di forme primitive (come importate da file CAD). Il valore predefinito è false

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


Imposta se generare un'istanza Video per [Texture](../../com.aspose.threed/texture) durante l'esportazione come FBX.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

