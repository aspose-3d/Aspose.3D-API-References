---
title: "Κύλινδρος"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Παραμετρικός Κύλινδρος.  Μπορεί επίσης να χρησιμοποιηθεί για την αναπαράσταση του κώνου όταν ένα από τα radiusTop/radiusBottom είναι μηδέν.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Cylinder. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(radius, height) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Cylinder. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | Αριθμός | Ακτίνα του επάνω και κάτω καπακιού. |
| height | Αριθμός | Ύψος. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Cylinder. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| radiusTop | Αριθμός | Ακτίνα επάνω. |
| radiusBottom | Αριθμός | Ακτίνα κάτω. |
| height | Αριθμός | Ύψος. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Cylinder. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| radiusTop | Αριθμός | Ακτίνα του επάνω καπακιού του κυλίνδρου. |
| radiusBottom | Αριθμός | Ακτίνα του κάτω καπακιού του κυλίνδρου. |
| height | Αριθμός | Ύψος του κυλίνδρου. |
| radialSegments | Αριθμός | Ακτινικές ενότητες και των δύο επάνω και κάτω κύκλων.. |
| heightSegments | Αριθμός | Τμήματα ύψους. |
| openEnded | boolean | Αν οριστεί σε |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Cylinder. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Το όνομα αυτού του αντικειμένου |
| radiusTop | Αριθμός | Ακτίνα του επάνω καπακιού του κυλίνδρου. |
| radiusBottom | Αριθμός | Ακτίνα του κάτω καπακιού του κυλίνδρου. |
| height | Αριθμός | Ύψος του κυλίνδρου. |
| radialSegments | Αριθμός | Ακτινικές ενότητες και των δύο επάνω και κάτω κύκλων.. |
| heightSegments | Αριθμός | Τμήματα ύψους. |
| openEnded | boolean | Αν οριστεί σε |
| thetaStart | Αριθμός | Αρχή του Theta. |
| thetaLength | Αριθμός | Μήκος του Theta. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Όνομα | Περιγραφή |
| --- | --- |
| getOffsetBottom() | Λαμβάνει ή ορίζει τη μετατόπιση μετασχηματισμού των κορυφών της κάτω πλευράς. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Όνομα | Περιγραφή |
| --- | --- |
| setOffsetBottom(value) | Λαμβάνει ή ορίζει τη μετατόπιση μετασχηματισμού των κορυφών της κάτω πλευράς. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Όνομα | Περιγραφή |
| --- | --- |
| getOffsetTop() | Λαμβάνει ή ορίζει τη μετατόπιση μετασχηματισμού των κορυφών της πάνω πλευράς. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Όνομα | Περιγραφή |
| --- | --- |
| setOffsetTop(value) | Λαμβάνει ή ορίζει τη μετατόπιση μετασχηματισμού των κορυφών της πάνω πλευράς. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Όνομα | Περιγραφή |
| --- | --- |
| getGenerateFanCylinder() | Λαμβάνει ή ορίζει εάν θα δημιουργηθεί ο κύλινδρος στυλ ανεμιστήρα όταν το ThetaLength είναι μικρότερο από 2PI, διαφορετικά το μοντέλο δεν θα κοπεί. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Όνομα | Περιγραφή |
| --- | --- |
| setGenerateFanCylinder(value) | Λαμβάνει ή ορίζει εάν θα δημιουργηθεί ο κύλινδρος στυλ ανεμιστήρα όταν το ThetaLength είναι μικρότερο από 2PI, διαφορετικά το μοντέλο δεν θα κοπεί. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Όνομα | Περιγραφή |
| --- | --- |
| getShearBottom() | Λαμβάνει ή ορίζει τον παραμόρφωση κάμψης της κάτω πλευράς, το διάνυσμα αποθηκεύει την τιμή κάμψης (x-axis, z-axis) που μετράται σε radian, η προεπιλεγμένη τιμή είναι (0, 0) |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Όνομα | Περιγραφή |
| --- | --- |
| setShearBottom(value) | Λαμβάνει ή ορίζει τον παραμόρφωση κάμψης της κάτω πλευράς, το διάνυσμα αποθηκεύει την τιμή κάμψης (x-axis, z-axis) που μετράται σε radian, η προεπιλεγμένη τιμή είναι (0, 0) |

 **Result:**



---


### getShearTop{#getShearTop}

| Όνομα | Περιγραφή |
| --- | --- |
| getShearTop() | Λαμβάνει ή ορίζει τον παραμόρφωση κάμψης της πάνω πλευράς, το διάνυσμα αποθηκεύει την τιμή κάμψης (x-axis, z-axis) που μετράται σε radian, η προεπιλεγμένη τιμή είναι (0, 0) |

 **Result:**



