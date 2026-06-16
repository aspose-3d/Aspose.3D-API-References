---
title: "License.License"
second_title: "Aspose.3D for .NET API 参考"
description: "License 构造函数。初始化此类的新实例。"
type: docs
weight: 10
url: /zh/net/aspose.threed/license/license/
---
## License constructor

初始化此类的新实例。

```csharp
public License()
```

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

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


