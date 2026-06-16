---
title: "Metered"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/metered/
---
## Metered class

Fournit des méthodes pour définir la clé mesurée.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de cette classe. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Nom | Description |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Définit les clés publiques et privées mesurées. Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, normalement cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, et si elle est en statut d'évaluation, appeler à nouveau cette API. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| publicKey | String | clé publique |
| privateKey | String | clé privée |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Nom | Description |
| --- | --- |
| getConsumptionQuantity() | Obtient la taille du fichier de consommation |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Nom | Description |
| --- | --- |
| getConsumptionCredit() | Obtient le crédit de consommation |

 **Result:**
BigDecimal


---



