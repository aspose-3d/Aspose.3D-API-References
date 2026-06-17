---
title: "Düğüm"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/node/
---
## Node class

Scene graph içinde bir öğeyi temsil eder. Scene graph, Node nesnelerinden oluşan bir ağaçtır. Ağaç yönetim hizmetleri bu sınıfta kendi içinde bulunur. Aspose.3D SDK'nın oluşturulan scene graph'ın geçerliliğini test etmediğini unutmayın. Çağıranın sorumluluğu, bir düğüm hiyerarşisinde döngüsel grafikler oluşturmadığından emin olmaktır. Ağaç yönetiminin yanı sıra, bu sınıf nesnenin sahnedeki konumunu tanımlamak için gereken tüm özellikleri tanımlar. Bu bilgiler temel Translation, Rotation ve Scaling özelliklerini ve pivots, limits ve IK eklemleri gibi daha gelişmiş seçenekleri, örneğin stiffness ve dampening gibi nitelikleri içerir. İlk oluşturulduğunda, Node nesnesi "empty" (yani: yalnızca konum bilgisi içeren ve herhangi bir grafik temsiline sahip olmayan bir nesnedir). Bu durumda, düğüm ağacı yapısında ebeveynleri temsil etmek için kullanılabilir ancak çok daha fazlası için değil. Bu tür nesnelerin normal kullanımı, düğümü özelleştirecek bir entity eklemektir ("Entity" bölümüne bakınız). Entity, kendisi bir nesnedir ve Node'a bağlanır. Bu aynı zamanda aynı entity'nin birden fazla düğüm arasında paylaşılabileceği anlamına gelir. Camera, Light, Mesh vb. hepsi entity'dir ve hepsi temel sınıf Entity'den türetilir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | Node sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(name, entity) | Node sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad. |
| varlık | Varlık | Varsayılan varlık. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2(name) | Node sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Ad | Açıklama |
| --- | --- |
| getAssetInfo() | Düğüm başına varlık bilgisi |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Ad | Açıklama |
| --- | --- |
| setAssetInfo(value) | Düğüm başına varlık bilgisi |

 **Result:**



---


### getVisible{#getVisible}

| Ad | Açıklama |
| --- | --- |
| getVisible() | Düğümü göstermek için alır veya ayarlar |

 **Result:**



---


### setVisible{#setVisible}

| Ad | Açıklama |
| --- | --- |
| setVisible(value) | Düğümü göstermek için alır veya ayarlar |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Ad | Açıklama |
| --- | --- |
| getChildNodes() | Çocuk düğümleri alır. Düğümler. |

 **Result:**



---


### getEntity{#getEntity}

| Ad | Açıklama |
| --- | --- |
| getEntity() | Bu düğüme eklenen ilk varlığı alır veya ayarlar, ayarlanırsa diğer varlıkları temizler. Düğüm varlığı. |

 **Result:**



---


### setEntity{#setEntity}

| Ad | Açıklama |
| --- | --- |
| setEntity(value) | Bu düğüme eklenen ilk varlığı alır veya ayarlar, ayarlanırsa diğer varlıkları temizler. Düğüm varlığı. |

 **Result:**



---


### getExcluded{#getExcluded}

| Ad | Açıklama |
| --- | --- |
| getExcluded() | Dışa aktarım sırasında bu düğümü ve tüm çocuk düğümleri/varlıkları dışlamayı alır veya ayarlar. |

 **Result:**



---


### setExcluded{#setExcluded}

| Ad | Açıklama |
| --- | --- |
| setExcluded(value) | Dışa aktarım sırasında bu düğümü ve tüm çocuk düğümleri/varlıkları dışlamayı alır veya ayarlar. |

 **Result:**



---


### getEntities{#getEntities}

| Ad | Açıklama |
| --- | --- |
| getEntities() | Tüm düğüm varlıklarını alır. Düğüm varlıkları. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Ad | Açıklama |
| --- | --- |
| getMetaDatas() | Bu düğümde tanımlanan meta verileri alır. Meta veriler. |

 **Result:**



---


### getMaterials{#getMaterials}

| Ad | Açıklama |
| --- | --- |
| getMaterials() | Bu düğümle ilişkili malzemeleri alır. Malzemeler. |

 **Result:**



---


### getMaterial{#getMaterial}

| Ad | Açıklama |
| --- | --- |
| getMaterial() | Bu düğümle ilişkili ilk malzemeyi alır veya ayarlar, ayarlanırsa diğer malzemeleri temizler. Malzeme. |

 **Result:**



---


### setMaterial{#setMaterial}

| Ad | Açıklama |
| --- | --- |
| setMaterial(value) | Bu düğümle ilişkili ilk malzemeyi alır veya ayarlar, ayarlanırsa diğer malzemeleri temizler. Malzeme. |

 **Result:**



---


### getParentNode{#getParentNode}

| Ad | Açıklama |
| --- | --- |
| getParentNode() | Üst düğümü alır veya ayarlar. Üst düğüm. |

 **Result:**



---


### setParentNode{#setParentNode}

