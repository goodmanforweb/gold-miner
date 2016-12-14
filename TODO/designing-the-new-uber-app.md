
> * 原文地址：[Designing the new Uber App](https://medium.com/uber-design/designing-the-new-uber-app-16afcc1d3c2e#.kaoghc61m)
* 原文作者：[Didier Hilhorst](https://medium.com/@didierh)
* 译文出自：[掘金翻译计划](https://github.com/xitu/gold-miner)
* 译者：[PhxNirvana](https://github.com/phxnirvana)
* 校对者：[Gocy](https://github.com/Gocy015), [Freya Yu](https://github.com/ZiXYu)

# 全新的 Uber 应用设计








![](https://cdn-images-1.medium.com/max/2000/1*7ocitrf1HvNFK8Hbo3FoOw.png)







大刀阔斧地（对当前应用）重新设计这种东西光是听起来就足以让人裹足不前。大量的变数和未知情况都暗示着这条道路上充满荆棘，甚至通向悬崖。但只要我们还想建设光明未来，就势必承担这风险。这意味着不仅要下血本重新设计界面外观，还要重新构思交互流程。

Uber 起初的愿景很简单。“轻触屏幕，即刻接驾。”无需设置目的地，无需选择套餐，只需轻轻一点，至多两次，就可以开启一段行程。

随着新功能的不断加入，我们的产品变得越来越复杂，我们不断地努力，试图保持最初一键式的简洁高效。后来我们意识到高效率绝不仅仅是减少点击和优化流程这么简单。人们总是在赶着去看电影时选择了错误的服务类型（对，就是你，Uber Pool）。通过选择合适接人地点来节省时间的这种机会就被生生错过了。

在一家快速增长的公司考虑未来道路是很有挑战性的。所以，为了走出我们先前的舒适区，我们决定用**“以终为始”**作为新 Uber 的设计理念。

有时为了更快的从 A 点到达 B 点，需要减速、抬头、观察前方。原先的 Uber 只让你考虑搭便车，而现在会问你“去哪儿？”（Where to go?）。

一切流程始于此并环绕它（Where to go）打造。下一步的界面元素飞入屏幕，并以动画的形式播放通往终点的路线。指引前进的是基于向前看的哲学理念。每一个动作都引领用户走向下一步，每一步结束时同样会带来反馈。当你打算开始一段行程时，一切都将水到渠成。







![](https://cdn-images-1.medium.com/max/2000/1*1xHu1vhKVvIx2SY-XdiF7A.jpeg)







一个关于体验的关键分歧是产品选择滑动条。一个好的界面有，呃，三到四个选项，至多八个，我们在洛杉矶和其他城市的司机可以证明这一点。（现实情况却）甚至更糟，当我们打开计划选项时，位置就不够用了，而且我们基本可以说是随意地把这个窗口扔在屏幕中间。

这项功能经历了最多的设计循环和迭代。从列表视图到表格视图再到分页视图及其之间的众多设计。用户调研和原型迭代在过程中扮演了重要角色。我们每天都带着用 Framer 和 Swift 建立的原型去人群中做调查。日复一日，周复一周地迭代，直到我们找到答案。我们发现人们并不关心我们能在一个屏幕上填满多少产品和特性。

通过对目的地的了解，我们可以在屏幕上显示最恰当的选项来提供让用户提供选择的机会。我们在（界面）最上层显示不同服务的费用，以此让用户可以简洁直观的选择到达方式。对于 Uber Pool 和 UberX 我们会显示到达时间来让你知道你能不能赶上晚餐订座的时间。






![](https://cdn-images-1.medium.com/max/2000/1*U6PKgfBbne-QQZJIWSOvew.jpeg)







就像期待的那样，应用总会先想一步来节省时间。它会在选择所需服务时搜索最佳搭车点。一旦提交请求，我们会马上显示可能的配对司机，并提供预估时间。

起初我们想建立一个其他人「能用、能建设、能扩展」的平台。这花了不少功夫，而且有着设计师、工程师、产品经理、运维、市场和其他各种人才的参与。边设计边创造一个全新的产品的确是个挑战，尤其是这么大的产品。

理想状况下你可能会选择先进行产品设计，再进行平台设计，但以我们进行的速度来说，这基本不可能。但这项限制，却最终成为了一个“美妙的意外”：它迫使我们不得不在敲定产品设计的同时应用相应的平台设计，并用真实数据开发。这让我想起了一个传奇赛车手的名言：

> “如果一切都在掌控中，那只能说明速度不够快。”——Mario Andretti.

我们在基础阶段就建立了一系列元素的标准，如间距、字体、颜色、内容、图标、图表、阴影、状态栏、动画以及用动作表单实现的警告框、头像、按钮、卡片、时间选择器、空状态、表格、标题、列表、地图、加载指示器、选择器和标签。但可能最重要的是，我们建立了和乘客交流的空间。







![](https://cdn-images-1.medium.com/max/2000/1*t_KgpnQ5C_CPhQxuXXCEtA.png)







我们曾以为用户走进车门时我们的工作就结束了，在那之后，（用户）越快关闭应用体验越好。但在审视每一步之后，发现我们忽略了旅程中最长的一部分：在路上。

我们考虑到了可能在路上听的音乐，目标饭馆的菜单，以及如何与将要见的人保持联系。（因此）我们建立了一个以旅客和旅程为中心的平台。







![](https://cdn-images-1.medium.com/max/2000/1*uX84vBZ06pGXvKnW0MZUPw.jpeg)







全新 Uber 应用是关于你，你的目标和你的目的地。我们以终为始，希望可以让你的下一次旅程到来的更早些。

特别鸣谢 Peter Ng，Bryant Jow，Nick Kruge 和 [Uber Design](https://medium.com/u/f0f8b53891a8) 的全体成员。除了设计之外，最值得称道的是和一群优异的工程师和产品经理共事的经历，正是他们的努力，才有了新 Uber 应用的诞生。设计并不止是设计师的职责，它关乎我们全体。我们工作的环境从一开始就有着一群以让用户更满意为目标的工程师和产品经理。如果（你）觉得这有趣的话，那就加入我们来一起设计更好未来吧——我们需要你的帮助。 [点这里](https://www.linkedin.com/in/dhilhorst)，让我们喝着咖啡携手共事吧。

年底，有着更多功能的更新会在全球各应用市场分批上线。 希望你和我们一样激动。如果你读到这里的话，可以看看下面介绍新应用的短视频：
<iframe width="1514" height="851" src="https://www.youtube.com/embed/I1DdoN6NLDg" frameborder="0" allowfullscreen></iframe>
[点这里](https://www.youtube.com/embed/I1DdoN6NLDg)（Youtube地址，需自备梯子）