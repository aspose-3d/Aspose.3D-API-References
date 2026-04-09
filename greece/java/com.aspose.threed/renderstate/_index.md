---
title: RenderState
second_title: Aspose.3D for Java API Reference
description: Κατάσταση απόδοσης για την κατασκευή του pipeline. Οι αλλαγές που γίνονται στην κατάσταση απόδοσης δεν θα επηρεάσουν τις δημιουργημένες παρουσίες του pipeline.
type: docs
weight: 151
url: /el/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Κατάσταση απόδοσης για την κατασκευή του pipeline. Οι αλλαγές που γίνονται στην κατάσταση απόδοσης δεν θα επηρεάσουν τις δημιουργημένες παρουσίες του pipeline.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [RenderState()](#RenderState--) | Κατασκευαστής της [RenderState](../../com.aspose.threed/renderstate) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Αποδεσμεύει το [RenderState](../../com.aspose.threed/renderstate) και απελευθερώνει όλους τους εσωτερικούς πόρους. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Συγκρίνετε την κατάσταση απόδοσης με άλλη παρουσία. |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με ένα καθορισμένο αντικείμενο. |
| [getBlend()](#getBlend--) | Ενεργοποίηση ή απενεργοποίηση της ανάμειξης θραυσμάτων. |
| [getBlendColor()](#getBlendColor--) | Λαμβάνει το χρώμα ανάμειξης όπου χρησιμοποιείται στο [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Ενεργοποίηση ή απενεργοποίηση του cull face |
| [getCullFaceMode()](#getCullFaceMode--) | Λαμβάνει ποια πλευρά θα αποκοπεί. |
| [getDepthFunction()](#getDepthFunction--) | Λαμβάνει τη λειτουργία σύγκρισης που χρησιμοποιείται στο τεστ βάθους |
| [getDepthMask()](#getDepthMask--) | Ενεργοποιήστε ή απενεργοποιήστε τη γραφή βάθους. |
| [getDepthTest()](#getDepthTest--) | Ενεργοποίηση ή απενεργοποίηση του ελέγχου βάθους. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Λαμβάνει πώς αναμειγνύεται το χρώμα. |
| [getFrontFace()](#getFrontFace--) | Λαμβάνει ποια σειρά είναι η μπροστινή όψη |
| [getPolygonMode()](#getPolygonMode--) | Gets the polygon's render mode. |
| [getScissorTest()](#getScissorTest--) | Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή scissor |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Λαμβάνει πώς αναμειγνύεται το χρώμα. |
| [getStencilBackFace()](#getStencilBackFace--) | Λαμβάνει την κατάσταση stencil για το πίσω πρόσωπο. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Λαμβάνει την κατάσταση stencil για το μπροστινό πρόσωπο. |
| [getStencilMask()](#getStencilMask--) | Gets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [getStencilReference()](#getStencilReference--) | Gets the reference value for the stencil test. |
| [getStencilTest()](#getStencilTest--) | Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή stencil. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την περίπτωση. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Ενεργοποίηση ή απενεργοποίηση της ανάμειξης θραυσμάτων. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Ενεργοποίηση ή απενεργοποίηση του cull face |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Sets which face will be culled. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Sets the compare function used in depth test |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Ενεργοποιήστε ή απενεργοποιήστε τη γραφή βάθους. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Ενεργοποίηση ή απενεργοποίηση του ελέγχου βάθους. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Sets which order is front face. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Ορίζει τη λειτουργία απόδοσης του πολυγώνου. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή scissor |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setStencilMask(int value)](#setStencilMask-int-) | Ορίζει τη μάσκα που γίνεται AND με την αναφορά και την αποθηκευμένη τιμή στένσιλ όταν ολοκληρωθεί η δοκιμή. |
| [setStencilReference(int value)](#setStencilReference-int-) | Ορίζει την τιμή αναφοράς για τη δοκιμή στένσιλ. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή stencil. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Κατασκευαστής της [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Αποδεσμεύει το [RenderState](../../com.aspose.threed/renderstate) και απελευθερώνει όλους τους εσωτερικούς πόρους.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Συγκρίνετε την κατάσταση απόδοσης με άλλη παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Άλλη κατάσταση απόδοσης για σύγκριση |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με ένα καθορισμένο αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Ενεργοποίηση ή απενεργοποίηση της ανάμειξης θραυσμάτων.

**Returns:**
boolean - Ενεργοποίηση ή απενεργοποίηση της ανάμειξης θραυσμάτων.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Λαμβάνει το χρώμα ανάμειξης όπου χρησιμοποιείται στο [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


Ενεργοποίηση ή απενεργοποίηση του cull face

**Returns:**
boolean - Ενεργοποίηση ή απενεργοποίηση του cull face
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Λαμβάνει ποια πλευρά θα αποκοπεί.

**Returns:**
int - ποια πλευρά θα αφαιρεθεί.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Λαμβάνει τη λειτουργία σύγκρισης που χρησιμοποιείται στο τεστ βάθους

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Ενεργοποιήστε ή απενεργοποιήστε τη γραφή βάθους.

**Returns:**
boolean - Ενεργοποίηση ή απενεργοποίηση της εγγραφής βάθους.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Ενεργοποίηση ή απενεργοποίηση του ελέγχου βάθους.

**Returns:**
boolean - Ενεργοποίηση ή απενεργοποίηση της δοκιμής βάθους.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Λαμβάνει πώς αναμειγνύεται το χρώμα.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Λαμβάνει ποια σειρά είναι η μπροστινή όψη

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Gets the polygon's render mode.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή scissor

**Returns:**
boolean - Ενεργοποίηση ή απενεργοποίηση της δοκιμής ψαλίδας
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Λαμβάνει πώς αναμειγνύεται το χρώμα.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Λαμβάνει την κατάσταση stencil για το πίσω πρόσωπο.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Λαμβάνει την κατάσταση stencil για το μπροστινό πρόσωπο.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Gets the mask that is ANDed with the both reference and stored stencil value when test is done.

**Returns:**
int - η μάσκα που γίνεται AND με την αναφορά και την αποθηκευμένη τιμή στένσιλ όταν ολοκληρωθεί η δοκιμή.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Gets the reference value for the stencil test.

**Returns:**
int - η τιμή αναφοράς για τη δοκιμή στένσιλ.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή stencil.

**Returns:**
boolean - Ενεργοποίηση ή απενεργοποίηση της δοκιμής στένσιλ.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την περίπτωση.

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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


Ενεργοποίηση ή απενεργοποίηση της ανάμειξης θραυσμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Νέα τιμή |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Ενεργοποίηση ή απενεργοποίηση του cull face

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Sets which face will be culled.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Sets the compare function used in depth test

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Νέα τιμή |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Ενεργοποιήστε ή απενεργοποιήστε τη γραφή βάθους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Ενεργοποίηση ή απενεργοποίηση του ελέγχου βάθους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Νέα τιμή |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Sets which order is front face.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Νέα τιμή |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Ορίζει τη λειτουργία απόδοσης του πολυγώνου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Νέα τιμή |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή scissor

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Νέα τιμή |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Ορίζει τη μάσκα που γίνεται AND με την αναφορά και την αποθηκευμένη τιμή στένσιλ όταν ολοκληρωθεί η δοκιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Ορίζει την τιμή αναφοράς για τη δοκιμή στένσιλ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Ενεργοποιήστε ή απενεργοποιήστε τη δοκιμή stencil.

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

