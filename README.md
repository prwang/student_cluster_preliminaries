# student_cluster_preliminaries
sc竞赛的预备知识学习

下面是要求




<blockquote>
<ol>
<li>
学习如何在Linux上从源代码安装库和软件，并了解make、cc、ld、ldd的使用，了解header file和shard library都放在什么路径、如何引用路径外的header file和shard library。下面几个任务需要用到这些知识。<br>
</li>
<li>
<p>运行benchmark</p>
<p>在自己的电脑上运行HPL（High Performance LINPACK）和HPCG（High Performance Conjugate Gradients）这两个benchmark，提交配置过程和运行输出。请自行下载源代码并自行完成依赖库安装、编译、环境配置。可以参考网上资料。</p>
</li>

<li>
<p>完成三个并行编程任务</p>
<p> 附件中有三个简单的并行编程作业，分别用到OpenMP、MPI和OpenCL。请独立在自己电脑上安装运行环境，然后按照handout要求完成这三个作业，并提交代码（带简单注释）和性能数据。</p>
</li>
<li>
<p>学习操作系统和体系结构的基本知识</p>
<p>主要了解以下概念：SIMD、MIMD、进程、线程、内核、系统调用、GPU（的组成和编程、内存模型）、MPI的编程模型、PCIe、profiling。回答以下几个问题：</p>
<ul>
<li> MPI属于什么编程模型？</li>
<li> OpenCL里workgroup是什么？它在实际GPU硬件上的对应物是什么？</li>
<li> 数据从CPU拷贝到GPU需要经过怎样的流程？</li>
<li> 程序调优的基本思路是？</li>
</ul>
</li>
</ol>
<div>参考资料</div>
<ul>
<li>manpage (man ld, man make, man cc, man ldd, man git)</li>
<li><a href="http://www.netlib.org/benchmark/hpl/" target="_blank">http://www.netlib.org/benchmark/hpl/</a></li>
<li><a href="https://github.com/hpcg-benchmark/hpcg" target="_blank">https://github.com/hpcg-benchmark/hpcg</a></li>
<li><a href="http://mpitutorial.com/tutorials/" target="_blank">http://mpitutorial.com/tutorials/</a></li>
<li><a href="https://anteru.net/blog/2012/11/03/2009/index.html" target="_blank">https://anteru.net/blog/2012/11/03/2009/index.html</a></li>
<li><a href="https://computing.llnl.gov/tutorials/openMP/samples/C/omp_hello.c" target="_blank">https://computing.llnl.gov/tutorials/openMP/samples/C/omp_hello.c</a></li>
</ul>

<div>以上所有任务请建一个git repository并往其中提交，完成后请把git repo地址或github页面地址发给我。初学这些知识可能有些steep，可能遇到诸多问题，特别是之前完全没接触过的同学。如果有问题欢迎随时讨论（可以发邮件问抄送的同学，也可以互相学习）。以上任务都是开放性的，没有标准答案，主要是帮助大家快速入门。请尽量在7月中下旬完成，然后我们会根据大家的特长分配更多任务。</div>
</blockquote>

