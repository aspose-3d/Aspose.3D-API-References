---
title: "Silindir"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

Parametreli Silindir. radiusTop/radiusBottom değerlerinden biri sıfır olduğunda koniyi temsil etmek için de kullanılabilir.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | Silindir sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(radius, height) | Silindir sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| yarıçap | Number | Üst ve alt kapakların yarıçapı. |
| height | Number | Yükseklik. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Silindir sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| radiusTop | Number | Üst yarıçap. |
| radiusBottom | Number | Alt yarıçap. |
| height | Number | Yükseklik. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Ad | Açıklama |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Silindir sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| radiusTop | Number | Silindirin üst kapağının yarıçapı. |
| radiusBottom | Number | Silindirin alt kapağının yarıçapı. |
| height | Number | Silindirin yüksekliği. |
| radialSegments | Number | Radial segmentleri hem üst hem alt dairelerin.. |
| heightSegments | Number | Yükseklik segmentleri. |
| openEnded | boolean | Eğer ayarlanırsa |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Ad | Açıklama |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Silindir sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Bu nesnenin adı |
| radiusTop | Number | Silindirin üst kapağının yarıçapı. |
| radiusBottom | Number | Silindirin alt kapağının yarıçapı. |
| height | Number | Silindirin yüksekliği. |
| radialSegments | Number | Radial segmentleri hem üst hem alt dairelerin.. |
| heightSegments | Number | Yükseklik segmentleri. |
| openEnded | boolean | Eğer ayarlanırsa |
| thetaStart | Number | Theta başlangıcı. |
| thetaLength | Number | Theta uzunluğu. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| Ad | Açıklama |
| --- | --- |
| getOffsetBottom() | Alt tarafın köşe dönüşüm ofsetini alır veya ayarlar. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| Ad | Açıklama |
| --- | --- |
| setOffsetBottom(value) | Alt tarafın köşe dönüşüm ofsetini alır veya ayarlar. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| Ad | Açıklama |
| --- | --- |
| getOffsetTop() | Üst tarafın köşe dönüşüm ofsetini alır veya ayarlar. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| Ad | Açıklama |
| --- | --- |
| setOffsetTop(value) | Üst tarafın köşe dönüşüm ofsetini alır veya ayarlar. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| Ad | Açıklama |
| --- | --- |
| getGenerateFanCylinder() | ThetaLength 2PI'den küçük olduğunda fan tarzı silindiri oluşturup oluşturmayacağını alır veya ayarlar; aksi takdirde model kesilmez. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| Ad | Açıklama |
| --- | --- |
| setGenerateFanCylinder(value) | ThetaLength 2PI'den küçük olduğunda fan tarzı silindiri oluşturup oluşturmayacağını alır veya ayarlar; aksi takdirde model kesilmez. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| Ad | Açıklama |
| --- | --- |
| getShearBottom() | Alt tarafın kayma dönüşümünü alır veya ayarlar, vektör (x ekseni, z ekseni) kayma değerini radyan cinsinden saklar, varsayılan değer (0, 0)'dır. |

 **Result:**



---


### setShearBottom{#setShearBottom}

| Ad | Açıklama |
| --- | --- |
| setShearBottom(value) | Alt tarafın kayma dönüşümünü alır veya ayarlar, vektör (x ekseni, z ekseni) kayma değerini radyan cinsinden saklar, varsayılan değer (0, 0)'dır. |

 **Result:**



---


### getShearTop{#getShearTop}

| Ad | Açıklama |
| --- | --- |
| getShearTop() | Üst tarafın kayma dönüşümünü alır veya ayarlar, vektör (x ekseni, z ekseni) kayma değerini radyan cinsinden saklar, varsayılan değer (0, 0)'dır. |

 **Result:**



---


### setShearTop{#setShearTop}

| Ad | Açıklama |
| --- | --- |
| setShearTop(value) | Üst tarafın kayma dönüşümünü alır veya ayarlar, vektör (x ekseni, z ekseni) kayma değerini radyan cinsinden saklar, varsayılan değer (0, 0)'dır. |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| Ad | Açıklama |
| --- | --- |
| getRadiusTop() | Silindirin üst kapağının yarıçapını alır veya ayarlar. Üst kapağın yarıçapı. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| Ad | Açıklama |
| --- | --- |
| setRadiusTop(value) | Silindirin üst kapağının yarıçapını alır veya ayarlar. Üst kapağın yarıçapı. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| Ad | Açıklama |
| --- | --- |
| getRadiusBottom() | Silindirin alt kapağının yarıçapını alır veya ayarlar. Alt kapağın yarıçapı. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| Ad | Açıklama |
| --- | --- |
| setRadiusBottom(value) | Silindirin alt kapağının yarıçapını alır veya ayarlar. Alt kapağın yarıçapı. |

 **Result:**



