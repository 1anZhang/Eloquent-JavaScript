{{meta {load_files: ["code/intro.js"]}}}

# 简介

{{quote {author: "Ellen Ullman", title: "Close to the Machine: Technophilia and its Discontents", chapter: true}

We think we are creating the system for our own purposes. We believe
we are making it in our own image... But the computer is not really
like us. It is a projection of a very slim part of ourselves: that
portion devoted to logic, order, rule, and clarity.

quote}}

{{figure {url: "img/chapter_picture_00.jpg", alt: "一张螺丝刀和电路板的图片", chapter: "framed"}}}

这是一本关于计算机的书，如今，计算机就像螺丝刀一样常见，但是它会复杂一些，让计算机做你所想的事并不是那么容易。

如果你想要执行的任务是一个简单常见的任务，比如显示你的电子邮件或者使用计算器进行计算，你可以使用现成的应用。但是对于一些独一无二的或开放式的任务，可能就没有现成的应用供你使用了。

这时候编程就有了用武之地，_编程_ 是构造应用程序的 _过程_——通过一组精确的指令告诉计算机应该做什么。
因为计算机是笨拙而愚蠢的生物，所以编程从根本上来说就是无趣而又让人沮丧的东西。
当然，如果你能够克服这些问题，甚至能够享受与呆板的机器打交道的乐趣，那你则可以从中收货许多。
计算机能够在几秒钟内计算完人这一辈子都无法手工完成的计算，并且你能从中提升你的逻辑思维。

{{index [programming, "joy of"], speed}}

大多数编程都是使用编程语言来实现的。 _编程语言_ 是一种人工构造的用来指导计算机的语言。
有趣的是，目前我们所发现的，和计算机进行沟通的最有效的方式，在很大的程度上借鉴了人与人之间的沟通方式。
像人类语言一样，计算机语言也有单词和短语，能够进行组合表达更多的概念。

{{index [JavaScript, "availability of"], "casual computing"}}

在20世纪80年代和90年代的BASIC和DOS提示符，是与计算机交互的主要方法。
之后，它们在很大程度上被可视化界面所取代，可视化界面更容易学习，但自由度更小。
但是编程语言仍然存在，其中一种语言就是JavaScript，它内置在每个现代web(浏览器)中，因此几乎在每个设备上都可以执行。

{{indexsee "web browser", browser}}

这本书将试图让你足够熟悉这门语言，用它来做一些有用和有趣的事情。

## 编程

{{index [programming, "difficulty of"]}}

除了解释JavaScript，我还将介绍编程的基本原理。事实证明，编程是有一些困难的。
基本规则简单明了，但建立在这些规则之上的程序往往足够复杂，以至于会引入它们自己的规则和复杂性。
当你建造迷宫时，在某种程度上，你可能会迷失在其中。

{{index learning}}

这本书可能会让你感到沮丧。如果你是编程新手，那么你需要消化很多许多新内容。
然后，你需要把这些内容建立额外的联系，并把他们 _组合_ 在一起。

你可以自己选择你所要做出的努力。当你在阅读过程中遇到困难，不要轻易对自己的能力下结论。
这都是正常的，你只需要坚持下去。休息一下，重新阅读一下之前的内容，确保你阅读并理解示例程序和练习。
学习非常的辛苦，但是学到的一切都是你自己的，并且为之后的学习奠定坚实的基础。

{{quote {author: "Ursula K. Le Guin", title: "The Left Hand of Darkness"}

{{index "Le Guin, Ursula K."}}

When action grows unprofitable, gather information; when information
grows unprofitable, sleep.

quote}}

{{index [program, "nature of"], data}}

一个程序包含很多东西。包含一段由程序员输入的文本，它是计算机进行运算的直接指示，
包含计算机内存中的数据，也包含在同一内存中执行的动作。试图将程序与我们熟悉的对象进行比较往往是不够的。
看起来最合适的类比应该是是机器——他有许多独立的模块，要使整个系统运转起来，
我们必须考虑这些模块如何相互连接，以及它们在整个系统中是如何发挥作用的。

计算机是一台物理机器，充当这些非物质机器的主机。计算机本身只能做一些简单而直接的事情。
但是它们能够以难以置信的速度来完成这些事情。一个程序可以巧妙地融合大量这些简单的动作来做非常复杂的事情。

{{index [programming, "joy of"]}}

程序是思维的建筑。它的制造成本低，重量轻，通过双手就能很轻易的搭建。
但是如果不加以注意，程序的大小和复杂性就会失去控制，最终连创建它的人也会感到困惑。
如何使程序处于受控状态是编程的主要问题。当一个程序正常工作时，它是优秀的。
如何控制程序的复杂性是编程的艺术。伟大的程序通常能够化繁为简。

