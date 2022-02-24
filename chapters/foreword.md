# 前言（Foreword）

*作者：Freek Van der Herten*

这是一件有趣的事情，在外行看来，IT 常常被看作是一门精确的科学。刚开始做开发人员时，经常听到有人说：“哦，你是做 IT 的，所以你一定擅长数学”。 我一直不明白，为什么一个擅长数学的人是修理打印机的合适人选。

当你有一些建立应用程序的经验时，你就知道 IT 不是一门精确的科学。对一个问题有多种有效的解决方案。找五个开发人员，问他们建立博客的最佳方法是什么。你可能会得到五个不同的答案。每个建议都会有自己权衡的一些东西。

在较低的层次上，需要做出许多有趣的选择，但没有明确的答案：

- 我们是否可以在控制器（controller）里发邮件？
- 这个概念怎么命名？
- 这条逻辑应该保存在哪里？
- 是否使用 final 来定义一个类？

这些问题没有明确的答案。这取决于几件事情：项目的规模，个别团队成员的偏好，以及团队达成的协议。

程序员对事情的处理方式都有各自的偏好。有些人喜欢非常严格地遵守 SOLID 规则来工作。其他人则倾向于更务实地工作。大多数开发者都会有不同。我把这看作是一个尺度。

也有不同类型的偏好。有些人考虑视觉债务，有些人则不在乎这个；有些人可能想坚持他们喜欢的框架的默认结构，有些人则喜欢使用自定义结构。

本质上没有对或错的方法。漂亮的、可维护的项目可以更实用地、更严格地构建。然而，大多数项目并不是由一个人构建或维护的。相反，有一群人参与其中，他们在严格/务实的尺度上都有不同的立场。

根据经验，我可以告诉你，让每个成员在一个项目上使用他们喜欢的风格并不是一个好主意。你很可能会得到一个编程规范不一致的项目，导致其难以增加功能或进行维护。

在一个运转良好的团队中，成员们会谈论和讨论他们每个人偏好的利弊。当达成共识时，最好把它写下来，同时说明选择某种方法的原因。这可以形成一套指南，供项目或团队的新成员参考。你可以在我们的网站上阅读我们的指南集。它包含了我们在细节上的约定，例如如何命名事物，以及如何使用某些 Laravel 功能.

你现在拿着的书是这些指南的延伸。你将了解到我们的团队是如何构建比一般项目更大的项目的。这本书中的内容是所有团队成员之间无数次讨论的结果。我们的团队已经建设并且正在建设多个大型项目。通过创建和维护这些项目，我们发现在哪些地方务实是安全的，在哪些地方坚持严格的方法往往是最好的。

我们认为我们的指南和这本书是一份活的文件。人、团队和意见都会随着时间的推移而变化。 不要死板的遵循你过去制定的规则，而是要不断挑战，新的经验应该指向新的规则和改进规则。

与其盲目地遵循书中分享的观点，我更鼓励你与你的同事讨论这些内容。也许你的团队成员更关注务实/严格之外的其他点，但是你与团队达成的约定应该反映这些。

我希望你会喜欢读这本书，并希望你能学到一些很酷的东西，能帮助你和你的团队建立更好的项目。