---


### getHeight{#getHeight}

| Ad | Açıklama |
| --- | --- |
| getHeight() | Silindirin yüksekliğini alır veya ayarlar. Yükseklik. |

 **Result:**



---


### setHeight{#setHeight}

| Ad | Açıklama |
| --- | --- |
| setHeight(value) | Silindirin yüksekliğini alır veya ayarlar. Yükseklik. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| Ad | Açıklama |
| --- | --- |
| getRadialSegments() | Radyal segmentleri alır veya ayarlar. Radyal segmentler. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| Ad | Açıklama |
| --- | --- |
| setRadialSegments(value) | Radyal segmentleri alır veya ayarlar. Radyal segmentler. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Ad | Açıklama |
| --- | --- |
| getHeightSegments() | Yükseklik segmentlerini alır veya ayarlar. Yükseklik segmentleri. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Ad | Açıklama |
| --- | --- |
| setHeightSegments(value) | Yükseklik segmentlerini alır veya ayarlar. Yükseklik segmentleri. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| Ad | Açıklama |
| --- | --- |
| getOpenEnded() | Bu silindirin açık uçlu olup olmadığını belirten bir değeri alır veya ayarlar. Varsayılan değer false'tur. Açık uçlu ise true; aksi takdirde üst/alt kapaklar bulunur. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| Ad | Açıklama |
| --- | --- |
| setOpenEnded(value) | Bu silindirin açık uçlu olup olmadığını belirten bir değeri alır veya ayarlar. Varsayılan değer false'tur. Açık uçlu ise true; aksi takdirde üst/alt kapaklar bulunur. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| Ad | Açıklama |
| --- | --- |
| getThetaStart() | Theta başlangıcını alır veya ayarlar. Varsayılan değer 0'dır. Theta başlangıcı. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| Ad | Açıklama |
| --- | --- |
| setThetaStart(value) | Theta başlangıcını alır veya ayarlar. Varsayılan değer 0'dır. Theta başlangıcı. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| Ad | Açıklama |
| --- | --- |
| getThetaLength() | Theta uzunluğunu alır veya ayarlar. Varsayılan değer 2π'dir. Theta uzunluğu. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| Ad | Açıklama |
| --- | --- |
| setThetaLength(value) | Theta uzunluğunu alır veya ayarlar. Varsayılan değer 2π'dir. Theta uzunluğu. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Ad | Açıklama |
| --- | --- |
| getCastShadows() | Bu geometrinin gölge oluşturup oluşturamayacağını alır veya ayarlar |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Ad | Açıklama |
| --- | --- |
| setCastShadows(value) | Bu geometrinin gölge oluşturup oluşturamayacağını alır veya ayarlar |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Ad | Açıklama |
| --- | --- |
| getReceiveShadows() | Bu geometrinin gölge alıp almayacağını alır veya ayarlar. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Ad | Açıklama |
| --- | --- |
| setReceiveShadows(value) | Bu geometrinin gölge alıp almayacağını alır veya ayarlar. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Ad | Açıklama |
| --- | --- |
| getParentNodes() | Tüm üst düğümleri alır; bir varlık geometri örneklemesi için birden çok üst düğüme bağlanabilir. Düğümler. |

 **Result:**



---


### getExcluded{#getExcluded}

| Ad | Açıklama |
| --- | --- |
| getExcluded() | Bu varlığın dışa aktarım sırasında hariç tutulup tutulmayacağını alır veya ayarlar. |

 **Result:**



---


### setExcluded{#setExcluded}

| Ad | Açıklama |
| --- | --- |
| setExcluded(value) | Bu varlığın dışa aktarım sırasında hariç tutulup tutulmayacağını alır veya ayarlar. |

 **Result:**



---


### getParentNode{#getParentNode}

| Ad | Açıklama |
| --- | --- |
| getParentNode() | İlk üst düğümü alır veya ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. Üst düğüm. |

 **Result:**



---


### setParentNode{#setParentNode}

| Ad | Açıklama |
| --- | --- |
| setParentNode(value) | İlk üst düğümü alır veya ayarlar, eğer ilk üst düğüm ayarlanırsa, bu varlık diğer üst düğümlerden ayrılacaktır. Üst düğüm. |

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


### toMesh{#toMesh}

| Ad | Açıklama |
| --- | --- |
| toMesh() | Mevcut nesneyi mesh'e dönüştür |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Ad | Açıklama |
| --- | --- |
| getEntityRendererKey() | Renderörde kaydedilen varlık renderlayıcısının anahtarını alır. |

 **Result:**
EntityRendererKey


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



