# 原汁原味 Go 语言学习——初衷

* 《原汁原味 Go 语言学习》系列课程。
* 在这个系列课程里，我会带着大家一起学习官方文档中提供的 effective-go 、 go内存模型、语言规范、FAQ等内容。
* 个人博客 jingwei.link。
* 因为制作这个视频有很多不确定性，大家可以通过关注我的个人博客 jingwei.link  和代码库 github.com/chalvern/books 来跟进最新的信息，未来有任何的信息我会首先在这两个地方发布。

## 系列课程初衷
* 学习 Go 语言有没有简单、可靠和高效的学习材料？
* 有没有在上下班或者周末休闲的时候愿意听的那种学习材料？
* 到哔哩哔哩、喜马拉雅搜索了一下，也观赏了一些已存在的课程与教程，感觉他们都讲了很多东西，但是对于我来说总觉得课程内容里附加了太多方法论的东西、太多讲师个人特色的东西；这往往造成几个不好的结果：1）如果课程里的东西是方法论的产物（把学习 C 语言的一套理论拿过来学习 Go 语言），我们学习到的并不是原汁原味的语言特性。2）有的语言特性仅仅是规范中的一个定义，但是加入了讲师的个人特色后可能就变成了一个很神秘的东西，让大家对 Go 语言的学习产生一种可望不可即的错觉。
* 学习分成两类：一类是教科书式的理论上的学习，最好有教材，当然最好也有老师可以带自己学习这门教材；对于 Golang 语言来说，可能是它的官方文档、书籍、或者一些课程。另一类则是相关内容的涉猎，比如对于 Golang 语言来说，可能是它的设计初衷、设计理念、相关的工具使用技巧、一个很有创意的用法、一个优雅的库、应用实践遇到的坑和填坑经验等等；总之，这部分的内容往往可以触发我们对 Golang 的进一步的探索，开阔视野的同时加深对它的理解。
* 我们可以把文档、书、课程、培训等当做第一类材料，这一类材料还是比较容易找的，不过这类材料要么冗长枯燥，要么就是获取成本比较高。论坛与社区讨论（比如 studygolang.com）、开发者会议（goconf）、博客等形成第二类材料（也是经验分享类的材料）。第二类的内容一般是需要靠大家自己留意并积累的，基本上可以和我们常说的经验对应起来。这也是一个一年经验的程序员与三年经验程序员的最大的区别——后者阅览过更多的资料、遇到并处理过更多的问题，因此有更多的经验。
* 第一类材料相对来说是比较容易找到的，比如对于我们 Go 语言学习者来说，Golang 官网（golang.google.cn）中的文档就是很好的学习材料，甚至可以说是第一手的Go语言学习资料。根据我这几年的工作经验，发现那些在技术上有所造诣的人其实都是有能耐心读文档的人，尤其各个书籍的作者尤其如此，他们必须要消化文档的内容，然后总结整理出自己的学习感悟，编纂成册以后其实就是我们见到的各种教程的书籍了。不过原汁原味的文档总是冗长枯燥的，而阅览别人小画过的视频、书籍、博客则要轻松、有趣的多，因此：
* 平日的学习过程中，大家总是倾向于看书看视频教程，却往往忽略官方文档中第一手的学习资料。这也可以理解，不过因为它的价值，错过这个资料的学习也是挺可惜的。为了降低第一手资料的难度，在接下来的视频中，我会带着大家过一下官方文档中提供的几篇文档，目前定的有 effective-go 、 go内存模型、FAQ、语言规范等等的一些内容，我希望这个系列的视频能给枯燥的文档内容增加一些生趣，如此，假如它能提起大家主动学习 Go 语言的兴趣，比如在上下班路上或者工作之余看一看或听一听，我觉得这将是非常有意义的。
* 
* 如果你是一个初学者，希望本系列视频能作为你学习 Go 变成的第一类材料；如果你是一个有 Go 开发经验的开发者，希望本系列视频能学到一些之前忽略了的知识点，巩固并加深自己的 Go 语言连接，提升自己的 Go 编程技能。

* 探索一下 Go 官方的网页 golang.google.cn， 如果大家能够读懂英文就最好了，可以在这个网页上找到下载、安装、使用的所有知识；如果不想读英文，也有一个 go-zh.org 的网站，基本上是 golang.google.cn 的中文翻版，大家也可以探索一下，不过版本比较老，里面的一些内容有的已经失效了。
* 回到 golang.google.cn 我们可以在 document 这里找到不少内容。

* 接下来的课程先让我们一起看一下文档 effective- Go 的内容。
