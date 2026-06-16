---
title: "Light"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/light/
---
## Light class

Το φως φωτίζει τη σκηνή.  Ο τύπος για τον υπολογισμό της συνολικής εξασθένισης του φωτός είναι:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Light. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(name) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Light. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload2(name, type) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Light. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| Όνομα | Περιγραφή |
| --- | --- |
| getColor() | Λαμβάνει ή ορίζει το χρώμα του φωτός |

 **Result:**



---


### setColor{#setColor}

| Όνομα | Περιγραφή |
| --- | --- |
| setColor(value) | Λαμβάνει ή ορίζει το χρώμα του φωτός |

 **Result:**



---


### getLightType{#getLightType}

| Όνομα | Περιγραφή |
| --- | --- |
| getLightType() | Λαμβάνει ή ορίζει τον τύπο του φωτός. Η τιμή της ιδιότητας είναι η ακέραια σταθερά LightType. |

 **Result:**



---


### setLightType{#setLightType}

| Όνομα | Περιγραφή |
| --- | --- |
| setLightType(value) | Λαμβάνει ή ορίζει τον τύπο του φωτός. Η τιμή της ιδιότητας είναι η ακέραια σταθερά LightType. |

 **Result:**



---


### getCastLight{#getCastLight}

| Όνομα | Περιγραφή |
| --- | --- |
| getCastLight() | Λαμβάνει ή ορίζει αν η τρέχουσα παρουσία φωτός μπορεί να φωτίσει άλλα αντικείμενα. |

 **Result:**



---


### setCastLight{#setCastLight}

| Όνομα | Περιγραφή |
| --- | --- |
| setCastLight(value) | Λαμβάνει ή ορίζει αν η τρέχουσα παρουσία φωτός μπορεί να φωτίσει άλλα αντικείμενα. |

 **Result:**



---


### getIntensity{#getIntensity}

| Όνομα | Περιγραφή |
| --- | --- |
| getIntensity() | Λαμβάνει ή ορίζει την ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100 |

 **Result:**



---


### setIntensity{#setIntensity}

| Όνομα | Περιγραφή |
| --- | --- |
| setIntensity(value) | Λαμβάνει ή ορίζει την ένταση του φωτός, η προεπιλεγμένη τιμή είναι 100 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| Όνομα | Περιγραφή |
| --- | --- |
| getHotSpot() | Λαμβάνει ή ορίζει τη γωνία του κώνου του σημείου ανάφλεξης (σε μοίρες). |

 **Result:**



---


### setHotSpot{#setHotSpot}

| Όνομα | Περιγραφή |
| --- | --- |
| setHotSpot(value) | Λαμβάνει ή ορίζει τη γωνία του κώνου του σημείου ανάφλεξης (σε μοίρες). |

 **Result:**



---


### getFalloff{#getFalloff}

| Όνομα | Περιγραφή |
| --- | --- |
| getFalloff() | Λαμβάνει ή ορίζει τη γωνία του κώνου εξασθένισης (σε μοίρες). |

 **Result:**



---


### setFalloff{#setFalloff}

| Όνομα | Περιγραφή |
| --- | --- |
| setFalloff(value) | Λαμβάνει ή ορίζει τη γωνία του κώνου εξασθένισης (σε μοίρες). |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| Όνομα | Περιγραφή |
| --- | --- |
| getConstantAttenuation() | Λαμβάνει ή ορίζει τη σταθερή εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| Όνομα | Περιγραφή |
| --- | --- |
| setConstantAttenuation(value) | Λαμβάνει ή ορίζει τη σταθερή εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| Όνομα | Περιγραφή |
| --- | --- |
| getLinearAttenuation() | Λαμβάνει ή ορίζει τη γραμμική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| Όνομα | Περιγραφή |
| --- | --- |
| setLinearAttenuation(value) | Λαμβάνει ή ορίζει τη γραμμική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| Όνομα | Περιγραφή |
| --- | --- |
| getQuadraticAttenuation() | Λαμβάνει ή ορίζει τη τετραγωνική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| Όνομα | Περιγραφή |
| --- | --- |
| setQuadraticAttenuation(value) | Λαμβάνει ή ορίζει τη τετραγωνική εξασθένιση για τον υπολογισμό της συνολικής εξασθένισης του φωτός |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Όνομα | Περιγραφή |
| --- | --- |
| getCastShadows() | Λαμβάνει ή ορίζει αν το φως μπορεί να ρίχνει σκιές σε άλλα αντικείμενα. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Όνομα | Περιγραφή |
| --- | --- |
| setCastShadows(value) | Λαμβάνει ή ορίζει αν το φως μπορεί να ρίχνει σκιές σε άλλα αντικείμενα. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| Όνομα | Περιγραφή |
| --- | --- |
| getShadowColor() | Λαμβάνει ή ορίζει το χρώμα της σκιάς. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| Όνομα | Περιγραφή |
| --- | --- |
| setShadowColor(value) | Λαμβάνει ή ορίζει το χρώμα της σκιάς. |

 **Result:**



