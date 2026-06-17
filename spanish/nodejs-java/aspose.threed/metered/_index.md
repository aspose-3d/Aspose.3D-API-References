---
title: "Metered"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/metered/
---
## Metered class

Proporciona métodos para establecer la clave medida.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de esta clase. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Nombre | Descripción |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Establece la clave pública y privada con medida. Si adquiere una licencia con medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| publicKey | Cadena | clave pública |
| privateKey | Cadena | clave privada |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Nombre | Descripción |
| --- | --- |
| getConsumptionQuantity() | Obtiene el tamaño del archivo de consumo |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Nombre | Descripción |
| --- | --- |
| getConsumptionCredit() | Obtiene el crédito de consumo |

 **Result:**
BigDecimal


---



