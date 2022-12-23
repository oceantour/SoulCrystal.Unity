## 初始化 Unity 项目

将此项目下的所有文件复制粘贴到新建的Unity项目中。

1. Assets/Plugins 下的DLL文件是测试文件，删除就行。
2. Src/Builder 下的文件会在项目生成时顺便把程序集复制到 Assets/Plugins 文件夹下。
3. 请将所有的项目底层代码写在 Src/[项目名.程序类型] 文件夹中。
4. 修改生成逻辑请参考 [MSBuild](https://learn.microsoft.com/zh-cn/visualstudio/msbuild/msbuild?view=vs-2022) 

☆ 工程文件管理请打开 sln，sln 文件无需复制到新建的Unity项目中。