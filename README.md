# 看见密码学
![](image/seeingcryptography.png)

 在我的职业生涯里密码学一直如影随形。自从2005年接触到密码学之后，就与她结下了不解之缘。虽然，中间开了几次小差，搞过ERP（Enterprise Resource Planning，企业资源计划）、物联网、区块链，但这些从业经验不仅没有减弱我对密码学的理解，反而让我在密码应用方面走的更远了。

20多年的从业经历中，我的主要工作是产品研发，并向客户讲解产品，这就使得我有大量接触用户的机会。对于有一定密码学或者信息安全从业经验的客户，讲解起来并不是太费劲，但工作中遇到大多数的客户都是没有密码学背景，甚至从来都没听过。当然这也没有什么奇怪的，我第一次接触密码学的时候，也是一脸懵逼，在图书馆里泡了一个多月后，才终于搞明白了密码学到底是什么东东，并研发了我人生第一个密码应用产品——统一用户。

每当我自嗨式的讲完精心准备的内容后，总是会有用户提出一个疑问，密码是什么？密码和口令有什么区别？瞬间之前讲课的满足感就荡然无存。经过N多次相同的经历后，每次讲课之前都会了解一下大家对密码学的认知情况，或者干脆加一页专门介绍密码学，这样的工作做久了之后，就有一种强烈的愿望想写一本普及密码学的书籍。

由于密码学是建立在复杂的数学理论和算法基础之上，例如公钥密码学使用了椭圆曲线相关的高级数学算法，对于非专业人士来还是很难理解。像李笑来这样的终身学习者有一次也坦言对于椭圆曲线算法他也不清楚，但这丝毫不影响他对区块链技术的理解。对于绝大多数人来说，我们不需要研究算法，不管是国外的密码算法还是国产密码算法来说，算法本身已经公开，我们只是使用而已。

既然算法已经公开，我们只是使用，那么密码学的学习门槛其实已经降到了一个很低的水平。就像我在《大话区块链》一书中提到的观点：只需高中学历就可以从事区块链开发，这背后的秘密是任何一门学问都分为专业知识和应用知识。除非你是想做密码理论研究，有志于成为王小云院士那样专家，那确实需要具备一定的数学专业背景和很多年的潜心研究，但对于大多数人来说其实只是密码应用，或者干脆是密码的使用。

举一个大家常见的密码使用场景，如果我们要访问一个网站，在地址栏我们会看到一个锁形的图标类似https://www.xxx.com这样的地址，这里面的HTTPS（Hypertext Transfer Protocol Secure，超文本传输安全协议）其实就是密码学的应用。采用HTTPS的网站就是使用密码在我们的电脑和网站之间建立了一个安全的通讯隧道，可以有效防止黑客窃听我们的敏感信息（比如系统登录的口令、购物时绑定的银行卡信息等）。

就这样一点密码使用知识，就可以避免大家访问一些钓鱼网站。因为识别网站是否是合法网站的一个重要标识就是看网站是否提供HTTPS这样的安全连接，像电子商务的网站更是如此。

为了让普通用户都能理解密码，我打算遵从以下原则编写这本书：

第一，假定你没有任何的密码学背景；

第二，假定你对密码感兴趣但没有时间去研究一些经典书籍；

第三，我希望这本书能够写的生动有趣，争取让你一口气就可以读完；

第四，我希望通过这本书能给你建立一个完整的密码学知识体系。

以上四点很难达成，但这就是我写这本书的目的。

为了确保本书质量，我尽量降低我个人对密码学的看法，而是采用一些行业内已经达成共识的知识。当然我不是机器，所以书中也难免会有个人主观理解，甚至是是我的一家之言，但请大家放心，这些一家之言虽然没有得到行业的普遍认可，但也是我20多年工作实践的总结，希望对大家有所帮助，如果对行业的发展能够起到一点推动作用，那我就荣幸之极了。

最后，我还是要着重强调一点，本书虽然是针对非专业人士写的密码学科普书籍，但对于密码从业者来说也非常值得阅读，这本书可以帮你建立起密码学的知识体系，让从业者在密码行业走的更远。

# 目录

# 书名：看见密码学

# [看清密码学](charpter01_unlocking_cryptography00.md)

## 密码学发展史

### 古典密码学

### 现代密码学

### 中国商用密码里程

### 未来密码学

#### 量子及抗量子

#### 白盒密码

#### 同态加密

#### 轻量级密码算法

# [看懂密码学](charpter02_understanding_cryptography00.md)

## 术语解释

## 密码学定义

## 密码算法和工作机制

### 基本数学知识

#### 二进制

#### 单项函数

#### 模运算

#### 质因数分解

### 基本原理

#### 对称加密

#### 非对称加密

#### RSA算法

#### 数字信封

#### CA认证

#### 密钥管理

# [看见密码学](charpter03_seeing_cryptograpy00.md)

## 密码的功能

## 密码的作用

## 密码应用原则

## 密码服务中台

### 典型密码应用技术框架

### 密码服务中台设计

### 典型密码资源

### 典型密码应用