---


### setShearTop{#setShearTop}

| Όνομα | Περιγραφή |
| --- | --- |
| setShearTop(value) | Λαμβάνει ή ορίζει τον παραμόρφωση κάμψης της πάνω πλευράς, το διάνυσμα αποθηκεύει την τιμή κάμψης (x-axis, z-axis) που μετράται σε radian, η προεπιλεγμένη τιμή είναι (0, 0) |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Όνομα | Περιγραφή |
| --- | --- |
| getRadiusTop() | Λαμβάνει ή ορίζει την ακτίνα του άνω καπάκιου του κυλίνδρου. Η ακτίνα του άνω καπάκιου. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Όνομα | Περιγραφή |
| --- | --- |
| setRadiusTop(value) | Λαμβάνει ή ορίζει την ακτίνα του άνω καπάκιου του κυλίνδρου. Η ακτίνα του άνω καπάκιου. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Όνομα | Περιγραφή |
| --- | --- |
| getRadiusBottom() | Λαμβάνει ή ορίζει την ακτίνα του κάτω καπάκιου του κυλίνδρου. Η ακτίνα του κάτω καπάκιου. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Όνομα | Περιγραφή |
| --- | --- |
| setRadiusBottom(value) | Λαμβάνει ή ορίζει την ακτίνα του κάτω καπάκιου του κυλίνδρου. Η ακτίνα του κάτω καπάκιου. |

 **Result:**



---


### getHeight{#getHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeight() | Λαμβάνει ή ορίζει το ύψος του κυλίνδρου. Το ύψος. |

 **Result:**



---


### setHeight{#setHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setHeight(value) | Λαμβάνει ή ορίζει το ύψος του κυλίνδρου. Το ύψος. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Όνομα | Περιγραφή |
| --- | --- |
| getRadialSegments() | Λαμβάνει ή ορίζει τα radial segments. Τα radial segments. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Όνομα | Περιγραφή |
| --- | --- |
| setRadialSegments(value) | Λαμβάνει ή ορίζει τα radial segments. Τα radial segments. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeightSegments() | Αποκτά ή ορίζει τα τμήματα ύψους. Τα τμήματα ύψους. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Όνομα | Περιγραφή |
| --- | --- |
| setHeightSegments(value) | Αποκτά ή ορίζει τα τμήματα ύψους. Τα τμήματα ύψους. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Όνομα | Περιγραφή |
| --- | --- |
| getOpenEnded() | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτός ο Cylinder είναι ανοιχτό στο άκρο. Η προεπιλεγμένη τιμή είναι false. true εάν είναι ανοιχτό στο άκρο· διαφορετικά, υπάρχουν άνω/κάτω caps. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Όνομα | Περιγραφή |
| --- | --- |
| setOpenEnded(value) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτός ο Cylinder είναι ανοιχτό στο άκρο. Η προεπιλεγμένη τιμή είναι false. true εάν είναι ανοιχτό στο άκρο· διαφορετικά, υπάρχουν άνω/κάτω caps. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Όνομα | Περιγραφή |
| --- | --- |
| getThetaStart() | Λαμβάνει ή ορίζει την theta start. Η προεπιλεγμένη τιμή είναι 0. Η theta start. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Όνομα | Περιγραφή |
| --- | --- |
| setThetaStart(value) | Λαμβάνει ή ορίζει την theta start. Η προεπιλεγμένη τιμή είναι 0. Η theta start. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Όνομα | Περιγραφή |
| --- | --- |
| getThetaLength() | Λαμβάνει ή ορίζει το length of the theta. Η προεπιλεγμένη τιμή είναι 2π. Το length of the theta. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Όνομα | Περιγραφή |
| --- | --- |
| setThetaLength(value) | Λαμβάνει ή ορίζει το length of the theta. Η προεπιλεγμένη τιμή είναι 2π. Το length of the theta. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Όνομα | Περιγραφή |
| --- | --- |
| getCastShadows() | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Όνομα | Περιγραφή |
| --- | --- |
| setCastShadows(value) | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Όνομα | Περιγραφή |
| --- | --- |
| getReceiveShadows() | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λάβει σκιά. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Όνομα | Περιγραφή |
| --- | --- |
| setReceiveShadows(value) | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λάβει σκιά. |

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


### toMesh{#toMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| toMesh() | Μετατρέπει το τρέχον αντικείμενο σε πλέγμα |

 **Result:**
Πλέγμα


---


### getBoundingBox{#getBoundingBox}

| Όνομα | Περιγραφή |
| --- | --- |
| getBoundingBox() | Λαμβάνει το πλαίσιο περιγράμματος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |

 **Result:**
Πλέγμα


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



