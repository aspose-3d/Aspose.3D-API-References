---
title: Html5SaveOptions
second_title: Aspose.3D for Java API Reference
description: Επιλογές αποθήκευσης για HTML5
type: docs
weight: 80
url: /el/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για HTML5
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | Κατασκευαστής του [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) με όλες τις προεπιλεγμένες ρυθμίσεις. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Λαμβάνει την αρχική θέση της κάμερας, η προεπιλεγμένη τιμή είναι (10, 10, 10). |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getExportTextures()](#getExportTextures--) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [getFarPlane()](#getFarPlane--) | Λαμβάνει το απομακρυσμένο επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1000. |
| [getFieldOfView()](#getFieldOfView--) | Λαμβάνει το πεδίο θέασης, η προεπιλεγμένη τιμή είναι 45, μετρημένη σε μοίρες. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getLookAt()](#getLookAt--) | Λαμβάνει την προεπιλεγμένη θέση προσανατολισμού, η προεπιλεγμένη τιμή είναι (0, 0, 0). |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [getNearPlane()](#getNearPlane--) | Λαμβάνει το κοντινό επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1. |
| [getOrientationBox()](#getOrientationBox--) | Εμφανίζει ένα κουτί προσανατολισμού. |
| [getShowGrid()](#getShowGrid--) | Εμφανίζει ένα πλέγμα στη σκηνή. |
| [getShowRulers()](#getShowRulers--) | Εμφανίζει χάρακες των αξόνων x/y/z στη σκηνή για τη μέτρηση του μοντέλου. |
| [getShowUI()](#getShowUI--) | Εμφανίζει ένα απλό UI στη σκηνή. |
| [getUpVector()](#getUpVector--) | Λαμβάνει το διάνυσμα up, η τιμή μπορεί να είναι "x"/"y"/"z", η προεπιλεγμένη τιμή είναι "y" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | Ορίζει τη αρχική θέση της κάμερας, η προεπιλεγμένη τιμή είναι (10, 10, 10) |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [setFarPlane(double value)](#setFarPlane-double-) | Ορίζει το απομακρυσμένο επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1000. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Ορίζει το πεδίο της προβολής, η προεπιλεγμένη τιμή είναι 45, μετρημένο σε μοίρες. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Ορίζει τη προεπιλεγμένη θέση προβολής, η προεπιλεγμένη τιμή είναι (0, 0, 0) |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [setNearPlane(double value)](#setNearPlane-double-) | Ορίζει το κοντινό επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1 |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | Εμφανίζει ένα κουτί προσανατολισμού. |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | Εμφανίζει ένα πλέγμα στη σκηνή. |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | Εμφανίζει χάρακες των αξόνων x/y/z στη σκηνή για τη μέτρηση του μοντέλου. |
| [setShowUI(boolean value)](#setShowUI-boolean-) | Εμφανίζει ένα απλό UI στη σκηνή. |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | Ορίζει το διάνυσμα up, η τιμή μπορεί να είναι "x"/"y"/"z", η προεπιλεγμένη τιμή είναι "y" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


Κατασκευαστής του [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) με όλες τις προεπιλεγμένες ρυθμίσεις.

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
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


Λαμβάνει την αρχική θέση της κάμερας, η προεπιλεγμένη τιμή είναι (10, 10, 10).

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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Λαμβάνει το απομακρυσμένο επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1000.

**Returns:**
double - το απομακρυσμένο επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1000.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Λαμβάνει το πεδίο θέασης, η προεπιλεγμένη τιμή είναι 45, μετρημένη σε μοίρες.

**Returns:**
double - το πεδίο της προβολής, η προεπιλεγμένη τιμή είναι 45, μετρημένο σε μοίρες.
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
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Λαμβάνει την προεπιλεγμένη θέση προσανατολισμού, η προεπιλεγμένη τιμή είναι (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
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
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Λαμβάνει το κοντινό επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1.

**Returns:**
double - το κοντινό επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


Εμφανίζει ένα κουτί προσανατολισμού. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean - Εμφανίζει ένα κουτί προσανατολισμού. Η προεπιλεγμένη τιμή είναι true.
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


Εμφανίζει ένα πλέγμα στη σκηνή. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean - Εμφανίζει ένα πλέγμα στη σκηνή. Η προεπιλεγμένη τιμή είναι true.
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


Εμφανίζει χάρακες των αξόνων x/y/z στη σκηνή για μέτρηση του μοντέλου. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean - Εμφανίζει χάρακες των αξόνων x/y/z στη σκηνή για μέτρηση του μοντέλου. Η προεπιλεγμένη τιμή είναι false.
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


Εμφανίζει ένα απλό UI στη σκηνή. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean - Εμφανίζει ένα απλό UI στη σκηνή. Η προεπιλεγμένη τιμή είναι true.
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


Λαμβάνει το διάνυσμα up, η τιμή μπορεί να είναι "x"/"y"/"z", η προεπιλεγμένη τιμή είναι "y"

**Returns:**
java.lang.String - το διάνυσμα up, η τιμή μπορεί να είναι "x"/"y"/"z", η προεπιλεγμένη τιμή είναι "y"
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


Ορίζει τη αρχική θέση της κάμερας, η προεπιλεγμένη τιμή είναι (10, 10, 10)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Ορίζει το απομακρυσμένο επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1000.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Ορίζει το πεδίο της προβολής, η προεπιλεγμένη τιμή είναι 45, μετρημένο σε μοίρες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Ορίζει τη προεπιλεγμένη θέση προβολής, η προεπιλεγμένη τιμή είναι (0, 0, 0)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

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

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Ορίζει το κοντινό επίπεδο της κάμερας, η προεπιλεγμένη τιμή είναι 1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


Εμφανίζει ένα κουτί προσανατολισμού. Η προεπιλεγμένη τιμή είναι true.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


Εμφανίζει ένα πλέγμα στη σκηνή. Η προεπιλεγμένη τιμή είναι true.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


Εμφανίζει χάρακες των αξόνων x/y/z στη σκηνή για μέτρηση του μοντέλου. Η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


Εμφανίζει ένα απλό UI στη σκηνή. Η προεπιλεγμένη τιμή είναι true.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


Ορίζει το διάνυσμα up, η τιμή μπορεί να είναι "x"/"y"/"z", η προεπιλεγμένη τιμή είναι "y"

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

