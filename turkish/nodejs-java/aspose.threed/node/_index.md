---
title: "Node"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/node/
---
## Node class

Sahne grafiğinde bir öğeyi temsil eder.  Sahne grafiği, Node nesnelerinden oluşan bir ağaçtır.  Ağaç yönetim hizmetleri bu sınıfta kendi içinde bulunur.  Not: Aspose.3D SDK, oluşturulan sahne grafiğinin geçerliliğini test etmez.  Çağıranın sorumluluğu, bir düğüm hiyerarşisinde döngüsel grafikler oluşturmadığından emin olmaktır.  Ağaç yönetiminin yanı sıra, bu sınıf nesnenin sahnedeki konumunu tanımlamak için gereken tüm özellikleri tanımlar.  Bu bilgiler temel Çeviri (Translation), Dönme (Rotation) ve Ölçekleme (Scaling) özelliklerini ve pivotalar, sınırlar ve IK eklemleri gibi daha gelişmiş seçenekleri, örneğin sertlik ve sönümleme gibi nitelikleri içerir.  İlk oluşturulduğunda, Node nesnesi "empty" (yani: yalnızca konum bilgisi içeren ve herhangi bir grafik temsili olmayan bir nesnedir) durumundadır.  Bu durumda, düğüm ağacı yapısında ebeveynleri temsil etmek için kullanılabilir ancak daha fazlası için uygun değildir.  Bu tür nesnelerin normal kullanımı, düğümü özelleştirecek bir varlık eklemektir ("Entity" bölümüne bakınız).  Varlık, kendisi bir nesnedir ve Node'a bağlanır.  Bu aynı zamanda aynı varlığın birden fazla düğüm arasında paylaşılabileceği anlamına gelir.  Kamera, Işık, Mesh vb. hepsi varlıklardır ve hepsi temel sınıf Entity'den türetilir.


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
| getVisible() | Düğümü göstermek için alır veya ayarlar. |

 **Result:**



---


### setVisible{#setVisible}

| Ad | Açıklama |
| --- | --- |
| setVisible(value) | Düğümü göstermek için alır veya ayarlar. |

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
| getExcluded() | Bu düğümü ve tüm çocuk düğüm/varlıkları dışa aktarma sırasında hariç tutup tutmayacağını alır veya ayarlar. |

 **Result:**



---


### setExcluded{#setExcluded}

| Ad | Açıklama |
| --- | --- |
| setExcluded(value) | Bu düğümü ve tüm çocuk düğüm/varlıkları dışa aktarma sırasında hariç tutup tutmayacağını alır veya ayarlar. |

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
| getGlobalTransform() | Genel dönüşümü alır. Genel dönüşüm. |

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
Node


---


### merge{#merge}

| Ad | Açıklama |
| --- | --- |
| merge(node) | Düğümün altındaki her şeyi ayır ve mevcut düğüme ekle. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| baş | Node | null |

 **Result:**
Node


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
Node


---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode(entity) | Verilen varlık ekli yeni bir alt düğüm oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| varlık | Varlık | Düğüme ekli varsayılan varlık |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode(nodeName, entity) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Yeni alt düğümün adı |
| varlık | Varlık | Düğüme ekli varsayılan varlık |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Ad | Açıklama |
| --- | --- |
| createChildNode(nodeName, entity, material) | Verilen düğüm adıyla yeni bir alt düğüm oluşturur ve belirtilen varlığı ve bir malzemeyi ekler |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Yeni alt düğümün adı |
| varlık | Varlık | Düğüme ekli varsayılan varlık |
| material | Malzeme | Düğüme ekli malzeme |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Ad | Açıklama |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Genel dönüşümü değerlendir, geometrik dönüşümü dahil et ya da etme. |

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
| indeks | Sayı | İndeks. |

 **Result:**
Node


---


### getChild{#getChild}

| Ad | Açıklama |
| --- | --- |
| getChild(nodeName) | Belirtilen ada sahip alt düğümü alır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| nodeName | String | Bulunacak alt düğüm adı. |

 **Result:**
Node


---


### accept{#accept}

| Ad | Açıklama |
| --- | --- |
| accept(visitor) | Mevcut düğüm dahil olmak üzere tüm alt düğümler arasında yürür ve ziyaretçiyi düğümle birlikte çağırır. Ziyaretçi, false döndürerek yürütmeyi durdurabilir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| visitor | NodeVisitor | Düğümü ziyaret etmek için ziyaretçi geri çağrısı |

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
| node | Node | Eklenecek alt düğüm |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Ad | Açıklama |
| --- | --- |
| selectSingleObject(path) | XPath benzeri sorgu sözdizimini kullanarak geçerli düğüm altında tek bir nesne seçin. |

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
| selectObjects(path) | XPath benzeri sorgu sözdizimini kullanarak geçerli düğüm altında birden fazla nesne seçin. |

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
| özellik | Özellik | Hangi özelliği kaldırmak istiyorsunuz |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Ad | Açıklama |
| --- | --- |
| removeProperty(property) | Adına göre belirtilen özelliği kaldır |

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
| özellik | String | Özellik adı |

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
| özellik | String | Özellik adı |
| değer | Object | Özelliğin değeri |

 **Result:**
Object


---


### findProperty{#findProperty}

| Ad | Açıklama |
| --- | --- |
| findProperty(propertyName) | Özelliği bulur. Dinamik bir özellik (CreateDynamicProperty/SetProperty ile oluşturulan) veya yerel özellik (adıyla tanımlanan) olabilir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| propertyName | String | Özellik adı. |

 **Result:**
Özellik


---



