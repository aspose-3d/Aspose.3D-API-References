---
title: GltfSaveOptions
second_title: Aspose.3D for Java API Reference
description: Επιλογές αποθήκευσης για τη μορφή glTF.
type: docs
weight: 74
url: /el/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για τη μορφή glTF.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Constructor of [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Constructor of [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Εφαρμόστε [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) στο πλέγμα. |
| [getBufferFile()](#getBufferFile--) | The file name of the external buffer file used to store binary data. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Gets whether to enable draco compression |
| [getEmbedAssets()](#getEmbedAssets--) | Ενσωματώστε όλα τα εξωτερικά περιουσιακά στοιχεία ως base64 σε ένα μόνο αρχείο σε λειτουργία ASCII, η προεπιλεγμένη τιμή είναι false. |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getExportTextures()](#getExportTextures--) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Use external draco encoder to accelerate the draco compression speed. |
| [getFallbackNormal()](#getFallbackNormal--) | When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Αναστρέψτε το συστατικό v(t) των συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι true. |
| [getImageFormat()](#getImageFormat--) | Το πρότυπο glTF υποστηρίζει μόνο PNG/JPG ως μορφή υφής, αυτή η επιλογή θα καθοδηγήσει πώς το Aspose.3D θα μετατρέψει τις μη τυπικές εικόνες σε υποστηριζόμενη μορφή κατά την εξαγωγή. |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [getMaterialConverter()](#getMaterialConverter--) | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας glTF 2.0 θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. |
| [getPrettyPrint()](#getPrettyPrint--) | Το περιεχόμενο JSON του αρχείου GLTF είναι εσοχή για ανθρώπινη ανάγνωση, η προεπιλεγμένη τιμή είναι false |
| [getSaveExtras()](#getSaveExtras--) | Αποθήκευση των δυναμικών ιδιοτήτων του αντικειμένου σκηνής σε πεδία 'extra' στο παραγόμενο αρχείο glTF. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Σειριοποίηση υλικών χρησιμοποιώντας τις κοινές επεκτάσεις υλικού KHR, η προεπιλεγμένη τιμή είναι false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Εφαρμόστε [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) στο πλέγμα. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | The file name of the external buffer file used to store binary data. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Ορίζει εάν θα ενεργοποιηθεί η συμπίεση draco |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Ενσωματώστε όλα τα εξωτερικά περιουσιακά στοιχεία ως base64 σε ένα μόνο αρχείο σε λειτουργία ASCII, η προεπιλεγμένη τιμή είναι false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Use external draco encoder to accelerate the draco compression speed. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Αναστρέψτε το συστατικό v(t) των συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Το πρότυπο glTF υποστηρίζει μόνο PNG/JPG ως μορφή υφής, αυτή η επιλογή θα καθοδηγήσει πώς το Aspose.3D θα μετατρέψει τις μη τυπικές εικόνες σε υποστηριζόμενη μορφή κατά την εξαγωγή. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας glTF 2.0 θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | Το περιεχόμενο JSON του αρχείου GLTF είναι εσοχή για ανθρώπινη ανάγνωση, η προεπιλεγμένη τιμή είναι false |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Αποθήκευση των δυναμικών ιδιοτήτων του αντικειμένου σκηνής σε πεδία 'extra' στο παραγόμενο αρχείο glTF. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Σειριοποίηση υλικών χρησιμοποιώντας τις κοινές επεκτάσεις υλικού KHR, η προεπιλεγμένη τιμή είναι false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Constructor of [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Constructor of [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Εφαρμόστε [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) στο πλέγμα. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean - Εφαρμόστε [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) στο πλέγμα. Η προεπιλεγμένη τιμή είναι false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


Το όνομα αρχείου του εξωτερικού αρχείου buffer που χρησιμοποιείται για την αποθήκευση δυαδικών δεδομένων. Εάν αυτό το αρχείο δεν καθοριστεί, το Aspose.3D θα δημιουργήσει ένα όνομα για εσάς. Αυτό αγνοείται όταν εξάγετε glTF σε δυαδική λειτουργία.

**Returns:**
java.lang.String - Το όνομα αρχείου του εξωτερικού αρχείου buffer που χρησιμοποιείται για την αποθήκευση δυαδικών δεδομένων. Εάν αυτό το αρχείο δεν καθοριστεί, το Aspose.3D θα δημιουργήσει ένα όνομα για εσάς. Αυτό αγνοείται όταν εξάγετε glTF σε δυαδική λειτουργία.
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


Gets whether to enable draco compression

**Returns:**
boolean - εάν θα ενεργοποιηθεί η συμπίεση draco
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Ενσωματώστε όλα τα εξωτερικά περιουσιακά στοιχεία ως base64 σε ένα μόνο αρχείο σε λειτουργία ASCII, η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean - Ενσωμάτωση όλων των εξωτερικών πόρων ως base64 σε ένα ενιαίο αρχείο σε λειτουργία ASCII, η προεπιλεγμένη τιμή είναι false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.

**Returns:**
java.nio.charset.Charset - η προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.

**Returns:**
boolean - Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Use external draco encoder to accelerate the draco compression speed.

**Returns:**
java.lang.String - Χρησιμοποιήστε εξωτερικό κωδικοποιητή draco για να επιταχύνετε την ταχύτητα συμπίεσης draco. **Remarks:** Το Aspose.3D θα δημιουργήσει νέα υποδιαδικασία για την κωδικοποίηση του πλέγματος στη μορφή draco, χρησιμοποιήστε το με δική σας ευθύνη.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


Όταν ο εξαγωγέας GLTF2 εντοπίσει ένα μη έγκυρο κανονικό, αυτό θα χρησιμοποιηθεί αντί της αρχικής του τιμής για να παρακάμψει την επικύρωση. Η προεπιλεγμένη τιμή είναι (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ.

**Returns:**
java.lang.String - Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Και μπορείτε επίσης να χρησιμοποιήσετε τη δική σας υλοποίηση.

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


Λαμβάνει την κλάση εργοστασίου για το FileSystem. Το προεπιλεγμένο εργοστάσιο θα δημιουργήσει το com.aspose.threed.LocalFileSystem, το οποίο δεν είναι κατάλληλο για περιβάλλον διακομιστή.

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


Αναστρέψτε το συστατικό v(t) των συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean - Αντιστροφή του συντελεστή υφής v(t), η προεπιλεγμένη τιμή είναι true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Το πρότυπο glTF υποστηρίζει μόνο PNG/JPG ως μορφή υφής, αυτή η επιλογή θα καθοδηγήσει πώς το Aspose.3D θα μετατρέψει τις μη τυπικές εικόνες σε υποστηριζόμενη μορφή κατά την εξαγωγή. Η προεπιλεγμένη τιμή είναι [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση.

**Returns:**
java.util.ArrayList<java.lang.String> - Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέψουν στο Aspose.3D να ψάξει για εξωτερικό αρχείο προς φόρτωση. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να καθορίσετε χειροκίνητα τις υφές αναζήτησης, ώστε ο εισαγωγέας να τις βρει

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


Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας glTF 2.0 θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null. Αυτή η ιδιότητα χρησιμοποιείται κατά την εξαγωγή μιας σκηνής σε αρχείο glTF 2.0.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


Το περιεχόμενο JSON του αρχείου GLTF είναι εσοχή για ανθρώπινη ανάγνωση, η προεπιλεγμένη τιμή είναι false

**Returns:**
boolean - Το περιεχόμενο JSON του αρχείου GLTF είναι εσοχή για ανθρώπινη ανάγνωση, η προεπιλεγμένη τιμή είναι false
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Αποθήκευση των δυναμικών ιδιοτήτων του αντικειμένου σκηνής σε πεδία 'extra' στο παραγόμενο αρχείο glTF. Αυτό είναι χρήσιμο για την παροχή δεδομένων ειδικών για την εφαρμογή. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean - Αποθήκευση των δυναμικών ιδιοτήτων του αντικειμένου σκηνής σε πεδία 'extra' στο παραγόμενο αρχείο glTF. Αυτό είναι χρήσιμο για την παροχή δεδομένων ειδικών για την εφαρμογή. Η προεπιλεγμένη τιμή είναι false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Σειριοποίηση υλικών χρησιμοποιώντας τις κοινές επεκτάσεις υλικού KHR, η προεπιλεγμένη τιμή είναι false. Ορισμός αυτού σε false θα προκαλέσει το Aspose.3D να εξάγει ένα σύνολο σκίασης κορυφής/κατακερματισμού εάν [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - Σειριοποίηση υλικών χρησιμοποιώντας τις κοινές επεκτάσεις υλικού KHR, η προεπιλεγμένη τιμή είναι false. Ορισμός αυτού σε false θα προκαλέσει το Aspose.3D να εξάγει ένα σύνολο σκίασης κορυφής/κατακερματισμού εάν [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** Αυτή η ιδιότητα λειτουργεί μόνο για glTF 1.0
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


Εφαρμόστε [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) στο πλέγμα. Η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


Το όνομα αρχείου του εξωτερικού αρχείου buffer που χρησιμοποιείται για την αποθήκευση δυαδικών δεδομένων. Εάν αυτό το αρχείο δεν καθοριστεί, το Aspose.3D θα δημιουργήσει ένα όνομα για εσάς. Αυτό αγνοείται όταν εξάγετε glTF σε δυαδική λειτουργία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Ορίζει εάν θα ενεργοποιηθεί η συμπίεση draco

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Ενσωματώστε όλα τα εξωτερικά περιουσιακά στοιχεία ως base64 σε ένα μόνο αρχείο σε λειτουργία ASCII, η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιήσει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset | Νέα τιμή |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Use external draco encoder to accelerate the draco compression speed.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή **Remarks:** Το Aspose.3D θα δημιουργήσει νέα υποδιαδικασία για την κωδικοποίηση του πλέγματος στη μορφή draco, χρησιμοποιήστε το με δική σας ευθύνη. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


Όταν ο εξαγωγέας GLTF2 εντοπίσει ένα μη έγκυρο κανονικό, αυτό θα χρησιμοποιηθεί αντί της αρχικής του τιμής για να παρακάμψει την επικύρωση. Η προεπιλεγμένη τιμή είναι (0, 1, 0).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Νέα τιμή **Παράδειγμα:** Το προεπιλεγμένο FileSystem είναι το LocalFileSystem, δεν είναι ασφαλές σε περιβάλλον όπως η πλευρά του διακομιστή, αλλά μπορείτε να παρακάμψετε την πρόσβαση στο σύστημα αρχείων καθορίζοντας διαφορετική υλοποίηση. Το Aspose.3D παρέχει διαφορετικές υλοποιήσεις FileSystem όπως: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Και μπορείτε επίσης να χρησιμοποιήσετε τη δική σας υλοποίηση.

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


Ορίζει την κλάση εργοστασίου για το FileSystem. Το προεπιλεγμένο εργοστάσιο θα δημιουργήσει το com.aspose.threed.LocalFileSystem, το οποίο δεν είναι κατάλληλο για περιβάλλον διακομιστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Νέα τιμή **Παράδειγμα:** Το προεπιλεγμένο FileSystem στα SaveOptions/LoadOptions είναι σύστημα αρχείων βασισμένο σε κατάλογο, μπορείτε να παρακάμψετε την προεπιλεγμένη υλοποίηση καθορίζοντάς το μέσω του IOConfig.FileSystemFactory: |

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


Αναστρέψτε το συστατικό v(t) των συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι true.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Το πρότυπο glTF υποστηρίζει μόνο PNG/JPG ως μορφή υφής, αυτή η επιλογή θα καθοδηγήσει πώς το Aspose.3D θα μετατρέψει τις μη τυπικές εικόνες σε υποστηριζόμενη μορφή κατά την εξαγωγή. Η προεπιλεγμένη τιμή είναι [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Νέα τιμή |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.util.ArrayList<java.lang.String> | Νέα τιμή **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να καθορίσετε χειροκίνητα τις υφές αναζήτησης, ώστε ο εισαγωγέας να τις βρει |

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


Προσαρμοσμένος μετατροπέας για τη μετατροπή του υλικού της γεωμετρίας σε υλικό PBR. Εάν δεν έχει οριστεί, ο εξαγωγέας glTF 2.0 θα μετατρέπει αυτόματα το τυπικό υλικό σε υλικό PBR. Η προεπιλεγμένη τιμή είναι null. Αυτή η ιδιότητα χρησιμοποιείται κατά την εξαγωγή μιας σκηνής σε αρχείο glTF 2.0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Νέα τιμή |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


Το περιεχόμενο JSON του αρχείου GLTF είναι εσοχή για ανθρώπινη ανάγνωση, η προεπιλεγμένη τιμή είναι false

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Αποθήκευση των δυναμικών ιδιοτήτων του αντικειμένου σκηνής σε πεδία 'extra' στο παραγόμενο αρχείο glTF. Αυτό είναι χρήσιμο για την παροχή δεδομένων ειδικών για την εφαρμογή. Η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Σειριοποίηση υλικών χρησιμοποιώντας τις κοινές επεκτάσεις υλικού KHR, η προεπιλεγμένη τιμή είναι false. Ορισμός αυτού σε false θα προκαλέσει το Aspose.3D να εξάγει ένα σύνολο σκίασης κορυφής/κατακερματισμού εάν [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή **Remarks:** Αυτή η ιδιότητα λειτουργεί μόνο για glTF 1.0 |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

