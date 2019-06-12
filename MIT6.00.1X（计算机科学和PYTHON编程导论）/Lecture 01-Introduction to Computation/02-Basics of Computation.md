# BASICS OF COMPUTATION

1. Welcome to the 6.00X（）

2. often referred to as the introduction to computer sicence and programming
## 6.00 Introduction to Computer Science and Programming
- Goal:
  - -Become skillful at making a computer do what you want it to do

这门课也叫做计算机科学和编程导论。
为什么课程名里既有计算机科学，又有编程，这很奇怪，
但这两个元素都十分重要。
这门课不仅要教你们怎样进行计算机编程，
怎样发送计算机能够理解的指令，
更重要的是让你们具有
计算思维。
所以我们不仅要让你们能够熟练地使用计算机，
还要让计算机完成你交代的任务，
用它解决问题。
当课程结束时，我们希望你在面对一切有趣的挑战时，
能够最先想到
怎么去战胜挑战，
怎样让计算机通过算法或机械表述
来解决问题，
为我服务。
如果你能做到这些，那么在面对任何问题时，
你将会受益无穷。
你会看到，这些能力贯穿了
整个课程。
如果我们的目标在于让你们学会使用计算机为自己做事，
与计算机对话，
学会计算思维，
那么我们能会问的一个问题就是，计算机能为我们
做什么？
它最擅长做什么？
这看起来是个奇怪的问题。
毕竟我们知道计算机能做许许多多的事情。
但是回到最初的原点，
仍然非常重要。
计算机能做什么？
事实上，它只做两件事，
那就是计算和记录结果，
以备后用。
你可能会说，好吧，那它就是做计算的。
这样说似乎没什么问题。
但是具体是哪些计算？
事实上任何一台计算机都能做一系列
简单的基本运算，我们叫做内置运算。
它们是由制造商提供给计算机使用的
基本元素，
很快我们就可以看到一些例子。
如果我们所拥有的仅限于此，那就太少了，
所以整个课程中一件关键的事情是
学会如何创造我们自己的计算方法。
如何获取像计算机一样思考，
也就是计算思维。
然后按这样的方式思考，
以便计算机能够提取它。
它的意思是
计算机明白如何你告诉它的东西转化为和
制造商提供的原语一样的东西
然后在计算过程中重复利用
这些东西。
这样计算机就可以运用内置指令以及我们给它的东西
为我们进行运算了。
你可能要问，这就够了吗？
如果计算机真的只能做基本运算的话，
那远远不够。
好吧，相信你已经意识到了，现代计算机以难以置信的速度
完成大多数运算。
所以这里有一个问题，如果我们能够做得足够快，
做有意思的事情就够了吗？
让我们看看这个问题的两个方面。
首先，现代计算机
到底能跑多快？
让我给你们举一个小例子。
如果我放一个软管台灯在
距离桌子一英尺高的地方，并且
能够恰好同时地按下台灯开关键和
键盘上的某个键，
那么在台灯光线到达桌面的
这段时间中，你的电脑就能
执行两个操作。
很神奇吧！
这段短短的时间内，光只走了一英尺，
但它做了两个操作，两个基本操作。
难以置信！
让我们换种方式想象这件事。
想象我拿着一个儿童橡皮球，
我把它悬在离地一米的地方然后放手。
如果我让它就这么落下去，考虑地球引力的话，
那么，当它碰到地面时，你的计算机已经执行了
10亿次操作。
简直太不可思议了！
球落地的时间内，
就有10亿次操作！
这意味着这些计算机实际上
非常快。
虽然做的计算都非常简单，
但他们跑得相当快。
的确如此。
我们说过计算机做一些简单的操作，
我们还说过他们会存储一些东西。
那么一台计算机内的存储容量有多大？
存储的1个基本单位称为1 byte。
如果我们假设 1 byte 重 1 盎司(约28克)，
当然我知道 1 byte 不是真的有 1 盎司那种重量。
但是假设它有 1 盎司重，
一台典型的电脑通常有成百上千个GB
的存储容量，
也就是说，如果 1 byte 重 1 盎司的话，
一台计算机中就有大约
3亿吨的存储容量。
好吧。
当然它们并不是以这样存储的，
但你已经有了一个直观印象。
超乎想象的巨大容量，能够存储许多东西，
再加上做计算时超乎想象的快速。
听起来真不错。
问题在于，如果都只是基本操作，
那足够吗？
这些简单的计算是否够用了？
它们确实可以做很多事情，我们已经见识过了。
但我们也同样看到，只有这些简单计算，还远不能完成所有
我们想做的事情。
举两个例子。
我相信你们都上网
搜索过信息，
你们在网上搜索你们想知道的
东西。
问题在于如果一台电脑直接用来
搜索，它搜索网页的速度
会有多快？
事实上，互联网上现在大约有450亿
可供搜索的页面。
如果我们假设每个页面有大约1000个词，

