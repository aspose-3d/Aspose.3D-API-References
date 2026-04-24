---
title: Node
second_title: Referensi API Aspose.3D untuk Java
description: Represents an element in the scene graph.
type: docs
weight: 110
url: /id/java/com.aspose.threed/node/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Node extends SceneObject
```

Menrepresentasikan sebuah elemen dalam grafik adegan. Grafik adegan adalah pohon objek Node. Layanan manajemen pohon disertakan dalam kelas ini. Perhatikan bahwa Aspose.3D SDK tidak memeriksa keabsahan grafik adegan yang dibangun. Tanggung jawab pemanggil adalah memastikan bahwa tidak menghasilkan grafik siklik dalam hierarki node. Selain manajemen pohon, kelas ini mendefinisikan semua properti yang diperlukan untuk menggambarkan posisi objek dalam adegan. Informasi ini mencakup properti dasar Translation, Rotation, dan Scaling serta opsi lanjutan untuk pivot, batas, dan atribut sambungan IK seperti kekakuan dan peredaman. Saat pertama kali dibuat, objek Node berstatus "kosong" (yaitu: objek tanpa representasi grafis yang hanya berisi informasi posisi). Dalam keadaan ini, ia dapat digunakan untuk mewakili induk dalam struktur pohon node tetapi tidak lebih. Penggunaan normal tipe objek ini adalah menambahkan sebuah entitas yang akan mengkhususkan node (lihat "Entity"). Entitas adalah objek tersendiri dan terhubung ke Node. Ini juga berarti bahwa entitas yang sama dapat dibagikan di antara beberapa node. Kamera, Light, Mesh, dll... semuanya merupakan entitas dan semuanya diturunkan dari kelas dasar Entity.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Node()](#Node--) | Menginisialisasi sebuah instance baru dari kelas [Node](../../com.aspose.threed/node). |
| [Node(String name, Entity entity)](#Node-java.lang.String-com.aspose.threed.Entity-) | Menginisialisasi sebuah instance baru dari kelas [Node](../../com.aspose.threed/node). |
| [Node(String name)](#Node-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [Node](../../com.aspose.threed/node). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept(NodeVisitor visitor)](#accept-com.aspose.threed.NodeVisitor-) | Melalui semua node turunan (termasuk node saat ini) dan memanggil visitor dengan node tersebut. |
| [addChildNode(Node node)](#addChildNode-com.aspose.threed.Node-) | Tambahkan node anak ke node ini |
| [addEntity(Entity entity)](#addEntity-com.aspose.threed.Entity-) | Tambahkan sebuah entitas ke node. |
| [createChildNode()](#createChildNode--) | Membuat node anak |
| [createChildNode(Entity entity)](#createChildNode-com.aspose.threed.Entity-) | Buat node anak baru dengan entitas yang diberikan terlampir |
| [createChildNode(String nodeName)](#createChildNode-java.lang.String-) | Buat node anak baru dengan nama node yang diberikan |
| [createChildNode(String nodeName, Entity entity)](#createChildNode-java.lang.String-com.aspose.threed.Entity-) | Buat node anak baru dengan nama node yang diberikan |
| [createChildNode(String nodeName, Entity entity, Material material)](#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-) | Buat node anak baru dengan nama node yang diberikan, dan lampirkan entitas yang ditentukan serta sebuah material |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluateGlobalTransform(boolean withGeometricTransform)](#evaluateGlobalTransform-boolean-) | Evaluasi transformasi global, sertakan transformasi geometrik atau tidak. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Menemukan properti. |
| [getAssetInfo()](#getAssetInfo--) | Info aset per-node |
| [getBoundingBox()](#getBoundingBox--) | Hitung kotak pembatas node |
| [getChild(int index)](#getChild-int-) | Mendapatkan node anak pada indeks yang ditentukan. |
| [getChild(String nodeName)](#getChild-java.lang.String-) | Mendapatkan node anak dengan nama yang ditentukan |
| [getChildNodes()](#getChildNodes--) | Mendapatkan node anak-anak. |
| [getClass()](#getClass--) |  |
| [getEntities()](#getEntities--) | Mendapatkan semua entitas node. |
| [getEntity()](#getEntity--) | Mendapatkan entitas pertama yang terlampir pada node ini, jika diatur, akan menghapus entitas lain. |
| [getExcluded()](#getExcluded--) | Mendapatkan apakah akan mengecualikan node ini dan semua node/entitas anak selama proses ekspor. |
| [getGlobalTransform()](#getGlobalTransform--) | Mendapatkan transformasi global. |
| [getMaterial()](#getMaterial--) | Mendapatkan material pertama yang terkait dengan node ini, jika diatur, akan menghapus material lain |
| [getMaterials()](#getMaterials--) | Mendapatkan material yang terkait dengan node ini. |
| [getMetaDatas()](#getMetaDatas--) | Mendapatkan metadata yang didefinisikan dalam node ini. |
| [getName()](#getName--) | Mendapatkan nama. |
| [getParentNode()](#getParentNode--) | Mendapatkan node induk. |
| [getProperties()](#getProperties--) | Mendapatkan koleksi semua properti. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Dapatkan nilai properti yang ditentukan |
| [getScene()](#getScene--) | Mendapatkan adegan yang dimiliki objek ini |
| [getTransform()](#getTransform--) | Mendapatkan transformasi lokal. |
| [getVisible()](#getVisible--) | Mendapatkan untuk menampilkan node |
| [hashCode()](#hashCode--) |  |
| [merge(Node node)](#merge-com.aspose.threed.Node-) | Lepaskan semua yang berada di bawah node dan lampirkan ke node saat ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Menghapus properti dinamis. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |
| [selectObjects(String path)](#selectObjects-java.lang.String-) | Pilih beberapa objek di bawah node saat ini menggunakan sintaks kueri mirip XPath. |
| [selectSingleObject(String path)](#selectSingleObject-java.lang.String-) | Pilih satu objek di bawah node saat ini menggunakan sintaks kueri mirip XPath. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Info aset per-node |
| [setEntity(Entity value)](#setEntity-com.aspose.threed.Entity-) | Mengatur entitas pertama yang terlampir pada node ini, jika diatur, akan menghapus entitas lain. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | Mengatur apakah akan mengecualikan node ini dan semua node/entitas anak selama proses ekspor. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | Mengatur material pertama yang terkait dengan node ini, jika diatur, akan menghapus material lain |
| [setName(String value)](#setName-java.lang.String-) | Mengatur nama. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | Mengatur node induk. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Mengatur nilai properti yang ditentukan |
| [setVisible(boolean value)](#setVisible-boolean-) | Mengatur untuk menampilkan node |
| [toString()](#toString--) | Mendapatkan representasi string dari node ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Node() {#Node--}
```
public Node()
```


Menginisialisasi sebuah instance baru dari kelas [Node](../../com.aspose.threed/node).

### Node(String name, Entity entity) {#Node-java.lang.String-com.aspose.threed.Entity-}
```
public Node(String name, Entity entity)
```


Menginisialisasi sebuah instance baru dari kelas [Node](../../com.aspose.threed/node).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |
| entity | [Entity](../../com.aspose.threed/entity) | Entitas default. |

### Node(String name) {#Node-java.lang.String-}
```
public Node(String name)
```


Menginisialisasi sebuah instance baru dari kelas [Node](../../com.aspose.threed/node).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama. |

### accept(NodeVisitor visitor) {#accept-com.aspose.threed.NodeVisitor-}
```
public boolean accept(NodeVisitor visitor)
```


Menelusuri semua node turunan (termasuk node saat ini) dan memanggil pengunjung dengan node tersebut. Pengunjung dapat menghentikan penelusuran dengan mengembalikan false

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| visitor | [NodeVisitor](../../com.aspose.threed/nodevisitor) | Callback pengunjung untuk mengunjungi node |

**Returns:**
boolean - true berarti pengunjung telah menghentikan penelusuran. **Example:** Kode berikut menunjukkan cara mendapatkan semua mesh dari sebuah adegan

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


Tambahkan node anak ke node ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | node | [Node](../../com.aspose.threed/node) | Node anak yang akan dilampirkan **Example:** Kode berikut menunjukkan cara mendapatkan semua mesh dari sebuah adegan |

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


Tambahkan sebuah entitas ke node.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Entitas yang akan dilampirkan ke node |

### createChildNode() {#createChildNode--}
```
public Node createChildNode()
```


Membuat node anak

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


Buat node anak baru dengan entitas yang diberikan terlampir

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| entity | [Entity](../../com.aspose.threed/entity) | Entitas default yang dilampirkan ke node |

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


Buat node anak baru dengan nama node yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | java.lang.String | Nama node anak baru |

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


Buat node anak baru dengan nama node yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | java.lang.String | Nama node anak baru |
| entity | [Entity](../../com.aspose.threed/entity) | Entitas default yang dilampirkan ke node |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### createChildNode(String nodeName, Entity entity, Material material) {#createChildNode-java.lang.String-com.aspose.threed.Entity-com.aspose.threed.Material-}
```
public Node createChildNode(String nodeName, Entity entity, Material material)
```


Buat node anak baru dengan nama node yang diberikan, dan lampirkan entitas yang ditentukan serta sebuah material

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | java.lang.String | Nama node anak baru |
| entity | [Entity](../../com.aspose.threed/entity) | Entitas default yang dilampirkan ke node |
| material | [Material](../../com.aspose.threed/material) | Material yang dilampirkan ke node |

**Returns:**
[Node](../../com.aspose.threed/node) - The new child node.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### evaluateGlobalTransform(boolean withGeometricTransform) {#evaluateGlobalTransform-boolean-}
```
public Matrix4 evaluateGlobalTransform(boolean withGeometricTransform)
```


Evaluasi transformasi global, sertakan transformasi geometrik atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| withGeometricTransform | boolean | Apakah transformasi geometrik diperlukan. |

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


Menemukan properti. Itu dapat menjadi properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | java.lang.String | Nama properti. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Info aset per-node

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - Per-node asset info
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


Hitung kotak pembatas node

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of current node
### getChild(int index) {#getChild-int-}
```
public Node getChild(int index)
```


Mendapatkan node anak pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks. |

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


Mendapatkan node anak dengan nama yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | java.lang.String | Nama anak yang akan dicari. |

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


Mendapatkan node anak-anak.

**Returns:**
java.util.List<com.aspose.threed.Node> - node anak. **Example:** Kode berikut menunjukkan cara mengenumerasi node anak dari node akar

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


Mendapatkan semua entitas node.

**Returns:**
java.util.List<com.aspose.threed.Entity> - semua entitas node.
### getEntity() {#getEntity--}
```
public Entity getEntity()
```


Mendapatkan entitas pertama yang terlampir pada node ini, jika diatur, akan menghapus entitas lain.

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


Mendapatkan apakah akan mengecualikan node ini dan semua node/entitas anak selama proses ekspor.

**Returns:**
boolean - apakah node ini dan semua node/entitas anak harus dikecualikan selama ekspor. **Example:** Kode berikut menunjukkan cara mengecualikan node tertentu dari proses ekspor

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


Mendapatkan transformasi global.

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


Mendapatkan material pertama yang terkait dengan node ini, jika diatur, akan menghapus material lain

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


Mendapatkan material yang terkait dengan node ini.

**Returns:**
java.util.List<com.aspose.threed.Material> - material yang terkait dengan node ini.
### getMetaDatas() {#getMetaDatas--}
```
public List<CustomObject> getMetaDatas()
```


Mendapatkan metadata yang didefinisikan dalam node ini.

**Returns:**
java.util.List<com.aspose.threed.CustomObject> - metadata yang didefinisikan dalam node ini.
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama.

**Returns:**
java.lang.String - nama.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


Mendapatkan node induk.

**Returns:**
[Node](../../com.aspose.threed/node) - the parent node.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Mendapatkan koleksi semua properti.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Dapatkan nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |

**Returns:**
java.lang.Object - Nilai dari properti yang ditemukan
### getScene() {#getScene--}
```
public Scene getScene()
```


Mendapatkan adegan yang dimiliki objek ini

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTransform() {#getTransform--}
```
public Transform getTransform()
```


Mendapatkan transformasi lokal.

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


Mendapatkan untuk menampilkan node

**Returns:**
boolean - untuk menampilkan node **Example:** Kode berikut menunjukkan cara membuat node tidak terlihat

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


Lepaskan semua yang berada di bawah node dan lampirkan ke node saat ini. **Example:** Kode berikut menunjukkan cara menggabungkan dua file 3D menjadi satu file

```
Scene scene1 = Scene.fromFile("scene1.fbx");
     Scene scene2 = Scene.fromFile("scene2.fbx");
     scene1.getRootNode().merge(scene2.getRootNode());
     scene1.save("merged.fbx");
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Menghapus properti dinamis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Hapus properti yang ditentukan yang diidentifikasi dengan nama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Properti mana yang akan dihapus |

