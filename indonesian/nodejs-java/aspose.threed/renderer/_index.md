---
title: "Renderer"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Konteks tentang renderer.  @hideconstructor


## Metode

### getShaderSet{#getShaderSet}

| Nama | Deskripsi |
| --- | --- |
| getShaderSet() | Mendapatkan atau mengatur set shader yang digunakan untuk merender adegan |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Nama | Deskripsi |
| --- | --- |
| setShaderSet(value) | Mendapatkan atau mengatur set shader yang digunakan untuk merender adegan |

 **Result:**



---


### getVariables{#getVariables}

| Nama | Deskripsi |
| --- | --- |
| getVariables() | Akses ke variabel internal yang digunakan untuk merender |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Nama | Deskripsi |
| --- | --- |
| getPresetShaders() | Mendapatkan atau mengatur set shader preset. Nilai properti ini adalah konstanta integer PresetShaders. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Nama | Deskripsi |
| --- | --- |
| setPresetShaders(value) | Mendapatkan atau mengatur set shader preset. Nilai properti ini adalah konstanta integer PresetShaders. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Nama | Deskripsi |
| --- | --- |
| getRenderFactory() | Mendapatkan pabrik untuk membangun objek terkait render. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Nama | Deskripsi |
| --- | --- |
| getAssetDirectories() | Direktori yang menyimpan aset eksternal |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Nama | Deskripsi |
| --- | --- |
| getPostProcessings() | Rantai pemrosesan pasca aktif |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Nama | Deskripsi |
| --- | --- |
| getEnableShadows() | Mendapatkan atau mengatur apakah bayangan diaktifkan. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Nama | Deskripsi |
| --- | --- |
| setEnableShadows(value) | Mendapatkan atau mengatur apakah bayangan diaktifkan. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Nama | Deskripsi |
| --- | --- |
| getRenderTarget() | Tentukan target render di mana operasi render berikut akan dilakukan. |

 **Result:**



---


### getNode{#getNode}

| Nama | Deskripsi |
| --- | --- |
| getNode() | Mendapatkan atau mengatur instance Node yang digunakan untuk menyediakan matriks transformasi dunia. |

 **Result:**



---


### setNode{#setNode}

| Nama | Deskripsi |
| --- | --- |
| setNode(value) | Mendapatkan atau mengatur instance Node yang digunakan untuk menyediakan matriks transformasi dunia. |

 **Result:**



---


### getFrustum{#getFrustum}

| Nama | Deskripsi |
| --- | --- |
| getFrustum() | Mendapatkan atau mengatur frustum yang digunakan untuk menyediakan matriks tampilan. |

 **Result:**



---


### setFrustum{#setFrustum}

| Nama | Deskripsi |
| --- | --- |
| setFrustum(value) | Mendapatkan atau mengatur frustum yang digunakan untuk menyediakan matriks tampilan. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Nama | Deskripsi |
| --- | --- |
| getRenderStage() | Mendapatkan tahap render saat ini. Nilai properti adalah konstanta integer RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nama | Deskripsi |
| --- | --- |
| getMaterial() | Mendapatkan atau mengatur material yang digunakan untuk menyediakan informasi material yang dipakai oleh shader. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nama | Deskripsi |
| --- | --- |
| setMaterial(value) | Mendapatkan atau mengatur material yang digunakan untuk menyediakan informasi material yang dipakai oleh shader. |

 **Result:**



---


### getShader{#getShader}

| Nama | Deskripsi |
| --- | --- |
| getShader() | Mendapatkan atau mengatur instance shader yang digunakan untuk merender geometri. |

 **Result:**



---


### setShader{#setShader}

| Nama | Deskripsi |
| --- | --- |
| setShader(value) | Mendapatkan atau mengatur instance shader yang digunakan untuk merender geometri. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Nama | Deskripsi |
| --- | --- |
| getFallbackEntityRenderer() | Mendapatkan atau mengatur renderer entitas fallback ketika entitas tidak memiliki renderer khusus yang didefinisikan. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Nama | Deskripsi |
| --- | --- |
| setFallbackEntityRenderer(value) | Mendapatkan atau mengatur renderer entitas fallback ketika entitas tidak memiliki renderer khusus yang didefinisikan. |

 **Result:**



---


### clearCache{#clearCache}

| Nama | Deskripsi |
| --- | --- |
| clearCache() | Bersihkan cache secara manual. Aspose.3D akan menyimpan beberapa objek seperti material/geometri ke dalam tipe internal yang kompatibel dengan pipeline render. Ini harus dipanggil secara manual ketika adegan mengalami perubahan besar. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Nama | Deskripsi |
| --- | --- |
| getPostProcessing(name) | Mendapatkan post-processor bawaan yang didukung oleh renderer. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Nama | Deskripsi |
| --- | --- |
| execute(postProcessing, result) | Jalankan pemrosesan pasca pada target render yang ditentukan |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Nama | Deskripsi |
| --- | --- |
| createRenderer() | Membuat Renderer baru dengan profil default. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| Nama | Deskripsi |
| --- | --- |
| registerEntityRenderer(renderer) | Daftarkan renderer entitas untuk entitas yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| Nama | Deskripsi |
| --- | --- |
| render(renderTarget) | Render target yang ditentukan |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



