转载：<https://sideproject.guide/>
作者：[Github@timqian](https://github.com/timqian)

---
# Side Project 指南

工作之余，很多程序员喜欢用代码建造一些小工具。有时候是为了解决一些自己或者朋友遇到的小问题，有时候是为了好玩儿。我们这行，通常称之为 Side Project。 不过可不能小看这些小工具。许多伟大的产品诞生于程序员的 Side Project。比如 [GitHub](https://gist.github.com/defunkt/6443), [Unsplash](https://medium.com/who-what-why/how-side-projects-saved-our-startup-a83a80f3b3ae), [Instagram](https://www.molfar.io/blog/2020/side-projects), [等等等等](https://www.molfar.io/blog/2020/side-projects)...

每次开启一个项目，虽然是 Side Project, 但内心其实隐隐也在期待着，这个 Side Project 或许可以帮到除自己以外的人？或许可能，这个产品价值足够高，甚至带来经济回报？然而现实是，99% 的 Side Project 都永远停留在自娱自乐的情况。经历三个阶段：从 **热情满满** 到 **无人问津** 最后 **弃坑**。

如何提升 Side Project 的存活概率？每次开启一个新项目，都应该问自己下面四个问题：

[**如何判断一个点子的好坏？**](#关于你的点子)

[**如何快速把 Side Project 做出来？**](#如何快速实现你的点子)

[**如何让更多人知道这个 Side Project？**](#如何获取用户)

[**如何把 Side Project 变成能为自己带来收入的产品？**](#Side%20Project%20如何赚钱)

这份小手册，记录下我对这几个问题的看法，以便复用。

## 参考资料

除了我自己的经验和思考，本指南参考了以下资料，推荐阅读：

- [Startup idea checklist](https://www.defmacro.org/2019/03/26/startup-checklist.html)
- [Founder Memos](https://www.julian.capital/)
- [The indie maker handbook](https://readmake.com/)
- [Startup marketing checklist](https://github.com/draftdev/startup-marketing-checklist/blob/master/marketing-checklist.md)
- [Startup library](https://startuplibrary.co/)

从 Side Project 出发变身知名产品的故事：

[GitHub](https://gist.github.com/defunkt/6443), [Unsplash](https://medium.com/who-what-why/how-side-projects-saved-our-startup-a83a80f3b3ae), [Instagram](https://www.molfar.io/blog/2020/side-projects), [Twitter 等](https://www.molfar.io/blog/2020/side-projects)

## 关于你的点子

### 什么样的点子是一个好点子？

好的点子通常有以下两个特点

#### 1. 从问题出发，而不是解决方案

从问题出发，做出能够节省时间，带来益处的产品，很难失败。

#### 2. 解决自己的问题

很多 Side Project 无法持续优化，通常是因为自己失去了动力。解决自己真正关心的问题，更有坚持的动力。

下面这这些问题帮助你更深入得理解和检验自己的点子，**对下面的几个问题有了自己满意的答案之后再动手也不迟**。

### 点子自测表

1. 这个产品的用户是谁？
    
2. 用户不满的本质是什么？如果他们看到你的解决方案，他们是否会这样说：“谢谢你，要是早点有这玩意儿就好了”
    
3. 你为他们做的产品是什么？
    
4. 写一条推文，从一个假想的用户出发，描述这个产品，以及这个产品如何解决了用户的问题。
    
5. 为你的产品的发布博客写一个标题。这个点子是否新颖？你的目标用户会想点击，分享它吗？即使过了几天后是否还是愿意分享它
    
6. 你的目标用户衡量好坏的主要标准是什么？你的产品能否在这些标准上都好过同类产品。（你的产品是否可以做到其他人做不到的事情）
    

> 以上问题参考了 [Startup idea checklist](https://www.defmacro.org/2019/03/26/startup-checklist.html)

### 点子怎么来？

我的建议是维护一个点子列表，把平时想到的问题，需求，想法都记录下来，好的点子，好的痛点会重复刺激你。

### 竞品调研

世界上有上亿大脑都在寻找着可被解决的问题，所以你的点子通常不会是完全独一无二的。参考现有的解决方案，思考它们为什么成功，或者为什么没有成功，为什么别人要选择你的产品，而不是现有的这个。我通常使用下面这些工具寻找竞品

- [AlternativeTo](https://alternativeto.net/)
- [ProductHunt](https://www.producthunt.com/)
- [Google](https://google.com/)

## 如何快速实现你的点子

当你对你的点子燃起了足够的热情，迫不及待想要敲击键盘，用代码改变世界之前，先冷静一下。

### 你不一定要写代码

每一行代码都需要被维护，每增加一行代码，你这个 Side Project 的成本就上升了一点。如果能不写代码就解决问题，那是最好的。

正确的解决问题的优先级：

1. 不写代码
2. 只写前端代码（包括 DAPP）
3. 如果必须有后端服务，使用可以 Serverless 方式部署的写法
4. 维护一个服务器

简而言之，对于开发来讲，优化的目标应当是让自己当前和未来的劳动越少越好。如果一定要写代码来解决，使用你最熟悉的工具。

### 第一版做到什么程度

- 是可用的，帮助用户解决了问题，或者提供了价值
- 提供渠道供用户反馈
- 花费时间最好不要超过一个月(因人的耐心而异)，以便及时获得用户反馈

### 我使用的一些建筑工具

- [TailwindCSS](https://tailwindcss.com/): 使用 class 来定义样式，比直接写 CSS 方便一些
- [React](https://reactjs.org/): 模块化构建前端项目
- [Nextjs](https://nextjs.org/): 用 React 写多页应用更方便，性能优秀
- [Serverless](https://serverless.com/): 免运维
- [Vercel](https://vercel.com/): 一键部署 Nextjs 等应用，性能有保障
- [Dynamodb](https://aws.amazon.com/cn/dynamodb): Serverless 数据库

## 如何获取用户

### 发布你的 Side Project

下面是一些对于分享新作品比较友好的社区

英文社区

- [HN](https://news.ycombinator.com/) - 记得以 `Show HN:` 开头，更容易进入专门展示创作的板块首页。上首页的话流量巨大。
- [ProductHunt](https://producthunt.com/) - 记得优化一下图标和产品截图
- [Reddit](https://reddit.com/) - 任何方向的产品，基本上都可以找到相关 subreddit
- [Indiehackers](https://www.indiehackers.com/) - 独立开发者比较多，可以收到不错的同行建议
- [Twitter](htpps://twitter.com/) - 如果你的产品好用，有可能出现人传人现象，甚至病毒性传播的可能，带来的流量不可想象。比如作为一个推特小透明，没想到我在推特上[分享这个 Guide 之后](https://twitter.com/Tim_Qian/status/1526793570107109377)，几小时之内就获得了上万展示和上千点击..

中文社区

- [V2EX](http://v2ex.com/) - 创意社区，很多开发者设计师交流的地方
- [阮一峰的周刊](https://github.com/ruanyf/weekly/) - 可以给周刊投稿，收录的话应该能带来几百个愿意尝鲜的用户
- [ruby-china](https://ruby-china.org/) - 老牌程序员论坛
- [cnodejs](https://cnodejs.org/) - nodejs 相关
- [小众软件](https://www.appinn.com/) - 老牌软件测评平台
- [w2solo](https://w2solo.com/) - 立志成为中国的独立开发者社区
- [Hello github](https://github.com/521xueweihan/HelloGitHub) - 收录开源项目，作者有一个公众号，被收录的话能带来一些用户
- [中国独立开发者列表](https://github.com/1c7/chinese-independent-developer) - 收录独立开发作品
- 我不太熟悉的一些社区：[少数派](https://sspai.com/), [learnku](https://learnku.com/)

### 搜索引擎优化

发布和分享产品是你找用户的方式，而搜索则是有需要的用户主动找到你。虽然短期效果不如主动分享立竿见影，但因为[长尾效应](https://zh.wikipedia.org/zh-sg/%E9%95%BF%E5%B0%BE)，只要你做好了该做的优化，从搜索引擎来的用户数量更大，且更需要你做的产品。

SEO 曾是一个高深的活计，很多技巧被发明出来欺骗搜索引擎来提高网站排名。但是对于搜索引擎来说，他的价值在于 **帮助用户找到想找的内容**。这些年博弈下来，黑科技大多失效了，搜索引擎帮助用户找到想要的内容的能力也越来越强。

所以对于你来说，最重要的是准确的写好你的产品介绍，剩下的事情交给谷歌去优化。花很多时间去和搜索引擎斗智斗勇不一定划算，不过我一般会做好下面这些事情：

- 在更多高质量的网站上出现你的链接
- 帮助搜索引擎找到你的内容，恰当得展示给用户
    - title 标签(`<title/>`)：告诉用户和搜索引擎网页的主题是什么
    - description 标签(`<meta name="description"/>`): 搜索引擎可能会将其用作你网页的摘要
- 使用简短但具有描述性的文字作为链接文字（链接的可见文字）。这类文字会告诉用户和搜索引擎链接到的网页的信息。
- 给图片取有意义的文件名和替代文字（`image` 标签的 `alt` 属性）：可使图片搜索引擎（如 Google 图片搜索）更好地理解你的图片。也是流量的一个来源。
- 构建适合移动设备的网站。因为发现大多数搜索来自移动端，Google 已经开始尝试[主要使用移动版网站内容进行排名和解析](https://webmasters.googleblog.com/2016/11/mobile-first-indexing.html)。如果移动版网页无法提供令人满意的搜索体验，在移动搜索结果中的排名便会下降。_工具：[Google 的移动设备适合性测试](https://search.google.com/test/mobile-friendly)_

### 产品自身的增长属性

最好的自增长属性是产品本身可以帮助用户，其他都是锦上添花的技巧。

这里记录一些技巧：

- 邀请奖励：促进分享
- 饥饿营销：邀请码机制
- 增加用户粘性：建立聊天组
- 培养用户信心：长期更新

### 持续改进的重要性

很少有产品做出来就是最好的样子。持续改进有两大好处

- 寻找产品与市场的契合(Product market fit), 很少有产品已做出来就满足很多人需求的
- 持续改进给用户信心

#### 参考资料及工具推荐

- [Hotjar](https://www.hotjar.com/): 观察用户如何使用你的产品
- [Marketing-Checklist](https://github.com/portable-cto/side-project-marketing/blob/master/marketing-checklist.md)
- [Gogle search console](https://search.google.com/search-console): Google 官方SEO
- [Lighthouse](https://github.com/GoogleChrome/lighthouse): 网站诊断工具。帮助你提升性能；SEO等。chrome 插件用起来很方便
- [Google 的移动设备适合性测试](https://search.google.com/test/mobile-friendly)

## Side Project 如何赚钱

作为一般等价物，“钱”被用来度量某个物品/服务的价值。当你做的 Side Project 帮助到了某些人，那么这个产品就是值钱的，不管你收不收费。

### 从 side project 转变为付费服务的常用策略

1. 在产品还没有人知道或者还不成熟的时候，免费让用户使用（但最好告诉他们不会永远免费，有个心理预期）
2. 根据早期用户的反馈，打磨产品，积累种子用户
3. 当产品足够成熟，有足够用户在用时。找到一个合理的收费方式，再次发布。这个时候，发布的成功率和付费转化率都会比较高

### 收费工具

对很多 Side Project 来说，可能接入付费系统显得太麻烦了。 比如 Side Project 本身花了两天时间做出来，肯定是不愿意再花两天接入 Stripe 支付。

但请至少需要考虑这种最简单的收费方式：**接受赞助**。你只需要在一些提供赞助功能的平台注册一个账号。然后在你的 Side Project 里面带上赞助链接即可。 时隔多年我到现在还记得 Side Project 第一次收到赞助时的喜悦之情，那是一种你做的东西真的被认可的感觉。

一些常用的赞助平台：

- [Patreon](https://www.patreon.com/)（全球）
- [Sponsor.cat](https://sponsor.cat/) (全球)
- [Github Sponsors](https://github.com/sponsors/)（全球）
- [BuyMeACoffee](https://buymeacoffee.com/)（全球）
- [Ko-fi](https://ko-fi.com/)（全球）
- [爱发电](https://afdian.net/)（中国）

- 微信/支付宝的支付码（中国）

如果你的 Side Project 收到了赞助，算是对他价值的一种肯定。当你把它做的更好用，为用户提供了更大价值。希望把它作为一个 “Major Project“。你可以选择下面几种支付系统。

- [Stripe](https://stripe.com/)（全球，需要香港或国外银行卡，费率低）
- [Lemon Squeezy](https://www.lemonsqueezy.com/)（全球，国内可用，配置方便，支持微信支付宝）
- [Gumroad](https://gumroad.com/)（全球，国内可用，配置方便）
- [Paddle](https://www.paddle.com/)（全球，国内可用，费率较高）
- [Coinbase commerce](https://commerce.coinbase.com/) （全球，国内可用，虚拟货币支付）
- [面包多](https://mbd.pub/)（中国）
- 接入微信/支付宝（中国）
- [微信小商店](https://shop.weixin.qq.com/)

### 常见收费模式

- 基础功能免费，付费可用高级功能 ([feeds.pub](https://feeds.pub/))
- 广告 ([star-history](https://star-history.com/))
- 收费应用 ([percento](https://www.percento.app/))
- 进入社区付费 ([疯投圈](https://crazy.capital/))
- 被收购 ([star-history](https://star-history.com/))