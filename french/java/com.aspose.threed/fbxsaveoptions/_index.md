---
title: "FbxSaveOptions"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Options d'enregistrement pour le fichier Fbx."
type: docs
weight: 63
url: /fr/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Options d'enregistrement pour le fichier Fbx.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | Initialise un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | Initialisez un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) en utilisant la dernière version prise en charge. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Obtient si la texture doit être intégrée au fichier de sortie final. |
| [getEnableCompression()](#getEnableCompression--) | Compression de grandes données binaires dans le fichier FBX (par ex. |
| [getEncoding()](#getEncoding--) | Obtient le codage par défaut pour les fichiers texte. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | Obtient si les propriétés de matériau héritées sont exportées, utilisées pour la rétrocompatibilité. |
| [getExportTextures()](#getExportTextures--) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [getFileFormat()](#getFileFormat--) | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [getFileName()](#getFileName--) | Le nom de fichier de la scène d'exportation/importation. |
| [getFileSystem()](#getFileSystem--) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtient la classe de fabrique pour FileSystem. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | Obtient si les données de courbe répétées sont réutilisées en augmentant le compteur de références des dernières données |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | Obtient si un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) est toujours généré pour les géométries lorsque le nœud attaché contient des matériaux. |
| [getLookupPaths()](#getLookupPaths--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille de la sortie FBX lorsque la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). |
| [getVideoForTexture()](#getVideoForTexture--) | Obtient si une instance Video est générée pour [Texture](../../com.aspose.threed/texture) lors de l'exportation en FBX. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Définit si la texture doit être intégrée au fichier de sortie final. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | Compression de grandes données binaires dans le fichier FBX (par ex. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Définit le codage par défaut pour les fichiers texte. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | Définit si les propriétés de matériau héritées sont exportées, utilisées pour la rétrocompatibilité. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Le nom de fichier de la scène d'exportation/importation. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Définit la classe de fabrique pour FileSystem. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | Définit si les données de courbe répétées sont réutilisées en augmentant le compteur de références des dernières données |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | Définit si un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) est toujours généré pour les géométries lorsque le nœud attaché contient des matériaux. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille de la sortie FBX lorsque la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | Définit si une instance Video est générée pour [Texture](../../com.aspose.threed/texture) lors de l'exportation en FBX. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


Initialise un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Instance de [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat), cela doit être un format FBX valide. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


Initialisez un [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) en utilisant la dernière version prise en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | Binaire ou ASCII |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient si la texture doit être intégrée au fichier de sortie final. L'exportateur FBX essaiera de trouver les données brutes de la texture depuis [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem), et d'intégrer le fichier au fichier FBX final. La valeur par défaut est false.

**Returns:**
booléen - indique si la texture doit être intégrée au fichier de sortie final. L'exportateur FBX essaiera de trouver les données brutes de la texture depuis [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem), et d'intégrer le fichier au fichier FBX final. La valeur par défaut est false.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


Compression de grandes données binaires dans le fichier FBX (par ex. données d'animation, points de contrôle, données d'éléments de sommet, indices), la valeur par défaut est true.

**Returns:**
booléen - Compression de grandes données binaires dans le fichier FBX (par ex. données d'animation, points de contrôle, données d'éléments de sommet, indices), la valeur par défaut est true.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Obtient le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.

**Returns:**
java.nio.charset.Charset - le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


Obtient si les propriétés de matériau héritées sont exportées, utilisées pour la rétrocompatibilité. Cette option est activée par défaut.

**Returns:**
booléen - indique si les propriétés de matériau héritées sont exportées, utilisées pour la rétrocompatibilité. Cette option est activée par défaut.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Returns:**
boolean - Tente de copier les textures utilisées dans la scène vers le répertoire de sortie.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.

**Returns:**
java.lang.String - Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Et vous pouvez également utiliser votre propre implémentation.

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


Obtient la classe de fabrique pour FileSystem. La fabrique par défaut créera com.aspose.threed.LocalFileSystem qui n'est pas adaptée à un environnement serveur.

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


Obtient si les données de courbe répétées sont réutilisées en augmentant le compteur de références des dernières données

**Returns:**
java.lang.Boolean - indique si les données de courbe répétées sont réutilisées en augmentant le compteur de références des dernières données
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


Obtient si un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) est toujours généré pour les géométries lorsque le nœud attaché contient des matériaux. Cette option est désactivée par défaut.

**Returns:**
booléen - indique si un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) est toujours généré pour les géométries lorsque le nœud attaché contient des matériaux. Cette option est désactivée par défaut.
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger.

**Returns:**
java.util.ArrayList<java.lang.String> - Certains fichiers comme OBJ dépendent de fichiers externes, les chemins de recherche permettront à Aspose.3D de rechercher les fichiers externes à charger. **Example:** Le code suivant montre comment spécifier manuellement les textures de recherche, afin que l'importateur puisse les trouver

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


Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille de la sortie FBX lorsque la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). La valeur par défaut est false

**Returns:**
booléen - Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille du fichier FBX dont la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). La valeur par défaut est false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


Obtient si une instance Video est générée pour [Texture](../../com.aspose.threed/texture) lors de l'exportation en FBX.

**Returns:**
booléen - indique si une instance Video doit être générée pour [Texture](../../com.aspose.threed/texture) lors de l'exportation en FBX.
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


Définit s'il faut incorporer la texture dans le fichier de sortie final. L'exportateur FBX tentera de récupérer les données brutes de la texture depuis [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) et d'incorporer le fichier dans le FBX final. La valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


Compression de grandes données binaires dans le fichier FBX (par ex. données d'animation, points de contrôle, données d'éléments de sommet, indices), la valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset | Nouvelle valeur |

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


Définit s'il faut exporter les propriétés de matériau héritées, utilisées pour la rétrocompatibilité. Cette option est activée par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nouvelle valeur **Example:** Le système de fichiers par défaut est LocalFileSystem, il n'est pas sûr dans un environnement côté serveur, mais vous pouvez remplacer l'accès au système de fichiers en spécifiant une implémentation différente. Aspose.3D fournit différentes implémentations de FileSystem comme : |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Et vous pouvez également utiliser votre propre implémentation.

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


Définit la classe de fabrique pour FileSystem. La fabrique par défaut créera com.aspose.threed.LocalFileSystem qui n'est pas adaptée à un environnement serveur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nouvelle valeur **Example:** Le système de fichiers par défaut dans SaveOptions/LoadOptions est un système de fichiers basé sur les répertoires, vous pouvez remplacer l'implémentation par défaut en le spécifiant via IOConfig.FileSystemFactory : |

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


Définit si les données de courbe répétées sont réutilisées en augmentant le compteur de références des dernières données

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Boolean | Nouvelle valeur |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


Définit s'il faut toujours générer un [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) pour les géométries si le nœud attaché contient des matériaux. Cette option est désactivée par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.util.ArrayList<java.lang.String> | Nouvelle valeur **Example:** Le code suivant montre comment spécifier manuellement les textures de recherche, afin que l'importateur puisse les trouver |

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


Réutilisez le maillage pour les primitives avec les mêmes paramètres, cela réduira considérablement la taille de la sortie FBX lorsque la scène a été construite à partir d'un grand ensemble de formes primitives (comme importées depuis des fichiers CAD). La valeur par défaut est false

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


Définit si une instance Video est générée pour [Texture](../../com.aspose.threed/texture) lors de l'exportation en FBX.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

