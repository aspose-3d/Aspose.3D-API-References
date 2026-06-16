---
title: "EntityRenderer"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Κληρονομήστε αυτήν την κλάση για να υλοποιήσετε την απόδοση για διαφορετικούς τύπους οντοτήτων.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(key, features) | Κατασκευαστής του EntityRenderer |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | String | Το κλειδί του entity renderer |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor_overload(key) | Κατασκευαστής του EntityRenderer |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | String | Το κλειδί του entity renderer |

 **Result:**



---


### initialize{#initialize}

| Όνομα | Περιγραφή |
| --- | --- |
| initialize(renderer) | Αρχικοποιήστε το entity renderer |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| rendere | Απόδοση | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Όνομα | Περιγραφή |
| --- | --- |
| resetSceneCache() | Η σκηνή έχει αλλάξει ή αφαιρεθεί, χρειάζεται να αποδεσμευτούν οι πόροι απόδοσης επιπέδου σκηνής σε αυτό |

 **Result:**



---


### frameBegin{#frameBegin}

| Όνομα | Περιγραφή |
| --- | --- |
| frameBegin(renderer, renderQueue) | Έναρξη απόδοσης ενός πλαισίου |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| απόδοση | Απόδοση | Τρέχουσα απόδοση |
| renderQueue | IRenderQueue | Ουρά απόδοσης |

 **Result:**



---


### frameEnd{#frameEnd}

| Όνομα | Περιγραφή |
| --- | --- |
| frameEnd(renderer, renderQueue) | Τελειώνει την απόδοση ενός πλαισίου |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| απόδοση | Απόδοση | Τρέχουσα απόδοση |
| renderQueue | IRenderQueue | Ουρά απόδοσης |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Όνομα | Περιγραφή |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Προετοιμάζει εντολές απόδοσης για το καθορισμένο ζεύγος κόμβου/οντότητας. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| απόδοση | Απόδοση | Το τρέχον παράδειγμα του renderer |
| queue | IRenderQueue | Η ουρά απόδοσης που χρησιμοποιείται για τη διαχείριση των εργασιών απόδοσης |
| κόμβος | Κόμβος | Τρέχων κόμβος |
| οντότητα | Οντότητα | Η οντότητα που πρέπει να αποδοθεί |

 **Result:**



---


### renderEntity{#renderEntity}

| Όνομα | Περιγραφή |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Κάθε εργασία απόδοσης που προωθείται στο com.aspose.threed.IRenderQueue θα έχει μια αντίστοιχη κλήση RenderEntity για την εκτέλεση της συγκεκριμένης εργασίας απόδοσης. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| απόδοση | Απόδοση | Ο renderer |
| commandList | ICommandList | Η commandList που χρησιμοποιείται για την καταγραφή των εντολών απόδοσης |
| κόμβος | Κόμβος | Ο ίδιος κόμβος που περάστηκε στο PrepareRenderQueue της οντότητας που θα αποδοθεί |
| renderableResource | Αντικείμενο | Το προσαρμοσμένο αντικείμενο που περάστηκε στο IRenderQueue κατά τη διάρκεια του PrepareRenderQueue |
| subEntity | Αριθμός | Ο δείκτης της sub entity που περάστηκε στο IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Όνομα | Περιγραφή |
| --- | --- |
| dispose() | Ο renderer της οντότητας διαγράφεται, απελευθερώστε τους κοινόχρηστους πόρους. |

 **Result:**



---