{{index "programming style", "best practices"}}

一些程序员相信，在他们的程序中，只使用一些特定的很好理解的技术就可以很好的管理程序的复杂性。
他们制定了严格的规则，称之为“最佳实践”，规定项目应该有的形式，并小心地使程序保持在安全的小范围内。

{{index experiment}}

这有些无趣，而且效率低下。新的问题往往需要新的解决方案。
编程领域还很年轻，而且仍在迅速发展，而且它的多样性足够支撑各种各样的方式去实现功能。
在设计程序的时候，你可能会犯很多糟糕的错误，你不应该去规避他，只有犯了错误你才能够理解的更加深刻。
优秀的程序是在实践中不断学习和优化的，而不是通过特定的规则来限制的。

## 为什么编程语言如此重要

{{index "programming language", "machine code", "binary data"}}

在计算机刚出现的时候，是没有编程语言的。程序通常是下面这样的：

```{lang: null}
00110001 00000000 00000000
00110001 00000001 00000001
00110011 00000001 00000010
01010001 00001011 00000010
00100010 00000010 00001000
01000011 00000001 00000000
01000001 00000001 00000001
00010000 00000010 00000000
01100010 00000000 00000000
```

{{index [programming, "history of"], "punch card", complexity}}

这个程序的功能是从1加到10并输出结果:`1 + 2 + ... + 10 = 55`。
它可以在一个简单的、假设的机器上运行。
在早期的计算机编程中，你需要在正确的位置设置大量的开关阵列，或者在纸板上打孔，然后把它们输入计算机。
你可以想象这个过程是多么的无趣和易错。
即使是编写简单的程序，也需要聪明的大脑和大量的训练。很难想象如何实现一个复杂的程序。

{{index bit, "wizard (mighty)"}}

当然，手动输入这些二进制序列，让程序正确运行，确实可以让程序员感觉到自己拥有强大的魔法。 
就满意度和成就感而言，这是值得的。

{{index memory, instruction}}

上一段程序中的每一行都包含一条计算机指令，翻译成中文如下：

1. 将数字0存储在内存位置0中。
2. 将数字1存储在内存位置1中。
3. 将内存位置1的值存储在存储位置2中。
4. 将内存位置2中的值减去11。
5. 如果内存位置2中的值为数字0，跳转到9。
6. 将内存位置1的值添加到内存位置0。
7. 内存位置1的值加1。
8. 跳转到3。
9. 输出内存位置0的值。

{{index readability, naming, binding}}

尽管这已经比二进制序列更易读了，但它仍然相当晦涩。 使用名称来替代指令位置和内存位置会让程序更加易读。

```{lang: "text/plain"}
 给“total”赋值0.
 给“count”赋值1.
[循环]
 给“count”赋值“compare”.
 给“compare”减11.
 如果“compare”为0, 跳出循环到[结束].
 给“total”加上“count”.
 给“count”加1.
 继续[循环].
[结束]
 输出 “total”.
```

{{index loop, jump, "summing example"}}

我们再来看看这段代码的含义? 前两行给出两个内存位置的初始值：`total`将用于建立计算结果，
而`count`将跟踪我们当前正在查看的数字。 使用`compare`的行可能不好理解。 
该程序根据`count`是否等于11来决定程序是否可以停止运行。 
因为我们的假设机器是相当原始而简陋的，所以它只能测试数字是否为零，并由此作出判断。 
因此，它使用标记为`compare`的内存位置来计算`count - 11`的值，并根据该值进行决策。
接下来的两行在程序确定`count`尚未为11时，将`count`的值添加到结果中，并将`count`的值增加1。

下面是使用JavaScript语言实现的同样的功能：

```
let total = 0, count = 1;
while (count <= 10) {
  total += count;
  count += 1;
}
console.log(total);
// → 55
```

{{index "while loop", loop, [braces, block]}}

此版本有了很多改进。最重要的一点是，我们无需指定程序来回跳转的方式。 
`while`指令解决了这个问题。 只要给出的条件成立，它将继续执行块中的内容（用大括号括起来）。 
该条件为`count <= 10`，表示“_count_ 小于或等于10”。 
我们不再需要创建一个临时值并将其与零进行比较，这只是一个无趣的细节。
编程语言的部分力量在于，它们可以为我们屏蔽大量无趣的工作。

{{index "console.log"}}

在程序的末尾，即`while`指令完成之后，将会有`console.log`操作用于打印结果。

{{index "sum function", "range function", abstraction, function}}

最后，如果我们碰巧有便利的方法`range`和`sum`，
分别用来创建指定范围内数字的集合和计算一组数字的总和，那么程序最终看起来会是这样的：

