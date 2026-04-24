---
title: Watermark
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/watermark/
---
## Watermark class

Utilitaire pour encoder/décoder un filigrane invisible vers/à partir d'un maillage.  @hideconstructor


## Méthodes

### encodeWatermark{#encodeWatermark}

| Nom | Description |
| --- | --- |
| encodeWatermark(input, text) | Encoder un texte dans le filigrane aveugle du maillage. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| input | Mesh | Maillage pour encoder un filigrane aveugle |
| text | String | Texte à encoder dans le maillage |

 **Result:**
Mesh


---


### encodeWatermark{#encodeWatermark}

| Nom | Description |
| --- | --- |
| encodeWatermark(input, text, password) | Encoder un texte dans le filigrane aveugle du maillage. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| input | Mesh | Maillage pour encoder un filigrane aveugle |
| text | String | Texte à encoder dans le maillage |
| mot de passe | String | Mot de passe pour protéger le filigrane, il est optionnel |

 **Result:**
Mesh


---


### decodeWatermark{#decodeWatermark}

| Nom | Description |
| --- | --- |
| decodeWatermark(input) | Décoder le filigrane d'un maillage |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| input | Mesh | Le maillage pour extraire le filigrane |

 **Result:**
String


---


### decodeWatermark{#decodeWatermark}

| Nom | Description |
| --- | --- |
| decodeWatermark(input, password) | Décoder le filigrane d'un maillage |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| input | Mesh | Le maillage pour extraire le filigrane |
| mot de passe | String | Le mot de passe pour déchiffrer le filigrane |

 **Result:**
String


---



