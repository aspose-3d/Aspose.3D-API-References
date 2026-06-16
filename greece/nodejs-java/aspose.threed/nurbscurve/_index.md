---
title: "NurbsCurve"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

Η καμπύλη NURBS είναι μια καμπύλη που αναπαρίσταται από NURBS (Non-uniform rational basis spline),  Μια καμπύλη NURBS ορίζεται από τη σειρά της (Order), ένα σύνολο βαρυκυβερνημένων Geometry.ControlPoints και ένα KnotVectors.  Το στοιχείο w στο σημείο ελέγχου χρησιμοποιείται ως βάρος του σημείου ελέγχου, ανεξάρτητα αν είναι CurveDimension.TWO_DIMENSIONAL ή CurveDimension.THREE_DIMENSIONAL.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(name) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης NurbsCurve. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Όνομα | Περιγραφή |
| --- | --- |
| getControlPoints() | Λαμβάνει όλα τα σημεία ελέγχου |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Όνομα | Περιγραφή |
| --- | --- |
| getMultiplicity() | Λαμβάνει την πολλαπλότητα. Η πολλαπλότητα. |

 **Result:**



---


### getOrder{#getOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| getOrder() | Λαμβάνει ή ορίζει τη σειρά μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο στην καμπύλη. Η σειρά. |

 **Result:**



---


### setOrder{#setOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| setOrder(value) | Λαμβάνει ή ορίζει τη σειρά μιας καμπύλης NURBS, ορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο στην καμπύλη. Η σειρά. |

 **Result:**



---


### getDimension{#getDimension}

| Όνομα | Περιγραφή |
| --- | --- |
| getDimension() | Λαμβάνει ή ορίζει τη διάσταση της καμπύλης. Η τιμή της ιδιότητας είναι η ακέραια σταθερά CurveDimension. Για μια καμπύλη CurveDimension.TWO_DIMENSIONAL, το συστατικό z στο σημείο ελέγχου δεν χρησιμοποιείται. |

 **Result:**



---


### setDimension{#setDimension}

| Όνομα | Περιγραφή |
| --- | --- |
| setDimension(value) | Λαμβάνει ή ορίζει τη διάσταση της καμπύλης. Η τιμή της ιδιότητας είναι η ακέραια σταθερά CurveDimension. Για μια καμπύλη CurveDimension.TWO_DIMENSIONAL, το συστατικό z στο σημείο ελέγχου δεν χρησιμοποιείται. |

 **Result:**



---


### getCurveType{#getCurveType}

| Όνομα | Περιγραφή |
| --- | --- |
| getCurveType() | Λαμβάνει ή ορίζει τον τύπο της καμπύλης. Η τιμή της ιδιότητας είναι η ακέραια σταθερά NurbsType.Ο τύπος της καμπύλης. |

 **Result:**



---


### setCurveType{#setCurveType}

| Όνομα | Περιγραφή |
| --- | --- |
| setCurveType(value) | Λαμβάνει ή ορίζει τον τύπο της καμπύλης. Η τιμή της ιδιότητας είναι η ακέραια σταθερά NurbsType.Ο τύπος της καμπύλης. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Όνομα | Περιγραφή |
| --- | --- |
| getKnotVectors() | Λαμβάνει το διάνυσμα κόμβων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS. |

 **Result:**



---


### getRational{#getRational}

| Όνομα | Περιγραφή |
| --- | --- |
| getRational() | Λαμβάνει ή ορίζει αν είναι ρητός, αυτή η τιμή υποδεικνύει αν αυτή η NurbsCurve είναι ρητή spline ή μη ρητή spline. Η μη ρητή B-spline είναι μια ειδική περίπτωση των ρητών B-splines. true αν είναι ρητή spline; διαφορετικά, false είναι μη ρητή spline. |

 **Result:**



---


### setRational{#setRational}

| Όνομα | Περιγραφή |
| --- | --- |
| setRational(value) | Λαμβάνει ή ορίζει αν είναι ρητός, αυτή η τιμή υποδεικνύει αν αυτή η NurbsCurve είναι ρητή spline ή μη ρητή spline. Η μη ρητή B-spline είναι μια ειδική περίπτωση των ρητών B-splines. true αν είναι ρητή spline; διαφορετικά, false είναι μη ρητή spline. |

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


### evaluate{#evaluate}

| Όνομα | Περιγραφή |
| --- | --- |
| evaluate(steps) | Αξιολογεί την καμπύλη NURBS |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| steps | Αριθμός | Η συχνότητα αξιολόγησης μεταξύ δύο γειτονικών κόμβων, η προεπιλεγμένη τιμή είναι 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Όνομα | Περιγραφή |
| --- | --- |
| evaluateAt(u) | Αξιολογεί το σημείο της καμπύλης στη συγκεκριμένη θέση |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| u | Αριθμός | Η θέση στην καμπύλη, μεταξύ 0 και 1 |

 **Result:**
Vector4


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



