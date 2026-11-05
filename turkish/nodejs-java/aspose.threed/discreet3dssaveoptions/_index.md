---
title: "Discreet3dsSaveOptions"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

3DS dosyası için kaydetme seçenekleri.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() | Discreet3dsSaveOptions yapıcısı. |

 **Result:**



---


### getExportLight{#getExportLight}

| Ad | Açıklama |
| --- | --- |
| getExportLight() | Sahnede tüm ışıkları dışa aktarılıp aktarılmayacağını alır veya ayarlar. |

 **Result:**



---


### setExportLight{#setExportLight}

| Ad | Açıklama |
| --- | --- |
| setExportLight(value) | Sahnede tüm ışıkları dışa aktarılıp aktarılmayacağını alır veya ayarlar. |

 **Result:**



---


### getExportCamera{#getExportCamera}

| Ad | Açıklama |
| --- | --- |
| getExportCamera() | Sahnede tüm kameraların dışa aktarılıp aktarılmayacağını alır veya ayarlar. |

 **Result:**



---


### setExportCamera{#setExportCamera}

| Ad | Açıklama |
| --- | --- |
| setExportCamera(value) | Sahnede tüm kameraların dışa aktarılıp aktarılmayacağını alır veya ayarlar. |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| Ad | Açıklama |
| --- | --- |
| getDuplicatedNameSeparator() | Nesnenin adı ile çoğaltılmış sayıcı arasındaki ayırıcı, varsayılan değer "_". Sahne aynı adı kullanan nesneler içerdiğinde, Aspose.3D 3DS dışa aktarıcı nesne için farklı bir ad oluşturur. Örneğin, "Box" adlı iki düğüm vardır, ilk düğümün adı "Box" olur ve ikinci düğüm varsayılan yapılandırma kullanılarak "Box_2" adını alır. |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| Ad | Açıklama |
| --- | --- |
| setDuplicatedNameSeparator(value) | Nesnenin adı ile çoğaltılmış sayıcı arasındaki ayırıcı, varsayılan değer "_". Sahne aynı adı kullanan nesneler içerdiğinde, Aspose.3D 3DS dışa aktarıcı nesne için farklı bir ad oluşturur. Örneğin, "Box" adlı iki düğüm vardır, ilk düğümün adı "Box" olur ve ikinci düğüm varsayılan yapılandırma kullanılarak "Box_2" adını alır. |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| Ad | Açıklama |
| --- | --- |
| getDuplicatedNameCounterBase() | Çoğaltılmış adlar için yeni ad oluştururken kullanılan sayıcı, varsayılan değer 2. |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| Ad | Açıklama |
| --- | --- |
| setDuplicatedNameCounterBase(value) | Çoğaltılmış adlar için yeni ad oluştururken kullanılan sayıcı, varsayılan değer 2. |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| Ad | Açıklama |
| --- | --- |
| getDuplicatedNameCounterFormat() | Çoğaltılmış sayıcının biçimi, varsayılan değer boş dizedir. |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| Ad | Açıklama |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | Çoğaltılmış sayıcının biçimi, varsayılan değer boş dizedir. |

 **Result:**



---


### getMasterScale{#getMasterScale}

| Ad | Açıklama |
| --- | --- |
| getMasterScale() | Dışa aktarmada kullanılan ana ölçeği alır veya ayarlar. |

 **Result:**



---


### setMasterScale{#setMasterScale}

