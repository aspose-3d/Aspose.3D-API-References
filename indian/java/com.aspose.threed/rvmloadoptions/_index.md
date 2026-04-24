---
title: RvmLoadOptions
second_title: Aspose.3D for Java API Reference
description: AVEVA Plant Design Management Systems RVM फ़ाइल के लिए लोड विकल्प।
type: docs
weight: 157
url: /hi/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

AVEVA Plant Design Management System की RVM फ़ाइल के लिए लोड विकल्प। **Example:** निम्नलिखित कोड दिखाता है कि कैसे RvmLoadOptions का उपयोग करके RVM फ़ाइल से आयातित प्रिमिटिव ज्यामितियों के टेस्सेलेशन पैरामीटर को अनुकूलित किया जाए।

```
RvmLoadOptions opt = new RvmLoadOptions();
             opt.setRectangularTorusSegments(30);
             opt.setCylinderRadialSegments(20);
             opt.setDishLatitudeSegments(20);
             opt.setDishLongitudeSegments(20);
             opt.setCenterScene(true);
             var scene = Scene.fromFile("input.rvm", opt);
             scene.save("output.obj");
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | एक [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) इंस्टेंस बनाएं |
| [RvmLoadOptions()](#RvmLoadOptions--) | एक [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) इंस्टेंस बनाएं |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | बाहरी एट्रिब्यूट फ़ाइलों में परिभाषित एट्रिब्यूट्स का प्रीफ़िक्स प्राप्त करता है, प्रीफ़िक्स का उपयोग नाम टकराव से बचने के लिए किया जाता है, डिफ़ॉल्ट मान "rvm:" है। |
| [getCenterScene()](#getCenterScene--) | लोड होने के बाद दृश्य को केंद्रित करें। |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | सिलेंडर के रेडियल सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 16 है। |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | डिश के लैटिट्यूड सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 8 है। |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | डिश के लॉन्गिट्यूड सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 12 है। |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। |
| [getFileFormat()](#getFileFormat--) | वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [getFileName()](#getFileName--) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [getFileSystem()](#getFileSystem--) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। |
| [getGenerateMaterials()](#getGenerateMaterials--) | यदि RVM फ़ाइल में कलर टेबल निर्यात नहीं की गई है तो दृश्य में प्रत्येक वस्तु के लिए यादृच्छिक रंगों के साथ सामग्री उत्पन्न करें। |
| [getLookupAttributes()](#getLookupAttributes--) | जाँचता है कि बाहरी एट्रिब्यूट सूची फ़ाइल (.att/.attrib/.txt) से एट्रिब्यूट लोड किए जाएँ या नहीं, डिफ़ॉल्ट मान true है। |
| [getLookupPaths()](#getLookupPaths--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | आयताकार टॉरस के रेडियल सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 20 है। |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | टॉरस के ट्यूब्युलर सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 20 है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | बाहरी एट्रिब्यूट फ़ाइलों में परिभाषित एट्रिब्यूट्स का प्रीफ़िक्स सेट करता है, प्रीफ़िक्स का उपयोग नाम टकराव से बचने के लिए किया जाता है, डिफ़ॉल्ट मान "rvm:" है। |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | लोड होने के बाद दृश्य को केंद्रित करें। |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | सिलेंडर के रेडियल सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 16 है। |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | डिश के लैटिट्यूड सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 8 है। |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | डिश के लॉन्गिट्यूड सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 12 है। |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। |
| [setFileName(String value)](#setFileName-java.lang.String-) | एक्सपोर्ट/इम्पोर्ट सीन का फ़ाइल नाम। |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है। |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | यदि RVM फ़ाइल में कलर टेबल निर्यात नहीं की गई है तो दृश्य में प्रत्येक वस्तु के लिए यादृच्छिक रंगों के साथ सामग्री उत्पन्न करें। |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | सेट करता है कि बाहरी एट्रिब्यूट सूची फ़ाइल (.att/.attrib/.txt) से एट्रिब्यूट लोड किए जाएँ या नहीं, डिफ़ॉल्ट मान true है। |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे। |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | आयताकार टॉरस के रेडियल सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 20 है। |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | टॉरस के ट्यूब्युलर सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 20 है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


एक [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) इंस्टेंस बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


एक [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) इंस्टेंस बनाएं

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


बाहरी एट्रिब्यूट फ़ाइलों में परिभाषित एट्रिब्यूट्स का प्रीफ़िक्स प्राप्त करता है, प्रीफ़िक्स का उपयोग नाम टकराव से बचने के लिए किया जाता है, डिफ़ॉल्ट मान "rvm:" है।

**Returns:**
java.lang.String - बाहरी एट्रिब्यूट फ़ाइलों में परिभाषित एट्रिब्यूट्स का उपसर्ग, उपसर्ग का उपयोग नाम टकराव से बचने के लिए किया जाता है, डिफ़ॉल्ट मान "rvm:" है
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


लोड होने के बाद दृश्य को केंद्रित करें।

**Returns:**
boolean - लोड होने के बाद दृश्य को केंद्रित करें।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCylinderRadialSegments() {#getCylinderRadialSegments--}
```
public int getCylinderRadialSegments()
```


सिलेंडर के रेडियल सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 16 है।

**Returns:**
int - सिलिंडर के रेडियल सेगमेंट्स की संख्या, डिफ़ॉल्ट मान 16 है
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


डिश के लैटिट्यूड सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 8 है।

**Returns:**
int - डिश के लैटिट्यूड सेगमेंट्स की संख्या, डिफ़ॉल्ट मान 8 है
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


डिश के लॉन्गिट्यूड सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 12 है।

**Returns:**
int - डिश के लोंगिट्यूड सेगमेंट्स की संख्या, डिफ़ॉल्ट मान 12 है
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।

**Returns:**
java.nio.charset.Charset - टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर उपयोग करने के लिए एन्कोडिंग तय करेगा।
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Returns:**
java.lang.String - एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है।

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की इम्प्लीमेंटेशन भी उपयोग कर सकते हैं।

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


FileSystem के लिए फ़ैक्टरी क्लास प्राप्त करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर वातावरण के लिए उपयुक्त नहीं है।

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


यदि RVM फ़ाइल में रंग तालिका निर्यात नहीं की गई है तो दृश्य में प्रत्येक वस्तु के लिए यादृच्छिक रंगों के साथ सामग्री उत्पन्न करें। डिफ़ॉल्ट मान true है

**Returns:**
boolean - यदि RVM फ़ाइल में रंग तालिका निर्यात नहीं की गई है तो दृश्य में प्रत्येक वस्तु के लिए यादृच्छिक रंगों के साथ सामग्री उत्पन्न करें। डिफ़ॉल्ट मान true है
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


जाँचता है कि बाहरी एट्रिब्यूट सूची फ़ाइल (.att/.attrib/.txt) से एट्रिब्यूट लोड किए जाएँ या नहीं, डिफ़ॉल्ट मान true है।

**Returns:**
boolean - बाहरी एट्रिब्यूट सूची फ़ाइल(.att/.attrib/.txt) से एट्रिब्यूट लोड करना है या नहीं, डिफ़ॉल्ट मान true है।
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Returns:**
java.util.ArrayList<java.lang.String> - OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को बाहरी फ़ाइल लोड करने के लिए खोजने की अनुमति देंगे। **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


आयताकार टॉरस के रेडियल सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 20 है।

**Returns:**
int - आयताकार टॉरस के रेडियल सेगमेंट्स की संख्या, डिफ़ॉल्ट मान 20 है
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


टॉरस के ट्यूब्युलर सेगमेंट्स की संख्या प्राप्त करता है, डिफ़ॉल्ट मान 20 है।

**Returns:**
int - टॉरस के ट्यूब्युलर सेगमेंट्स की संख्या, डिफ़ॉल्ट मान 20 है
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


बाहरी एट्रिब्यूट फ़ाइलों में परिभाषित एट्रिब्यूट्स का प्रीफ़िक्स सेट करता है, प्रीफ़िक्स का उपयोग नाम टकराव से बचने के लिए किया जाता है, डिफ़ॉल्ट मान "rvm:" है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


लोड होने के बाद दृश्य को केंद्रित करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


सिलेंडर के रेडियल सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 16 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


डिश के लैटिट्यूड सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 8 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


डिश के लॉन्गिट्यूड सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 12 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग सेट करता है। डिफ़ॉल्ट मान null है, जिसका अर्थ है कि इम्पोर्टर/एक्सपोर्टर तय करेगा कि कौन सी एन्कोडिंग उपयोग करनी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset | नया मान |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


एक्सपोर्ट/इम्पोर्ट सीन की फ़ाइल नाम। यह वैकल्पिक है, लेकिन OBJ की सामग्री जैसे बाहरी एसेट्स को सीरियलाइज़ करते समय उपयोगी है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने का तरीका उपयोगकर्ता को संभालने की अनुमति देता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | नई मान **Example:** डिफ़ॉल्ट FileSystem LocalFileSystem है, यह सर्वर-साइड जैसे वातावरण में सुरक्षित नहीं है, लेकिन आप अलग इम्प्लीमेंटेशन निर्दिष्ट करके फ़ाइल सिस्टम एक्सेस को ओवरराइड कर सकते हैं। Aspose.3D विभिन्न FileSystem इम्प्लीमेंटेशन प्रदान करता है जैसे: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

और आप अपनी स्वयं की इम्प्लीमेंटेशन भी उपयोग कर सकते हैं।

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


FileSystem के लिए फ़ैक्टरी क्लास सेट करता है। डिफ़ॉल्ट फ़ैक्टरी com.aspose.threed.LocalFileSystem बनाएगी जो सर्वर वातावरण के लिए उपयुक्त नहीं है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | नई मान **Example:** SaveOptions/LoadOptions में डिफ़ॉल्ट FileSystem डायरेक्टरी-आधारित फ़ाइल सिस्टम है, आप इसे IOConfig.FileSystemFactory के माध्यम से निर्दिष्ट करके डिफ़ॉल्ट इम्प्लीमेंटेशन को ओवरराइड कर सकते हैं: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


यदि RVM फ़ाइल में रंग तालिका निर्यात नहीं की गई है तो दृश्य में प्रत्येक वस्तु के लिए यादृच्छिक रंगों के साथ सामग्री उत्पन्न करें। डिफ़ॉल्ट मान true है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


सेट करता है कि बाहरी एट्रिब्यूट सूची फ़ाइल (.att/.attrib/.txt) से एट्रिब्यूट लोड किए जाएँ या नहीं, डिफ़ॉल्ट मान true है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


OBJ जैसी कुछ फ़ाइलें बाहरी फ़ाइल पर निर्भर करती हैं, लुकअप पाथ्स Aspose.3D को लोड करने के लिए बाहरी फ़ाइल खोजने की अनुमति देंगे।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.util.ArrayList<java.lang.String> | नई मान **Example:** निम्नलिखित कोड दिखाता है कि कैसे मैन्युअली लुकअप टेक्सचर निर्दिष्ट करें, ताकि इम्पोर्टर उन्हें पा सके |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


आयताकार टॉरस के रेडियल सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 20 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


टॉरस के ट्यूब्युलर सेगमेंट्स की संख्या सेट करता है, डिफ़ॉल्ट मान 20 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

