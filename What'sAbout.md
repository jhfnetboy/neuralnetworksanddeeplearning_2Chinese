What this book is about?

Neural networks are one of the most beautiful programming paradigms ever invented. In the conventional approach to programming, we tell the computer what to do, breaking big problems up into many small, precisely defined tasks that the computer can easily perform. By contrast, in a neural network we don't tell the computer how to solve our problem. Instead, it learns from observational data, figuring out its own solution to the problem at hand.

Automatically learning from data sounds promising. However, until 2006 we didn't know how to train neural networks to surpass more traditional approaches, except for a few specialized problems. What changed in 2006 was the discovery of techniques for learning in so-called deep neural networks. These techniques are now known as deep learning. They've been developed further, and today deep neural networks and deep learning achieve outstanding performance on many important problems in computer vision, speech recognition, and natural language processing. They're being deployed on a large scale by companies such as Google, Microsoft, and Facebook.

The purpose of this book is to help you master the core concepts of neural networks, including modern techniques for deep learning. After working through the book you will have written code that uses neural networks and deep learning to solve complex pattern recognition problems. And you will have a foundation to use neural networks and deep learning to attack problems of your own devising.

A principle-oriented approach

One conviction underlying the book is that it's better to obtain a solid understanding of the core principles of neural networks and deep learning, rather than a hazy understanding of a long laundry list of ideas. If you've understood the core ideas well, you can rapidly understand other new material. In programming language terms, think of it as mastering the core syntax, libraries and data structures of a new language. You may still only "know" a tiny fraction of the total language - many languages have enormous standard libraries - but new libraries and data structures can be understood quickly and easily.

This means the book is emphatically not a tutorial in how to use some particular neural network library. If you mostly want to learn your way around a library, don't read this book! Find the library you wish to learn, and work through the tutorials and documentation. But be warned. While this has an immediate problem-solving payoff, if you want to understand what's really going on in neural networks, if you want insights that will still be relevant years from now, then it's not enough just to learn some hot library. You need to understand the durable, lasting insights underlying how neural networks work. Technologies come and technologies go, but insight is forever.

A hands-on approach

We'll learn the core principles behind neural networks and deep learning by attacking a concrete problem: the problem of teaching a computer to recognize handwritten digits. This problem is extremely difficult to solve using the conventional approach to programming. And yet, as we'll see, it can be solved pretty well using a simple neural network, with just a few tens of lines of code, and no special libraries. What's more, we'll improve the program through many iterations, gradually incorporating more and more of the core ideas about neural networks and deep learning.

This hands-on approach means that you'll need some programming experience to read the book. But you don't need to be a professional programmer. I've written the code in Python (version 2.7), which, even if you don't program in Python, should be easy to understand with just a little effort. Through the course of the book we will develop a little neural network library, which you can use to experiment and to build understanding. All the code is available for download here. Once you've finished the book, or as you read it, you can easily pick up one of the more feature-complete neural network libraries intended for use in production.

On a related note, the mathematical requirements to read the book are modest. There is some mathematics in most chapters, but it's usually just elementary algebra and plots of functions, which I expect most readers will be okay with. I occasionally use more advanced mathematics, but have structured the material so you can follow even if some mathematical details elude you. The one chapter which uses heavier mathematics extensively is Chapter 2, which requires a little multivariable calculus and linear algebra. If those aren't familiar, I begin Chapter 2 with a discussion of how to navigate the mathematics. If you're finding it really heavy going, you can simply skip to the summary of the chapter's main results. In any case, there's no need to worry about this at the outset.

It's rare for a book to aim to be both principle-oriented and hands-on. But I believe you'll learn best if we build out the fundamental ideas of neural networks. We'll develop living code, not just abstract theory, code which you can explore and extend. This way you'll understand the fundamentals, both in theory and practice, and be well set to add further to your knowledge.

#关于本书

+ 神经网络(算法框架)是迄今为止已发明的最优美的编程范本(范式)之一。在既有的编程方式中,我们告诉电脑如何去做，把大的难题切分为许多电脑可执行的、精确定义的任务。相对而言，在神经网络中我们不会告诉电脑如何解决(我们)的问题，取而代之的是，它从观察数据中学习，亲手搞清楚自己的解决方案。

+ 自动化学习听起来很有前途。但是，直到2006年，除了一些特定问题领域，我们还不知道如何训练神经网络如何超越更多的传统途径。直到2006年一个所谓的深度神经网络学习技术的发现。这项技术现在叫深度学习。它们已经得到了进一步发展，今天深度神经网络和深度学习在计算机视觉、语音识别和自然语言处理许多重要的问题突出表现。已被公司如谷歌，微软和Facebook展开大规模的应用。

+ 这本书的目的是帮助你掌握神经网络，包括深度学习现代技术的核心概念。通过这本书，你就可以通过你的编码，使用神经网络和深度学习来解决复杂的模式识别问题。你将为使用神经网络和深度学习来攻克你自己的设计规划问题奠定扎实的基础。

+ 一种面向原理的方法

+ 一个信念本书根本的是，它是更好地获得的神经网络和深度学习，而不是想法很长的洗衣清单的朦胧认识的核心原则有充分的了解。如果你已经理解的核心思想好，你可以迅速了解其他新材料。在编程语言方面，认为它是掌握一门新语言的核心语法，库和数据结构。你可能仍然只是“知道”的语言总额的一小部分 - 许多语言都有巨大的标准库 - 但新库和数据结构可以快速，容易地理解。

+ 这意味着，这本书显然不是在如何使用一些特定的神经网络图书馆的教程。如果你主要是想了解周围库中的方式，不读这本书！您可以透过教程和文档您想了解图书馆，和工作。但被警告。虽然这有一个直接的解决问题的回报，如果你想了解到底发生了什么在神经网络，如果你想要的见解，仍将是相关年内从现在开始，那么它不够只是为了学习一些热点库。你需要了解的耐用，持久的见解如何神经网络工作的基本。技术来和技术去，但洞察力是永恒的。



