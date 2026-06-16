---
title: "IBuffer"
second_title: "Aspose.3D for Java API Referansı"
description: "Renderleme sırasında kullanılan tüm yönetilen tamponların temel arayüzü"
type: docs
weight: 239
url: /tr/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

Renderleme sırasında kullanılan tüm yönetilen tamponların temel arayüzü
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Bu tamponun bayt cinsinden boyutu |
| [loadData(byte[] data)](#loadData-byte---) | Veriyi mevcut tampona yükle |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Bu tamponun bayt cinsinden boyutu

**Returns:**
int - Bu tamponun bayt cinsinden boyutu
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Veriyi mevcut tampona yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] |  |

