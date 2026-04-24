---
title: FbxSaveOptions
second_title: Aspose.3D for Java API Reference
description: Επιλογές αποθήκευσης για αρχείο Fbx.
type: docs
weight: 63
url: /el/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για αρχείο Fbx.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | Αρχικοποιεί ένα [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | Αρχικοποιήστε ένα [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) χρησιμοποιώντας την πιο πρόσφατη υποστηριζόμενη έκδοση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | Λαμβάνει αν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. |
| [getEnableCompression()](#getEnableCompression--) | Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | Λαμβάνει αν θα εξαχθούν οι κληρονομικές ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. |
| [getExportTextures()](#getExportTextures--) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | Λαμβάνει αν θα επαναχρησιμοποιηθεί επαναλαμβανόμενο δεδομένο καμπύλης αυξάνοντας τον αριθμό αναφορών του τελευταίου δεδομένου |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | Λαμβάνει αν θα δημιουργείται πάντα ένα [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | Επαναχρησιμοποιήστε το πλέγμα για τα πρωτότυπα με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος της εξόδου FBX όταν η σκηνή έχει κατασκευαστεί από μεγάλο σύνολο πρωτότυπων σχημάτων (όπως εισαγόμενα από αρχεία CAD). |
| [getVideoForTexture()](#getVideoForTexture--) | Λαμβάνει αν θα δημιουργηθεί ένα αντικείμενο Video για το [Texture](../../com.aspose.threed/texture) κατά την εξαγωγή ως FBX. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | Ορίζει αν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | Ορίζει αν θα εξαχθούν οι κληρονομικές ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | Ορίζει αν θα επαναχρησιμοποιηθεί επαναλαμβανόμενο δεδομένο καμπύλης αυξάνοντας τον αριθμό αναφορών του τελευταίου δεδομένου |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | Ορίζει αν θα δημιουργείται πάντα ένα [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | Επαναχρησιμοποιήστε το πλέγμα για τα πρωτότυπα με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος της εξόδου FBX όταν η σκηνή έχει κατασκευαστεί από μεγάλο σύνολο πρωτότυπων σχημάτων (όπως εισαγόμενα από αρχεία CAD). |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | Ορίζει αν θα δημιουργηθεί ένα αντικείμενο Video για το [Texture](../../com.aspose.threed/texture) κατά την εξαγωγή ως FBX. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


Αρχικοποιεί ένα [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Παράδειγμα του [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat), πρέπει να είναι έγκυρη μορφή FBX. |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


Αρχικοποιήστε ένα [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) χρησιμοποιώντας την πιο πρόσφατη υποστηριζόμενη έκδοση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | Δυαδικό ή ASCII |

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


Λαμβάνει αν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. Ο FBX Exporter θα προσπαθήσει να βρει τα ακατέργαστα δεδομένα της υφής από το [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) και θα ενσωματώσει το αρχείο στο τελικό αρχείο FBX. Η προεπιλεγμένη τιμή είναι ψευδής.

**Returns:**
boolean - αν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. Ο FBX Exporter θα προσπαθήσει να βρει τα ακατέργαστα δεδομένα της υφής από το [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) και θα ενσωματώσει το αρχείο στο τελικό αρχείο FBX. Η προεπιλεγμένη τιμή είναι ψευδής.
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. δεδομένα κίνησης, σημεία ελέγχου, δεδομένα στοιχείων κορυφής, δείκτες), η προεπιλεγμένη τιμή είναι αληθής.

**Returns:**
boolean - Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. δεδομένα κίνησης, σημεία ελέγχου, δεδομένα στοιχείων κορυφής, δείκτες), η προεπιλεγμένη τιμή είναι αληθής.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.

**Returns:**
java.nio.charset.Charset - η προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


Λαμβάνει αν θα εξαχθούν οι κληρονομικές ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. Αυτή η επιλογή είναι ενεργοποιημένη από προεπιλογή.

**Returns:**
boolean - αν θα εξαχθούν οι κληρονομικές ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. Αυτή η επιλογή είναι ενεργοποιημένη από προεπιλογή.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.

**Returns:**
boolean - Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.
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
### getFoldRepeatedCurveData() {#getFoldRepeatedCurveData--}
```
public Boolean getFoldRepeatedCurveData()
```


Λαμβάνει αν θα επαναχρησιμοποιηθεί επαναλαμβανόμενο δεδομένο καμπύλης αυξάνοντας τον αριθμό αναφορών του τελευταίου δεδομένου

**Returns:**
java.lang.Boolean - αν θα επαναχρησιμοποιηθεί επαναλαμβανόμενο δεδομένο καμπύλης αυξάνοντας τον αριθμό αναφορών του τελευταίου δεδομένου
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


Λαμβάνει αν θα δημιουργείται πάντα ένα [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. Αυτό είναι απενεργοποιημένο από προεπιλογή.

**Returns:**
boolean - αν θα δημιουργείται πάντα ένα [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. Αυτό είναι απενεργοποιημένο από προεπιλογή.
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
### getReusePrimitiveMesh() {#getReusePrimitiveMesh--}
```
public boolean getReusePrimitiveMesh()
```


Επαναχρησιμοποιήστε το πλέγμα για τα πρωτότυπα με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος της εξόδου FBX όταν η σκηνή έχει κατασκευαστεί από μεγάλο σύνολο πρωτότυπων σχημάτων (όπως εισαγόμενα από αρχεία CAD). Η προεπιλεγμένη τιμή είναι ψευδής

**Returns:**
boolean - Επαναχρησιμοποίηση του πλέγματος για τα πρωτότυπα με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος του εξόδου FBX, το οποίο σκηνή κατασκευάστηκε από μεγάλο σύνολο πρωτότυπων σχημάτων (όπως εισήχθησαν από αρχεία CAD). Η προεπιλεγμένη τιμή είναι false
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


Λαμβάνει αν θα δημιουργηθεί ένα αντικείμενο Video για το [Texture](../../com.aspose.threed/texture) κατά την εξαγωγή ως FBX.

**Returns:**
boolean - αν θα δημιουργηθεί μια παρουσία Video για το [Texture](../../com.aspose.threed/texture) κατά την εξαγωγή ως FBX.
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


Ορίζει αν θα ενσωματωθεί η υφή στο τελικό αρχείο εξόδου. Ο FBX Exporter θα προσπαθήσει να βρει τα ακατέργαστα δεδομένα της υφής από το [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\\#getFileSystem) και να ενσωματώσει το αρχείο στο τελικό αρχείο FBX. Η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


Συμπίεση μεγάλων δυαδικών δεδομένων στο αρχείο FBX (π.χ. δεδομένα κίνησης, σημεία ελέγχου, δεδομένα στοιχείων κορυφής, δείκτες), η προεπιλεγμένη τιμή είναι αληθής.

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

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


Ορίζει αν θα εξαχθούν οι κληρονομικές ιδιότητες υλικού, που χρησιμοποιούνται για συμβατότητα με παλαιότερες εκδόσεις. Αυτή η επιλογή είναι ενεργοποιημένη από προεπιλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

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

### setFoldRepeatedCurveData(Boolean value) {#setFoldRepeatedCurveData-java.lang.Boolean-}
```
public void setFoldRepeatedCurveData(Boolean value)
```


Ορίζει αν θα επαναχρησιμοποιηθεί επαναλαμβανόμενο δεδομένο καμπύλης αυξάνοντας τον αριθμό αναφορών του τελευταίου δεδομένου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Boolean | Νέα τιμή |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


Ορίζει αν θα δημιουργείται πάντα ένα [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) για γεωμετρίες εάν ο συνημμένος κόμβος περιέχει υλικά. Αυτό είναι απενεργοποιημένο από προεπιλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

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

### setReusePrimitiveMesh(boolean value) {#setReusePrimitiveMesh-boolean-}
```
public void setReusePrimitiveMesh(boolean value)
```


Επαναχρησιμοποιήστε το πλέγμα για τα πρωτότυπα με τις ίδιες παραμέτρους, αυτό θα μειώσει σημαντικά το μέγεθος της εξόδου FBX όταν η σκηνή έχει κατασκευαστεί από μεγάλο σύνολο πρωτότυπων σχημάτων (όπως εισαγόμενα από αρχεία CAD). Η προεπιλεγμένη τιμή είναι ψευδής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


Ορίζει αν θα δημιουργηθεί ένα αντικείμενο Video για το [Texture](../../com.aspose.threed/texture) κατά την εξαγωγή ως FBX.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

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

