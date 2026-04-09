---
title: Node
second_title: Aspose.3D for Java API Reference
description: Αναπαριστά ένα στοιχείο στο γράφημα σκηνής.
type: docs
weight: 110
url: /el/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Αντιπροσωπεύει ένα στοιχείο στο γράφημα σκηνής. Ένα γράφημα σκηνής είναι ένα δέντρο αντικειμένων Node. Οι υπηρεσίες διαχείρισης του δέντρου περιλαμβάνονται σε αυτήν την κλάση. Σημειώστε ότι το Aspose.3D SDK δεν ελέγχει την εγκυρότητα του κατασκευασμένου γραφήματος σκηνής. Είναι ευθύνη του καλούντος να διασφαλίσει ότι δεν δημιουργεί κυκλικά γραφήματα σε ιεραρχία κόμβων. Εκτός από τη διαχείριση του δέντρου, αυτή η κλάση ορίζει όλες τις ιδιότητες που απαιτούνται για την περιγραφή της θέσης του αντικειμένου στη σκηνή. Αυτές οι πληροφορίες περιλαμβάνουν τις βασικές ιδιότητες Translation, Rotation και Scaling καθώς και τις πιο προχωρημένες επιλογές για άξονες, όρια και χαρακτηριστικά αρθρώσεων IK, όπως η σκληρότητα και η αποσβέση. Όταν δημιουργείται για πρώτη φορά, το αντικείμενο Node είναι "empty" (δηλαδή: είναι ένα αντικείμενο χωρίς καμία γραφική αναπαράσταση που περιέχει μόνο τις πληροφορίες θέσης). Σε αυτήν την κατάσταση, μπορεί να χρησιμοποιηθεί για την αναπαράσταση γονέων στη δομή δέντρου κόμβων, αλλά όχι πολύ περισσότερο. Η κανονική χρήση αυτού του τύπου αντικειμένων είναι να τους προστεθεί μια οντότητα που θα εξειδικεύσει τον κόμβο (δείτε το "Entity"). Η οντότητα είναι ένα αντικείμενο από μόνη της και είναι συνδεδεμένη με το Node. Αυτό επίσης σημαίνει ότι η ίδια οντότητα μπορεί να μοιράζεται μεταξύ πολλών κόμβων. Η Camera, το Light, το Mesh κ.λπ. είναι όλες οντότητες και όλες προέρχονται από τη βασική κλάση Entity.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Node()](#Node--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Node](../../com.aspose.threed/node). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Περπατάει μέσω όλων των απογόνων κόμβων (συμπεριλαμβανομένου του τρέχοντος κόμβου) και καλεί τον επισκέπτη με τον κόμβο. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Προσθέστε έναν υποκόμβο σε αυτόν τον κόμβο |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Προσθέστε μια οντότητα στον κόμβο. |
| [createChildNode()](#createChildNode--) | Δημιουργεί έναν υποκόμβο |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Δημιουργήστε έναν νέο υποκόμβο με την καθορισμένη οντότητα προσαρτημένη |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Δημιουργήστε έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Δημιουργήστε έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Δημιουργήστε έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου και προσαρτήστε την καθορισμένη οντότητα και ένα υλικό |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Αξιολογήστε τον παγκόσμιο μετασχηματισμό, συμπεριλαμβάνοντας ή όχι τον γεωμετρικό μετασχηματισμό |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getAssetInfo()](#getAssetInfo--) | Πληροφορίες πόρων ανά κόμβο |
| [getBoundingBox()](#getBoundingBox--) | Υπολογίστε το περιοριστικό κουτί του κόμβου |
| [getChild(int index)](#getChild-int-) | Λαμβάνει τον υποκόμβο στο καθορισμένο δείκτη. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Λαμβάνει τον υποκόμβο με το καθορισμένο όνομα |
| [getChildNodes()](#getChildNodes--) | Λαμβάνει τους υποκόμβους. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Λαμβάνει όλες τις οντότητες του κόμβου. |
| [getEntity()](#getEntity--) | Λαμβάνει την πρώτη οντότητα προσαρτημένη σε αυτόν τον κόμβο· εάν οριστεί, θα διαγράψει τις άλλες οντότητες. |
| [getExcluded()](#getExcluded--) | Λαμβάνει αν θα εξαλειφθεί αυτός ο κόμβος και όλοι οι υποκόμβοι/οντότητες κατά την εξαγωγή. |
| [getGlobalTransform()](#getGlobalTransform--) | Λαμβάνει τον παγκόσμιο μετασχηματισμό. |
| [getMaterial()](#getMaterial--) | Λαμβάνει το πρώτο υλικό που σχετίζεται με αυτόν τον κόμβο· εάν οριστεί, θα διαγράψει τα άλλα υλικά. |
| [getMaterials()](#getMaterials--) | Λαμβάνει τα υλικά που σχετίζονται με αυτόν τον κόμβο. |
| [getMetaDatas()](#getMetaDatas--) | Λαμβάνει τα μεταδεδομένα που ορίζονται σε αυτόν τον κόμβο. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getParentNode()](#getParentNode--) | Λαμβάνει τον γονικό κόμβο. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getScene()](#getScene--) | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [getTransform()](#getTransform--) | Λαμβάνει τον τοπικό μετασχηματισμό. |
| [getVisible()](#getVisible--) | Λαμβάνει την εντολή εμφάνισης του κόμβου |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Αποσυνδέστε όλα κάτω από τον κόμβο και συνδέστε τα στον τρέχοντα κόμβο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Επιλέξτε πολλαπλά αντικείμενα κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος τύπου XPath. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Επιλέξτε ένα μόνο αντικείμενο κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος τύπου XPath. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Πληροφορίες πόρων ανά κόμβο |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Ορίζει την πρώτη οντότητα προσαρτημένη σε αυτόν τον κόμβο· εάν οριστεί, θα διαγράψει τις άλλες οντότητες. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Ορίζει αν θα εξαλειφθεί αυτός ο κόμβος και όλοι οι υποκόμβοι/οντότητες κατά την εξαγωγή. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Ορίζει το πρώτο υλικό που συσχετίζεται με αυτόν τον κόμβο· εάν οριστεί, θα καθαρίσει τα άλλα υλικά |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Ορίζει τον γονικό κόμβο. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setVisible(boolean value)](#setVisible-boolean-) | Ορίζει την εμφάνιση του κόμβου. |
| [toString()](#toString--) | Αποκτά την αναπαράσταση συμβολοσειράς αυτού του κόμβου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Node](../../com.aspose.threed/node).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |
| entity | [Entity](../../com.aspose.threed/entity) | Προεπιλεγμένη οντότητα. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [Node](../../com.aspose.threed/node).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Περπατάει μέσω όλων των απογόνων κόμβων (συμπεριλαμβανομένου του τρέχοντος κόμβου) και καλεί τον επισκέπτη με τον κόμβο. Ο επισκέπτης μπορεί να διακόψει την πορεία επιστρέφοντας false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Callback του επισκέπτη για την επίσκεψη του κόμβου. |

**Returns:**
boolean - true σημαίνει ότι ο επισκέπτης διέκοψε την πορεία. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να λάβετε όλα τα πλέγματα από μια σκηνή

```
Scene scene = Scene.fromFile("input.fbx");
     List<Mesh> meshes = new ArrayList<Mesh>();
     scene.getRootNode().accept(new NodeVisitor() {
         @Override
         public boolean call(Node node) {
             if(node.Entity instanceof Mesh)
                 meshes.add(((Mesh)node).getEntity());
             //continue searching
             return true;
         }
     });
```
### addChildNode(Node node) {#addChildNode-com.aspose.threed.Node-}
```
public void addChildNode(Node node)
```


Προσθέστε έναν υποκόμβο σε αυτόν τον κόμβο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Ο υποκόμβος που θα προσαρτηθεί **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να λάβετε όλα τα πλέγματα από μια σκηνή |

```
Scene scene = Scene.fromFile("input.fbx");
     var newNode = new Node();
     //add a new node manually
     scene.getRootNode().addChildNode(newNode);
``` |

### addEntity(Entity entity) {#addEntity-com.aspose.threed.Entity-}
```
public void addEntity(Entity entity)
```


Προσθέστε μια οντότητα στον κόμβο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Η οντότητα που θα προσαρτηθεί στον κόμβο |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Δημιουργεί έναν υποκόμβο

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode();
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### createChildNode(Entity entity) {#createChildNode-com.aspose.threed.Entity-}
```
public Node createChildNode(Entity entity)
```


Δημιουργήστε έναν νέο υποκόμβο με την καθορισμένη οντότητα προσαρτημένη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Προεπιλεγμένη οντότητα προσαρτημένη στον κόμβο |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode(new Box());
     scene.save("output.fbx");
```
### createChildNode(String nodeName) {#createChildNode-java.lang.String-}
```
public Node createChildNode(String nodeName)
```


Δημιουργήστε έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | java.lang.String | Το όνομα του νέου υποκόμβου |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### createChildNode(String nodeName, Entity entity) {#createChildNode-java.lang.String-com.aspose.threed.Entity-}
```
public Node createChildNode(String nodeName, Entity entity)
```


Δημιουργήστε έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | java.lang.String | Το όνομα του νέου υποκόμβου |
| entity | [Entity](../../com.aspose.threed/entity) | Προεπιλεγμένη οντότητα προσαρτημένη στον κόμβο |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Δημιουργήστε έναν νέο υποκόμβο με το δεδομένο όνομα κόμβου και προσαρτήστε την καθορισμένη οντότητα και ένα υλικό

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | java.lang.String | Το όνομα του νέου υποκόμβου |
| entity | [Entity](../../com.aspose.threed/entity) | Προεπιλεγμένη οντότητα προσαρτημένη στον κόμβο |
| material | [Material](../../com.aspose.threed/material) | Το υλικό που προσαρτήθηκε στον κόμβο |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
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
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Αξιολογήστε τον παγκόσμιο μετασχηματισμό, συμπεριλαμβάνοντας ή όχι τον γεωμετρικό μετασχηματισμό

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| withGeometricTransform | boolean | Εάν απαιτείται η γεωμετρική μετατροπή. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The global transform matrix. **Example:** The following code shows how to read the node's global transform matrix.

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     Matrix4 mat = boxNode.evaluateGlobalTransform(true);
     System.out.printf("The box's global transform matrix is %s", mat);
```
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
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Πληροφορίες πόρων ανά κόμβο

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Υπολογίστε το περιοριστικό κουτί του κόμβου

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Λαμβάνει τον υποκόμβο στο καθορισμένο δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης. |

**Returns:**
[Node](../../com.aspose.threed/node) - The child. **Example:** The following code shows how to get a child node at specified index.

```
Scene scene = Scene.fromFile("input.fbx");
     var node = scene.getRootNode().getChild(0);
     System.out.printf("The first node of the file is %s", node.getName());
```
### getChild(String nodeName) {#getChild-java.lang.String-}
```
public Node getChild(String nodeName)
```


Λαμβάνει τον υποκόμβο με το καθορισμένο όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | java.lang.String | Το όνομα του υποκόμβου προς εύρεση. |

**Returns:**
[Node](../../com.aspose.threed/node) - The child. **Example:** The following code shows how to get a child node with specified name

```
Scene scene = Scene.fromFile("input.fbx");
     var node = scene.getRootNode().getChild("box");
     System.out.printf("The box node's translation is %s", node.getTransform().getTranslation());
```
### getChildNodes() {#getChildNodes--}
```
public List<Node> getChildNodes()
```


Λαμβάνει τους υποκόμβους.

**Returns:**
java.util.List<com.aspose.threed.Node> - οι κόμβοι-παιδιά. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να απαριθμήσετε τον υποκόμβο του ριζικού κόμβου

```
Scene scene = Scene.fromFile("test.fbx");
     for(var child : scene.getRootNode().getChildNodes())
     {
         //do your business
     }
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntities() {#getEntities--}
```
public List<Entity> getEntities()
```


Λαμβάνει όλες τις οντότητες του κόμβου.

**Returns:**
java.util.List<com.aspose.threed.Entity> - όλες τις οντότητες κόμβου.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Λαμβάνει την πρώτη οντότητα προσαρτημένη σε αυτόν τον κόμβο· εάν οριστεί, θα διαγράψει τις άλλες οντότητες.

**Returns:**
[Entity](../../com.aspose.threed/entity) - the first entity attached to this node, if sets, will clear other entities. **Example:** The following code shows how to create a new child node under root node

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
```
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


Λαμβάνει αν θα εξαλειφθεί αυτός ο κόμβος και όλοι οι υποκόμβοι/οντότητες κατά την εξαγωγή.

**Returns:**
boolean - εάν θα εξαλειφθεί αυτός ο κόμβος και όλοι οι υποκόμβοι/οντότητες κατά την εξαγωγή. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να εξαιρέσετε τον καθορισμένο κόμβο από την εξαγωγή

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode("excluded", new Box()).setExcluded(true);
     scene.getRootNode().createChildNode("not excluded", new Box());
     scene.save("output.usdz");
```
### getGlobalTransform() {#getGlobalTransform--}
```
public GlobalTransform getGlobalTransform()
```


Λαμβάνει τον παγκόσμιο μετασχηματισμό.

**Returns:**
[GlobalTransform](../../com.aspose.threed/globaltransform) - the global transform. **Example:** The following code shows how to read node's global transform

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
     var global = boxNode.getGlobalTransform();
     System.out.printf("The box's position in world coordinate is %s", global.getTranslation());
```
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


Λαμβάνει το πρώτο υλικό που σχετίζεται με αυτόν τον κόμβο· εάν οριστεί, θα διαγράψει τα άλλα υλικά.

**Returns:**
[Material](../../com.aspose.threed/material) - the first material associated with this node, if sets, will clear other materials **Example:**

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
```
### getMaterials() {#getMaterials--}
```
public List<Material> getMaterials()
```


Λαμβάνει τα υλικά που σχετίζονται με αυτόν τον κόμβο.

**Returns:**
java.util.List<com.aspose.threed.Material> - τα υλικά που συσχετίζονται με αυτόν τον κόμβο.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Λαμβάνει τα μεταδεδομένα που ορίζονται σε αυτόν τον κόμβο.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - τα μεταδεδομένα που ορίζονται σε αυτόν τον κόμβο.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Λαμβάνει τον γονικό κόμβο.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Λαμβάνει τον τοπικό μετασχηματισμό.

**Returns:**
[Transform](../../com.aspose.threed/transform) - the local transform. **Example:** The following code shows how to change the transform of the node:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Λαμβάνει την εντολή εμφάνισης του κόμβου

**Returns:**
boolean - για την εμφάνιση του κόμβου **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν αόρατο κόμβο

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("test-node", new Box());
     node.setVisible(false);
     scene.save("output.fbx");
```
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### merge(Node node) {#merge-com.aspose.threed.Node-}
```
public void merge(Node node)
```


Αποσυνδέστε όλα κάτω από τον κόμβο και συνδέστε τα στον τρέχοντα κόμβο. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε δύο αρχεία 3D σε ένα αρχείο

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |

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
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Επιλέξτε πολλαπλά αντικείμενα κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος τύπου XPath.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Το ερώτημα τύπου XPath |

**Returns:**
java.util.ArrayList<java.lang.Object> - Πολλά αντικείμενα ταιριάζουν με το ερώτημα τύπου XPath.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Επιλέξτε ένα μόνο αντικείμενο κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος τύπου XPath.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Το ερώτημα τύπου XPath |

**Returns:**
java.lang.Object - Αντικείμενο που εντοπίστηκε από το ερώτημα τύπου XPath.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Πληροφορίες πόρων ανά κόμβο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Νέα τιμή |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Ορίζει την πρώτη οντότητα προσαρτημένη σε αυτόν τον κόμβο· εάν οριστεί, θα διαγράψει τις άλλες οντότητες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Νέα τιμή **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν νέο κόμβο-παιδί κάτω από τον ριζικό κόμβο |

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("new node");
     node.setEntity(new Box());
     scene.save("output.fbx");
``` |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


Ορίζει αν θα εξαλειφθεί αυτός ο κόμβος και όλοι οι υποκόμβοι/οντότητες κατά την εξαγωγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Νέα τιμή **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να εξαιρέσετε έναν καθορισμένο κόμβο από την εξαγωγή |

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode("excluded", new Box()).setExcluded(true);
     scene.getRootNode().createChildNode("not excluded", new Box());
     scene.save("output.usdz");
``` |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


Ορίζει το πρώτο υλικό που συσχετίζεται με αυτόν τον κόμβο· εάν οριστεί, θα καθαρίσει τα άλλα υλικά

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Νέα τιμή **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Ορίζει τον γονικό κόμβο.

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

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Ορίζει την εμφάνιση του κόμβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Νέα τιμή **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν αόρατο κόμβο |

```
Scene scene = new Scene();
     Node node = scene.getRootNode().createChildNode("test-node", new Box());
     node.setVisible(false);
     scene.save("output.fbx");
``` |

### toString() {#toString--}
```
public String toString()
```


Αποκτά την αναπαράσταση συμβολοσειράς αυτού του κόμβου.

**Returns:**
java.lang.String - Η αναπαράσταση συμβολοσειράς αυτού του κόμβου για εντοπισμό σφαλμάτων.
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