当然有些页面多，有些页面少，但平均
我们取每个页面1000个单词。
为了论证，我们假设在页面上找到某个词
并且判断正确与否，
需要执行约100次操作。
100 有些高，
我们选一个稍小的数字。
假设每个词需要10次操作，
执行这种搜索需要多长时间？
我们可以做一下计算，
你们自己也可以做一下。
你有450亿个页面，
你有那么多次操作。
你知道我们做这些操作有多快？
如果你把时间加在一起，你会发现我们要花
5.2天来搜索互联网才能找到要找的东西。
这太慢了。
起不了什么作用。
总的说来，这个例子提示我们即便拥有运行如飞的电脑，
我们也必须要更聪明些才行。
下面是第二个例子。
下棋——这通常被认为是
一件很难的事情。
然而10年还是15年前，一个计算机程序在比赛中
战胜了当时国际象棋的世界冠军。
这令人印象深刻。
好吧，那问题在于，这仅仅是因为
电脑运行得很快吗？
我们可以从两方面来看，
在一场象棋比赛中，任何时候都有差不多
35种走法。
那么问题来了，如果我想
让我的计算机程序提前想好6步，其中3步是我的，3步是对手的，
那么在每一步都有35种走法的情况下，
一共有多少种不同的选择？
答案是，我们必须要面对 18 亿套完全不同的
棋局。
如果每个下一步我们可以通过 100 次操作计算出来，
那意味着真正看一步棋
需要花半个小时。
太慢了。
这就指向了一个我们想
说明的问题。
即，是的，计算机很快，但
我们同样需要设计好的算法。
为了解决这些有趣的问题，我们需要
更聪明、智能、灵敏的算法
完成相关工作。
这也是我们这门课将探讨的
主要内容。
另外，我们也说过空间是一个问题。
我们计算机中有很大的空间，
再回到刚才象棋那个例子，你可能会问
象棋中有多少不同的
比赛局势？
专家会告诉你有差不多 10^123 那么多种
可能的局势。
这会不会太多了以至于计算机存储不下？
毕竟在可观测的宇宙中也只有
10^80 个原子而已，
所以我们不能够仅仅只是把这些棋局存储起来，
然后查找就行了。
所有这些都在说明我们为什么要通过这门课
学习算法思维。
这看起来只是个用速度和智商
就能解决的问题，
但是头脑清晰的人可能会说，
电脑能为我们做的事情
有限制吗？
事实上，即使有这样的速度和存储容量，而且还有聪明的算法，
我们的计算机也还是有一些
限制。
举几个例子。
首先，有一些问题
非常的复杂。
我们没有足够的速度，足够的存储容量(来解决)。
这些问题可能会随着时代发展而解决。
其中一个例子就是在一个非常局部的比例尺下
预测天气。
我想知道接下来半个小时，或1个小时，或3个小时
我窗外的
(天气)会发生什么(变化)。
这种问题的规模大到足以让一台计算机无法
在合理的时间内建好模型，
并解决它。
事实上，这些高难度问题有时候
还会帮到我们。
现代密码学，
即研究让信息在互联网上安全传播的学科，
就依赖于一些难以计算的问题，
从而保证难以被破解。
所以我们确实受益于
这些从复杂问题。
但是在课程的后面部分，我们也会看到一些
无论如何先进的计算机都无法计算的问题，
从根本上就无解。
这里面有些问题难度过大。
举个例子，输入任何信息，我们能够判断
输入的编码是否会结束（停机）并给出答案。
我不是说让你跑这段程序然后看它是否会停机，
而是写一段代码，然后用另一段代码来
检查它，然后给出结论它是否总是能起作用。
总能停机，而且总能给我们一个输出答案。