| Ad | Açıklama |
| --- | --- |
| setParentNode(value) | Üst düğümü alır veya ayarlar. Üst düğüm. |

 **Result:**



---


### getTransform{#getTransform}

| Ad | Açıklama |
| --- | --- |
| getTransform() | Yerel dönüşümü alır. Dönüşüm. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Ad | Açıklama |
| --- | --- |
| getGlobalTransform() | Küresel dönüşümü alır. Küresel dönüşüm. |

 **Result:**



---


### getScene{#getScene}

| Ad | Açıklama |
| --- | --- |
| getScene() | Bu nesnenin ait olduğu sahneyi alır. |

 **Result:**



---


### getName{#getName}

| Ad | Açıklama |
| --- | --- |
| getName() | Adı alır veya ayarlar. Ad. |

 **Result:**



---


### setName{#setName}

| Ad | Açıklama |
| --- | --- |
| setName(value) | Adı alır veya ayarlar. Ad. |

 **Result:**



---


### getProperties{#getProperties}

| Ad | Açıklama |
| --- | --- |
| getProperties() | Tüm özelliklerin koleksiyonunu alır. |

 **Result:**



---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode() | Bir alt düğüm oluşturur |

 **Result:**
Düğüm


---


### merge{#merge}

| Ad | Açıklama |
| --- | --- |
| merge(node) | Düğüm altındaki her şeyi ayır ve mevcut düğüme ekle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nod | Düğüm | null |

 **Result:**
Düğüm


---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode(nodeName) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Yeni alt düğümün adı |

 **Result:**
Düğüm


---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode(entity) | Verilen varlık eklenmiş yeni bir alt düğüm oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Düğüme eklenmiş varsayılan varlık |

 **Result:**
Düğüm


---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode(nodeName, entity) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Yeni alt düğümün adı |
| varlık | Varlık | Düğüme eklenmiş varsayılan varlık |

 **Result:**
Düğüm


---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode(nodeName, entity, material) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur ve belirtilen varlığı ve bir malzemeyi ekler |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Yeni alt düğümün adı |
| varlık | Varlık | Düğüme eklenmiş varsayılan varlık |
| material | Malzeme | Düğüme eklenmiş malzeme |

 **Result:**
Düğüm


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Ad | Açıklama |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Küresel dönüşümü değerlendir, geometrik dönüşümü dahil edip etmeyeceğini belirt. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| withGeometricTransform | boolean | Geometrik dönüşümün gerekip gerekmediği. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Ad | Açıklama |
| --- | --- |
| getChild(index) | Belirtilen indeksteki alt düğümü alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| indeks | Number | İndeks. |

 **Result:**
Düğüm


---


### getChild{#getChild}

| Ad | Açıklama |
| --- | --- |
| getChild(nodeName) | Belirtilen ada sahip alt düğümü alır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Bulunacak alt düğüm adı. |

 **Result:**
Düğüm


---


### accept{#accept}

| Ad | Açıklama |
| --- | --- |
| accept(visitor) | Tüm alt düğümler arasında (geçerli düğüm dahil) yürür ve ziyaretçiyi düğümle birlikte çağırır. Ziyaretçi, false döndürerek yürütmeyi durdurabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| ziyaretçi | NodeVisitor | Düğümü ziyaret etmek için ziyaretçi geri çağrısı |

 **Result:**
boolean


---


### toString{#toString}

| Ad | Açıklama |
| --- | --- |
| toString() | Bu düğümün string temsilini alır. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Düğümün sınırlayıcı kutusunu hesapla |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Ad | Açıklama |
| --- | --- |
| addEntity(entity) | Bir varlığı düğüme ekle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Düğüme eklenecek varlık |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Ad | Açıklama |
| --- | --- |
| addChildNode(node) | Bu düğüme bir alt düğüm ekle |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| düğüm | Düğüm | Eklenecek alt düğüm |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Ad | Açıklama |
| --- | --- |
| selectSingleObject(path) | XPath benzeri sorgu sözdizimi kullanarak geçerli düğüm altında tek bir nesne seç. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| Ad | Açıklama |
| --- | --- |
| selectObjects(path) | XPath benzeri sorgu sözdizimi kullanarak geçerli düğüm altında birden fazla nesne seç. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| pat | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Dinamik bir özelliği kaldırır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | Property | Hangi özellik kaldırılacak |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Adı belirtilen özelliği kaldır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Ad | Açıklama |
| --- | --- |
| getProperty(property) | Belirtilen özelliğin değerini al |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | String | Özellik adı |

 **Result:**
Object


---


### setProperty{#setProperty}

| Ad | Açıklama |
| --- | --- |
| setProperty(property, value) | Belirtilen özelliğin değerini ayarlar |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| property | String | Özellik adı |
| değer | Object | Özelliğin değeri |

 **Result:**
Object


---


### findProperty{#findProperty}

| Ad | Açıklama |
| --- | --- |
| findProperty(propertyName) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propertyName | String | Özellik adı. |

 **Result:**
Property


---



