---
title: "Node"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/node/
---
## Node class

Mewakili elemen dalam scene graph. Scene graph adalah pohon objek Node. Layanan manajemen pohon berada dalam kelas ini secara mandiri. Perlu dicatat bahwa Aspose.3D SDK tidak menguji validitas scene graph yang dibangun. Tanggung jawab pemanggil adalah memastikan tidak menghasilkan graf siklik dalam hierarki node. Selain manajemen pohon, kelas ini mendefinisikan semua properti yang diperlukan untuk menggambarkan posisi objek dalam scene. Informasi ini mencakup properti dasar Translation, Rotation, dan Scaling serta opsi lanjutan untuk pivot, batas, dan atribut sambungan IK seperti kekakuan dan peredaman. Saat pertama kali dibuat, objek Node berstatus \"empty\" (yaitu: objek tanpa representasi grafis yang hanya berisi informasi posisi). Dalam keadaan ini, ia dapat digunakan untuk merepresentasikan induk dalam struktur pohon node tetapi tidak lebih. Penggunaan umum tipe objek ini adalah menambahkan entitas yang akan mengkhususkan node (lihat \"Entity\"). Entitas adalah objek tersendiri dan terhubung ke Node. Ini juga berarti entitas yang sama dapat dibagikan di antara beberapa node. Kamera, Light, Mesh, dll... semuanya merupakan entitas dan semuanya diturunkan dari kelas dasar Entity.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas Node. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(name, entity) | Menginisialisasi instance baru dari kelas Node. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |
| entity | Entity | Entitas default. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload2(name) | Menginisialisasi instance baru dari kelas Node. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nama | Deskripsi |
| --- | --- |
| getAssetInfo() | Info aset per-node |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nama | Deskripsi |
| --- | --- |
| setAssetInfo(value) | Info aset per-node |

 **Result:**



---


### getVisible{#getVisible}

| Nama | Deskripsi |
| --- | --- |
| getVisible() | Mendapatkan atau mengatur untuk menampilkan node |

 **Result:**



---


### setVisible{#setVisible}

| Nama | Deskripsi |
| --- | --- |
| setVisible(value) | Mendapatkan atau mengatur untuk menampilkan node |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Nama | Deskripsi |
| --- | --- |
| getChildNodes() | Mendapatkan node anak. Node-node tersebut. |

 **Result:**



---


### getEntity{#getEntity}

| Nama | Deskripsi |
| --- | --- |
| getEntity() | Mendapatkan atau mengatur entitas pertama yang terlampir pada node ini, jika diatur, akan menghapus entitas lain. Entitas node. |

 **Result:**



---


### setEntity{#setEntity}

| Nama | Deskripsi |
| --- | --- |
| setEntity(value) | Mendapatkan atau mengatur entitas pertama yang terlampir pada node ini, jika diatur, akan menghapus entitas lain. Entitas node. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nama | Deskripsi |
| --- | --- |
| getExcluded() | Mendapatkan atau mengatur apakah akan mengecualikan node ini dan semua node/entitas anak selama proses ekspor. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nama | Deskripsi |
| --- | --- |
| setExcluded(value) | Mendapatkan atau mengatur apakah akan mengecualikan node ini dan semua node/entitas anak selama proses ekspor. |

 **Result:**



---


### getEntities{#getEntities}

| Nama | Deskripsi |
| --- | --- |
| getEntities() | Mendapatkan semua entitas node. Entitas node. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Nama | Deskripsi |
| --- | --- |
| getMetaDatas() | Mendapatkan metadata yang didefinisikan dalam node ini. Metadata. |

 **Result:**



---


### getMaterials{#getMaterials}

| Nama | Deskripsi |
| --- | --- |
| getMaterials() | Mendapatkan material yang terkait dengan node ini. Material. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nama | Deskripsi |
| --- | --- |
| getMaterial() | Mendapatkan atau mengatur material pertama yang terkait dengan node ini, jika diatur, akan menghapus material lain. Material. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nama | Deskripsi |
| --- | --- |
| setMaterial(value) | Mendapatkan atau mengatur material pertama yang terkait dengan node ini, jika diatur, akan menghapus material lain. Material. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nama | Deskripsi |
| --- | --- |
| getParentNode() | Mendapatkan atau mengatur node induk. Node induk. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nama | Deskripsi |
| --- | --- |
| setParentNode(value) | Mendapatkan atau mengatur node induk. Node induk. |

 **Result:**



---


### getTransform{#getTransform}

| Nama | Deskripsi |
| --- | --- |
| getTransform() | Mendapatkan transformasi lokal. Transformasi tersebut. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Nama | Deskripsi |
| --- | --- |
| getGlobalTransform() | Mendapatkan transformasi global. Transformasi global tersebut. |

 **Result:**



