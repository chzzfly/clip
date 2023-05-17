---
title: I built a SaaS app using ChatGPT
date: 2023-05-17T11:48:20.000Z
updated: 2023-05-17T11:48:20.000Z
taxonomies:
  tags:
    - Tech
extra:
  source: >-
    https://productlessons.substack.com/p/i-built-a-saas-app-using-chatgpt?utm_source=substack&utm_medium=email
  hostname: productlessons.substack.com
  author: Product Lessons
  original_title: I built a SaaS app using ChatGPT
  original_lang: en

---

[![](https3A2F2Fsubstack-post-media.s3.amazonaws.com2Fpublic2Fimages2Fd7fdf4b4-479c-41c6-8aa3-267be1fca0e1_1024x1024.jpeg)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd7fdf4b4-479c-41c6-8aa3-267be1fca0e1_1024x1024.jpeg)

Last year, I learned to [code in 30 days](https://www.productlessons.xyz/article/learn-to-code-when-no-code-tools-fail) with the help of YouTube tutorials and a LOT of google searches. [The site I built](https://topstartups.io/) had a simple interface, simple database, narrow functionality. It works, but it’s not what I would consider real software — a tool that lets people make things.  

去年，借助 YouTube 教程和大量谷歌搜索，我在 30 天内学会了编码。我建立的网站有一个简单的界面、简单的数据库和狭窄的功能。它可以工作，但它不是我认为的真正的软件——一种让人们创造东西的工具。

This year, I surprised myself by building a software tool end-to-end using ChatGPT in 30 days. In my previous life as a product manager, this was the kind of work that would take 2 engineers and 1 designer at _least_ 30 days. And they would be an A-team.  

今年，我在 30 天内使用 ChatGPT 构建了一个端到端的软件工具，这让我感到很惊讶。在我以前担任产品经理的时候，这种工作需要 2 名工程师和 1 名设计师至少 30 天才能完成。他们将是一支一流的球队。

Mind-bending is probably the best way to describe this experience. What used to be sprinting is more like crawling compared to what’s possible today. We’ve entered a new age of knowledge work. Let’s unpack what this means.  

令人费解的可能是描述这种体验的最佳方式。与今天的可能相比，过去的短跑更像是爬行。我们已经进入了知识工作的新时代。让我们解开这意味着什么。

But first, a quick shoutout. 但首先，快速大喊一声。

**[Partner shoutout: Amplitude 合作伙伴大喊：振幅](https://vpdae.com/redirect/5y3vn136e3it6zucmfa1ps4y16l)**

The heart of every great business is great user retention. Amplitude, an industry leader in product analytics, has mined the data for a **[framework on mastering retention](https://vpdae.com/redirect/5y3vn136e3it6zucmfa1ps4y16l)**. It applies to products at all stages of growth, in all verticals. Whether you’re a growth expert or just starting out, this can be your go-to guide:  

每个伟大企业的核心都是出色的用户保留率。 Amplitude 是产品分析领域的行业领导者，它挖掘了数据以构建掌握保留率的框架。它适用于所有垂直领域中处于所有增长阶段的产品。无论您是增长专家还是刚刚起步，这都是您的首选指南：

[Get the Guide  获取指南](https://vpdae.com/redirect/5y3vn136e3it6zucmfa1ps4y16l)

**[permanent link to this post→ 这篇文章的永久链接→](https://www.productlessons.xyz/article/i-built-a-saas-app-using-chatgpt)**

Whenever I talk about this project, the most common reaction is that I’ve become an engineer. But now that I’ve seen the sausage get made, I feel a duty to share the truth. **There was no engineer behind this project — at least not in the traditional sense.** The code came not from my head or ChatGPT’s, but a tight collaboration _between_ us.  

每当我谈到这个项目时，最常见的反应就是我成为了一名工程师。但既然我已经看到香肠的制作过程，我觉得有责任分享真相。这个项目背后没有工程师——至少不是传统意义上的。代码不是来自我的头脑或 ChatGPT 的，而是我们之间的紧密合作。

Typically, someone who knows _what_ to build and _why_, but doesn’t know _how_ to do it writes a document, then gives it to an engineer to execute. Whatever is lost in translation takes time to iterate on. This is the old way.   

通常，知道要构建什么以及为什么构建但不知道如何构建的人会编写文档，然后将其交给工程师来执行。翻译中丢失的任何内容都需要时间来迭代。这是老办法。

The new way is to break down what would be a document into step-by-step instructions and send it to ChatGPT. There’s no need to sell a mission , or sprinkle in carrots for their career. ChatGPT prefers to get straight down to business, like this:    

新的方法是将文档分解为分步说明，然后将其发送到 ChatGPT。没有必要出售任务，或为他们的职业撒上胡萝卜。 ChatGPT 更喜欢直截了当，像这样：

> Generate a box with dotted lines that takes up most of the screen. Allow users to drag and drop images into the box, or click to browse and select their images. Then render out thumbnails of the selected images in stacked rows with some spacing in between.  
> 
> 生成一个占据大部分屏幕的虚线框。允许用户将图像拖放到框中，或单击以浏览并选择他们的图像。然后在堆叠的行中渲染出所选图像的缩略图，中间有一些间距。

The feedback loop is airtight because I immediately test ChatGPT’s output, and can see what needs fixing. After some iteration, we got to a screen that looks like this:  

反馈回路是无懈可击的，因为我立即测试了 ChatGPT 的输出，并且可以看到需要修复的地方。经过一些迭代，我们得到了一个看起来像这样的屏幕：

[![](https3A2F2Fsubstack-post-media.s3.amazonaws.com2Fpublic2Fimages2Fa25f1f52-3e42-44c1-895b-5fc9965909f9_3448x1742.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa25f1f52-3e42-44c1-895b-5fc9965909f9_3448x1742.png)

It’s magic with one caveat: it doesn’t happen on its own. Right now, I still need to be involved at every step to share right-sized instructions and feedback. But the technical barrier to code collaborate with ChatGPT is fairly accessible:  

有一个警告是神奇的：它不会自行发生。现在，我仍然需要参与每一步，以分享适当的说明和反馈。但是与 ChatGPT 进行代码协作的技术障碍是相当容易实现的：

-   Use an IDE to test the code  
    
    使用 IDE 测试代码
    
-   Understand at a high-level what it takes to build things: HTML (elements on a page), CSS (styling), JS (frontend logic that controls how elements behave), Python (backend logic that usually involves saving information into a database)  
    
    从高层次理解构建事物需要什么：HTML（页面上的元素）、CSS（样式）、JS（控制元素行为方式的前端逻辑）、Python（通常涉及将信息保存到数据库中的后端逻辑）
    
-   Know that there are open-source libraries where you can borrow someone’s code  
    
    知道有开源库可以借用别人的代码
    

ChatGPT is enthusiastic, relentless… and quirky. It’s an absolute beast at taking specific instructions, drafting code, and debugging syntax. But it also suffers from amnesia at times, forgetting previous context, or repeating the same wrong answer. When this happens, I ~lose faith in AI~ start a new chat and make my ask more precise .  

ChatGPT 热情、不屈不挠……而且古怪。在接受特定指令、起草代码和调试语法方面，它绝对是一头野兽。但它有时也会失忆，忘记以前的背景，或者重复同样的错误答案。当这种情况发生时，我对 AI 失去了信心开始新的聊天并让我的问题更加精确。

ChatGPT also has a bias for writing code from scratch even when libraries are available. When it creates excess code, I nudge it like this: “Are there libraries or pre-built components I can use for this? This is a Django app, btw”  

即使库可用，ChatGPT 也倾向于从头开始编写代码。当它创建多余的代码时，我会这样推动它：“是否有我可以使用的库或预构建组件？这是一个 Django 应用程序，顺便说一句”

When a use case is poorly documented, ChatGPT sometimes overstretches its assumptions. This brings us to an important point: ChatGPT _is_ regurgitating a lot of online content. **The output is often generic, but when it comes to building a product, especially an MVP, generic code that does the job** _**is**_ **the job.** You don’t need unique code to build a uniquely valuable business.  

当用例记录不当时，ChatGPT 有时会夸大其假设。这给我们带来了一个重要的观点：ChatGPT 正在反省大量在线内容。输出通常是通用的，但在构建产品时，尤其是 MVP，完成工作的通用代码就是工作。您不需要独特的代码来建立具有独特价值的业务。

When a seismic change happens, it’s fun to predict follow-on effects. Three that come to mind:  

当发生翻天覆地的变化时，预测后续影响很有趣。想到的三个：

1.  Decline of the “code monkey” “代码猴子”的没落
    
2.  Rise of nontechnical “tech” founders  
    
    非技术“技术”创始人的崛起
    
3.  Intention as humanity’s last bastion  
    
    意图作为人类最后的堡垒
    

One of the surprises from working in tech is how often engineers play the role of “code monkey” — there to follow someone else’s commands to the T. I think this will slowly fade because on its best days, ChatGPT _is_ the perfect code monkey.  

在技术领域工作的惊喜之一是工程师经常扮演“代码猴子”的角色——在那里听从别人对 T 的命令。我认为这会慢慢消失，因为在最好的日子里，ChatGPT 是完美的代码猴子。

While companies will not want proprietary code on ChatGPT, I imagine building in-house replicas is already underway. With that said, generating new code compatible with a pre-existing codebase is significantly harder. There are fewer “right” answers compared to having 0 dependencies, but I trust this will be solved with time.  

虽然公司不希望在 ChatGPT 上使用专有代码，但我想构建内部副本已经在进行中。话虽如此，生成与现有代码库兼容的新代码要困难得多。与 0 依赖项相比，“正确”答案更少，但我相信这会随着时间的推移得到解决。

**As basic code execution gets commoditized, I expect the value pendulum to swing towards the “ideas guy”.** The “ideas guy” has been routinely mocked as someone who’s long on talk, short on action. But as the barrier between _ideating_ and _creating_ melts away, taking action becomes easier and faster, which makes a vibrant pipeline of ideas supremely valuable.  

随着基本代码执行的商品化，我预计价值钟摆会向“创意人”摆动。 “有想法的人”经常被嘲笑为长篇大论、缺乏行动的人。但随着构思和创造之间的障碍逐渐消失，采取行动变得更加容易和快速，这使得充满活力的创意管道变得极其有价值。

When I lived in San Francisco, I held [serious distortions](https://www.productlessons.xyz/article/silicon-valley-distortions) about what made a business valuable. Now that I’ve left the bubble and tasted the power of ChatGPT, two things are obvious:   

当我住在旧金山时，我对是什么让一家企业有价值持有严重的扭曲。既然我已经离开了泡沫并体验了 ChatGPT 的强大功能，有两件事是显而易见的：

1.  There are many people outside of tech with unique insights on problems worth solving  
    
    技术之外有很多人对值得解决的问题有独特的见解
    
2.  They tend to start service-based businesses because they don’t “know tech”, but as ChatGPT goes mainstream, more of them will be able to productize their service  
    
    他们倾向于开始基于服务的业务，因为他们“不懂技术”，但随着 ChatGPT 成为主流，他们中的更多人将能够将他们的服务产品化
    

In fact, “tech” is being demystified everyday. When I was in college, I never got into coding because I struggled to memorize syntax. Hunting for missing commas felt like 80% of the tortuous battle. Even when I could read basic code, I was still walled off from writing code.  

事实上，“技术”每天都在被揭开神秘面纱。当我上大学的时候，我从来没有接触过编码，因为我很难记住语法。寻找丢失的逗号感觉就像是曲折战斗的 80%。即使我可以阅读基本代码，我仍然无法编写代码。

Nowadays, if you can read code, you can definitely write code with ChatGPT and Codex. And if you can’t read code yet, you can get ChatGPT to translate code line-by-line into plain English. ChatGPT can be everyone’s free, real-time tutor.  

如今，如果你能阅读代码，你肯定可以用 ChatGPT 和 Codex 编写代码。如果您还不能阅读代码，您可以让 ChatGPT 将代码逐行翻译成简单的英语。 ChatGPT 可以成为每个人的免费实时导师。

In short, a new level of the game has opened up to all of us. It’s cheaper and faster than ever to build what you want. We can all do more with less.  

简而言之，一个新的游戏水平已经向我们所有人开放。构建您想要的东西比以往任何时候都更便宜、更快捷。我们都可以事半功倍。

One predictor for whether ChatGPT will reach median performance in your job is by looking at what’s shared online. ChatGPT is freakishly good at drafting code in large part because there’s a deep repository of code in places like Stack Overflow… and on every website ever made. Same goes for designs. Wherever there are large bodies of data to learn from, performance will eventually follow.  

预测 ChatGPT 是否会在你的工作中达到中等表现的一个预测因素是查看在线共享的内容。 ChatGPT 非常擅长起草代码，这在很大程度上是因为在 Stack Overflow 等地方以及曾经创建的每个网站上都有一个很深的代码存储库。设计也是如此。只要有大量数据可供学习，性能最终就会随之而来。

What is _not_ explicitly revealed online is intention. **We see what is launched, but we don’t see the core insight, the thousands of decisions made, and paths forgone to build a successful business.** This is why blind copying often backfires because you can only copy what you see, and reality has a lot of hidden details.  

网上没有明确透露的是意图。我们看到了发布的内容，但看不到核心洞察力、做出的数千个决策以及为建立成功企业而放弃的道路。这就是为什么盲目复制往往适得其反，因为你只能复制你看到的东西，而现实有很多隐藏的细节。

The _intention_ to build something, the focus to deliver on a promise worth paying for has been rare and valuable since the beginning of time. Intention sets us apart.   

自古以来，打造某样东西的意图，以及兑现值得付出的承诺的专注都是罕见而宝贵的。意图使我们与众不同。

The seed of intention is _attention_ — paying attention to the problems around us. Paying attention though is harder than ever because distractions are getting more addictive. I think the great struggle of our time is preserving our finite attention, so we can channel our intention and make progress, on our terms, using these new superpowers.  

意图的种子是注意力——关注我们周围的问题。注意力比以往任何时候都更难，因为分心越来越容易让人上瘾。我认为我们这个时代的伟大斗争是保持我们有限的注意力，因此我们可以引导我们的意图并根据我们的条件利用这些新的超级大国取得进步。

This newsletter grows because of you! 🤗 **Share with a friend, or if you’re new, subscribe below:**  

本期通讯因您而成长！ 🤗 与朋友分享，或者如果您是新朋友，请在下方订阅：

**[Finally, here’s my toolkit to grow your product career](https://www.product-toolkit.com/).** Get the shortcuts that took me years of work to figure out.  

最后，这是我用来发展你的产品事业的工具包。找到我花了多年时间才弄清楚的捷径。

[![](https3A2F2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com2Fpublic2Fimages2Fa1c9f27e-c35e-4241-9287-b77ac7baa74f_2498x1408.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fa1c9f27e-c35e-4241-9287-b77ac7baa74f_2498x1408.png)

As always, thank you for reading!  

一如既往，感谢您的阅读！

[\-Linda](https://twitter.com/thelindazhang)
