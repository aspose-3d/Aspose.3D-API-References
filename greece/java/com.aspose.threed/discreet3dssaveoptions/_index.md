---
title: Discreet3dsSaveOptions
second_title: Aspose.3D for Java API Reference
description: Επιλογές αποθήκευσης για αρχείο 3DS.
type: docs
weight: 44
url: /el/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για αρχείο 3DS.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | Κατασκευαστής της [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | Ο μετρητής που χρησιμοποιείται για τη δημιουργία νέου ονόματος για διπλότυπα ονόματα, η προεπιλεγμένη τιμή είναι 2. |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | Η μορφή του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά. |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | Ο διαχωριστής μεταξύ του ονόματος του αντικειμένου και του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι "\_". |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getExportCamera()](#getExportCamera--) | Λαμβάνει αν θα εξαχθούν όλες οι κάμερες στη σκηνή. |
| [getExportLight()](#getExportLight--) | Λαμβάνει αν θα εξαχθούν όλα τα φώτα στη σκηνή. |
| [getExportTextures()](#getExportTextures--) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Λαμβάνει την αντιστροφή του συστήματος συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή/εξαγωγή. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | Ένα αρχείο 3ds μπορεί να περιέχει αρχικό χρώμα και χρώμα διορθωμένο με γάμμα για το ίδιο χαρακτηριστικό· ορίζοντας αυτό σε true θα χρησιμοποιηθεί το χρώμα διορθωμένο με γάμμα αν είναι δυνατόν, διαφορετικά το Aspose.3D θα προσπαθήσει να χρησιμοποιήσει το αρχικό χρώμα. |
| [getHighPreciseColor()](#getHighPreciseColor--) | Εάν αυτό είναι true, το παραγόμενο αρχείο 3ds θα χρησιμοποιεί χρώμα υψηλής ακρίβειας, δηλαδή κάθε κανάλι κόκκινο/πράσινο/μπλε είναι σε 32-bit float. |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [getMasterScale()](#getMasterScale--) | Λαμβάνει την κύρια κλίμακα που χρησιμοποιείται κατά την εξαγωγή. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | Ο μετρητής που χρησιμοποιείται για τη δημιουργία νέου ονόματος για διπλότυπα ονόματα, η προεπιλεγμένη τιμή είναι 2. |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | Η μορφή του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά. |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | Ο διαχωριστής μεταξύ του ονόματος του αντικειμένου και του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι "\_". |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | Ορίζει εάν θα εξάγει όλες τις κάμερες στη σκηνή. |
| [setExportLight(boolean value)](#setExportLight-boolean-) | Ορίζει εάν θα εξάγει όλα τα φώτα στη σκηνή. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Ορίζει την αντιστροφή του συστήματος συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή/εξαγωγή. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | Ένα αρχείο 3ds μπορεί να περιέχει αρχικό χρώμα και χρώμα διορθωμένο με γάμμα για το ίδιο χαρακτηριστικό· ορίζοντας αυτό σε true θα χρησιμοποιηθεί το χρώμα διορθωμένο με γάμμα αν είναι δυνατόν, διαφορετικά το Aspose.3D θα προσπαθήσει να χρησιμοποιήσει το αρχικό χρώμα. |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | Εάν αυτό είναι true, το παραγόμενο αρχείο 3ds θα χρησιμοποιεί χρώμα υψηλής ακρίβειας, δηλαδή κάθε κανάλι κόκκινο/πράσινο/μπλε είναι σε 32-bit float. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [setMasterScale(double value)](#setMasterScale-double-) | Ορίζει την κύρια κλίμακα που χρησιμοποιείται κατά την εξαγωγή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


Κατασκευαστής της [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions)

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
### getDuplicatedNameCounterBase() {#getDuplicatedNameCounterBase--}
```
public int getDuplicatedNameCounterBase()
```


Ο μετρητής που χρησιμοποιείται για τη δημιουργία νέου ονόματος για διπλότυπα ονόματα, η προεπιλεγμένη τιμή είναι 2.

**Returns:**
int - Ο μετρητής που χρησιμοποιείται για τη δημιουργία νέου ονόματος για διπλότυπα ονόματα, η προεπιλεγμένη τιμή είναι 2.
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


Η μορφή του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά.

**Returns:**
java.lang.String - Η μορφή του μετρητή διπλοτύπων, η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά.
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


Ο διαχωριστής μεταξύ του ονόματος του αντικειμένου και του μετρητή διπλοτύπων, η προεπιλεγμένη τιμή είναι "\_". Όταν η σκηνή περιέχει αντικείμενα που χρησιμοποιούν το ίδιο όνομα, ο εξαγωγέας Aspose.3D 3DS θα δημιουργήσει διαφορετικό όνομα για το αντικείμενο. Για παράδειγμα, υπάρχουν δύο κόμβοι με όνομα "Box", ο πρώτος κόμβος θα έχει όνομα "Box", και ο δεύτερος θα λάβει νέο όνομα "Box\_2" χρησιμοποιώντας την προεπιλεγμένη διαμόρφωση.

**Returns:**
java.lang.String - Ο διαχωριστής μεταξύ του ονόματος του αντικειμένου και του μετρητή διπλοτύπων, η προεπιλεγμένη τιμή είναι "\_". Όταν η σκηνή περιέχει αντικείμενα που χρησιμοποιούν το ίδιο όνομα, ο εξαγωγέας Aspose.3D 3DS θα δημιουργήσει διαφορετικό όνομα για το αντικείμενο. Για παράδειγμα, υπάρχουν δύο κόμβοι με όνομα "Box", ο πρώτος κόμβος θα έχει όνομα "Box", και ο δεύτερος θα λάβει νέο όνομα "Box\_2" χρησιμοποιώντας την προεπιλεγμένη διαμόρφωση.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.

**Returns:**
java.nio.charset.Charset - η προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


Λαμβάνει αν θα εξαχθούν όλες οι κάμερες στη σκηνή.

**Returns:**
boolean - εάν θα εξάγει όλες τις κάμερες στη σκηνή.
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


Λαμβάνει αν θα εξαχθούν όλα τα φώτα στη σκηνή.

**Returns:**
boolean - εάν θα εξάγει όλα τα φώτα στη σκηνή.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


Λαμβάνει την αντιστροφή του συστήματος συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή/εξαγωγή.

**Returns:**
boolean - αντιστροφή του συστήματος συντεταγμένων των σημείων ελέγχου/κανονικής κατά την εισαγωγή/εξαγωγή.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


Ένα αρχείο 3ds μπορεί να περιέχει αρχικό χρώμα και χρώμα διορθωμένο με γάμμα για το ίδιο χαρακτηριστικό· ορίζοντας αυτό σε true θα χρησιμοποιηθεί το χρώμα διορθωμένο με γάμμα αν είναι δυνατόν, διαφορετικά το Aspose.3D θα προσπαθήσει να χρησιμοποιήσει το αρχικό χρώμα.

**Returns:**
boolean - Ένα αρχείο 3ds μπορεί να περιέχει αρχικό χρώμα και χρώμα διορθωμένο με γάμμα για το ίδιο χαρακτηριστικό. Ορίζοντας αυτό σε true θα χρησιμοποιηθεί το χρώμα διορθωμένο με γάμμα αν είναι δυνατόν, διαφορετικά το Aspose.3D θα προσπαθήσει να χρησιμοποιήσει το αρχικό χρώμα.
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


Εάν αυτό είναι true, το παραγόμενο αρχείο 3ds θα χρησιμοποιεί χρώμα υψηλής ακρίβειας, δηλαδή κάθε κανάλι κόκκινου/πράσινου/μπλε είναι σε 32‑bit float. Διαφορετικά, το παραγόμενο αρχείο θα χρησιμοποιεί χρώμα 24‑bit, κάθε κανάλι σε 8‑bit byte. Η προεπιλεγμένη τιμή είναι false, επειδή δεν υποστηρίζουν όλα τα εφαρμογές το χρώμα υψηλής ακρίβειας.

**Returns:**
boolean - Εάν αυτό είναι true, το παραγόμενο αρχείο 3ds θα χρησιμοποιεί χρώμα υψηλής ακρίβειας, δηλαδή κάθε κανάλι κόκκινου/πράσινου/μπλε είναι σε 32‑bit float. Διαφορετικά, το παραγόμενο αρχείο θα χρησιμοποιεί χρώμα 24‑bit, κάθε κανάλι σε 8‑bit byte. Η προεπιλεγμένη τιμή είναι false, επειδή δεν υποστηρίζουν όλα τα εφαρμογές το χρώμα υψηλής ακρίβειας.
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
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


Λαμβάνει την κύρια κλίμακα που χρησιμοποιείται κατά την εξαγωγή.

**Returns:**
double - η κύρια κλίμακα που χρησιμοποιείται κατά την εξαγωγή.
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




### setDuplicatedNameCounterBase(int value) {#setDuplicatedNameCounterBase-int-}
```
public void setDuplicatedNameCounterBase(int value)
```


Ο μετρητής που χρησιμοποιείται για τη δημιουργία νέου ονόματος για διπλότυπα ονόματα, η προεπιλεγμένη τιμή είναι 2.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


Η μορφή του διπλότυπου μετρητή, η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


Ο διαχωριστής μεταξύ του ονόματος του αντικειμένου και του μετρητή διπλοτύπων, η προεπιλεγμένη τιμή είναι "\_". Όταν η σκηνή περιέχει αντικείμενα που χρησιμοποιούν το ίδιο όνομα, ο εξαγωγέας Aspose.3D 3DS θα δημιουργήσει διαφορετικό όνομα για το αντικείμενο. Για παράδειγμα, υπάρχουν δύο κόμβοι με όνομα "Box", ο πρώτος κόμβος θα έχει όνομα "Box", και ο δεύτερος θα λάβει νέο όνομα "Box\_2" χρησιμοποιώντας την προεπιλεγμένη διαμόρφωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιήσει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset | Νέα τιμή |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


Ορίζει εάν θα εξάγει όλες τις κάμερες στη σκηνή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


Ορίζει εάν θα εξάγει όλα τα φώτα στη σκηνή.

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


Ορίζει την αντιστροφή του συστήματος συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή/εξαγωγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


Ένα αρχείο 3ds μπορεί να περιέχει αρχικό χρώμα και χρώμα διορθωμένο με γάμμα για το ίδιο χαρακτηριστικό· ορίζοντας αυτό σε true θα χρησιμοποιηθεί το χρώμα διορθωμένο με γάμμα αν είναι δυνατόν, διαφορετικά το Aspose.3D θα προσπαθήσει να χρησιμοποιήσει το αρχικό χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


Εάν αυτό είναι true, το παραγόμενο αρχείο 3ds θα χρησιμοποιεί χρώμα υψηλής ακρίβειας, δηλαδή κάθε κανάλι κόκκινου/πράσινου/μπλε είναι σε 32‑bit float. Διαφορετικά, το παραγόμενο αρχείο θα χρησιμοποιεί χρώμα 24‑bit, κάθε κανάλι σε 8‑bit byte. Η προεπιλεγμένη τιμή είναι false, επειδή δεν υποστηρίζουν όλα τα εφαρμογές το χρώμα υψηλής ακρίβειας.

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

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


Ορίζει την κύρια κλίμακα που χρησιμοποιείται κατά την εξαγωγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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