---


### getScene{#getScene}

| Nama | Deskripsi |
| --- | --- |
| getScene() | Mendapatkan adegan yang dimiliki objek ini |

 **Result:**



---


### getName{#getName}

| Nama | Deskripsi |
| --- | --- |
| getName() | Mendapatkan atau mengatur nama. Nama. |

 **Result:**



---


### setName{#setName}

| Nama | Deskripsi |
| --- | --- |
| setName(value) | Mendapatkan atau mengatur nama. Nama. |

 **Result:**



---


### getProperties{#getProperties}

| Nama | Deskripsi |
| --- | --- |
| getProperties() | Mendapatkan koleksi semua properti. |

 **Result:**



---


### createChildNode{#createChildNode}

| Nama | Deskripsi |
| --- | --- |
| createChildNode() | Membuat node anak |

 **Result:**
Node


---


### merge{#merge}

| Nama | Deskripsi |
| --- | --- |
| merge(node) | Lepaskan semua yang berada di bawah node dan lampirkan ke node saat ini. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nod | Node | null |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nama | Deskripsi |
| --- | --- |
| createChildNode(nodeName) | Buat node anak baru dengan nama node yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | String | Nama node anak baru |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nama | Deskripsi |
| --- | --- |
| createChildNode(entity) | Buat node anak baru dengan entitas yang diberikan terlampir |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| entity | Entity | Entitas default yang terlampir pada node |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nama | Deskripsi |
| --- | --- |
| createChildNode(nodeName, entity) | Buat node anak baru dengan nama node yang diberikan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | String | Nama node anak baru |
| entity | Entity | Entitas default yang terlampir pada node |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nama | Deskripsi |
| --- | --- |
| createChildNode(nodeName, entity, material) | Buat node anak baru dengan nama node yang diberikan, dan lampirkan entitas yang ditentukan serta sebuah material |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | String | Nama node anak baru |
| entity | Entity | Entitas default yang terlampir pada node |
| material | Material | Material yang terlampir pada node |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Nama | Deskripsi |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Evaluasi transformasi global, sertakan transformasi geometrik atau tidak. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| withGeometricTransform | boolean | Apakah transformasi geometrik diperlukan. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Nama | Deskripsi |
| --- | --- |
| getChild(index) | Mendapatkan node anak pada indeks yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | Angka | Indeks. |

 **Result:**
Node


---


### getChild{#getChild}

| Nama | Deskripsi |
| --- | --- |
| getChild(nodeName) | Mendapatkan node anak dengan nama yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nodeName | String | Nama anak yang akan dicari. |

 **Result:**
Node


---


### accept{#accept}

| Nama | Deskripsi |
| --- | --- |
| accept(visitor) | Menelusuri semua node turunan (termasuk node saat ini) dan memanggil visitor dengan node tersebut. Visitor dapat menghentikan penelusuran dengan mengembalikan false |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| visitor | NodeVisitor | Callback Visitor untuk mengunjungi node |

 **Result:**
boolean


---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mendapatkan representasi string dari node ini. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| Nama | Deskripsi |
| --- | --- |
| getBoundingBox() | Menghitung kotak pembatas (bounding box) dari node |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Nama | Deskripsi |
| --- | --- |
| addEntity(entity) | Menambahkan entitas ke node. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| entity | Entity | Entitas yang akan dilampirkan ke node |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Nama | Deskripsi |
| --- | --- |
| addChildNode(node) | Menambahkan node anak ke node ini |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| node | Node | Node anak yang akan dilampirkan |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Nama | Deskripsi |
| --- | --- |
| selectSingleObject(path) | Pilih satu objek di bawah node saat ini menggunakan sintaks kueri mirip XPath. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| Nama | Deskripsi |
| --- | --- |
| selectObjects(path) | Pilih beberapa objek di bawah node saat ini menggunakan sintaks kueri mirip XPath. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| pat | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### removeProperty{#removeProperty}

| Nama | Deskripsi |
| --- | --- |
| removeProperty(property) | Menghapus properti dinamis. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | Property | Properti mana yang akan dihapus |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nama | Deskripsi |
| --- | --- |
| removeProperty(property) | Hapus properti yang ditentukan yang diidentifikasi dengan nama |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nama | Deskripsi |
| --- | --- |
| getProperty(property) | Dapatkan nilai properti yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | String | Nama properti |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nama | Deskripsi |
| --- | --- |
| setProperty(property, value) | Menetapkan nilai properti yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| property | String | Nama properti |
| value | Object | Nilai properti |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nama | Deskripsi |
| --- | --- |
| findProperty(propertyName) | Menemukan properti. Bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti native (Diidentifikasi berdasarkan namanya) |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| propertyName | String | Nama properti. |

 **Result:**
Property


---



