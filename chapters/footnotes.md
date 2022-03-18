# 脚注（Footnotes）

在这一章中，我想列出多年来塑造我对代码架构思想的所有灵感来源。这些资源对本书的写作产生了深刻的影响。

如你所知，我所写的大多数想法都不是我自己的。我是在与几个开发人员友好工作中和多年积累的知识基础上写的。现在你已经读完了这本书，还有很多优秀的资料可以让你阅读、观看和学习。

## Gary Bernhardt 对类型系统的看法（Gary Bernhardt's thoughts on type systems）

[https://www.destroyallsoftware.com/talks/ideology](https://www.destroyallsoftware.com/talks/ideology)

不是每个人都和我一样喜欢强类型系统。Gary Bernhardt 有一个关于这两类人之间差异的精彩演讲。

## Matthias Noback 谈论值对象和 DTO 的区别（Matthias Noback on the difference between value objects and DTOs）

[https://github.com/spatie/data-transfer-object/issues/17](https://github.com/spatie/data-transfer-object/issues/17)

起初，我把 DTO 称为『值对象』，但其含义略有不同。Matthias 非常友好地打开一个 GitHub thread 来讨论这些区别。

## Alan Kay 对 OOP 的看法（Alan Kay's vision of OOP）

[https://www.youtube.com/watch?v=oKg1hTOQXoY](https://www.youtube.com/watch?v=oKg1hTOQXoY)

Alan Kay，这个 `OOP` 的提出者解释了他对『面向对象』最初的看法。这个讲座高度影响了我对使用面向对象（OO）语言编程的思考。

## Freek Van der Herten 写的用 Action 重构（Refactoring to actions by Freek Van der Herten）

[https://freek.dev/1371-refactoring-to-actions](https://freek.dev/1371-refactoring-to-actions)

这些年来，我们在 Spatie 的项目中应用了本书所描述的原则；Freek 探讨了如何将老项目重构为面向领域的设计。

## Martin Fowler 谈论事务脚本（Martin Fowler on transaction scripts）

[https://martinfowler.com/eaaCatalog/transactionScript.html](https://martinfowler.com/eaaCatalog/transactionScript.html)

由 Martin Fowler 描述的事务脚本是 Action 的基础。

## Martin Fowler 谈论贫血领域模型（Martin Fowler on anemic domain models）

[https://martinfowler.com/bliki/AnemicDomainModel.html](https://martinfowler.com/bliki/AnemicDomainModel.html)

Martin Fowler 也写了关于贫血模型的文章，以及它是如何成为一种反模式的（anti-pattern）。我的观点更倾向于 Alan Kay 的观点：分别表示过程和数据，并让它们一起工作。

## Tim MacDonald 写的自定义 eloquent 集合（Custom eloquent collections by Tim MacDonald）

[https://timacdonald.me/giving-collections-a-voice/](https://timacdonald.me/giving-collections-a-voice/)

Tim MacDonald 给出了关于定制 eloquent 集合的灵感；这种模式我们至今仍然喜欢。

## Tim MacDonald 写的独立查询构造器（Dedicated query builders by Tim MacDonald）

[https://timacdonald.me/dedicated-eloquent-model-query-builders](https://timacdonald.me/dedicated-eloquent-model-query-builders)

Tim 还更深入地写了关于独立查询构造器的文章。

## Christopher Okhravi 深入解释了状态机（Christopher Okhravi explains state machines in depth）

[https://www.youtube.com/watch?v=N12L5D78MAA](https://www.youtube.com/watch?v=N12L5D78MAA)

如果你对状态模式仍不太理解，Christopher Okhravi 在这段视频中进行了详尽的解释。

## Symfony 的工作流程包用于构建复杂的状态机（Symfony's workflow package to build complex state machines）

[https://symfony.com/doc/current/workflow/workflow-and-state-machine.html](https://symfony.com/doc/current/workflow/workflow-and-state-machine.html)

Symfony 的工作流程包是我写的简化状态包的一个很好的替代品。

## Sandi Metz 对真正的 OO 代码的看法（Sandi Metz's vision of truly OO code）

[https://www.youtube.com/watch?v=29MAL8pJImQ](https://www.youtube.com/watch?v=29MAL8pJImQ)

在谈到面向对象的编程时，又一次大开眼界：Sandi Metz 展示了如何摆脱所有的 if 语句，以及这些与 OO 有什么关系。

## Freek 写的开始使用面向领域的 Laravel（Freek gets started with domain-oriented Laravel）

[https://freek.dev/1486-getting-started-with-domain-oriented-laravel](https://freek.dev/1486-getting-started-with-domain-oriented-laravel)

由 Freek 撰写的另一个面向领域的 Laravel 的实用介绍。

## Tighten 对模型工厂的做法（Tighten's approach to model factories）

[https://tighten.co/blog/tidy-up-your-tests-with-class-based-model-factories](https://tighten.co/blog/tidy-up-your-tests-with-class-based-model-factories)

Spatie 和 Tighten 同时提出了一个类似的方法来改进测试工厂。阅读他们的方法也很有趣。

## Spatie packages

[https://spatie.be/open-source](https://spatie.be/open-source)

在过去的几年里，我们工作室编写了许多软件包用于改进面向领域的 Laravel 工作流程。

- [spatie/data-transfer-object](https://github.com/spatie/data-transfer-object)
- [spatie/laravel-query-builder](https://github.com/spatie/laravel-query-builder)
- [spatie/laravel-view-models](https://github.com/spatie/laravel-view-models)
- [spatie/laravel-model-states](https://github.com/spatie/laravel-model-states)
- [spatie/enum](https://github.com/spatie/enum)
- [spatie/laravel-enum](https://github.com/spatie/laravel-enum)
- [spatie/laravel-queueable-action](https://github.com/spatie/laravel-queueable-action)

## 链接

- [目录](../README.md)
- 上一章：[尾言（In closing）](in-closing.md)
