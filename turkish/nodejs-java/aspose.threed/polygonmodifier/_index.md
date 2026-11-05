---
title: "PolygonModifier"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Poligonları değiştirmek için yardımcı programlar  @hideconstructor


## Yöntemler

### triangulate{#triangulate}

| Ad | Açıklama |
| --- | --- |
| triangulate(scene) | Tüm çokgen tabanlı ağları tam üçgen ağa dönüştür |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| scene | Sahne | İşlenecek sahne |

 **Result:**



---


### triangulate{#triangulate}

| Ad | Açıklama |
| --- | --- |
| triangulate(mesh) | Bir çokgen tabanlı ağı tam üçgen ağa dönüştür |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| mesh | Mesh | Orijinal üçgen olmayan ağ |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Ad | Açıklama |
| --- | --- |
| mergeMesh(scene) | Tüm sahneyi tek bir dönüştürülmüş ağa dönüştür. Normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| scene | Sahne | Birleştirilecek sahne |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Ad | Açıklama |
| --- | --- |
| mergeMesh(node) | Tüm düğümü tek bir dönüştürülmüş ağa dönüştür. Normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| node | Node | Birleştirilecek düğüm |

 **Result:**
Mesh


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(scene, scale) | Bu sahnedeki tüm geometrileri ölçeklendir (Kontrol noktalarını ölçeklendir, dönüşüm matrisini değil) |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| scene | Sahne | Ölçeklendirilecek sahne |
| ölçek | Vector3 | Ölçek faktörü |

 **Result:**
Mesh


---


### scale{#scale}

| Ad | Açıklama |
| --- | --- |
| scale(node, scale) | Bu düğümde tüm geometrileri ölçekle (Dönüşüm matrisini değil, kontrol noktalarını ölçekle) |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| node | Node | Ölçeklenecek düğüm |
| ölçek | Vector3 | Ölçek faktörü |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Ad | Açıklama |
| --- | --- |
| generateNormal(mesh) | Mesh tanımından normal verileri oluştur |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Ad | Açıklama |
| --- | --- |
| generateUV(mesh, normals) | Verilen giriş mesh'inden ve belirtilen normal verilerinden UV verileri oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| mesh | Mesh | Giriş mesh'i |
| normaller | VertexElementNormal | Normal verileri |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Ad | Açıklama |
| --- | --- |
| generateUV(mesh) | Verilen giriş mesh'inden UV verileri oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| mesh | Mesh | Giriş mesh'i |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Ad | Açıklama |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Mesh'i VertexElementMaterial'e göre alt-mesh'lere böl. Her alt-mesh yalnızca bir malzeme kullanacak. Bir düğümde mesh bölmeyi gerçekleştir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| baş | Node | null |
| politika | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Her alt-mesh için çocuk düğümler oluştur. |
| removeOldMesh | boolean | Bölme işleminden sonra eski mesh'i kaldır, bu parametre false ise eski ve yeni mesh'ler birlikte var olacaktır. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Ad | Açıklama |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Mesh'i VertexElementMaterial'e göre alt-mesh'lere böl. Her alt-mesh yalnızca bir malzeme kullanacak. Sahnedeki tüm düğümlerde mesh bölmeyi gerçekleştir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| scen | Sahne | null |
| politika | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Ad | Açıklama |
| --- | --- |
| splitMesh(mesh, policy) | Mesh'i VertexElementMaterial ile alt-mesh'lere böl. Her alt-mesh yalnızca bir malzeme kullanacak. Orijinal mesh değiştirilmeyecek. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Ad | Açıklama |
| --- | --- |
| buildTangentBinormal(scene) | Bu, sahnedeki tüm mesh'lerde teğet ve binormal oluşturur. Normal gereklidir, eğer mesh'te normal yoksa, konumdan normal verisi de oluşturulur. UV da gereklidir, UV tanımlı değilse mesh yok sayılacak. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Ad | Açıklama |
| --- | --- |
| buildTangentBinormal(mesh) | Bu, mesh üzerinde teğet ve binormal oluşturur. Normal gereklidir, eğer mesh'te normal yoksa, konumdan normal verisi de oluşturulur. UV da gereklidir, UV bulunamazsa bir istisna fırlatılacak. |

 **Result:**
Mesh[]


---



