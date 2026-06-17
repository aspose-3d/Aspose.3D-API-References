---
title: "Metered"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/metered/
---
## Metered class

Предоставляет методы установки измеряемого ключа.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр этого класса. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Имя | Описание |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Устанавливает публичный и приватный ключ для лицензии с учётом потребления. Если вы приобрели лицензию с учётом потребления, при запуске приложения необходимо вызвать этот API; обычно этого достаточно. Однако если постоянно не удаётся загрузить данные о потреблении и прошло более 24 часов, лицензия будет переключена в режим оценки. Чтобы избежать этого, регулярно проверяйте статус лицензии; если она находится в режиме оценки, вызовите этот API снова. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| publicKey | String | публичный ключ |
| privateKey | String | закрытый ключ |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Имя | Описание |
| --- | --- |
| getConsumptionQuantity() | Получает размер файла потребления |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Имя | Описание |
| --- | --- |
| getConsumptionCredit() | Получает кредит потребления |

 **Result:**
BigDecimal


---



