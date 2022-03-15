# 脚注（Footnotes）

In this chapter I'd like to list all the sources of inspiration that shaped my vision over the years on code architecture. These resources influenced the writing of this book.

As you know, most ideas I've written about aren't my own. I built upon the great work of several developers and years of knowledge. Now that you've finished this book, there's still lots of great material that you can read, watch or learn.

## Gary Bernhardt's thoughts on type systems

[https://www.destroyallsoftware.com/talks/ideology](https://www.destroyallsoftware.com/talks/ideology)

Not everyone shares my preference for strong type systems these days. Gary Bernhardt has a fantastic talk about the differences between these two groups of people.

## Matthias Noback on the difference between value objects and DTOs

[https://github.com/spatie/data-transfer-object/issues/17](https://github.com/spatie/data-transfer-object/issues/17)

Originally, I called DTOs "Value Objects", which have a slightly different meaning. Matthias was so friendly to jump into a GitHub thread to discuss the differences.

## Alan Kay's vision of OOP

[https://www.youtube.com/watch?v=oKg1hTOQXoY](https://www.youtube.com/watch?v=oKg1hTOQXoY)

Alan Kay, who invented the term OOP, explains his original vision of "objectoriented". This talk highly influenced how I think about programming in an OO language.

## Refactoring to actions by Freek Van der Herten

[https://freek.dev/1371-refactoring-to-actions](https://freek.dev/1371-refactoring-to-actions)

Over the years, we applied the principles described in this book in the projects of Spatie; Freek explores how to refactor old projects to a domainoriented design.

## Martin Fowler on transaction scripts

[https://martinfowler.com/eaaCatalog/transactionScript.html](https://martinfowler.com/eaaCatalog/transactionScript.html)

Transaction scripts, described by Martin Fowler, are the basis of actions.

## Martin Fowler on anemic domain models

[https://martinfowler.com/bliki/AnemicDomainModel.html](https://martinfowler.com/bliki/AnemicDomainModel.html)

Martin Fowler also writes about anemic models, and how it's an anti-pattern. My vision leans closer to Alan Kay's: represent processes and data separately, and have them work together.

## Custom eloquent collections by Tim MacDonald

[https://timacdonald.me/giving-collections-a-voice/](https://timacdonald.me/giving-collections-a-voice/)

Tim MacDonald gave the inspiration about using custom eloquent collections; a pattern we still enjoy to this day.

## Dedicated query builders by Tim MacDonald

[https://timacdonald.me/dedicated-eloquent-model-query-builders](https://timacdonald.me/dedicated-eloquent-model-query-builders)

Tim also wrote more in-depth about dedicated query builders.

## Christopher Okhravi explains state machines in depth

[https://www.youtube.com/watch?v=N12L5D78MAA](https://www.youtube.com/watch?v=N12L5D78MAA)

If you're still unsure about the state pattern, Christopher Okhravi explains it thoroughly in this video.

## Symfony's workflow package to build complex state machines

[https://symfony.com/doc/current/workflow/workflow-and-state-machine.html](https://symfony.com/doc/current/workflow/workflow-and-state-machine.html)

Symfony's workflow package is an excellent alternative to the simplified state package I wrote.

##  Sandi Metz's vision of truly OO code

[https://www.youtube.com/watch?v=29MAL8pJImQ](https://www.youtube.com/watch?v=29MAL8pJImQ)

Another eye-opener when it comes to object-oriented programming: Sandi Metz shows how to get rid of all if statements, and what it has to do with OO.

## Freek gets started with domain-oriented Laravel

[https://freek.dev/1486-getting-started-with-domain-oriented-laravel](https://freek.dev/1486-getting-started-with-domain-oriented-laravel)

Another practical introduction to domain-oriented Laravel by Freek.

## Tighten's approach to model factories

[https://tighten.co/blog/tidy-up-your-tests-with-class-based-model-factories](https://tighten.co/blog/tidy-up-your-tests-with-class-based-model-factories)

Both Spatie and Tighten came up with a similar approach to improved test factories at the same time. It's interesting to read about their approach as well.

## Spatie packages

[https://spatie.be/open-source](https://spatie.be/open-source)

Over the past years, numerous packages have been written at our office to improve our domain-oriented Laravel workflow.

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
