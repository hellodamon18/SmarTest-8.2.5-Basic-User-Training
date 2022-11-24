# V93000 SmarTest 8 Basic User Training

==Version 8.2.5==



[TOC]

Introduction/Agenda 

## Lecture 01: Introduction, Concepts and Software overview 

* ==Key Objectives of SmarTest 8==
  1. Enable the **shortest** time from **tape-out to volume production**.
  2. Enable **best test program development efficiency**.
  3. Offer the **fastest test throughput** for manufacturing test of complex SOC/SiP/TSV and also small
     low complexity devices.  

<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\1.png" alt="image-20221123235651317" style="zoom:80%;" />



* ==**SmarTest 8 Values**==

  1. Simple synchronization across domains

     <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\2.png" alt="image-20221124000359545" style="zoom:;" />

  2. Unified setups and tools

     > **Hardware Abstraction**: awg, clock, dcVI, digInout...
     >
     > **Multi Domain Tools**:  Timing Debug, digital/analog/RF/DC/PA...

     <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\3.png" alt="image-20221124000458942" style="zoom:67%;" />

  3. Reuse

     > Every node of a testflow can be a test suite or another testflow. 
     >
     > Every testflow can have input and output parameters.  

     <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\4.png" alt="image-20221124001249187" style="zoom:80%;" />

  4. Collaborative development

     > • Flexible file structure for setup files
     > • Allows a dedicated file for a setup entity
     > • Integrated support for SVN and GIT
     > • Links to external setup files  

  5. Assisted setup generation

     > SmarTest Setup Format (SSF)  
     >
     > 快捷键：ctrl-space, F3
     >
     > 视图切换：例如 pin定义

  6. Smart test methods

     > 单site扩展成多site容易
     >
     > 支持特定site的数据处理
     >
     > 结果支持后台运算

  7. Java  

* graphical tools

  <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\5.png" alt="image-20221124002520023" style="zoom:80%;" />

  

## Lecture 02: SmarTest Projects 

* SmarTest 8 Project

  > – Java Libraries
  > – V93000 System Libraries
  > – Source Folders
  > – Configuration Files
  > – Compile/Build Directories  

<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\6.png" alt="image-20221124003109861" style="zoom:80%;" />

* Project Setup

  > 1. Creat new SmarTest Project
  > 2. Import SmarTest Project

<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\7.png" alt="image-20221124231537168" style="zoom:80%;" />





### Lab 01: Preparation and Prerequisites 

• Start SmarTest 8 with the correct model file.
• Create a workspace
• Change the view
• Import the SmarTest 8 project (i.e. test program) used in the lab  



## Lecture 03: Test Program File

* **==Test Program File==** 

  <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\8.png" alt="image-20221124232943873" style="zoom:80%;" />

* **==DUT Board Description File==**  

  <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\9.png" alt="image-20221124233006235" style="zoom:80%;" />



* **==Main Flow File==**  

* **==Auxiliary Flow Files==**  

<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\10.png" alt="image-20221124233225641" style="zoom: 67%;" />



==**example**==

![image-20221124233339242](D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\11.png)



> Ctrl+Space

<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\12.png" alt="image-20221124233711809" style="zoom:80%;" />



## Lecture 04: DUT Board Description File

* **example**

![image-20221124234117858](D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\13.png)

> dutboard = crossconnect.common.BasicLab;

<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\14.png" alt="image-20221124234518529" style="zoom:80%;" />



<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\15.png" alt="image-20221124234738193" style="zoom:80%;" />



<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\16.png" alt="image-20221124235352921" style="zoom:80%;" />

* Ganging DPS Channels

  <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\17.png" alt="image-20221124235446840" style="zoom:80%;" />



* DUT Boards with Switches  

  <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\18.png" alt="image-20221124235557920" style="zoom:80%;" />



* RF Pins Setup

  <img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\19.png" alt="image-20221124235737763" style="zoom:80%;" />



<img src="D:\Study\9.Semiconductor\SmarTest 8.2.5 Basic User Training\pic\20.png" alt="image-20221124235817951" style="zoom:80%;" />



### Lab 02: DUT Board Description





## Lecture 05: Building Blocks of Test Programs





### Lab 03: Test Program





## Lecture 06: Testflow and Test Suites



### Lab 04: Testflow



## Lecture 07: Operating Sequence



### Lab 05: Operating Sequence



## Lecture 08: Hardware Overview*



## Lecture 09:  Instruments



## Lecture 10: Basics Level and Timing*



## Lecture 11: Specification Files - Digital Setups



### Lab 06: Timing Sets and Level Sets

​     

## Lecture 12: Specification Files - Multi Domains 



### Lab 07: Timing Debug 



## Lecture 13: Patterns 



### Lab 08+09: X-Mode + Pattern Debug 



## Lecture 14: Actions, Patterns and Transactions 



### Lab 10: DC Measurement 



## Lecture 15: Technical Documentation Center

   

## Lecture 16: Testflow File



### Lab 11: Test Method Library*



## Lecture 17:  Test Methods – Introduction



### Lab 12: Test Method Creation



## Lecture 18: Test Methods – Basics



## Lecture 19:  Test Methods – Multi Site Types



### Lab 13: Test Setup Modifications



## Lecture 20: Test Methods – Result Access 



### Lab 14:  Retrieving Test Results



## Lecture 21: Datalogging



### Lab 15: Datalogging 



## Lecture 22: Binning



​    

## Lecture 23: Usage of Test Tables

## Lecture 24: Content of Test Tables

## Lecture 25: Test Program Execution and Debug

## Lecture 26: Internal Steps of Test Program Execution

## Lecture 27: Protocol Aware – Introduction

### Lab 16: Protocol Aware Setup Files*

## Lecture 28: Test Methods – Programmatic Setup Generation*

### Lab 17:  Setup Generation in Test Methods*

## Lecture 29: Test Methods – Parameters*

## Lecture 30:  Debug Tools

### Lab 18:  Debugging Measurement Setups 

​     

## Lecture 31: Characterization Tools

### Lab 19: Characterization/Shmoo*

## Lecture 32:  Recommended Setup Structure

## Lecture 33: Utility Lines

## Lecture 34: Licensing

## Lecture 35: TCCT

## Lecture 36: Test Program Migration Framework* 

## Lecture 37: Conversion of STIL files* 

## Open Questions

## Feedback  




## 进阶+++

[SmarTest 8.2.0-8.3.0 Delta Trainings](https://dojo.advantest.com/learn/course/151/smartest-820-830-delta-trainings;lp=56)

