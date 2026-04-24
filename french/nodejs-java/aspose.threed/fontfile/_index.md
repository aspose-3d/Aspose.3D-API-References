---
title: FontFile
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/fontfile/
---
## FontFile class

Le fichier de police contient les définitions des glyphes, il est utilisé pour créer le profil de texte.  @hideconstructor


## Méthodes

### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**



---


### fromFile{#fromFile}

| Nom | Description |
| --- | --- |
| fromFile(fileName) | Charger FontFile à partir du nom de fichier |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileName | String | Chemin vers le fichier de police |

 **Result:**
FontFile


---


### parse{#parse}

| Nom | Description |
| --- | --- |
| parse(bytes) | Analyser FontFile à partir des octets |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| bytes | byte[] | Contenu brut du fichier de police OTF |

 **Result:**
FontFile


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime une propriété dynamique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | Property | Quelle propriété supprimer |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime la propriété spécifiée identifiée par son nom |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nom | Description |
| --- | --- |
| getProperty(property) | Obtenir la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nom | Description |
| --- | --- |
| setProperty(property, value) | Définit la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |
| valeur | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---



