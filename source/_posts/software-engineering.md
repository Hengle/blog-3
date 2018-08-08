---
layout: post
title: 乱七八糟的软件工程助教总结
date: 2013/6/7
---

其实本来研究生阶段我是不准备做任何社工活动⊙﹏⊙b 上学期的时候忘了具体啥事，好像是在微博上和刘老师聊了几次，她表示“嗯下学期来做助教吧”，嗯然后我就成为了软工课的助教，负责整个大作业部分，嗯嗯<del>坑</del>帮助学弟义不容辞^_^

<!--more-->

# 最早的题目

其实一开始我编了俩题目，其中一个我现在自己也想不起来了(╯‵□′)╯︵┻━┻，还有一个题目是做一个文本编辑器(实现大文件载入、语法高亮、正则搜索等等)。不过后来在定题目的时候正好看到36kr上面的friendcode的新闻，刘老师说这个挺有意思的，做这个吧！然后，然后大家就都知道了

# 为什么出这样一个题目

嗯其实软工这门课的价值，我自己也是在外面团队接触真实项目之后才有了很多感触的，单纯的授课确实<del>意义不大</del>没那么大意义(嗯其实差不多意思→_→)。通过这样一个题目，主要是想给大家一个机会来提前体会一个完整项目的流程，多体会一些软件课堂上讲的内容~因此这次的题目和以往有不同之处

- 实现方法、使用技术不作任何限制，大家自由选择(但这句话背后的意义是如果出了问题是大家自己的事...)
- 在工作量上严格限制：本身这样一个功能单一的网站，包括代码编辑器、编译运行模块都推荐大家去使用开源模块，协同编辑部分也有不少成熟的开源项目以及资料供参考，因此可以和前几届相比工作量确实降低了很多。我的观点是只要大家不同类型的坑踩一遍就行了，没必要用逼着大家反复跳...
- 本身这个题目也有点意思，实现一个协作编程的系统还是挺有成就感的
- 争取这样一个大作业包含各方面的知识点，如前端页面、数据库、网络通信、运营维护等杂七杂八的内容，不用很深入但是让大家知道所学知识之价值

# 被坑的助教

出于难度考虑，我暑假在家的时候被分配了一个光荣而又艰巨的任务：实现一个协同编辑原型系统，体会下难度级别以及可能遇到的问题o(╯□╰)o当时主要看了2份开源项目的核心代码，外加一堆wiki+blog+论文，花了一周搞出符合基本要求的原型系统……基本上调试JS调的快吐了。之后测试组的性能测试等我也都搞过保证至少能有难度不过高……蛋疼的不能自已

# 被坑者必坑人

当然了，作为TA最好玩的地方不是被坑而是坑别人oy(不要在意细节 逃) 其实最早设计题目的时候有两个点是留作坑的，虽然最后都没用上T T

* 最早需求上只写文字聊天，等期中的时候给大家追加语音/表情聊天的功能；这点主要是想考察大家的架构可扩展性【需求变更赛高！】
* 第二次迭代前一周提供一次“提前检查”的机会，并给与bonus；这个主要是考察大家的计划安排的合理性
* 不同组成员之间互查代码并新加功能，例如SSSTA去在OCD基础上加一个语音聊天功能；OCD去codechoir上加一个……不过要真这样我估计大家就会互喷噗~

嗯虽然比较可惜这两点都没用起来，但是由于鄙人工作失误，第二次迭代检查变成了一次“突击检查”，在没有特意准备ppt的情况下看到了每组的真实进展【喂喂别抽我o(>﹏<)】

# 开发人员的天敌——测试人员

这学期还有一个很好玩的地方就是，终于把测试课和软工课给同步起来了【我印象中8字班就有这个说法，不过一直没搞起来】因为课程的安排，这学期的软工进度其实一直算挺快的，基本迭代贰（刚过期中没多久）就所有功能性的东西完成了，小孩挺厉害的都O(∩_∩)O~

通过测试，主要还是让大家了解一下真实开发过程。开发人员自己测试东西会有很多盲区性的地方，但是别人一用就会遇到很多奇奇怪怪的bug了~测试课的时候大家都在吐槽开发组，开发组的时候有在吐槽测试组，真是无比<del>火药味</del>和谐的场景啊！<del>我想这时候把大家放在一个教室肯定是棒♂极了！</del>

