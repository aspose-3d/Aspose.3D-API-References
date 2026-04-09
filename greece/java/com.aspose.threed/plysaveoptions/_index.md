---
title: PlySaveOptions
second_title: Aspose.3D for Java API Reference
description: Save options for exporting scene as PLY file.
type: docs
weight: 131
url: /el/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

Save options for exporting scene as PLY file.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | Κατασκευαστής του [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | Κατασκευαστής του [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | Αποκτά το σύστημα αξόνων στο εξαγόμενο αρχείο stl. |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | Τα ονόματα των στοιχείων για το χρώμα κορυφής, η προεπιλεγμένη τιμή είναι ("red", "green", "blue") |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getExportTextures()](#getExportTextures--) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [getFaceElement()](#getFaceElement--) | Το όνομα του στοιχείου για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "face" |
| [getFaceProperty()](#getFaceProperty--) | Το όνομα της ιδιότητας για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "vertex\_index" |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getFlipCoordinate()](#getFlipCoordinate--) | Αναστροφή του συντεταγμένου κατά την αποθήκευση της σκηνής, η προεπιλεγμένη τιμή είναι true |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [getNormalComponents()](#getNormalComponents--) | Τα ονόματα των στοιχείων για τα δεδομένα κανονικών, η προεπιλεγμένη τιμή είναι ("nx", "ny", "nz") |
| [getPointCloud()](#getPointCloud--) | Εξαγωγή της σκηνής ως σύννεφο σημείων, η προεπιλεγμένη τιμή είναι false. |
| [getPositionComponents()](#getPositionComponents--) | Τα ονόματα των στοιχείων για τα δεδομένα θέσης, η προεπιλεγμένη τιμή είναι ("x", "y", "z") |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | Τα ονόματα των στοιχείων για τα δεδομένα συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι ("u", "v") |
| [getVertexElement()](#getVertexElement--) | Το όνομα του στοιχείου για τα δεδομένα κορυφής, η προεπιλεγμένη τιμή είναι "vertex" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Ορίζει το σύστημα αξόνων στο εξαγόμενο αρχείο stl. |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Τα ονόματα των στοιχείων για το χρώμα κορυφής, η προεπιλεγμένη τιμή είναι ("red", "green", "blue") |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | Το όνομα του στοιχείου για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "face" |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | Το όνομα της ιδιότητας για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "vertex\_index" |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | Αναστροφή του συντεταγμένου κατά την αποθήκευση της σκηνής, η προεπιλεγμένη τιμή είναι true |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Τα ονόματα των στοιχείων για τα δεδομένα κανονικών, η προεπιλεγμένη τιμή είναι ("nx", "ny", "nz") |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | Εξαγωγή της σκηνής ως σύννεφο σημείων, η προεπιλεγμένη τιμή είναι false. |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Τα ονόματα των στοιχείων για τα δεδομένα θέσης, η προεπιλεγμένη τιμή είναι ("x", "y", "z") |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | Τα ονόματα των στοιχείων για τα δεδομένα συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι ("u", "v") |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | Το όνομα του στοιχείου για τα δεδομένα κορυφής, η προεπιλεγμένη τιμή είναι "vertex" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


Κατασκευαστής του [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


Κατασκευαστής του [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Αποκτά το σύστημα αξόνων στο εξαγόμενο αρχείο stl.

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


Τα ονόματα των στοιχείων για το χρώμα κορυφής, η προεπιλεγμένη τιμή είναι ("red", "green", "blue")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Τα ονόματα των στοιχείων για το χρώμα της κορυφής, η προεπιλεγμένη τιμή είναι ("red", "green", "blue")
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
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


Το όνομα του στοιχείου για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "face"

**Returns:**
java.lang.String - Το όνομα του στοιχείου για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "face"
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


Το όνομα της ιδιότητας για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "vertex\_index"

**Returns:**
java.lang.String - Το όνομα της ιδιότητας για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "vertex\_index"
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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


Αναστροφή του συντεταγμένου κατά την αποθήκευση της σκηνής, η προεπιλεγμένη τιμή είναι true

**Returns:**
boolean - Αναστροφή του συντεταγμένου κατά την αποθήκευση της σκηνής, η προεπιλεγμένη τιμή είναι true
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
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


Τα ονόματα των στοιχείων για τα δεδομένα κανονικών, η προεπιλεγμένη τιμή είναι ("nx", "ny", "nz")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Τα ονόματα των στοιχείων για τα δεδομένα κανονικών, η προεπιλεγμένη τιμή είναι ("nx", "ny", "nz")
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


Εξαγωγή της σκηνής ως σύννεφο σημείων, η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean - Εξαγωγή της σκηνής ως σύννεφο σημείων, η προεπιλεγμένη τιμή είναι false.
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


Τα ονόματα των στοιχείων για τα δεδομένα θέσης, η προεπιλεγμένη τιμή είναι ("x", "y", "z")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Τα ονόματα των στοιχείων για τα δεδομένα θέσης, η προεπιλεγμένη τιμή είναι ("x", "y", "z")
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


Τα ονόματα των στοιχείων για τα δεδομένα συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι ("u", "v")

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - Τα ονόματα των στοιχείων για τα δεδομένα συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι ("u", "v")
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


Το όνομα του στοιχείου για τα δεδομένα κορυφής, η προεπιλεγμένη τιμή είναι "vertex"

**Returns:**
java.lang.String - Το όνομα του στοιχείου για τα δεδομένα κορυφής, η προεπιλεγμένη τιμή είναι "vertex"
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


Ορίζει το σύστημα αξόνων στο εξαγόμενο αρχείο stl.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Νέα τιμή **Remarks:** FlipCoordinateSystem πρέπει να ενεργοποιηθεί για να χρησιμοποιηθεί αυτή η λειτουργία. |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


Τα ονόματα των στοιχείων για το χρώμα κορυφής, η προεπιλεγμένη τιμή είναι ("red", "green", "blue")

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Νέα τιμή |

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

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


Το όνομα του στοιχείου για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "face"

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


Το όνομα της ιδιότητας για τα δεδομένα προσώπου, η προεπιλεγμένη τιμή είναι "vertex\_index"

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


Αναστροφή του συντεταγμένου κατά την αποθήκευση της σκηνής, η προεπιλεγμένη τιμή είναι true

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

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


Τα ονόματα των στοιχείων για τα δεδομένα κανονικών, η προεπιλεγμένη τιμή είναι ("nx", "ny", "nz")

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Νέα τιμή |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


Εξαγωγή της σκηνής ως σύννεφο σημείων, η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


Τα ονόματα των στοιχείων για τα δεδομένα θέσης, η προεπιλεγμένη τιμή είναι ("x", "y", "z")

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Νέα τιμή |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


Τα ονόματα των στοιχείων για τα δεδομένα συντεταγμένων υφής, η προεπιλεγμένη τιμή είναι ("u", "v")

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | Νέα τιμή |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


Το όνομα του στοιχείου για τα δεδομένα κορυφής, η προεπιλεγμένη τιμή είναι "vertex"

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

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

