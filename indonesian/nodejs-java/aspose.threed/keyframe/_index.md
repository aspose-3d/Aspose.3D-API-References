---
title: "KeyFrame"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Key frame terutama didefinisikan oleh waktu dan nilai, untuk beberapa tipe interpolasi, tangent/tension/bias/continuity juga digunakan dalam menghitung nilai sampel akhir. Nilai yang disampel pada posisi waktu non-key-frame diinterpolasi oleh key-frame antara key-frame sebelumnya dan berikutnya. Nilai sebelum/setelah key-frame pertama/terakhir dihitung oleh kelas Extrapolation.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(curve, time) | Buat key frame baru pada kurva yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| curve | KeyframeSequence | Kurva yang akan dibuat pada frame kunci |
| waktu | Angka | Posisi waktu dari frame kunci |

 **Result:**



---


### getTime{#getTime}

| Nama | Deskripsi |
| --- | --- |
| getTime() | Mendapatkan atau mengatur posisi waktu dari frame kunci list.data[index], diukur dalam detik. Waktu. |

 **Result:**



---


### setTime{#setTime}

| Nama | Deskripsi |
| --- | --- |
| setTime(value) | Mendapatkan atau mengatur posisi waktu dari frame kunci list.data[index], diukur dalam detik. Waktu. |

 **Result:**



---


### getValue{#getValue}

| Nama | Deskripsi |
| --- | --- |
| getValue() | Mendapatkan atau mengatur nilai frame kunci. Nilainya. |

 **Result:**



---


### setValue{#setValue}

| Nama | Deskripsi |
| --- | --- |
| setValue(value) | Mendapatkan atau mengatur nilai frame kunci. Nilainya. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Nama | Deskripsi |
| --- | --- |
| getInterpolation() | Mendapatkan atau mengatur tipe interpolasi kunci, list.data[index] menentukan algoritma bagaimana nilai yang diambil sampelnya dihitung. Nilai properti ini adalah konstanta integer Interpolation. Interpolasi. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Nama | Deskripsi |
| --- | --- |
| setInterpolation(value) | Mendapatkan atau mengatur tipe interpolasi kunci, list.data[index] menentukan algoritma bagaimana nilai yang diambil sampelnya dihitung. Nilai properti ini adalah konstanta integer Interpolation. Interpolasi. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Nama | Deskripsi |
| --- | --- |
| getTangentWeightMode() | Mendapatkan atau mengatur mode bobot tangent kunci. Tangent keluar atau tangent masuk berikutnya dapat disesuaikan dengan memilih WeightedMode yang tepat. Nilai properti ini adalah konstanta integer WeightedMode. Mode bobot tangent. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Nama | Deskripsi |
| --- | --- |
| setTangentWeightMode(value) | Mendapatkan atau mengatur mode bobot tangent kunci. Tangent keluar atau tangent masuk berikutnya dapat disesuaikan dengan memilih WeightedMode yang tepat. Nilai properti ini adalah konstanta integer WeightedMode. Mode bobot tangent. |

 **Result:**



---


### getStepMode{#getStepMode}

| Nama | Deskripsi |
| --- | --- |
| getStepMode() | Mendapatkan atau mengatur mode langkah kunci. Jika tipe interpolasi adalah Interpolation.CONSTANT, list.data[index] menentukan nilai frame kunci mana yang akan digunakan selama interpolasi. StepMode.PREVIOUS_VALUE berarti nilai frame kunci kiri yang akan digunakan. StepMode.NEXT_VALUE berarti nilai frame kunci kanan berikutnya yang akan digunakan. Nilai properti ini adalah konstanta integer StepMode. Mode langkah. |

 **Result:**



---


### setStepMode{#setStepMode}

