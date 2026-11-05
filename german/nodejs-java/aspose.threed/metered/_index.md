---
title: "Abgerechnet"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/metered/
---
## Metered class

Stellt Methoden zum Festlegen eines gemessenen Schlüssels bereit.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() | Initialisiert eine neue Instanz dieser Klasse. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Name | Beschreibung |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Legt den abgerechneten öffentlichen und privaten Schlüssel fest. Wenn Sie eine abgerechnete Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um diesen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus prüfen und bei Evaluierungsstatus diese API erneut aufrufen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | String | öffentlicher Schlüssel |
| privateKey | String | privater Schlüssel |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Name | Beschreibung |
| --- | --- |
| getConsumptionQuantity() | Gibt die Dateigröße des Verbrauchs zurück |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Name | Beschreibung |
| --- | --- |
| getConsumptionCredit() | Ruft Verbrauchsguthaben ab |

 **Result:**
BigDecimal


---



