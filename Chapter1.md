# Chapter 1:Computer abstractions and Technology

## Introduction

##### 	计算机发展历史

##### 	Turing-complete（图灵完备/图灵完全）：一种计算模型能够模拟任何其他计算模型的能力

##### 	Von Neumann Architecture（冯·诺伊曼结构）：

<img src="C:\Users\28067\AppData\Roaming\Typora\typora-user-images\image-20240920113418071.png" alt="image-20240920113418071" style="zoom: 67%;" />

​	组成部分：

​		Arithmetic/Logic Unit（运算器）、Control Unit（控制器）、Memory Unit（存储器）、Input Device（输入设备）、Output Device（输出设备）五大部分。<u>通常也将最后两部分统称为I/O Device（输入输出设备）。</u>

​	特点：

​		Computation and memory are seperated（计算与存储分离）

​		Memory that stores data and instructions（数据与指令保存在同一个存储器）

​		Input and output mechanisms（输入与输出机制）

​		Instruction set architecture（ISA 指令集架构）

##### Analog Computing（模拟计算机）：

​		与数字计算机运用数字电路处理**离散的数字信号**不同，模拟计算机使用电子器件或机械、液压等物理量，来处理**连续的模拟信号**，以模拟实际物理过程或事件。

Digital computing（数字计算机） | Analogcomputing（模拟计算机）
:-:|:-:
Accurate when encoded in many bits（以多位编码时较准确）| Less precision affected by noise （易受到模拟噪声的影响而导致不准确）
Scalable（可扩展的，因其本身依赖于数以亿计的晶体管组成的半导体电路） | Diffucult to integrate（难以集成，因为模拟噪声和错误会在级联电路中累积）
General Purpose（通用性） | Application-specific（特定应用）
Computational heavy（计算密集型） | Fast by nature（在模拟相关物理变化等响应较快）
Compute-only（专注于计算任务） | Sensors and actuators are mostly analog（传感器和执行器大多数是模拟的）

*模拟计算在AI领域的复兴能够帮助其克服冯·诺伊曼瓶颈*

##### What is a computer?

​		
