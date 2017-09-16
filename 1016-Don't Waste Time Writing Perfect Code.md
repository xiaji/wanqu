# Don't Waste Time Writing Perfect Code

Source: https://dzone.com/articles/dont-waste-time-writing

湾区日报 [2017/09/14 第1016期](https://wanqu.co/issues/1016?s=/issues)

一些代码的重要性确实是更高。那是什么样的代码呢？在系统里最重要也是最核心的代码，我们需要不断的改变，重构。当你对系统的代码更熟悉，就会更快的发现和判断哪些代码一直在改变，哪些不是；哪些重要，哪些不是。在工作中确实是如此，当对一个项目熟悉了，才会知道从哪里入手去改代码；最基本的工作就是增加一些功能以及修改出现的bug。一些代码需要改么？要看是否重要，是否能提高performance。一些边角料的修改是否有必要，即使有时间这些代码重构的优先级是否排在前面？工作里什么最重要，看文章第二段就是最好的实践策略。

我们是否要写完美代码？no，代码的第一要素clean and simple，可读性高！但是如果因为这个标准，要求自己必须写出beautiful and elegant的完美代码，这个有必要吗？具体问题具体分析，如果代码不需要经常性的重构，那就不需要要求完美，只需要正确和可读性高。因为这部分的代码会伴随系统的使用被你现在和将来的同事使用。这种代码不需要polished抛光（很形象的用词），不需要重构，甚至当调用这些代码的部分在重构时，我们都可以忽略它，这些代码是我们最不需要花费多余时间的，压根就没有优先级。

对于那些经常要更改的代码，我们也不需要一步到位想到最好的解法，因为它会一直在变，可能是需求上的，也可能是业务逻辑上的，甚至会重写。这时候重构就更适合，每次重构比代码有进步就好。但是这并不重要。

重要的是代码正确，实用和有效的完成了它需要做的事。对待错误和坏的数据是否有操作而不会造成系统的崩溃，或者用户友好的错误提示。debug是否简单，修改代码简单且安全。这些并不是完美代码的内容，但是这是实用的工程方法，保证系统的成功。也是工作中我们应该关心自己代码质量的真正方面。

不要浪费时间在不重要的事情上面，不管是生活中还是工作上都是如此。在重构，code review上都应该focus on important parts。is the code correct? is it defensive? is it secure? can u follow it? is it safe to change? 测试更重要，是否覆盖了主要的流程和边界，特殊例外的cases。不管是ttd还是先写代码后测试的老路子，测试都要写。

good code:  code that is understandable, correct, safe and secure. We need to refactor and review it, and write good useful tests, all the while knowing that some of this code, or maybe all of it, could be thrown out soon, or that it may never be looked at again, or that it may not get used at all. 

需要发现我们的代码有些确实是垃圾，需要我们去改进。做我们必须做的，剩下的不要touch。不要浪费时间在完美代码上。