---


### getRotationMode{#getRotationMode}

| Όνομα | Περιγραφή |
| --- | --- |
| getRotationMode() | Λαμβάνει ή ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το Target είναι null. Εάν η τιμή είναι RotationMode.FIXED_TARGET, η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα LookAt. Διαφορετικά, το LookAt υπολογίζεται πάντα από την Direction. Η τιμή της ιδιότητας είναι η ακέραια σταθερά RotationMode. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| Όνομα | Περιγραφή |
| --- | --- |
| setRotationMode(value) | Λαμβάνει ή ορίζει τη λειτουργία προσανατολισμού του θόλου. Αυτή η ιδιότητα λειτουργεί μόνο όταν το Target είναι null. Εάν η τιμή είναι RotationMode.FIXED_TARGET, η κατεύθυνση υπολογίζεται πάντα από την ιδιότητα LookAt. Διαφορετικά, το LookAt υπολογίζεται πάντα από την Direction. Η τιμή της ιδιότητας είναι η ακέραια σταθερά RotationMode. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| Όνομα | Περιγραφή |
| --- | --- |
| getNearPlane() | Λαμβάνει ή ορίζει την απόσταση του κοντινού επιπέδου του θόλου. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| Όνομα | Περιγραφή |
| --- | --- |
| setNearPlane(value) | Λαμβάνει ή ορίζει την απόσταση του κοντινού επιπέδου του θόλου. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| Όνομα | Περιγραφή |
| --- | --- |
| getFarPlane() | Λαμβάνει ή ορίζει την απόσταση του απομακρυσμένου επιπέδου του frustum. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| Όνομα | Περιγραφή |
| --- | --- |
| setFarPlane(value) | Λαμβάνει ή ορίζει την απόσταση του απομακρυσμένου επιπέδου του frustum. |

 **Result:**



---


### getAspect{#getAspect}

| Όνομα | Περιγραφή |
| --- | --- |
| getAspect() | Λαμβάνει ή ορίζει την αναλογία διαστάσεων του frustum |

 **Result:**



---


### setAspect{#setAspect}

| Όνομα | Περιγραφή |
| --- | --- |
| setAspect(value) | Λαμβάνει ή ορίζει την αναλογία διαστάσεων του frustum |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getOrthoHeight() | Λαμβάνει ή ορίζει το ύψος όταν το frustum βρίσκεται σε ορθογώνια προβολή. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setOrthoHeight(value) | Λαμβάνει ή ορίζει το ύψος όταν το frustum βρίσκεται σε ορθογώνια προβολή. |

 **Result:**



---


### getUp{#getUp}

| Όνομα | Περιγραφή |
| --- | --- |
| getUp() | Λαμβάνει ή ορίζει την κατεύθυνση ανόδου της κάμερας |

 **Result:**



---


### setUp{#setUp}

| Όνομα | Περιγραφή |
| --- | --- |
| setUp(value) | Λαμβάνει ή ορίζει την κατεύθυνση ανόδου της κάμερας |

 **Result:**



---


### getLookAt{#getLookAt}

| Όνομα | Περιγραφή |
| --- | --- |
| getLookAt() | Λαμβάνει ή ορίζει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα. |

 **Result:**



---


### setLookAt{#setLookAt}

| Όνομα | Περιγραφή |
| --- | --- |
| setLookAt(value) | Λαμβάνει ή ορίζει τη θέση ενδιαφέροντος στην οποία κοιτάζει η κάμερα. |

 **Result:**



