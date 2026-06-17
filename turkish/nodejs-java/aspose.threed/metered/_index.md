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
| setMeteredKey(publicKey, privateKey) | Ölçülen public ve private anahtarı ayarlar. Ölçülen lisans satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. Ancak tüketim verilerini yükleme sürekli başarısız olur ve 24 saati aşarsa, lisans değerlendirme durumuna geçer; bu durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa, bu API'yi tekrar çağırın. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| publicKey | String | public anahtar |
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



