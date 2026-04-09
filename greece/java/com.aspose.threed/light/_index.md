---
title: Light
second_title: Aspose.3D for Java API Reference
description: Το φως φωτίζει τη σκηνή.
type: docs
weight: 94
url: /el/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

Το φως φωτίζει τη σκηνή.

Ο τύπος για τον υπολογισμό της συνολικής εξασθένισης του φωτός είναι:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Light()](#Light--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Light](../../com.aspose.threed/light). |
| [Light(String name)](#Light-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Light](../../com.aspose.threed/light). |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Light](../../com.aspose.threed/light). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getAspect()](#getAspect--) | Λαμβάνει την αναλογία διαστάσεων του frustum |
| [getBoundingBox()](#getBoundingBox--) | Λαμβάνει το πλαίσιο περιβάλλουσας της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| [getCastLight()](#getCastLight--) | Λαμβάνει αν η τρέχουσα παρουσία του φωτός μπορεί να φωτίσει άλλα αντικείμενα. |
| [getCastShadows()](#getCastShadows--) | Λαμβάνει αν το φως μπορεί να ρίξει σκιές σε άλλα αντικείμενα. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Λαμβάνει το χρώμα του φωτός |
| [getConstantAttenuation()](#getConstantAttenuation--) | Λαμβάνει την σταθερή εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός |
| [getDirection()](#getDirection--) | Λαμβάνει την κατεύθυνση προς την οποία κοιτάζει η κάμερα. |
| [getEntityRendererKey()](#getEntityRendererKey--) | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον αποτυπωτή |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [getFalloff()](#getFalloff--) | Λαμβάνει τη γωνία εκπτώσεως του κώνου (σε μοίρες). |
| [getFarPlane()](#getFarPlane--) | Λαμβάνει την απόσταση του απομακρυσμένου επιπέδου του frustum. |
| [getHotSpot()](#getHotSpot--) | Λαμβάνει τη γωνία κώνου του σημείου ανάφλεξης (σε μοίρες). |
| [getIntensity()](#getIntensity--) | Λαμβάνει την ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100 |
| [getLightType()](#getLightType--) | Λαμβάνει τον τύπο του φωτός |
| [getLinearAttenuation()](#getLinearAttenuation--) | Λαμβάνει τη γραμμική αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός |
| [getLookAt()](#getLookAt--) | Λαμβάνει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getNearPlane()](#getNearPlane--) | Λαμβάνει την απόσταση του κοντινού επιπέδου του πυρήνα προβολής. |
| [getOrthoHeight()](#getOrthoHeight--) | Λαμβάνει το ύψος όταν ο πυρήνας προβολής είναι ορθογώνιος. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [getParentNodes()](#getParentNodes--) | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρικών αντιγράφων. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | Λαμβάνει την τετραγωνική αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός |
| [getRotationMode()](#getRotationMode--) | Λαμβάνει τη λειτουργία προσανατολισμού του πυρήνα προβολής. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [getTarget](../../com.aspose.threed/frustum\#getTarget) είναι null. |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getShadowColor()](#getShadowColor--) | Λαμβάνει το χρώμα της σκιάς. |
| [getTarget()](#getTarget--) | Λαμβάνει τον στόχο στον οποίο κοιτάζει η κάμερα. |
| [getUp()](#getUp--) | Λαμβάνει την κατεύθυνση πάνω της κάμερας |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setAspect(double value)](#setAspect-double-) | Ορίζει την αναλογία διαστάσεων του πυρήνα προβολής |
| [setCastLight(boolean value)](#setCastLight-boolean-) | Ορίζει αν η τρέχουσα παρουσία φωτός μπορεί να φωτίσει άλλα αντικείμενα. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | Ορίζει αν το φως μπορεί να ρίξει σκιές σε άλλα αντικείμενα. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | Ορίζει το χρώμα του φωτός |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | Ορίζει τη σταθερή αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Ορίζει την κατεύθυνση στην οποία κοιτάζει η κάμερα. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [setFalloff(double value)](#setFalloff-double-) | Ορίζει τη γωνία κώνου εξασθένισης (σε μοίρες). |
| [setFarPlane(double value)](#setFarPlane-double-) | Ορίζει την απόσταση του απομακρυσμένου επιπέδου του πυρήνα προβολής. |
| [setHotSpot(double value)](#setHotSpot-double-) | Ορίζει τη γωνία κώνου του σημείου ανάφλεξης (σε μοίρες). |
| [setIntensity(double value)](#setIntensity-double-) | Ορίζει την ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100 |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | Ορίζει τον τύπο του φωτός |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | Ορίζει τη γραμμική αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Ορίζει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setNearPlane(double value)](#setNearPlane-double-) | Ορίζει την απόσταση του κοντινού επιπέδου του θόλου. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | Ορίζει το ύψος όταν ο θόλος βρίσκεται σε ορθογραφική προβολή. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | Ορίζει την τετραγωνική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός. |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | Ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [getTarget](../../com.aspose.threed/frustum\#getTarget) είναι null. |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | Ορίζει το χρώμα της σκιάς. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Ορίζει τον στόχο προς τον οποίο κοιτάζει η κάμερα. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | Ορίζει την κατεύθυνση προς τα πάνω της κάμερας. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Light](../../com.aspose.threed/light).

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Light](../../com.aspose.threed/light).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Light](../../com.aspose.threed/light).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |
| type | [LightType](../../com.aspose.threed/lighttype) | Νέος τύπος φωτός. |

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
### getAspect() {#getAspect--}
```
public double getAspect()
```


Λαμβάνει την αναλογία διαστάσεων του frustum

**Returns:**
double - η αναλογία διαστάσεων του θόλου
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
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


Λαμβάνει αν η τρέχουσα παρουσία του φωτός μπορεί να φωτίσει άλλα αντικείμενα.

**Returns:**
boolean - αν η τρέχουσα παρουσία φωτός μπορεί να φωτίσει άλλα αντικείμενα.
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


Λαμβάνει αν το φως μπορεί να ρίξει σκιές σε άλλα αντικείμενα.

**Returns:**
boolean - αν το φως μπορεί να ρίξει σκιές σε άλλα αντικείμενα.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Λαμβάνει το χρώμα του φωτός

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Λαμβάνει την σταθερή εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός

**Returns:**
double - η σταθερή εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός
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
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


Λαμβάνει τη γωνία εκπτώσεως του κώνου (σε μοίρες).

**Returns:**
double - η γωνία εκπτώσεως του κώνου (σε μοίρες).
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Λαμβάνει την απόσταση του απομακρυσμένου επιπέδου του frustum.

**Returns:**
double - η απόσταση του απομακρυσμένου επιπέδου του θόλου.
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


Λαμβάνει τη γωνία κώνου του σημείου ανάφλεξης (σε μοίρες).

**Returns:**
double - η γωνία του κώνου του σημείου εστίασης (σε μοίρες).
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


Λαμβάνει την ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100

**Returns:**
double - η ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100.
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


Λαμβάνει τον τύπο του φωτός

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


Λαμβάνει τη γραμμική αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός

**Returns:**
double - η γραμμική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός.
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Λαμβάνει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
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
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


Λαμβάνει την τετραγωνική αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός

**Returns:**
double - η τετραγωνική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός.
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
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


Λαμβάνει το χρώμα της σκιάς.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


Ορίζει την αναλογία διαστάσεων του πυρήνα προβολής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


Ορίζει αν η τρέχουσα παρουσία φωτός μπορεί να φωτίσει άλλα αντικείμενα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


Ορίζει αν το φως μπορεί να ρίξει σκιές σε άλλα αντικείμενα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


Ορίζει το χρώμα του φωτός

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


Ορίζει τη σταθερή αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός

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

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


Ορίζει τη γωνία κώνου εξασθένισης (σε μοίρες).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Ορίζει την απόσταση του απομακρυσμένου επιπέδου του πυρήνα προβολής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


Ορίζει τη γωνία κώνου του σημείου ανάφλεξης (σε μοίρες).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


Ορίζει την ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


Ορίζει τον τύπο του φωτός

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | Νέα τιμή |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


Ορίζει τη γραμμική αποσβέση για τον υπολογισμό της συνολικής αποσβέσης του φωτός

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

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


Ορίζει την τετραγωνική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


Ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το [getTarget](../../com.aspose.threed/frustum\#getTarget) είναι null. Εάν η τιμή είναι [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα [getLookAt](../../com.aspose.threed/frustum\#getLookAt). Διαφορετικά, το [getLookAt](../../com.aspose.threed/frustum\#getLookAt) υπολογίζεται πάντα από το [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | Νέα τιμή |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


Ορίζει το χρώμα της σκιάς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

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

