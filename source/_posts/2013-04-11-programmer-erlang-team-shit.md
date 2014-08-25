---
layout: post
title: "程序员/erlang/团队/扯淡"
categories: [other]
tags: erlang
comments: true
published: false
keywords: erlang, 程序员
description: 关于我和erlang的故事竟然可以追溯到2009年的时候，在那个时候我还没有接触过任何函数式编程语言
---

关于我和erlang的故事竟然可以追溯到2009年的时候，在那个时候我还没有接触过任何函数式编程语言。当时我稍微看了下haskell，被那唬人的代码以及自己迟迟写不出一个应用的窘境吓倒了。关于haskell的事情不了了之，然后我开始看erlang的书。那个时候我已经开始使用google的svn服务在家里和公司之间中转文件，如今我找到里面依然放着两本erlang的电子书：<Programming Erlang>和<Erlang Programming>。

在我草草看到`concurrent programming`的章节时，我的领导开完会出来，坐在椅子上，不久后转过来问我正在做的事。我本以为那是一场争论我学习erlang是否有用的对话。我们该如何应用erlang到我们的服务器架构中，能带来哪些好处。但是，直到那场对话结束，我才渐渐明白，问题根本不在于erlang，而在于我花了大量工作时间在非工作的事务上。我想，我还不如偷偷看看八卦新闻，当嗅到领导的味道时迅速地ALT+TAB。对，我正在全神贯注地阅读项目代码，我是一个好员工。我缓缓神，嗯，我怎么在看resource.h文件。

我中断了erlang的学习。在后来的几年中，我也曾花了很多工作时间学习工作之外的技术知识，但大部分时候我真的是偷偷地。我没有耽误工作进度，但我还是偷偷地。我也不再和我的领导交流我正在学习的有趣的东西，因为即使是朋友，领导也有领导的立场。如果我的领导再来问问我学习的这些东西对我的工作有什么直接联系，好吧，我真的无法告诉他我正在写一个网站，这对于我们的游戏服务器有好处。

如今我也面临了这个团队管理问题。一个在上班时间里看八卦网页的程序员，会把这种团队臭味扩散出去，这当然不允许。但一个在工作完成的情况下学习其他技术的程序员，其行为却很难做出正确与否的判断。我个人鼓励这种自我提高的行为，至少，他不是一个仅仅把写程序当工作的程序员。但这样的行为放在工作时间，极有可能导致另一种工作重心的臭味。当学习工作之外的东西成为一种风气，我们能保证每个人都意识到工作的重心吗？更何况，一个不懂技术团队建设的老板怎么喜欢看到这样的情况？但另一方面，限制这种行为又会在一定程度上打击程序员的积极性，这是在暗示：工作就是工作，它和做技术不一样。

这个问题从某方面来看，其实和管理有很大关系。一直以来，我们都缺乏精确的项目计划管理。如果你仔细地单独和每个团队成员交流，你会发现每个人手头上的工作量差别是非常大的。软件开发的进度计算本来就不精确，再加上程序员在做这件事时的能力也无法量化，最后项目经理如果还不做仔细的项目计划，那么在某时间段里，就必然存在某些成员事情做完了，需要等待另一个程序员的模块。如果这是多部门之间的协作，那情况就更糟了。

这种人员之间工作负载程度不同的情况，还会导致另一个现象：加班。比加班更可怕的是，项目经理看不到项目的完成日期，为了保持团队的“一致性”，维护团队“凝聚力”，大家统一加班。你可别告诉我你没事，没事把那某某某模块重构了。噢，草，又是那个模块。

曾经有个程序员向我抱怨，他从项目开始到项目结束一直在负责一个模块。项目运营后，每个人都很清闲。于是他开始做他感兴趣的事，这个事和项目可以说还是较高相关的。他做了个DEMO，兴高采烈地交给领导看。领导一脸不屑，你上班时间做这个干嘛，你要感兴趣你回家做去。后来他还向领导提出想负责另一个模块的请求，保证原有工作内容不影响，所谓多劳多得，他说，不多要一分钱。但得到的答案依然是否。

我至今不明白一个好的技术团队该是怎样的。一个成员之间协作较久的团队，其工作能力肯定比一个刚组建的团队好。至少，成员之间的沟通成本相对较低。大部分程序员性格都比较内向，牛逼的程序员群里内向比例也必然更高。我发现一个新加入团队的程序员，即使你告诉他你面临的问题另一个程序员比较熟，他也很少主动去交流。大公司在人员招聘上，会对沟通能力考量得更多。但在年轻的程序员人群中，往往沟通能力强的反而技术真的很平庸。我相信人的大部分能力都跟后天有莫大关系。为什么你的沟通能力会比别人强，因为你有更大的社交圈，你花了更多的时间在社交上。一个沟通能力良好的程序员，可能在几年的技术钻研之后，变得不善言谈；一个沟通能力良好的程序员，也有可能在一个过度模式化或者过度清闲的公司里停滞不前（技术上）。去年的时候不少大公司裁了不少员工，今年年初的时候这些程序员就来我们这种小不垃圾的公司应聘。我一看简历，大公司两三年工作经验，研究生学历，再一看笔试情况，次奥，最后再看期望薪资，噢，草，请不起。这可不是个例。

当然，这些个例和预估数据真的就是个例和预估，我相信绝对有例外。

我从未在博客发类似本篇扯淡文章，因为一直以来我觉得我是一个喜爱技术的程序员。而在博客上大谈团队管理什么的跟我根本就不是一类人。噢，草，我忘了交代了。时隔3年时间，我竟然又开始学erlang了，因为我正在做一个类似SOA架构的项目，也许erlang比C++更适合干这事。

