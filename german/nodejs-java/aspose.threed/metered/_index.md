---
title: Nutzungsbasiert
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/metered/
---
## Metered class

Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit.


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
| setMeteredKey(publicKey, privateKey) | Setzt den nutzungsbasierten öffentlichen und privaten Schlüssel. Wenn Sie eine nutzungsbasierte Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Sollte jedoch ständig das Hochladen von Verbrauchsdaten fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |

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
| getConsumptionQuantity() | Ermittelt die Größe der Verbrauchsdatei |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Name | Beschreibung |
| --- | --- |
| getConsumptionCredit() | Ermittelt das Verbrauchsguthaben |

 **Result:**
BigDecimal


---