```{startCode: true}
console.log(sum(range(1, 10)));
// → 55
```

{{index readability}}

上面这些内容的意义是，同一个程序可以用长或短，不可读或可读的方式表示。
该程序的第一个版本非常晦涩，而最后一个版本几乎是英文的：`log` 1到10的数字范围的`sum`。
（我们将在[后续章节](data) 中学到如何定义`sum`和`range`之类的操作。）

{{index ["programming language", "power of"], composability}}

好的编程语言允许程序员在更高的层次对程序的执行进行讨论。
它有助于省略细节，提供方便的构建块(如`while`和`console.log`)，
允许你定义自己的构建块(如`sum`和`range`)，并使这些块易于组合。

## JavaScript是什么?

{{index history, Netscape, browser, "web application", JavaScript, [JavaScript, "history of"], "World Wide Web"}}

{{indexsee WWW, "World Wide Web"}}

{{indexsee Web, "World Wide Web"}}

JavaScript是1995年引入的，它可以给Netscape浏览器中的网页添加程序代码。目前，此语言已被所有其他主要的Web浏览器采用。 
JavaScript为开发现代应用程序成为了可能——无需重新加载页面，你就可以与应用程序进行交互。
此外，JavaScript还用于更传统的网站中，以提供各种形式的交互性和智能性。

{{index Java, naming}}

值得注意的是，JavaScript与名为Java的编程语言几乎没有任何关系。
选择这个名字主要是出于营销考虑而不是理性的判断。
在JavaScript出现时，Java已经是一个被广泛使用的编程语言了，它借此蹭了Java的热度。
有人认为这种尝试是个好主意。 但是现在我们会因为这个名字而感到困扰。

{{index ECMAScript, compatibility}}

在Netscape之外的浏览器支持JavaScript之后，
为了保证支持JavaScript的各种软件实际上都在谈论同一语言， 需要制定一个标准来描述JavaScript语言的工作方式，
在Ecma International组织完成语言的标准化后，我们称之为称为ECMAScript标准。
事实上，术语ECMAScript和JavaScript可以替换使用——它们是同一语言的两个名称。

{{index [JavaScript, "weaknesses of"], debugging}}

有人会说一些关于JavaScript的糟糕的事情。这些事情中有许多确实存在。
当我第一次被要求用JavaScript写一些东西时，我很快就开始鄙视它。
它几乎可以接受我输入的任何东西，但用一种与我想法完全不同的方式来解释它。
当然，这与我不知道自己在做什么有很大关系，但这里有一个真正的问题:JavaScript所允许的自由有些太过荒诞了。
这个设计背后的想法是，JavaScript对初学者来说更容易上手。
实际上，它让你在程序中查找问题变得更加困难，因为系统不会抛出它们。

{{index [JavaScript, "flexibility of"], flexibility}}

不过，这种灵活性也有它的优点。
它为许多技术留下了空间，而这些技术在更严格的语言中是不可能的出现的，
正如你即将看到的(章节[Chapter ?](modules))，它可以用来克服JavaScript的一些缺点。
在正确地学习这门语言并使用它一段时间之后，我学会了真正喜欢上JavaScript。

{{index future, [JavaScript, "versions of"], ECMAScript, "ECMAScript 6"}}

JavaScript有好几个版本。大约在2000年到2010年间，
在JavaScript崛起为主流时，ECMAScript的第3个版本得到了广泛的支持。
在此期间，雄心勃勃的版本4正在进行中，该版本计划对JavaScript进行一些根本性的改进和扩展。
以如此激进的方式改变一种广泛使用的语言在政治上是困难的，
因此，ECMA组织在2008年放弃了版本4的工作，并在2009年发布了一个不那么雄心勃勃的版本5，
它只做了一些毫无争议的改进。
然后在2015年版本6出现了，它是一个重大的更新，包含了很多版本4中的想法。从那时起，ECMA每年都有新的小更新。

语言在不断的发展，这意味着浏览器必须不断地跟进，如果你使用的是老式浏览器，
它可能不支持新的特性。语言设计人员非常小心，不做任何可能破坏现有程序的更改，
所以新浏览器仍然可以运行旧程序。在这本书中，我使用的是2017版的JavaScript。

{{index [JavaScript, "uses of"]}}

Web浏览器并不是使用JavaScript的唯一平台。
一些数据库，如MongoDB和CouchDB，使用JavaScript作为脚本和查询语言。
一些桌面和服务器编程的平台，最著名的是((node .js))项目([Chapter ?](node))，提供了一个在浏览器之外的JavaScript运行环境。

## 编码, 以及如何处理它

{{index "reading code", "writing code"}}

