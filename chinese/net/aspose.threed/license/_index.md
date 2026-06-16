---
title: "类 License"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.License 类。提供对组件进行授权的方法"
type: docs
weight: 1610
url: /zh/net/aspose.threed/license/
---
## License class

提供对组件授权的方法。

```csharp
public class License
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license/)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | 对组件进行授权。 |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | 对组件进行授权。 |

## 示例

在本例中，将尝试在以下位置查找名为 MyLicense.lic 的许可证文件：组件所在文件夹、调用程序集所在文件夹、入口程序集所在文件夹，随后在调用程序集的嵌入资源中查找。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

组件 jar 文件：

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 另请参见

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


