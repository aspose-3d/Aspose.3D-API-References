---
title: "TriMesh"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Ένα TriMesh περιέχει ακατέργαστα δεδομένα που μπορούν να χρησιμοποιηθούν απευθείας από την GPU. Αυτή η κλάση είναι ένα εργαλείο για τη δημιουργία ενός πλέγματος που περιέχει μόνο δεδομένα ανά κορυφή.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(name, declaration) | Αρχικοποιήστε ένα στιγμιότυπο του TriMesh |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Το όνομα αυτού του TriMesh |
| δήλωση | VertexDeclaration | Η δήλωση της κορυφής |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Όνομα | Περιγραφή |
| --- | --- |
| getVertexDeclaration() | Η διάταξη κορυφών του TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getVerticesCount() | Ο αριθμός των κορυφών σε αυτό το TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getIndicesCount() | Ο αριθμός των δεικτών σε αυτό το TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getUnmergedVerticesCount() | Ο αριθμός των μη συγχωνευμένων κορυφών που περάστηκαν από τις beginVertex() και endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Όνομα | Περιγραφή |
| --- | --- |
| getCapacity() | Η χωρητικότητα των προ-καθορισμένων κορυφών. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Όνομα | Περιγραφή |
| --- | --- |
| getVerticesSizeInBytes() | Το συνολικό μέγεθος όλων των κορυφών σε bytes |

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


### fromMesh{#fromMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| fromMesh(declaration, mesh) | Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο mesh με τη δοσμένη διάταξη κορυφών. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Πλέγμα | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Όνομα | Περιγραφή |
| --- | --- |
| copyFrom(input, vd) | Αντιγράψτε το TriMesh από το input με νέα διάταξη κορυφών |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | TriMesh | Το input TriMesh για αντιγραφή |
| vd | VertexDeclaration | Η νέα δήλωση κορυφών του output TriMesh |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Όνομα | Περιγραφή |
| --- | --- |
| fromMesh(mesh, useFloat) | Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο mesh, η δήλωση κορυφών βασίζεται στη δομή του input mesh. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| mes | Πλέγμα | null |
| useFloat | boolean | Χρησιμοποιήστε τύπο float αντί για τύπο double για κάθε στοιχείο της κορυφής. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Όνομα | Περιγραφή |
| --- | --- |
| beginVertex() | Ξεκινήστε την προσθήκη κορυφής |

 **Result:**
Κορυφή


---


### endVertex{#endVertex}

| Όνομα | Περιγραφή |
| --- | --- |
| endVertex() | Τέλος προσθήκης κορυφής |

 **Result:**
Κορυφή


---


### verticesToArray{#verticesToArray}

| Όνομα | Περιγραφή |
| --- | --- |
| verticesToArray() | Μετατρέψτε τα δεδομένα των κορυφών σε πίνακα byte |

 **Result:**
byte[]


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| Όνομα | Περιγραφή |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Δημιουργήστε TriMesh από ακατέργαστα δεδομένα. Το επιστρεφόμενο TriMesh δεν θα αντιγράψει τον εισαγόμενο πίνακα byte για απόδοση· εξωτερικές αλλαγές στον πίνακα θα αντικατοπτρίζονται σε αυτήν την παρουσία. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| vd | VertexDeclaration | Δήλωση κορυφής, πρέπει να περιέχει τουλάχιστον ένα πεδίο. |
| vertices | byte[] | Τα δεδομένα εισόδου της κορυφής, το ελάχιστο μήκος των κορυφών πρέπει να είναι μεγαλύτερο ή ίσο με το μέγεθος της δήλωσης κορυφής |
| indices | Number[] | Οι δείκτες τριγώνων |
| generateVertexMapping | boolean | Δημιουργία |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Όνομα | Περιγραφή |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Φορτώστε κορυφές από bytes, το μήκος των bytes πρέπει να είναι ακέραιο πολλαπλάσιο του μεγέθους της κορυφής. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Όνομα | Περιγραφή |
| --- | --- |
| readVector4(idx, field) | Διαβάστε το πεδίο vector4 |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με τύπο δεδομένων Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Όνομα | Περιγραφή |
| --- | --- |
| readFVector4(idx, field) | Διαβάστε το πεδίο vector4 |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με τύπο δεδομένων Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Όνομα | Περιγραφή |
| --- | --- |
| readVector3(idx, field) | Διαβάστε το πεδίο vector3 |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με τύπο δεδομένων Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Όνομα | Περιγραφή |
| --- | --- |
| readFVector3(idx, field) | Διαβάστε το πεδίο vector3 |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με τύπο δεδομένων Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Όνομα | Περιγραφή |
| --- | --- |
| readVector2(idx, field) | Διαβάστε το πεδίο vector2 |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με τύπο δεδομένων Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Όνομα | Περιγραφή |
| --- | --- |
| readFVector2(idx, field) | Διαβάστε το πεδίο vector2 |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με τύπο δεδομένων Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Όνομα | Περιγραφή |
| --- | --- |
| readDouble(idx, field) | Διαβάστε το πεδίο double |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με συμβατό τύπο δεδομένων float/double |

 **Result:**
Αριθμός


---


### readFloat{#readFloat}

| Όνομα | Περιγραφή |
| --- | --- |
| readFloat(idx, field) | Διαβάστε το πεδίο float |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| idx | Αριθμός | Ο δείκτης της κορυφής για ανάγνωση |
| field | VertexField | Το πεδίο με συμβατό τύπο δεδομένων float/double |

 **Result:**
Αριθμός


---


### getBoundingBox{#getBoundingBox}

| Όνομα | Περιγραφή |
| --- | --- |
| getBoundingBox() | Λαμβάνει το πλαίσιο περιγράμματος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |

 **Result:**
Αριθμός


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


### iterator{#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator() | Δεσμευμένο για εσωτερική χρήση. |

 **Result:**
Property


---