_Code_ 是组成程序的文本。这本书的大部分章节都包含了相当多的代码。
我认为读代码和写代码是学习编程不可缺少的一部分。不要只是浏览实例——尝试仔细阅读并理解它们。
一开始可能会比较慢，让人感到困惑，但我保证您很快就会掌握它的用法。
运动也是一样。在你实际编写出一个可行的解决方案之前，不要假设你理解它们。

{{index interpretation}}


我建议您在真正的JavaScript解释器中尝试你的解决方案。
这样，你就能立即得到关于你所做的是否有效的反馈，并且，我希望，你能尝试自己解决相应的练习。

{{if interactive

当您在浏览器中阅读这本书时，您可以通过单击来编辑(和运行)所有示例程序。

if}}

{{if book

{{index download, sandbox, "running code"}}

要运行书中的示例代码并进行尝试，最简单的方法是在
[_https://eloquentjavascript.net_ (https://eloquentjavascript.net/)上查找该书的在线版本。
在那里，您可以单击任何代码示例来编辑和运行它，并查看它的输出。
要进行练习，请访问[_https://eloquentjavascript.net/code_](https://eloquentjavascript.net/code)，
这里为每个编码练习提供了初始代码，并允许你查看解决方案。

if}}

{{index "developer tools", "JavaScript console"}}

如果你想在本书的网站之外运行本书中定义的程序，则需要格外小心。
许多示例都是独立的，可以在任何JavaScript环境中工作。
但是后面章节中的代码通常是为特定环境(浏览器或Node.js)编写的，并且只能在那里运行。
此外，许多章节定义了更大的程序，其中出现的代码片段相互依赖或依赖于外部文件。
网站上的[sandbox](https://eloquentjavascript.net/code)提供到Zip文件的链接，
这些文件包含运行给定章节代码所需的所有脚本和数据文件。

## 全书概览

这本书大致包括三个部分。
前12章讨论了JavaScript语言。
接下来的7章是关于web((浏览器))以及JavaScript是如何与浏览器交互。
最后，有两章专门讨论((Node.js))，这是编写JavaScript的另一种环境。

全书共有5个_project章节，它们描述了更大的示例程序，可以让你体验更加实际的编程。
按照顺序，我们将通过构建一个[传送机器人](机器人)，一个[编程语言](语言)，
一个[平台游戏](游戏)，一个[像素绘制程序](绘画)，和一个[动态网站](技能分享)。

本书的语言部分为前四章，介绍了JavaScript语言的基本结构。
它们引入了[控制结构](program_structure)(比如在本介绍中看到的`while`单词)、
[函数](functions)(编写自己的构建块)和[数据结构](data)。
在这之后，你将能够编写基本的程序。接下来，章节[?](higher_order)和章节[?](object)介绍了使用函数和对象编写更多抽象代码，以及控制程序复杂性的方法。

After a [first project chapter](robot), the language part of the book
continues with chapters on [error handling and bug fixing](error),
[regular expressions](regexp) (an important tool for working with
text), [modularity](modules) (another defense against complexity), and
[asynchronous programming](async) (dealing with events that take
time). The [second project chapter](language) concludes the first part
of the book.

在第一个[项目章节](机器人)后,这本书的语言部分继续章节[错误处理和修复bug](错误), 
[正则表达式](正则表达式)(和文本打交道的一个重要工具),
[模块化](模块)(另一个处理复杂性的强有力工具),
和[异步编程](异步)(处理异步事件)。
[第二个项目章节](语言)结束了本书的第一部分。

第二部分，从[?](浏览器)到[?](绘画)，描述了在浏览器中JavaScript可以访问的一些工具。
您将学习在屏幕上显示内容(章节[?](dom)和章节[?](canvas))，响应用户输入([章节?](事件))，
以及通过网络进行通信([章节?](http))。在本部分中还有两个专题章节。

在这之后，[章节?](node)描述nodejs。[Chapter ?](技能分享)使用nodejs建立了一个小型网站。

{{if commercial

Finally, [Chapter ?](fast) describes some of the considerations that
come up when optimizing JavaScript programs for speed.

最后，[Chapter ?](fast)描述了在优化JavaScript程序以提高速度时需要考虑的一些问题。

if}}

## 排版约定

{{index "factorial function"}}

在这本书中，用`等宽(monospaced)`字体编写的文本表示程序的元素——有时它们是能够独立运行的片段，
有时它们仅指附近程序的一部分。程序(其中你已经看到了一些)如下所写:

```
function factorial(n) {
  if (n == 0) {
    return 1;
  } else {
    return factorial(n - 1) * n;
  }
}
```

{{index "console.log"}}

有时，为了展示程序的输出，会在后面写出预期的输出，以两个斜杠和一个箭头开头。

```
console.log(factorial(8));
// → 40320
```

祝你好运!