---


### getDirection{#getDirection}

| Όνομα | Περιγραφή |
| --- | --- |
| getDirection() | Λαμβάνει ή ορίζει την κατεύθυνση στην οποία κοιτάζει η κάμερα. Οι αλλαγές σε αυτήν την ιδιότητα θα επηρεάσουν επίσης το LookAt και το Target. |

 **Result:**



---


### setDirection{#setDirection}

| Όνομα | Περιγραφή |
| --- | --- |
| setDirection(value) | Λαμβάνει ή ορίζει την κατεύθυνση στην οποία κοιτάζει η κάμερα. Οι αλλαγές σε αυτήν την ιδιότητα θα επηρεάσουν επίσης το LookAt και το Target. |

 **Result:**



---


### getTarget{#getTarget}

| Όνομα | Περιγραφή |
| --- | --- |
| getTarget() | Λαμβάνει ή ορίζει το στόχο στον οποίο κοιτάζει η κάμερα. Εάν ο χρήστης υποστηρίζει αυτήν την ιδιότητα, θα πρέπει να προηγείται της ιδιότητας LookAt. |

 **Result:**



---


### setTarget{#setTarget}

| Όνομα | Περιγραφή |
| --- | --- |
| setTarget(value) | Λαμβάνει ή ορίζει το στόχο στον οποίο κοιτάζει η κάμερα. Εάν ο χρήστης υποστηρίζει αυτήν την ιδιότητα, θα πρέπει να προηγείται της ιδιότητας LookAt. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentNodes() | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλαπλούς γονικούς κόμβους για geometry instancing. Οι κόμβοι. |

 **Result:**



---


### getExcluded{#getExcluded}

| Όνομα | Περιγραφή |
| --- | --- |
| getExcluded() | Λαμβάνει ή ορίζει εάν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |

 **Result:**



---


### setExcluded{#setExcluded}

| Όνομα | Περιγραφή |
| --- | --- |
| setExcluded(value) | Λαμβάνει ή ορίζει εάν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |

 **Result:**



---


### getParentNode{#getParentNode}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentNode() | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. Ο γονικός κόμβος. |

 **Result:**



---


### setParentNode{#setParentNode}

| Όνομα | Περιγραφή |
| --- | --- |
| setParentNode(value) | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. Ο γονικός κόμβος. |

 **Result:**



---


### getScene{#getScene}

| Όνομα | Περιγραφή |
| --- | --- |
| getScene() | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |

 **Result:**



---


### getName{#getName}

| Όνομα | Περιγραφή |
| --- | --- |
| getName() | Λαμβάνει ή ορίζει το όνομα. Το όνομα. |

 **Result:**



---


### setName{#setName}

| Όνομα | Περιγραφή |
| --- | --- |
| setName(value) | Λαμβάνει ή ορίζει το όνομα. Το όνομα. |

 **Result:**



---


### getProperties{#getProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperties() | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| Όνομα | Περιγραφή |
| --- | --- |
| getBoundingBox() | Λαμβάνει το πλαίσιο περιγράμματος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |

 **Result:**



---


### getEntityRendererKey{#getEntityRendererKey}

| Όνομα | Περιγραφή |
| --- | --- |
| getEntityRendererKey() | Λαμβάνει το κλειδί του αποτυπωτή οντοτήτων που είναι καταχωρημένο στον αποτυπωτή |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| removeProperty(property) | Αφαιρεί μια δυναμική ιδιότητα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | Property | Ποια ιδιότητα να αφαιρεθεί |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| removeProperty(property) | Αφαιρέστε την καθορισμένη ιδιότητα που αναγνωρίζεται με όνομα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperty(property) | Αποκτήστε την τιμή της καθορισμένης ιδιότητας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | String | Όνομα ιδιότητας |

 **Result:**
Αντικείμενο


---


### setProperty{#setProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| setProperty(property, value) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | String | Όνομα ιδιότητας |
| τιμή | Αντικείμενο | Η τιμή της ιδιότητας |

 **Result:**
Αντικείμενο


---


### findProperty{#findProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| findProperty(propertyName) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Created by CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Identified by its name) |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | String | Όνομα ιδιότητας. |

 **Result:**
Property


---



