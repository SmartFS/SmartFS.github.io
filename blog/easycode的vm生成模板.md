点击返回[🔗我的博客文章目录](https://smartfs.github.io/#/toc)
* 目录
{:toc}
<div onclick="window.scrollTo({top:0,behavior:'smooth'});" style="background-color:white;position:fixed;bottom:20px;right:40px;padding:10px 10px 5px 10px;cursor:pointer;z-index:10;border-radius:13%;box-shadow:0.5px 3px 7px rgba(0,0,0,0.3);"><img src="https://smartfs.github.io/blogImg/backTop.png" alt="TOP" style="background-color:white;width:30px;"></div>

# EasyCode的vm生成模板

> 这是一堆vm模板，用来生成各种代码，如果你对easycode了解就知道是干嘛的，我这个可以一口气将spring boot项目所有的代码生成出来，包括controller，service，mapper，application，redis，sa-token等等。现在留在CSDN上方便查看和下载，本文所有的内容均为我的原创，而且开源免费。

## 1.教程文档

使用教程有如下三篇文章，都是我原创的，在`CSDN`上均有上万的浏览量。

### 1.1 [Easy Code的使用教程（带模板）](https://blog.csdn.net/weixin_43982359/article/details/121799836)

<img src="https://smartfs.github.io/blogImg/java.png" width="15%" alt="" />

### 1.2 [MyBatis-Plus的easycode模板](https://blog.csdn.net/weixin_43982359/article/details/124287922)

<img src="https://smartfs.github.io/blogImg/mybatisplus.png" width="15%" alt="" />

### 1.3 [EasyCode的Mybatis终极版模板](https://blog.csdn.net/weixin_43982359/article/details/127930723)

<img src="https://smartfs.github.io/blogImg/MYBATIS.png" width="15%" alt="" />

## 2.导入文件

> 这里是最新的模板，是GitHub上导入文件。项目的开源地址是[开源地址链接🔗](https://github.com/smartfs/vmCreate)

### 2.1 ColumnConfig

> 列配置文件

[下载链接🔗](https://raw.githubusercontent.com/smartfs/vmCreate/main/vm/ColumnConfig/EasyCodeConfig.json)

### 2.2 GlobalConfig

> 全局配置，能修复easycode在idea2023版本以后生成的mapper没有逗号的错误

[下载链接🔗](https://raw.githubusercontent.com/smartfs/vmCreate/main/vm/GlobalConfig/EasyCodeConfig.json)

### 2.3 TypeMapper

> 控制easy code的Java映射sql的关系

[下载链接🔗](https://raw.githubusercontent.com/smartfs/vmCreate/main/vm/TypeMapper/EasyCodeConfig.json)

### 2.4 Template

#### 2.4.1 mybatis-mvc

> 这里是<img src="https://smartfs.github.io/blogImg/MYBATIS.png" width="30px" alt="" />mybatis的增删改查代码

[下载链接🔗](https://raw.githubusercontent.com/smartfs/vmCreate/main/vm/Template/mybatis-mvc/EasyCodeConfig.json)

#### 2.4.2 mybatis-config

> <img src="https://smartfs.github.io/blogImg/mybatisplus.png" width="30px" alt="" style="transform: scaleX(-1);"/><img src="https://smartfs.github.io/blogImg/MYBATIS.png" width="30px" alt=""/>mybatis和mybatis-plus可以共用这个，里面是配置类

[下载链接🔗](https://raw.githubusercontent.com/smartfs/vmCreate/main/vm/Template/mybatis-config/EasyCodeConfig.json)

#### 2.4.3 mybatis-util

> <img src="https://smartfs.github.io/blogImg/mybatisplus.png" width="30px" alt="" style="transform: scaleX(-1);"/><img src="https://smartfs.github.io/blogImg/MYBATIS.png" width="30px" alt=""/>mybatis和mybatis-plus可以共用，这是我自己写的一些工具类

[下载链接🔗](https://raw.githubusercontent.com/smartfs/vmCreate/main/vm/Template/mybatis-util/EasyCodeConfig.json)

#### 2.4.4 mybatis-plus-config

> <img src="https://smartfs.github.io/blogImg/mybatisplus.png" width="30px" alt=""/>执行后将mybatis项目升成mybatis-plus项目

[下载链接🔗](https://raw.githubusercontent.com/smartfs/vmCreate/main/vm/Template/mybatis-util/EasyCodeConfig.json)