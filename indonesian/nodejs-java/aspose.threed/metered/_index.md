---
title: "Metered"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/metered/
---
## Metered class

Menyediakan metode untuk mengatur kunci bermeter.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor() | Menginisialisasi instance baru dari kelas ini. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| Nama | Deskripsi |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | Menetapkan kunci publik dan pribadi berbayar. Jika Anda membeli lisensi berbayar, saat memulai aplikasi, API ini harus dipanggil, biasanya ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi; untuk menghindari hal tersebut, Anda harus secara teratur memeriksa status lisensi, jika berada dalam status evaluasi, panggil API ini lagi. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | String | kunci publik |
| privateKey | String | kunci privat |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| Nama | Deskripsi |
| --- | --- |
| getConsumptionQuantity() | Mendapatkan ukuran file konsumsi |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| Nama | Deskripsi |
| --- | --- |
| getConsumptionCredit() | Mendapatkan kredit konsumsi |

 **Result:**
BigDecimal


---



