---
title: MemoryFileSystem
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

Le MemoryFileSystem mappe les opérations de lecture/écriture vers la mémoire.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| Nom | Description |
| --- | --- |
| getFileNames() | Noms de fichiers qui se trouvent dans ce système de fichiers en mémoire. |

 **Result:**



---


### getFileContent{#getFileContent}

| Nom | Description |
| --- | --- |
| getFileContent(fileName) | Renvoie le contenu brut du fichier spécifié. Lève System.IO.FileNotFoundException si le fichier spécifié n'existe pas. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| Nom | Description |
| --- | --- |
| readFile(fileName, options) | Créez un flux pour lire les dépendances. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| Nom | Description |
| --- | --- |
| writeFile(fileName, options) | Créez un flux pour écrire les dépendances. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| fileNam | String | null |
| option | IOConfig | null |

 **Result:**
Stream


---



