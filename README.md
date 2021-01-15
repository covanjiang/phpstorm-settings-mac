# phpstorm-settings-mac
Mac OS PHPStorm settings.

## 配置

```xml
<?xml version="1.0"?>
<ruleset name="CustomStandard">
  <rule ref="PSR2">
    <!-- 隐藏命名空间反白 -->
    <!-- <exclude name="PSR1.Classes.ClassDeclaration.MissingNamespace"/> -->
    <!-- 隐藏行代码字符数超出反白 --> 
    <exclude name="Generic.Files.LineLength"/>
  </rule>
  <rule ref="PSR1">
    <!-- 隐藏蛇形命名法反白 -->
    <exclude name="PSR1.Methods.CamelCapsMethodName.NotCamelCaps"/>
  </rule>
</ruleset>
```

## 使用方法

![image](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F5eeac47c-bcfb-4c31-ba9a-be86e79ce20f%2Fimage.png?table=collection&id=a082762f-9f92-403b-98a2-f07d09619838&width=3740&userId=f4352030-2ac9-4df3-b6f4-09d9bf65ca89&cache=v2)

1. `phpstorm > Preferences > Inspections `, 展开 `PHP > Quality tools`, 选中 `PHP_CodeSniffer validation`, 点击右侧的 `Coding standard` 的 `...`, 选择保存的文件. 
2. 点击右侧的 `Coding standard` 的下拉框, 选择 `custom`.
