---
title: "Πυραμίδα"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/frustum/
---
## Frustum class

Η βασική κλάση της Camera και του Light  @hideconstructor


## Μέθοδοι

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



