---
title: "NurbsCurve"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS eğrisi, NURBS (Non-uniform rational basis spline) tarafından temsil edilen bir eğridir,  Bir NURBS eğrisi, Order'ı, ağırlıklı Geometry.ControlPoints kümesi ve KnotVectors ile tanımlanır. Kontrol noktasındaki w bileşeni, kontrol noktasının ağırlığı olarak kullanılır; bu, CurveDimension.TWO_DIMENSIONAL ya da CurveDimension.THREE_DIMENSIONAL olsun fark etmez.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | NurbsCurve sınıfının yeni bir örneğini başlatır. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(name) | NurbsCurve sınıfının yeni bir örneğini başlatır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| name | String | Ad |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Ad | Açıklama |
| --- | --- |
| getControlPoints() | Tüm kontrol noktalarını alır |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Ad | Açıklama |
| --- | --- |
| getMultiplicity() | Çokluğu alır. Çokluk. |

 **Result:**



---


### getOrder{#getOrder}

| Ad | Açıklama |
| --- | --- |
| getOrder() | Bir NURBS eğrisinin mertebesini alır veya ayarlar, bu mertebe eğri üzerindeki herhangi bir noktayı etkileyen yakın kontrol noktalarının sayısını tanımlar. Mertebe. |

 **Result:**



---


### setOrder{#setOrder}

| Ad | Açıklama |
| --- | --- |
| setOrder(value) | Bir NURBS eğrisinin mertebesini alır veya ayarlar, bu mertebe eğri üzerindeki herhangi bir noktayı etkileyen yakın kontrol noktalarının sayısını tanımlar. Mertebe. |

 **Result:**



---


### getDimension{#getDimension}

| Ad | Açıklama |
| --- | --- |
| getDimension() | Eğrinin boyutunu alır veya ayarlar. Özelliğin değeri CurveDimension tam sayı sabitidir. CurveDimension.TWO_DIMENSIONAL bir eğri için kontrol noktasındaki z bileşeni kullanılmaz. |

 **Result:**



---


### setDimension{#setDimension}

| Ad | Açıklama |
| --- | --- |
| setDimension(value) | Eğrinin boyutunu alır veya ayarlar. Özelliğin değeri CurveDimension tam sayı sabitidir. CurveDimension.TWO_DIMENSIONAL bir eğri için kontrol noktasındaki z bileşeni kullanılmaz. |

 **Result:**



---


### getCurveType{#getCurveType}

| Ad | Açıklama |
| --- | --- |
| getCurveType() | Eğrinin tipini alır veya ayarlar. Özelliğin değeri NurbsType tamsayı sabitidir. Eğrinin tipi. |

 **Result:**



---


### setCurveType{#setCurveType}

| Ad | Açıklama |
| --- | --- |
| setCurveType(value) | Eğrinin tipini alır veya ayarlar. Özelliğin değeri NurbsType tamsayı sabitidir. Eğrinin tipi. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Ad | Açıklama |
| --- | --- |
| getKnotVectors() | Knot vektörünü alır, bu kontrol noktalarının NURBS eğrisini nerede ve nasıl etkilediğini belirleyen parametre değerlerinin bir dizisidir. |

 **Result:**



---


### getRational{#getRational}

| Ad | Açıklama |
| --- | --- |
| getRational() | Rasyonel olup olmadığını alır veya ayarlar, bu değer bu NurbsCurve'un rasyonel spline mı yoksa rasyonel olmayan spline mı olduğunu gösterir. Rasyonel olmayan B-spline, rasyonel B-spline'ların özel bir durumudur. true ise rasyonel spline; aksi takdirde false rasyonel olmayan spline'dır. |

 **Result:**



---


### setRational{#setRational}

| Ad | Açıklama |
| --- | --- |
| setRational(value) | Rasyonel olup olmadığını alır veya ayarlar, bu değer bu NurbsCurve'un rasyonel spline mı yoksa rasyonel olmayan spline mı olduğunu gösterir. Rasyonel olmayan B-spline, rasyonel B-spline'ların özel bir durumudur. true ise rasyonel spline; aksi takdirde false rasyonel olmayan spline'dır. |

 **Result:**



---


### getColor{#getColor}

| Ad | Açıklama |
| --- | --- |
| getColor() | Çizginin rengini alır veya ayarlar, varsayılan değer beyazdır (1, 1, 1). |

 **Result:**



---


### setColor{#setColor}

| Ad | Açıklama |
| --- | --- |
| setColor(value) | Çizginin rengini alır veya ayarlar, varsayılan değer beyazdır (1, 1, 1). |

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


### evaluate{#evaluate}

| Ad | Açıklama |
| --- | --- |
| evaluate(steps) | NURBS eğrisini değerlendir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| steps | Number | İki komşu knot arasındaki değerlendirme sıklığı, varsayılan değer 20'dir. |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Ad | Açıklama |
| --- | --- |
| evaluateAt(u) | Eğrinin belirtilen konumdaki noktasını değerlendir |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| u | Number | Eğrideki konum, 0 ile 1 arasında |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| Ad | Açıklama |
| --- | --- |
| getEntityRendererKey() | Renderörde kaydedilen varlık renderlayıcısının anahtarını alır. |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Ad | Açıklama |
| --- | --- |
| getBoundingBox() | Geçerli varlığın nesne uzayı koordinat sistemindeki sınırlayıcı kutusunu alır. |

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



