---
title: IBuffer
second_title: Aspose.3D for Java API Reference
description: Η βασική διεπαφή όλων των διαχειριζόμενων buffer που χρησιμοποιούνται στην απόδοση.
type: docs
weight: 239
url: /el/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

Η βασική διεπαφή όλων των διαχειριζόμενων buffer που χρησιμοποιούνται στην απόδοση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSize()](#getSize--) | Μέγεθος αυτού του buffer σε byte |
| [loadData(byte[] data)](#loadData-byte---) | Φορτώστε τα δεδομένα στο τρέχον buffer |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Μέγεθος αυτού του buffer σε byte

**Returns:**
int - Μέγεθος αυτού του buffer σε byte
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Φορτώστε τα δεδομένα στο τρέχον buffer

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] |  |

