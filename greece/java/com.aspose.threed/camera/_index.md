---
title: Camera
second_title: Aspose.3D for Java API Reference
description: Η κάμερα περιγράφει το σημείο ματιού του θεατή που κοιτάζει τη σκηνή.
type: docs
weight: 28
url: /el/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

Η κάμερα περιγράφει το σημείο ματιού του θεατή που κοιτάζει τη σκηνή.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Camera()](#Camera--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera). |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera). |
| [Camera(String name)](#Camera-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera). |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getApertureMode()](#getApertureMode--) | Λαμβάνει τη λειτουργία διαφράγματος της κάμερας |
| [getAspect()](#getAspect--) | Λαμβάνει την αναλογία διαστάσεων του frustum |
| [getAspectRatio()](#getAspectRatio--) | Λαμβάνει την αναλογία διαστάσεων του επιπέδου προβολής. |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | Λαμβάνει την κατεύθυνση προς την οποία κοιτάζει η κάμερα. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getFarPlane()](#getFarPlane--) | Λαμβάνει την απόσταση του απομακρυσμένου επιπέδου του frustum. |
| [getFieldOfView()](#getFieldOfView--) | Λαμβάνει το πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ή [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | Λαμβάνει το οριζόντιο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | Λαμβάνει το κάθετο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος του επιπέδου προβολής σε ίντσες |
| [getLookAt()](#getLookAt--) | Λαμβάνει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα. |
| [getMagnification()](#getMagnification--) | Λαμβάνει τη μεγέθυνση που χρησιμοποιείται στην ορθογώνια κάμερα |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getNearPlane()](#getNearPlane--) | Λαμβάνει την απόσταση του κοντινού επιπέδου του πυρήνα προβολής. |
| [getOrthoHeight()](#getOrthoHeight--) | Λαμβάνει το ύψος όταν ο πυρήνας προβολής είναι ορθογώνιος. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProjectionType()](#getProjectionType--) | Λαμβάνει τον τύπο προβολής της κάμερας. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getRotationMode()](#getRotationMode--) | Λαμβάνει τη λειτουργία προσανατολισμού του πυρήνα προβολής. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [getTarget](../../com.aspose.threed/frustum\#getTarget) είναι null. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getTarget()](#getTarget--) | Λαμβάνει τον στόχο στον οποίο κοιτάζει η κάμερα. |
| [getUp()](#getUp--) | Λαμβάνει την κατεύθυνση πάνω της κάμερας |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του επιπέδου προβολής σε ίντσες |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | Μετακινήστε την κάμερα προς τα εμπρός προς την κατεύθυνσή της ή τον στόχο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | Ορίζει τη λειτουργία διαφράγματος της κάμερας |
| [setAspect(double value)](#setAspect-double-) | Ορίζει την αναλογία διαστάσεων του πυρήνα προβολής |
| [setAspectRatio(double value)](#setAspectRatio-double-) | Ορίζει την αναλογία διαστάσεων του επιπέδου προβολής. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Ορίζει την κατεύθυνση στην οποία κοιτάζει η κάμερα. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setFarPlane(double value)](#setFarPlane-double-) | Ορίζει την απόσταση του απομακρυσμένου επιπέδου του πυρήνα προβολής. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Ορίζει το πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ή [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | Ορίζει το οριζόντιο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | Ορίζει το κάθετο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | Ορίζει το ύψος του επιπέδου προβολής σε ίντσες |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Ορίζει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | Ορίζει τη μεγέθυνση που χρησιμοποιείται στην ορθογώνια κάμερα |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setNearPlane(double value)](#setNearPlane-double-) | Ορίζει την απόσταση του κοντινού επιπέδου του θόλου. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Ορίζει το ύψος όταν ο θόλος βρίσκεται σε ορθογραφική προβολή. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | Ορίζει τον τύπο προβολής της κάμερας. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [getTarget](../../com.aspose.threed/frustum\#getTarget) είναι null. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Ορίζει τον στόχο προς τον οποίο κοιτάζει η κάμερα. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Ορίζει την κατεύθυνση προς τα πάνω της κάμερας. |
| [setWidth(double value)](#setWidth-double-) | Ορίζει το πλάτος του επιπέδου προβολής σε ίντσες |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera).

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Τύπος προβολής. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Camera](../../com.aspose.threed/camera).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | Τύπος προβολής. |

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε με CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Προσδιορίζεται με το όνομά της)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | java.lang.String | Όνομα ιδιότητας. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


Λαμβάνει τη λειτουργία διαφράγματος της κάμερας

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Λαμβάνει την αναλογία διαστάσεων του frustum

**Returns:**
double - η αναλογία διαστάσεων του θόλου
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


Λαμβάνει την αναλογία διαστάσεων του επιπέδου προβολής.

**Returns:**
double - η αναλογία διαστάσεων του επιπέδου προβολής.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


Λαμβάνει την κατεύθυνση προς την οποία κοιτάζει η κάμερα. Οι αλλαγές σε αυτήν την ιδιότητα θα επηρεάσουν επίσης το [getLookAt](../../com.aspose.threed/frustum\#getLookAt) και το [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.

**Returns:**
boolean - αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Λαμβάνει την απόσταση του απομακρυσμένου επιπέδου του frustum.

**Returns:**
double - η απόσταση του απομακρυσμένου επιπέδου του θόλου.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Λαμβάνει το πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ή [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
double - το πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ή [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


Λαμβάνει το οριζόντιο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - το οριζόντιο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


Λαμβάνει το κάθετο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - το κάθετο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


Λαμβάνει το ύψος του επιπέδου προβολής σε ίντσες

**Returns:**
double - το ύψος του επιπέδου προβολής σε ίντσες
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Λαμβάνει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


Λαμβάνει τη μεγέθυνση που χρησιμοποιείται στην ορθογώνια κάμερα

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Λαμβάνει την απόσταση του κοντινού επιπέδου του πυρήνα προβολής.

**Returns:**
double - η απόσταση του κοντινού επιπέδου του θόλου.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


Λαμβάνει το ύψος όταν ο πυρήνας προβολής είναι ορθογώνιος.

**Returns:**
double - το ύψος όταν ο θόλος είναι σε ορθογραφική προβολή.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - όλοι οι γονικοί κόμβοι, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιτύπων
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


Λαμβάνει τον τύπο προβολής της κάμερας. Από προεπιλογή χρησιμοποιείται η προοπτική προβολή.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Λαμβάνει τη συλλογή όλων των ιδιοτήτων.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Λάβετε την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |

**Returns:**
java.lang.Object - Η τιμή της ευρεθείσας ιδιότητας
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


Λαμβάνει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [getTarget](../../com.aspose.threed/frustum\#getTarget) είναι null. Εάν η τιμή είναι [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Διαφορετικά, το [getLookAt](../../com.aspose.threed/frustum\#getLookAt) υπολογίζεται πάντα από το [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


Λαμβάνει τον στόχο προς τον οποίο κοιτάζει η κάμερα. Εάν ο χρήστης υποστηρίζει αυτήν την ιδιότητα, θα πρέπει να είναι πριν από την ιδιότητα [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


Λαμβάνει την κατεύθυνση πάνω της κάμερας

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
### getWidth() {#getWidth--}
```
public double getWidth()
```


Λαμβάνει το πλάτος του επιπέδου προβολής σε ίντσες

**Returns:**
double - το πλάτος του επιπέδου προβολής μετρημένο σε ίντσες
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


Μετακινήστε την κάμερα προς τα εμπρός προς την κατεύθυνσή της ή τον στόχο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| απόσταση | double | Πόσο καιρό να κινηθεί μπροστά |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Αφαιρεί μια δυναμική ιδιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


Ορίζει τη λειτουργία διαφράγματος της κάμερας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | Νέα τιμή |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Ορίζει την αναλογία διαστάσεων του πυρήνα προβολής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


Ορίζει την αναλογία διαστάσεων του επιπέδου προβολής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


Ορίζει την κατεύθυνση προς την οποία κοιτάζει η κάμερα. Οι αλλαγές σε αυτήν την ιδιότητα θα επηρεάσουν επίσης το [getLookAt](../../com.aspose.threed/frustum\#getLookAt) και το [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Ορίζει την απόσταση του απομακρυσμένου επιπέδου του πυρήνα προβολής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Ορίζει το πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) ή [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


Ορίζει το οριζόντιο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


Ορίζει το κάθετο πεδίο θέασης της κάμερας σε μοίρες, αυτή η ιδιότητα χρησιμοποιείται μόνο όταν το ApertureMode είναι [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Ορίζει το ύψος του επιπέδου προβολής σε ίντσες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Ορίζει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


Ορίζει τη μεγέθυνση που χρησιμοποιείται στην ορθογώνια κάμερα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Ορίζει την απόσταση του κοντινού επιπέδου του θόλου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


Ορίζει το ύψος όταν ο θόλος βρίσκεται σε ορθογραφική προβολή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Νέα τιμή |

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


Ορίζει τον τύπο προβολής της κάμερας. Από προεπιλογή χρησιμοποιείται η προοπτική προβολή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | Νέα τιμή |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ορίζει την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |
| τιμή | java.lang.Object | Η τιμή της ιδιότητας |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [getTarget](../../com.aspose.threed/frustum\#getTarget) είναι null. Εάν η τιμή είναι [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Διαφορετικά, το [getLookAt](../../com.aspose.threed/frustum\#getLookAt) υπολογίζεται πάντα από το [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Νέα τιμή |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


Ορίζει τον στόχο που κοιτάζει η κάμερα. Εάν ο χρήστης υποστηρίζει αυτήν την ιδιότητα, θα πρέπει να είναι πριν από την ιδιότητα [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Νέα τιμή |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


Ορίζει την κατεύθυνση προς τα πάνω της κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Ορίζει το πλάτος του επιπέδου προβολής σε ίντσες

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

