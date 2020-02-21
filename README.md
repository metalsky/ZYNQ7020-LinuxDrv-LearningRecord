基于ALINX的AX7020开发板的Linux驱动学习和开发。

前不久开始学习Linux，困难到想放弃。
让我回想起从51单片机转向stm32时的那种感受，那种无从下手的恐惧和只能按部就班的做实验却完全不理解内容的卑怯。
那时候看到寄存器就头昏眼花，现在再看到寄存器操作，又觉得亲切无比。
在挣扎许久之后，终于稍有眉目。
今天开始记录学习过程，并把自己所学所得以教程的形式记录，希望与同样正在学习的朋友共勉。

困难的一部分原因来自开发平台，用ZYNQ来入门Linux实在不是什么好的选择，资料是在太少。
光是学习Xilinx的一套开发工具就花了不少时间，好在工具上手之后，使用起来也算方便。
主要涉及到PC端工具vivado、ubuntu端的vivado和ubuntu端的petalinux，这些软件能让我们快速得到一个可在ZYNQ上运行的Linux系统。
都是Xilinx官方提供的工具，这些我就不细说了，在ALINX开发板配套的教程中，这些都有详细的讲解。
至于为什么要在ZYNQ平台上学习Linux驱动，其中原由，不方便说，哈哈。

关于Linux学习个人的看法。个人的看法。个人的看法。
①我接触到的Linux学习资料，无论是书籍还是开发板配套教程，无一例外，都是从移植u-boot、内核、文件系统三巨头开始。
当然得到这三巨头，是接下去学习的基础，但是说要对内核要有较为深入认识和理解，我觉得不可操之过急。
学习内核知识是极为枯燥的，而且学习过程中几乎没有编码机会。
姑且不说那万行代码，光是理论层面的设计思想，我就得花几个月去消化。
很容易感到挫败而放弃。
当然肯定不是说不要去学习内核了。
不如先用现成的资源把环境搭好，颠倒一下传统的学习顺序，先从Linux驱动开始学习，从Linux驱动这个角度慢慢的去了解内核相关的知识。
驱动学的差不多了，再回头去研究内核又如何呢。
②关于常用的Linux指令，没必要花时间刻意的去记忆，四个字熟能生巧。
哪怕每次要用到的时候都要去搜索一下，也总会有烂熟于心的一天。

关于这个项目的内容，会按项目持续更新，每个项目形式为：驱动程序+测试程序+实验教程。
若内容错误请务必不吝指正！

<---------------已更新---------------->
=======================================
||==== 1.字符设备
=======================================
||==== 2.字符设备的新写法
=======================================
