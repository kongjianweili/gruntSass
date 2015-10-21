# gruntSass

这是一个使用grunt管理scss文件并将其转成css文件的项目。实现了对scss文件的实时监控。


##使用方法

在_build目录下执行 
  
    # grunt watch
  
在assets/sass文件夹中写scss文件，css文件将出现在assets/css 中。

#如何添加一个scss文件？

在assets/sass文件夹中添加一个scss文件，在 main.scss 文件中添加一行：

    @import "filename.scss";// 这里是你添加的文件的文件名，可以是任意的 如 reset.scss
 
注意要以分号结尾， import 导入的文件名要以引号引起来。

