# PicGo + GitHub + Typora 搭建个人图床工具

----

## 一 .GitHub仓库设置

> 流程：新建public仓库 - > 创建Token -> 复制Token备用

### 1.1 新建仓库 

* **点击git主页右上角的 `+`号创建`New repository`**

  ![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/1.png)

* **填写仓库信息 **

  ![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/2.png)



### 1.2 创建Token 并复制保存

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/3.png)

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/4.png)

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/5.png)

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/6.png)

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/7.png)



## 二 . PicGo客户端配置

### 2.1 下载 & 安装

**PicGo 是一个开源的图床工具，非常优秀。可以到 git 上下载，但下载速度太慢，所以我放了一个百度云的链接，速度快很多。**

> git地址：
>
> Win版下载链接：[百度云](https://pan.baidu.com/s/17KycPMoqNCnc1cR_yQO8nQ) 密码：PicG

### 2.2 配置

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/123.png)

* **仓库名：**也就仓库名字而已，比如我github用户名叫``EayonLee``，仓库名叫``IMG-Cloud``那么这里就写``EayonLee/IMG-Cloud``

* **分支名：**默认写``master``即可

* **Token：**刚刚生成并保存的token

* **存储路径：**这个也可以不填，不填默认放到git仓库的``img``这个文件夹，像我填了就放到``data``文件夹

* **域名：**原本的域名应该是这样的``https://raw.githubusercontent.com/EayonLee/IMG-Cloud/master``。但是你们发现我并没有这样写，因为github在国内访问巨慢，所以为了咱们的图片能够加载的快一点，我使用了代理，所以域名就变成了图中的这样``https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master``。你们只需要修改仓库名就可以了，其他不用变。

  

## 三. Typora配置

### 3.1 配置

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/9.png)

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/10.png)

### 3.2 测试 演示

* **在Typora中插入一个图片**

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/11.png)

* **将本地图片上传到github仓库图床**

![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/12.png)

* **查看仓库图床是否上传成功**

  ![](https://cdn.jsdelivr.net/gh/EayonLee/IMG-Cloud@master/data/13.png)

> 【🍔Java全生态技术学习笔记，一起超神吧🍔】：[飞机票](https://github.com/EayonLee/JavaGod)