这被证明是无解的。
这就是著名的图灵停机问题，
之后我们还会简单讲一下它。
但是它说明了存在那种难度高到无法在
有限时间内解决的问题。
话虽如此，但在这门课程中我们将讲解
我们如何以算法式思维思考问题并
利用计算机为我们做一些有趣的事情。




ERIC GRIMSON: Welcome to the 6.00x, often referred to as
the introduction to computer science and programming.
It's odd to have both of those terms in the title, but both
of them are important.
This course is going to be not just about teaching you how to
program a computer, how to tell the computer instructions
that it can understand.
It's also going to be really important to create within you
a capability to think computationally.
So our goal is to let you become skillful at not only
getting the computer to do something, but to do that
thing that you want it to, to get it to solve a problem.
By the end of this course, we hope that your first instinct
when faced with any interesting challenge is to
first think about how could I capture that challenge, that
problem in an algorithmic or mechanical description of
steps such that I could get the computer to do
If you can do that, it's going to give you a great deal of
advantage as you face any kind of problem.
And those are the skills that you're going to see throughout
this course.
Now if our goal is to have you learn how to get a computer to
do something for you, how to talk to the computer, how to
think algorithmically.
1 of the questions we can ask is, so what's the computer
going to do for us?
What's it actually good at?
That seems like probably an odd question.
After all, we know computers could do a ton of things.
But it's still important to go back to a very fundamental and
basic point.
What does a computer do?
In fact it does 2 things and 2 things only.
It performs some calculations, and it remembers results so
that it can reuse them.
Now you'd say, OK, so it performs calculations.
That seems fine.
But what kinds of calculations.
Well, it turns out that every computer comes with a simple
set of primitive calculations, things that we call built in.
They're provided by the manufacturer as the basic
elements that a computer could use.
We'll see some examples of that shortly.
If that's all we have, that's pretty limiting.
So a key thing, as we go through the material in this
course, is to learn how we can create our own methods for
computing something, how we can capture the computational
way of thinking about something in a manner that
could be used by the computer, and to do it in a way whereby
the computer can abstract that.
By that we mean that the computer can figure out how to
take what you tell it and turn it into something that it can
now treat as if it were a primitive, something that was
provided by the manufacturer, and reuse that throughout its
computations.
So our computers are going to do calculations for us, using
a set of built-in primitives, plus things that we add.
Now you might ask, gee, is that enough?
If it turns out that a computer can just perform
primitives calculations, it's not sufficient.
Well, as I'm sure you already realize, modern computers can
perform most calculations incredibly quickly.
And so one question is if we can do them fast enough is
that sufficient to do interesting things?
Let's look at both parts of that.
First of all, how quickly does a modern
computer actually run?
Well, let me give you a simple little thought example.
If I were to take a little gooseneck lamp and put it
right here, a foot above my desk, and I were to time
things perfectly so that as I hit the switch on the lamp I
hit a key on my computer and started them both up at
exactly the same time, in the length of time it takes the
light to go from the lamp to the desk your computer will
execute two operations.
That's amazing.
It does two operations, two of those primitive operations in
the amount of time it takes light to go basically a foot.
Unbelievable.
Here's another way of thinking about it.
Imagine I take a simple child's rubber ball and I
suspend it about a meter off the ground and I drop it.
If I let it drop, by the time it hits the ground, assuming
gravity behaves normally, your computer will have executed
1,000,000,000 operations.
Unbelievable.
1,000,000,000 operations by the time that
ball hits the ground.
Now, that suggests that in fact these computers are
And even though they're computing very simple things,
they're doing incredibly quickly.
They are.
We say computers do simple operations.
We also said that they have some storage.
So how big is the storage inside of a computer?
Well, every element of storage is called a byte.
And if we were to assume that a byte weighed 1 ounce --
I know bytes don't really weigh ounces, but assume they
weigh 1 ounce.
A typical computer has hundreds of
gigabytes of storage.
And that says if each one of those bytes weighs 1 ounce a
computer would be able to store the equivalent of
300,000,000 tons of storage.
They don't really store it that way.
But you get the idea.
Incredible amount of storage, can remember a lot of things,
and incredibly quick in terms of doing the computation.
So, that sounds really good.
The question is if they're only primitive operations is
Are these simple calculations sufficient?
Well, they're going to do a lot as we see.
But we're also going to see that they're not quite enough
to do everything we'd like.
Let me give you 2 examples.
I'm sure all of you have gone to the World Wide Web to look
You've searched the web to try and find things that you'd
like to know about.
The question is if a computer is just doing this the
straightforward way how quickly would
it search the web?
Well, it turns out there are about 45,000,000,000
searchable pages on the web at the moment.
If we assume that it takes about 1,000 words, or there
are about 1,000 words per page.
Some, of course, are much more than that, some of less, but
about a thousand words per page.
And just for sake of argument, we're going to assume it takes
about 100 operations per word to find the word on the page
and to decide it's the right thing.
Let's just assume it's only 10 operations per word.
How long does it take to actually execute that search?
Well, we can do the math.
You can grind it through.
You have 45,000,000,000 pages.
You know how quickly we're doing these actual operations.
If you put it all together, what you find is it's going to
take you about 5.2 days to find something on the web.
That's a slow browser.
That's not going to work very well.
And that basically is giving us a hint that even with
really fast computers we have to be smarter.
Let me give you a second example.
Playing chess, something that's seen as a very
difficult task.
It's impressive that about 10 or 15 years ago a computer
program actually beat the world
champion in a chess match.
And 1 of the questions is, well, OK, is it just because
the computers are really fast?
Well, we can look at this two ways.
In a typical chess game, there are about 35
moves at any one time.
And so the question you could ask is to say, OK, if I want
to have my computer program look ahead 6 moves, 3 moves by
me, 3 moves by my opponent, how many different options are
there if there are about 35 moves each?
And the answer is about 1.8 billion different sets of the
chess board that I'd have to look at.
If I can check each move out in about 100 operations per
move, then that says it's going to take me about a half
hour to actually look at each move.
That's pretty slow.
And this is pointing to a problem that
we want to get at.
And the problem is that, yes, computers are really fast, but
we need good algorithmic design as well.
To deal with interesting problems, we need algorithms
that are clever, are intelligent, are smart about
how they actually do the work.
And that's a lot of what we're going to talk about this
during this term.
By the way, we also said space was a big issue.
And we got a lot of space in the computer.
If you go back to the chess example, you can ask the
following question: How many different games
are there in chess?
Experts will tell you there about 10^123 different chess
games that are possible.
Is that too big for storing in your computer?
Well there are only 10^80 atoms in
the observable universe.
So we can't just store away all the games
and look them up.
And both of these are pointing to why we're going to use this
course to actually learn about thinking algorithmically.
Now this suggests it's just a matter of putting together
enough speed and enough smartness.
But one can be a little bit more distinct and say, are
there actual limitations to what we
can do with the computer?
And in fact despite its speed and its size and the
cleverness of the algorithm, our computer still has some
Here are a couple of examples.
First of all, there are some problems that
are just too complex.
We don't have enough speed, enough storage.
And they may get tackle as things improve.
But examples here would be things like predicting weather
at a very local scale.
I'd love to know what's exactly going to happen
outside my window for the next half hour or next
hour or next 3 hours.
The size of the problem simply too big for a computer to be
able to model well enough and solve in a
reasonable amount of time.
It turns out some of these complex problems
actually help us.
Modern cryptography, the way in which information is
securely transmitted across the net, relies on having some
problems that are simply too difficult to compute and,
therefore, too difficult to break the code.
So we actually get some benefits about the problems
that are too complex.
But as we're also going to see later on the course, there are
some problems that are just fundamentally impossible to
compute no matter how big the computer is.
And some of those are really heavy.
Here is one example, being able to predict whether a
piece of code will always stop with an answer for any input.
By that I don't mean just you run it and see if it stops,
being able to write a piece of code and then have some other
piece of code inspect it to say, this will always work.
It will always stop, and it will always give us an answer.
This turns out to not be possible to solve.
And this is known as Turing's Halting Problem.
And we'll talk briefly about that later on in the term.
But it says that there are some problems that are simply
too hard to solve period.
Nonetheless, in this course, we're going to start talking
about how do we think algorithmically and get the
computer to do interesting things for us.