**Returns:**
boolean - true jika properti berhasil dihapus
### selectObjects(String path) {#selectObjects-java.lang.String-}
```
public ArrayList<Object> selectObjects(String path)
```


Pilih beberapa objek di bawah node saat ini menggunakan sintaks kueri mirip XPath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | java.lang.String | Kueri mirip XPath |

**Returns:**
java.util.ArrayList<java.lang.Object> - Beberapa objek cocok dengan kueri bergaya XPath.
### selectSingleObject(String path) {#selectSingleObject-java.lang.String-}
```
public Object selectSingleObject(String path)
```


Pilih satu objek di bawah node saat ini menggunakan sintaks kueri mirip XPath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | java.lang.String | Kueri mirip XPath |

**Returns:**
java.lang.Object - Objek yang ditemukan oleh kueri bergaya XPath.
### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Info aset per-node

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nilai baru |

### setEntity(Entity value) {#setEntity-com.aspose.threed.Entity-}
```
public void setEntity(Entity value)
```


Mengatur entitas pertama yang terlampir pada node ini, jika diatur, akan menghapus entitas lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Entity](../../com.aspose.threed/entity) | Nilai baru **Example:** Kode berikut menunjukkan cara membuat node anak baru di bawah node akar |

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


Mengatur apakah akan mengecualikan node ini dan semua node/entitas anak selama proses ekspor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | Nilai baru **Example:** Kode berikut menunjukkan cara mengecualikan node yang ditentukan dari proses ekspor |

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


Mengatur material pertama yang terkait dengan node ini, jika diatur, akan menghapus material lain

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [Material](../../com.aspose.threed/material) | Nilai baru **Example:** |

```
Scene scene = new Scene();
     var node = scene.getRootNode().createChildNode(new Box());
     node.setMaterial(new LambertMaterial());
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengatur nama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


Mengatur node induk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nilai baru |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Mengatur nilai properti yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti |
| nilai | java.lang.Object | Nilai properti |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Mengatur untuk menampilkan node

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | Nilai baru **Example:** Kode berikut menunjukkan cara membuat node tak terlihat |

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


Mendapatkan representasi string dari node ini.

**Returns:**
java.lang.String - Representasi string dari node ini untuk debugging.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