八卦环节：某个下午我在bugfree上围观邓毓楠组vs司徒组，就看到邓毓楠他们在狂加bug，然后司徒他们在狂修……到最后是一堆won't fix和by design……真是两组人战斗的如火如荼啊23333

# 作为助教的一些失误

嗯作为助教这学期也犯了一些错误（嗯要是有想对我吐槽的可以留言或者发邮件，记得勾上<b>悄悄话</b>就行……），在这里简单总结一下

- 最开始对大家知识储备估计的有些错误，基础知识及框架介绍还是过少，导致有的相对技术比较薄弱的组吃亏【当时考虑的是希望大家的框架选择有足够的多样性，不要最后变成我讲了什么大家就用什么的情况】
- 迭代一之后各个组的进展都或多或少的超出我期望，因此迭代二过程中并没有保持足够的关注，之后迭代二检查的时候明显感到有些组的进度落下了不少进度
- 和每个组的沟通交流还有所欠缺，迭代1之后有几组完全更换了原有框架，也有组在更换框架之后一直没有赶上进度~如果最早和每个组长交流一下进度和框架，能够减少类似情况发生
- 讲东西过快导致有点讲不清=。=这个被刘老师也批评过，我讲东西的时候很容易讲快+讲不清，不少被我潜意识误认大家都了解的知识点我就会跳过，最后变成只有几个人能跟上的情况

# 给大家的一些建议

同样的，这样一个学期下来，作为助教也有一些建议提供给大家

- 灵活使用各种开源项目和现有资源，即“现有的轮子”。但使用的过程中，切记不要只停留在“用”的基础上，如有可能看看具体的代码实现，或者在解决问题的过程中直接hack现有代码。毕竟大家还没有到不得不自己实现具体东西的情况(例如极端追求性能的环境)，使用现有的东西能极大提高开发效率~
- 学会掌握各种工具，如源代码管理的svn/git等，有小组就提到用rollback来恢复改崩的代码~有人问过如何将代码上传到虚拟机，其实这个用svn就一行命令svn update搞定了啊 摔-。- 
- 希望大家养成任何时刻都保持一份可用代码的习惯，就算重构代码或者大改，在没有确认可用的情况下就不要合并到主分支~像“我们前段时间在重构导致现在不能看”这种理由就不应当存在
- 学会问问题，熟练掌握stackoverflow, google查找答案能力（请用英文谢谢~）
- 掌握一定的linux使用能力，包括基本的命令行，常见的软件包等~不要求大家有很强的运维能力，但是搭一个网站并学会看看log，改改配置还是挺有价值的技能
- 掌握新知识的能力，以及偷懒的能力=。=像svn之类的东西都有现成的GUI客户端，我确实无法理解为什么最简单的commit/update会觉得hold不住……千万不能有畏难的心理
- 没事多看一些技术博客、业内新闻，多涨涨姿势总是好的

吐槽：测试课的性能测试环节分享了两个现有的开源测试工具jmeter和dagger，然后最后有的测试组吐槽这个工具这里不适合那里不适合……千万不要有这种心态！什么不适合你就直接改就行了，有现成的代码不是么？我知道有的组就在dagger上扩展了双击事件、键盘事件等~使用工具是好的，但是不要<b>只会用工具</b>就行了！

# 总结

(嗯这一定不是官方口吻喂喂……)希望大家这一学期下来，能在项目过程中不仅仅是写了多少行的代码，更多的是对项目本身的思考：团队建设上有什么体悟，有什么可以避免的问题和改进的地方；技术框架上走过什么弯路，为什么一开始没能调研到或者如何进行避免；用户交互上有什么可以感觉的地方，不会让新用户(非开发者)觉得摸不到头脑；文档描述是否清晰，和测试人员的沟通是否足够了；代码管理是否恰当，能不能任意时刻都有一份可以用的代码；运营维护是否用心，服务能否自动的启动；有没有发现之前学习的其他课程知识的价值……

希望这样一个尽可能模拟真实环境下的开发项目，能给大家不同于以往大作业的体验oy

【话说我真是越来越能扯了……想当年高考写800字作文都能憋死我。。。不bibi了拖走了……