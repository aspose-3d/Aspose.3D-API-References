---
title: "Metered"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | Bu sınıfın yeni bir örneğini başlatır. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Ad | Açıklama |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Ölçülen genel ve özel anahtarı ayarlar. Ölçülen lisansı satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. Ancak, tüketim verilerini yüklemekte sürekli başarısız olur ve 24 saat aşarsa, lisans değerlendirme durumuna ayarlanır; böyle bir durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa, bu API'yi tekrar çağırın. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| publicKey | String | genel anahtar |
| privateKey | String | özel anahtar |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Ad | Açıklama |
| --- | --- |
| getConsumptionQuantity() | Tüketim dosya boyutunu alır |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Ad | Açıklama |
| --- | --- |
| getConsumptionCredit() | Tüketim kredisini alır |

 **Result:**
BigDecimal


---



