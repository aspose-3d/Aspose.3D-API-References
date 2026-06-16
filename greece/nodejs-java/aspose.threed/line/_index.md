---
title: "Line"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/line/
---
## Line class

Μια πολυγραμμή είναι μια διαδρομή που ορίζεται από ένα σύνολο σημείων με Geometry.ControlPoints και συνδέεται με Segments,  πράγμα που σημαίνει ότι μπορεί επίσης να είναι ένα σύνολο συνδεδεμένων τμημάτων γραμμής.  Η γραμμή είναι συνήθως ένα γραμμικό αντικείμενο, πράγμα που σημαίνει ότι δεν μπορεί να χρησιμοποιηθεί για την αναπαράσταση μιας καμπύλης· για την αναπαράσταση μιας καμπύλης, χρησιμοποιεί το NurbsCurve.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Line. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(name) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Line. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| getControlPoints() | Λαμβάνει όλα τα σημεία ελέγχου |

 **Result:**



---


### getVisible{#getVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| getVisible() | Λαμβάνει ή ορίζει αν η γεωμετρία είναι ορατή |

 **Result:**



---


### setVisible{#setVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| setVisible(value) | Λαμβάνει ή ορίζει αν η γεωμετρία είναι ορατή |

 **Result:**



---


### getSegments{#getSegments}

| Όνομα | Περιγραφή |
| --- | --- |
| getSegments() | Λαμβάνει τα τμήματα της γραμμής |

 **Result:**



---


### getColor{#getColor}

| Όνομα | Περιγραφή |
| --- | --- |
| getColor() | Λαμβάνει ή ορίζει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Όνομα | Περιγραφή |
| --- | --- |
| setColor(value) | Λαμβάνει ή ορίζει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό(1, 1, 1) |

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


### fromPoints{#fromPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| fromPoints(points) | Δημιουργεί ένα αντικείμενο Line από ένα σύνολο σημείων. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | Vector3[] | null |

 **Result:**
Line


---


### makeDefaultIndices{#makeDefaultIndices}

| Όνομα | Περιγραφή |
| --- | --- |
| makeDefaultIndices() | Δημιουργήστε τη σειρά 0,1,2,3....Geometry.ControlPoints.Length-1 σε Segments ώστε τα ControlPoints να μπορούν να χρησιμοποιηθούν ως μία ενιαία γραμμή |

 **Result:**
Line


---


### getEntityRendererKey{#getEntityRendererKey}

| Όνομα | Περιγραφή |
| --- | --- |
| getEntityRendererKey() | Λαμβάνει το κλειδί του αποτυπωτή οντοτήτων που είναι καταχωρημένο στον αποτυπωτή |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Όνομα | Περιγραφή |
| --- | --- |
| getBoundingBox() | Λαμβάνει το πλαίσιο περιγράμματος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |

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



