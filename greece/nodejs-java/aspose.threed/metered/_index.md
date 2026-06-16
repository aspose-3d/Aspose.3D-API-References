---
title: "Metered"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/metered/
---
## Metered class

Παρέχει μεθόδους για τον ορισμό κλειδιού μετρητή.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor() | Αρχικοποιεί ένα νέο αντικείμενο αυτής της κλάσης. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Όνομα | Περιγραφή |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Ορίζει το δημόσιο και ιδιωτικό κλειδί για τη μετρημένη άδεια. Εάν αγοράσετε μετρημένη άδεια, όταν ξεκινάτε την εφαρμογή, αυτό το API πρέπει να κληθεί· συνήθως αυτό είναι αρκετό. Ωστόσο, εάν αποτυγχάνει συνεχώς η μεταφόρτωση των δεδομένων κατανάλωσης και υπερβεί τις 24 ώρες, η άδεια θα μετατραπεί σε κατάσταση αξιολόγησης· για να αποφύγετε αυτήν την περίπτωση, θα πρέπει να ελέγχετε τακτικά την κατάσταση της άδειας· εάν είναι σε κατάσταση αξιολόγησης, καλέστε ξανά αυτό το API. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | String | δημόσιο κλειδί |
| privateKey | String | ιδιωτικό κλειδί |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Όνομα | Περιγραφή |
| --- | --- |
| getConsumptionQuantity() | Λαμβάνει μέγεθος αρχείου κατανάλωσης |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Όνομα | Περιγραφή |
| --- | --- |
| getConsumptionCredit() | Λαμβάνει πίστωση κατανάλωσης |

 **Result:**
BigDecimal


---



