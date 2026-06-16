---
title: "RenderFactory"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory membuat semua sumber daya yang direpresentasikan dalam pipeline rendering.  @hideconstructor


## Metode

### createRenderTexture{#createRenderTexture}

| Nama | Deskripsi |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Buat target render yang merender ke tekstur |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| parameter | RenderParameters | Parameter render untuk membuat tekstur render |
| target | Angka | Berapa banyak target output warna |
| lebar | Angka | Lebar tekstur render |
| height | Angka | Tinggi tekstur render |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Nama | Deskripsi |
| --- | --- |
| createRenderTexture(parameters, width, height) | Buat target render yang berisi 1 target yang merender ke tekstur |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| parameter | RenderParameters | Parameter render untuk membuat tekstur render |
| lebar | Angka | Lebar tekstur render |
| height | Angka | Tinggi tekstur render |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Nama | Deskripsi |
| --- | --- |
| createDescriptorSet(shader) | Buat set deskriptor untuk program shader yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| shader | ShaderProgram | Program shader |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Nama | Deskripsi |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Buat target render yang berisi 1 tekstur kubus |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| parameter | RenderParameters | Parameter render untuk membuat tekstur render |
| lebar | Angka | Lebar tekstur render |
| height | Angka | Tinggi tekstur render |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Nama | Deskripsi |
| --- | --- |
| createRenderWindow(parameters, handle) | Buat target render yang merender ke jendela native. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| parameter | RenderParameters | Parameter render untuk membuat jendela render |
| handle | WindowHandle | Handle jendela yang akan dirender |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Nama | Deskripsi |
| --- | --- |
| createVertexBuffer(declaration) | Buat sebuah instance com.aspose.threed.IVertexBuffer untuk menyimpan informasi vertex poligon. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Nama | Deskripsi |
| --- | --- |
| createIndexBuffer() | Buat sebuah instance com.aspose.threed.IIndexBuffer untuk menyimpan informasi wajah poligon. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Nama | Deskripsi |
| --- | --- |
| createTextureUnit(textureType) | Buat unit tekstur yang dapat diakses oleh shader. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Nama | Deskripsi |
| --- | --- |
| createTextureUnit() | Buat unit tekstur 2D yang dapat diakses oleh shader. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Nama | Deskripsi |
| --- | --- |
| createShaderProgram(shaderSource) | Buat objek ShaderProgram |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| shaderSource | ShaderSource | Kode sumber shader |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Nama | Deskripsi |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Buat pipeline grafis yang telah dikonfigurasi sebelumnya dengan shader/render state/vertex declaration dan draw operations. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| shader | ShaderProgram | Shader yang digunakan dalam rendering |
| renderState | RenderState | Render state yang digunakan dalam rendering |
| vertexDeclaration | VertexDeclaration | Deklarasi vertex dari data vertex input |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Nama | Deskripsi |
| --- | --- |
| createUniformBuffer(size) | Buat buffer uniform baru di sisi GPU dengan ukuran yang telah dialokasikan sebelumnya. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| ukuran | Angka | Ukuran buffer uniform |

 **Result:**
IBuffer


---



