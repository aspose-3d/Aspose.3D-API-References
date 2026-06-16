---
title: "BindPoint"
second_title: "Aspose.3D για Node.js μέσω Java API Αναφορά"
description: 
type: docs

url: /el/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Ένα BindPoint συνήθως δημιουργείται σε μια ιδιότητα αντικειμένου, ορισμένοι τύποι ιδιοτήτων περιέχουν πολλαπλά πεδία συνιστωσών (όπως ένα πεδίο Vector3), το BindPoint θα δημιουργήσει κανάλι για κάθε πεδίο συνιστώσας και συνδέει το πεδίο με μία ή περισσότερες εμφανίσεις ακολουθίας κλειδιών-πλαισίων μέσω των καναλιών.


## Μέθοδοι

### constructor{#constructor}

| Όνομα | Περιγραφή |
| --- | --- |
| constructor(scene, prop) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BindPoint. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | Scene | Η σκηνή που περιέχει την κίνηση. |
| prop | Property | Ιδιότητα. |

 **Result:**



---


### getProperty{#getProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperty() | Λαμβάνει την ιδιότητα που σχετίζεται με το CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| setProperty(value) | Λαμβάνει την ιδιότητα που σχετίζεται με το CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getChannelsCount() | Λαμβάνει τον συνολικό αριθμό των καναλιών ιδιοτήτων που ορίζονται σε αυτήν τη χαρτογράφηση καμπύλης κίνησης. |

 **Result:**
Αριθμός


---


### getName{#getName}

| Όνομα | Περιγραφή |
| --- | --- |
| getName() | Λαμβάνει ή ορίζει το όνομα. Το όνομα. |

 **Result:**
Αριθμός


---


### setName{#setName}

| Όνομα | Περιγραφή |
| --- | --- |
| setName(value) | Λαμβάνει ή ορίζει το όνομα. Το όνομα. |

 **Result:**
Αριθμός


---


### getProperties{#getProperties}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperties() | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |

 **Result:**
Αριθμός


---


### get{#get}

| Όνομα | Περιγραφή |
| --- | --- |
| get(channelName) |  |

 **Result:**
Αριθμός


---


### getKeyframeSequence{#getKeyframeSequence}

| Όνομα | Περιγραφή |
| --- | --- |
| getKeyframeSequence(channelName) | Αποκτά την πρώτη ακολουθία keyframe sequence στο καθορισμένο κανάλι |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | String | Το όνομα του καναλιού για εύρεση |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Όνομα | Περιγραφή |
| --- | --- |
| getKeyframeSequences(channelName) | Αποκτά όλες τις ακολουθίες keyframe στο καθορισμένο κανάλι |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | String | Το όνομα του καναλιού για εύρεση |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Όνομα | Περιγραφή |
| --- | --- |
| createKeyframeSequence(name) | Δημιουργεί μια νέα curve και τη συνδέει με το πρώτο κανάλι της curve mapping |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Το όνομα της νέας sequence. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Όνομα | Περιγραφή |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Συνδέει την keyframe sequence με το καθορισμένο κανάλι |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | String | Σε ποιο κανάλι θα συνδεθεί η keyframe sequence |
| sequence | KeyframeSequence | Η keyframe sequence για σύνδεση |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Όνομα | Περιγραφή |
| --- | --- |
| getChannel(channelName) | Αποκτά το channel με το δοσμένο όνομα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelName | String | Το όνομα του καναλιού για εύρεση |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Όνομα | Περιγραφή |
| --- | --- |
| addChannel(name, value) | Προσθέτει την καθορισμένη ιδιότητα channel. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα. |
| τιμή | Αντικείμενο | Τιμή. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Όνομα | Περιγραφή |
| --- | --- |
| addChannel(name, type, value) | Προσθέτει την καθορισμένη ιδιότητα channel. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα. |
| type | Κλάση | Τύπος. |
| τιμή | Αντικείμενο | Τιμή. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Όνομα | Περιγραφή |
| --- | --- |
| resetChannels() | Αδειάζει τα property channels αυτής της animation curve mapping. |

 **Result:**
boolean


---


### toString{#toString}

| Όνομα | Περιγραφή |
| --- | --- |
| toString() | Μορφοποιεί το αντικείμενο σε συμβολοσειρά |

 **Result:**
String


---


### removeProperty{#removeProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| removeProperty(property) | Αφαιρεί μια δυναμική ιδιότητα. |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | Property | Ποια ιδιότητα να αφαιρεθεί |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| removeProperty(property) | Αφαιρέστε την καθορισμένη ιδιότητα που αναγνωρίζεται με όνομα |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| getProperty(property) | Αποκτήστε την τιμή της καθορισμένης ιδιότητας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | String | Όνομα ιδιότητας |

 **Result:**
Αντικείμενο


---


### setProperty{#setProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| setProperty(property, value) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | String | Όνομα ιδιότητας |
| τιμή | Αντικείμενο | Η τιμή της ιδιότητας |

 **Result:**
Αντικείμενο


---


### findProperty{#findProperty}

| Όνομα | Περιγραφή |
| --- | --- |
| findProperty(propertyName) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Created by CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Identified by its name) |

 **Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | String | Όνομα ιδιότητας. |

 **Result:**
Property


---



