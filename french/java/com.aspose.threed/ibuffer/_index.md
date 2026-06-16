---
title: "IBuffer"
second_title: "Référence d'API Aspose.3D pour Java"
description: "L'interface de base de tous les tampons gérés utilisés dans le rendu"
type: docs
weight: 239
url: /fr/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

L'interface de base de tous les tampons gérés utilisés dans le rendu
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSize()](#getSize--) | Taille de ce tampon en octets |
| [loadData(byte[] data)](#loadData-byte---) | Charge les données dans le tampon actuel |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Taille de ce tampon en octets

**Returns:**
int - Taille de ce tampon en octets
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Charge les données dans le tampon actuel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] |  |