| Ad | Açıklama |
| --- | --- |
| setMasterScale(value) | Dışa aktarmada kullanılan ana ölçeği alır veya ayarlar. |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| Ad | Açıklama |
| --- | --- |
| getGammaCorrectedColor() | Bir 3ds dosyası aynı öznitelik için özgün renk ve gama düzeltmeli renk içerebilir, bunu true olarak ayarlamak mümkünse gama düzeltmeli rengi kullanır, aksi takdirde Aspose.3D özgün rengi kullanmaya çalışır. |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| Ad | Açıklama |
| --- | --- |
| setGammaCorrectedColor(value) | Bir 3ds dosyası aynı öznitelik için özgün renk ve gama düzeltmeli renk içerebilir, bunu true olarak ayarlamak mümkünse gama düzeltmeli rengi kullanır, aksi takdirde Aspose.3D özgün rengi kullanmaya çalışır. |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| Ad | Açıklama |
| --- | --- |
| getFlipCoordinateSystem() | İçe/dışa aktarım sırasında kontrol noktalarının/normalin ters koordinat sistemini alır veya ayarlar. |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| Ad | Açıklama |
| --- | --- |
| setFlipCoordinateSystem(value) | İçe/dışa aktarım sırasında kontrol noktalarının/normalin ters koordinat sistemini alır veya ayarlar. |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| Ad | Açıklama |
| --- | --- |
| getHighPreciseColor() | Bu true ise, oluşturulan 3ds dosyası yüksek hassasiyetli renk kullanır, yani kırmızı/yeşil/mavi kanallarının her biri 32bit float olur. Aksi takdirde oluşturulan dosya 24bit renk kullanır, her kanal 8bit byte olur. Varsayılan değer false'tur, çünkü tüm uygulamalar yüksek hassasiyetli rengi desteklemez. |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| Ad | Açıklama |
| --- | --- |
| setHighPreciseColor(value) | Bu true ise, oluşturulan 3ds dosyası yüksek hassasiyetli renk kullanır, yani kırmızı/yeşil/mavi kanallarının her biri 32bit float olur. Aksi takdirde oluşturulan dosya 24bit renk kullanır, her kanal 8bit byte olur. Varsayılan değer false'tur, çünkü tüm uygulamalar yüksek hassasiyetli rengi desteklemez. |

 **Result:**



---


### getExportTextures{#getExportTextures}

| Ad | Açıklama |
| --- | --- |
| getExportTextures() | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dene. |

 **Result:**



---


### setExportTextures{#setExportTextures}

| Ad | Açıklama |
| --- | --- |
| setExportTextures(value) | Sahnede kullanılan dokuları çıktı dizinine kopyalamayı dene. |

 **Result:**



---


### getFileFormat{#getFileFormat}

| Ad | Açıklama |
| --- | --- |
| getFileFormat() | Mevcut Kaydet/Yükle seçeneğinde belirtilen dosya formatını alır. |

 **Result:**



---


### getEncoding{#getEncoding}

| Ad | Açıklama |
| --- | --- |
| getEncoding() | Metin tabanlı dosyalar için varsayılan kodlamayı alır veya ayarlar. Varsayılan değer null'dur, bu da içe aktarıcı/dışa aktarıcının hangi kodlamayı kullanacağını belirleyeceği anlamına gelir. |

 **Result:**



---


### getFileSystem{#getFileSystem}

| Ad | Açıklama |
| --- | --- |
| getFileSystem() | Kullanıcının yükleme/kaydetme sırasında dış bağımlılıkların nasıl yönetileceğini ele almasına izin verir. |

 **Result:**



---


### setFileSystem{#setFileSystem}

| Ad | Açıklama |
| --- | --- |
| setFileSystem(value) | Kullanıcının yükleme/kaydetme sırasında dış bağımlılıkların nasıl yönetileceğini ele almasına izin verir. |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| Ad | Açıklama |
| --- | --- |
| getLookupPaths() | OBJ gibi bazı dosyalar dış dosyalara bağımlıdır, arama yolları Aspose.3D'nin dış dosyayı yüklemek için aramasına izin verir. |

 **Result:**



---


### getFileName{#getFileName}

| Ad | Açıklama |
| --- | --- |
| getFileName() | Dışa/İçe aktarılan sahnenin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi dış varlıkları serileştirirken faydalıdır. |

 **Result:**



---


### setFileName{#setFileName}

| Ad | Açıklama |
| --- | --- |
| setFileName(value) | Dışa/İçe aktarılan sahnenin dosya adı. Bu isteğe bağlıdır, ancak OBJ'nin materyali gibi dış varlıkları serileştirirken faydalıdır. |

 **Result:**



---