| Nama | Deskripsi |
| --- | --- |
| setStepMode(value) | Mendapatkan atau mengatur mode langkah kunci. Jika tipe interpolasi adalah Interpolation.CONSTANT, list.data[index] menentukan nilai frame kunci mana yang akan digunakan selama interpolasi. StepMode.PREVIOUS_VALUE berarti nilai frame kunci kiri yang akan digunakan. StepMode.NEXT_VALUE berarti nilai frame kunci kanan berikutnya yang akan digunakan. Nilai properti ini adalah konstanta integer StepMode. Mode langkah. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Nama | Deskripsi |
| --- | --- |
| getNextInTangent() | Mendapatkan atau mengatur tangent masuk (kiri) berikutnya pada frame kunci ini. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Nama | Deskripsi |
| --- | --- |
| setNextInTangent(value) | Mendapatkan atau mengatur tangent masuk (kiri) berikutnya pada frame kunci ini. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Nama | Deskripsi |
| --- | --- |
| getOutTangent() | Mendapatkan atau mengatur tangent keluar (kanan) pada frame kunci ini. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Nama | Deskripsi |
| --- | --- |
| setOutTangent(value) | Mendapatkan atau mengatur tangent keluar (kanan) pada frame kunci ini. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Nama | Deskripsi |
| --- | --- |
| getOutWeight() | Mendapatkan atau mengatur bobot keluar (kanan) pada frame kunci ini. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Nama | Deskripsi |
| --- | --- |
| setOutWeight(value) | Mendapatkan atau mengatur bobot keluar (kanan) pada frame kunci ini. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Nama | Deskripsi |
| --- | --- |
| getNextInWeight() | Mendapatkan atau mengatur bobot masuk (kiri) berikutnya pada frame kunci ini. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Nama | Deskripsi |
| --- | --- |
| setNextInWeight(value) | Mendapatkan atau mengatur bobot masuk (kiri) berikutnya pada frame kunci ini. |

 **Result:**



---


### getTension{#getTension}

| Nama | Deskripsi |
| --- | --- |
| getTension() | Mendapatkan atau mengatur ketegangan yang digunakan dalam spline TCB |

 **Result:**



---


### setTension{#setTension}

| Nama | Deskripsi |
| --- | --- |
| setTension(value) | Mendapatkan atau mengatur ketegangan yang digunakan dalam spline TCB |

 **Result:**



---


### getContinuity{#getContinuity}

| Nama | Deskripsi |
| --- | --- |
| getContinuity() | Mendapatkan atau mengatur kontinuitas yang digunakan dalam spline TCB |

 **Result:**



---


### setContinuity{#setContinuity}

| Nama | Deskripsi |
| --- | --- |
| setContinuity(value) | Mendapatkan atau mengatur kontinuitas yang digunakan dalam spline TCB |

 **Result:**



---


### getBias{#getBias}

| Nama | Deskripsi |
| --- | --- |
| getBias() | Mendapatkan atau mengatur bias yang digunakan dalam spline TCB |

 **Result:**



---


### setBias{#setBias}

| Nama | Deskripsi |
| --- | --- |
| setBias(value) | Mendapatkan atau mengatur bias yang digunakan dalam spline TCB |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Nama | Deskripsi |
| --- | --- |
| getIndependentTangent() | Mendapatkan atau mengatur agar tangens keluar dan masuk berikutnya bersifat independen. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Nama | Deskripsi |
| --- | --- |
| setIndependentTangent(value) | Mendapatkan atau mengatur agar tangens keluar dan masuk berikutnya bersifat independen. |

 **Result:**



---


### getFlat{#getFlat}

| Nama | Deskripsi |
| --- | --- |
| getFlat() | Mendapatkan atau mengatur apakah frame kunci datar. Frame kunci harus datar jika frame kunci berikutnya atau sebelumnya memiliki nilai yang sama. Frame kunci datar memiliki tangens datar dan interpolasi tetap. |

 **Result:**



---


### setFlat{#setFlat}

| Nama | Deskripsi |
| --- | --- |
| setFlat(value) | Mendapatkan atau mengatur apakah frame kunci datar. Frame kunci harus datar jika frame kunci berikutnya atau sebelumnya memiliki nilai yang sama. Frame kunci datar memiliki tangens datar dan interpolasi tetap. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Nama | Deskripsi |
| --- | --- |
| getTimeIndependentTangent() | Mendapatkan atau mengatur tangens menjadi tidak bergantung pada waktu |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Nama | Deskripsi |
| --- | --- |
| setTimeIndependentTangent(value) | Mendapatkan atau mengatur tangens menjadi tidak bergantung pada waktu |

 **Result:**



---


### toString{#toString}

| Nama | Deskripsi |
| --- | --- |
| toString() | Mendapatkan representasi string dari frame kunci |

 **Result:**
String


---



