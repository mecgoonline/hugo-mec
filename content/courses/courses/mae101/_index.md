---
title: "MAE101"
date: 2020-03-17T18:44:38-04:00
weight : 2
katex: true
---

## Engineering Lab I 

### Content 

1. [Course Syllabus](https://docs.google.com/document/d/1_3bIj8newFlfAYBzj5NxzTrlFv9eG-ZNWI_A5mRph_M/edit?usp=sharing)
2. [Lab Report](###Lab-Report)
3. [Bridge Design Module](#bridge-design-module)
	* [Lab Experiments](#lab-experiments)
	* [Experiments Data and Handouts](#lab-experiments-data-and-handouts) 
	* [Project: Design & Analysis of a Warren Truss Bridge](#Project:-Design-&-Analysis-of-a-Warren-Truss-Bridge) 
4. [Robot Design Module](#robot-design-module)

### Lab Report

It is important for students to communicate his or her knowledge of the subject with well-written **individual** lab report that are decent and that accurately explain the efforts, hypthesis or concise theoretical background of the the topic under inverstigation, observations and discussion of the results. it is imperative for the student to keep in mind that instructor may not be the only reader of the report and to write in a clear fashion such that other people who are unfamiliar with the subject matter can read and understand the material presented. Desirably the narration sould be free of any commitment to any person(s), that is refrain from the use of pronouns such as I, We, Our, Us, etc.

To convey understanding, the organization of the lab report should lead to a deft arrangment of information including data, graphs, and pertinent answes to such questions posed by the experiments.

The preferred lab report format is typewritten, double-space. thus for this course the guideline for an acceptable lab report format is outlined in the following example {{% button href="/engineering/courses/mae101/docs/outline.pdf" icon="fas fa-download" %}}Lab Report Ouline{{% /button %}}  

Also a Lab report template is available here {{% button href="/engineering/courses/mae101/docs/template.pdf" icon="fas fa-download" %}}Lab Report Template{{% /button %}} 
### Bridge Design Module

In This Module you will study the behavior of material, structural members and equilibrium.

#### Lab Experiments:

Student are required to submit an individual lab report for the each experiment. PDFs are the preferred format since PDFs can be uploaded to Blackboard.

- Experiment 1 : Fatigue Failure
- Experiment 2 & 3 : Tension & Compression Test
- Experiment 4 & 5 : Bending of Beam & Moments of Forces
- Experiment 6 & 7 : Internal Forces in Truss Members & End Reaction of a loaded Beam

{{% notice info %}}
Student are required to submit an individual lab report for each experiment. PDFs are the preferred format since PDFs can be uploaded to Blackboard. Also make sure you write a separate lab report for each experiment. 
{{% /notice %}}

#### Experiments Data and Handouts: 

| Experiment                        | Manual  | Data     | Resources  |
|-----------------------------------|---------|----------|-------|
| Fatigue Failure                   | [Handout](/engineering/courses/mae101/docs/fatigue.pdf) | {{% button href="/engineering/courses/mae101/docs/fatigue.xlsx" icon="fas fa-download" %}}Get Data{{% /button %}} | [Video1](https://www.youtube.com/watch?v=LhUclxBUV_E), [video2](https://youtu.be/ywDsB3umK2Y), [video3](https://youtu.be/TH9k9fWaFrs), [video4](https://youtu.be/meEG7VwjTew) |
| Tension Test                      | [Handout](/engineering/courses/mae101/docs/tension.pdf) | {{% button href="/engineering/courses/mae101/docs/tensionData.xlsx" icon="fas fa-download" %}}Get Data{{% /button %}} | [Demo](https://www.youtube.com/watch?v=RgLYTgQ14gs)|
| Compression Test                  | [Handout](/engineering/courses/mae101/docs/compression.pdf) | {{% button href="/engineering/courses/mae101/docs/compressionData.xlsx" icon="fas fa-download" %}}Get Data{{% /button %}} | [Eulers Equation](https://www.youtube.com/watch?v=jaIlEFiA9n8&feature=youtu.be) -- [Backling Example](https://www.youtube.com/watch?v=jNwvub87l8o&feature=youtu.be) |
| Bending of Beam                   | [Handout](/engineering/courses/mae101/docs/bending.pdf) | {{% button href="/engineering/courses/mae101/docs/bendingData.xlsx" icon="fas fa-download" %}}Get Data{{% /button %}} | [Demo](https://www.youtube.com/watch?v=rrWxCcA2NgM) - [Virtual lab Demo](https://www.youtube.com/watch?v=GvmVRXajneY)--[Free Beam Calculator](https://skyciv.com/free-beam-calculator/)|
| Moments of Forces                 | [Handout](/engineering/courses/mae101/docs/moments.pdf) | {{% button href="/engineering/courses/mae101/docs/moment.xlsx" icon="fas fa-download" %}}Get Data{{% /button %}} | [Using Interactive](https://www.physicsclassroom.com/Physics-Interactives/Balance-and-Rotation/Balance-Beam/Balance-Beam-Interactive) |
| End Reaction of a Loaded Beam     | [Handout](/engineering/courses/mae101/docs/endReaction.pdf) | {{% button href="/engineering/courses/mae101/docs/EndReaction.xlsx" icon="fas fa-download" %}}Get Data{{% /button %}} | [Beam Calculator](https://beamguru.com/online/beam-calculator/) |
| Interenal Forces in Truss Members | [Handout](/engineering/courses/mae101/docs/internalforces.pdf) | {{% button href="/engineering/courses/mae101/docs/Internalforces.xlsx" icon="fas fa-download" %}}Get Data{{% /button %}} | [Setup and Instruction Manual](/engineering/courses/mae101/docs/Internal_forces.pdf)- [Truss Simulator](https://ei.jhu.edu/truss-simulator/) - [Equilibrium](https://www.walter-fendt.de/html5/phen/equilibriumforces_en.htm)|


#### Values of modulus of elasticity:


| Material | E value in [Pa] | E value in [psi] |
|----------|-----------------|------------------|
| Rubber   |$$1.72\times 10^6$$| $$250$$              |
| Aluminum | $$70\times 10^9$$| $$10\times 10^6$$          |
| Wood     | $$15\times 10^9$$| $$2\times 10^6$$           |
| Ruler    | $$2.8\times 10^9$$        | $$400\times 10^3$$         |

#### Project: Design & Analysis of a Warren Truss Bridge 

The last section demonstrated the use of powerful tool for analyzing civil engineering structures where the program was used to perform static analysis of truss. The SAP2000 program is also capable of analyzing frames plates and shell for static as well as dynamic loads.
In this section, its application will be extended to the analysis of a simple truss bridge.

**SAP2000 Software**

CSI introduced a cloud sign-in in the new version of SAP2000, where students will need to sign-in in order to activate the software.Please follow these steps to download and activate your software.
1. Download {{% button href="https://www.csiamerica.com/software/SAP2000/25/SAP2000v2520Setup.exe" icon="fas fa-download" %}}Get SAP2000 Student Version{{% /button %}}.
2. Fill out the following form to request an account [CSI Account Request](https://forms.gle/Q4tE7DEGyrSXuKp98)
3. After Installation run the program and login using the email you provided

{{% notice note %}}
SAP2000 programs cannot be run directly within the Mac operating system. However, if Windows operating system is virtualized on the Mac machine (via virtualization platforms such as Parallels or [VirtualBox](https://www.virtualbox.org/wiki/Downloads)) then SAP2000 programs can be run within such virtualized Windows operating system.
{{% /notice %}}

##### Introductory Tutorial for SAP2000

The manual provided bellow will introduces you to SAP2000. The step-by-step instructions guide you through development of your first model. The intent is to demonstrate the fundamentals and to show how quickly and easily a model can be created using the program. Completing the tutorial will give you hands-on experience working with SAP2000, which for most people is the quickest way to become familiar with the program.

{{% button href="/engineering/courses/mae101/docs/SAP2000Tutorial.pdf" icon="fas fa-file-pdf" %}}Download SAP2000 Tutorial{{% /button %}}

{{% button href="https://www.youtube.com/watch?v=LA-sKoBp5-0" icon="fas fa-video" %}}First Problem Solution{{% /button %}}

{{% notice note %}}
The pdf tutorials were created using SAP2020 v17. In the New SAP2020 v20 there are some small changes related to how live load is applied.
Please follow the animation below to see how to define the loads on SAP2020 v20.
{{% /notice %}}

![load](/engineering/courses/mae101/docs/load.gif)

##### Design and Analysis Of a WARREN Truss Bridge

Perform the structural analysis of a steel truss bridge that spans a total distance of 63 ft. The truss bridge consists of two parallel trusses and the truss configuration is given in the figure below. The lower chords of the trusses support the roadway which in turn carries the car and truck traffic. The object of this analysis is to calculate the internal forces in each member of the bridge under the effect of the weight of the bridge and roadway (the dead load) and the weight of the vehicles (the live loads) that are likely to cross the bridge. It is here in assumed that the bridge carries two lanes of vehicle traffic. Make a first estimate of the internal forces in each truss member under regular truck traffic. The analysis must be performed using the SAP2000 package. Use the simplifying assumptions given below to analyze the four-bay Warren truss bridge shown in Fig 1.

![Truss](/engineering/courses/mae101/docs/bridge.png)

#### Bridge Preliminary design On SAP2000

- WARREN Truss bridge step by step design instructions {{% button href="/engineering/courses/mae101/docs/SAP2000Project.pdf" icon="fas fa-file-pdf" %}}Download pdf file{{% /button %}}
- Watch Demo video [here](https://www.youtube.com/watch?v=e04NXwZTvqQ&t=519s)

{{% notice note %}}
Similary follow the animation below to see how to define the loads on SAP2020 v20.
{{% /notice %}}

![load](/engineering/courses/mae101/docs/bridge.gif)


#### Bridge Analysis, and Assessement of Results

**STEP 1: Calculate the areas required for each member**

Use MS-Excel to calculate the areas required for each member to carry the force produced by different loading condition considered.
Recall that the analysis of the truss bridge was performed by assuming that each member had an area equal to 20in^2. To find the area required for each member to support the loading conditions, we assumed that A36 structural steel was used with a design safety factor of 1.5. the maximum possible stress is 36,000 psi for A36 steel. Therefore the allowable stress is obtained as :

$$\sigma_{all} = \frac{\sigma_{max}}{S.F} = \frac{36,000 psi}{1.5} = 24,000 psi$$

if the force in a member is given as F and the area is given as A, the stress in the member is 
$${{{\sigma}}} = \frac{F}{A}$$

if the stress is set at a value equal to the allowable stress, The minimum required area for the steel member is solve as 

$$A_{min} = \frac{F}{{\sigma}_{all}}$$

As a first step in the design process. follow the summary table below:


| Member Number | Combination Force (DSTL4) | $$A_{min} = \frac{Force}{{\sigma}_{all}}$$ | $$ A_{required} = A_{min} + margin$$ |
|---------------|---------------------------|---------------------------------:|----------------------------------|
| 1             |                           |                                  |                                  |
| 2             |                           |                                  |                                  |
| ...           |                           |                                  |                                  |

$$DSTL4 = (All\space Live\space Loads) + (Dead\space Loads)$$

Note : the margin is an estimated number that needs to be added in order to find the final area that must be used for each member, and that is the largest area obtained for that member for the different loading conditions considered. 

___

**STEP 2: Assign the new required areas to the bridge steel members**

1. Check the [W-Beams - American Wide Flange Beams](https://www.engineeringtoolbox.com/american-wide-flange-steel-beams-d_1319.html) or [S-Beams](https://www.engineeringtoolbox.com/american-standard-beams-d_1320.html) and select the proper cross section area (e.g. W10x68 for 20in^2) calculated in the previous step.
2. In SAP2000 select a member that you want to change the cross section then follow step 3 in the tutorial to assign it.
3. Check the safety of a design again and make sure your member is optimum in terms of cost and not overstressed (green Color)

The following video demonstrate how to assign a cross section and check the safety of design.

___

**STEP 3: Cost analysis**

After finding the area required for each member, use this [excel file template](/engineering/courses/mae101/docs/cost_calculation.xlsx) to calculate the volume V of each member. the volume is given by :

$$V = A.L$$

Where A is cross sectional area of the member and L is the length of member. After finding the volume calculate the weight of each element using the specific weigth of steel.

- Steel cost $560 per ton 
- Concrete cost $50 per cubic yard 
- Calculate only the material cost for the steel members and roadway (neglect connections and 
Labor costs)

{{% notice info %}}
Need help? join the [slack channel](https://lagccmaelab.slack.com/) to request support
{{% /notice %}}

### Robot Design Module

![ER-4U](https://intelitek.com/wp-content/uploads/2020/01/A_RBTC_P_RoboticsAutoTechCompFullSolution_644x350.jpg)

Robotics and Automation Project is an engaging simulation of the industrial automated manufacturing process. Teams of two students layout and program a robotic production system as a solution to the project scenario.

For this project students will use The ScorBot ER-4U robot arm 3D simulation software that simulate the same Robot arm we have in our enineering Lab at LaGuardia Community Collge. The robot's speed and repeatability make it highly suited for both stand-alone operations and integrated use in automated workcell applications such as robotic welding, machine vision, CNC machine tending and other FMS operations The robot is supported by ScorBase robotics programming and control software. The software provides dynamic simulation of the robot and workcell devices during position teaching and program execution. The robot is designed to enable observation of its working mechanical parts while ensuring a safe environment for students.

**Example Applications**

- ER 4U with Machine Tending (Milling/Turning/Laser Engraver)
- ER 4U with SkillsUSA materials handling package (RAT – Robotic Automation Technology)
- ER 4U with ASRS (Automated Storage and Retrieval System)
- ER 4U with machine vision system from Cognex for Quality Control

### Student Activities

{{< youtube s_vWStKa_KM >}}

The robot Design Module activities and ER-4U simulation sotftware tutorial will be accessible from [the LearnMate platform](https://laguardiacommcollege.intelitek.com). Please follow below steps to get access to course content:

1. Step 1 [Creating an Account :](https://laguardiacommcollege.intelitek.com/login/signup.php) When accessing the site for the first time, you need to create an account with your profile information and a password. 
2. **Step 2 Logging In** Before you can login, you must activate your account with the link sent to your email address. If you did not receive this email, please check your junk/spam folder.
3. **Step 3 Join your course:** After logging in click **Fundamentals of Robotics for SCORBOT-ER4u** course to join. You'll be asked for a course enrolment key, Enter the enrollment key supplied by your instrucor. 
Step 4 Installing Required Utilities :
	- [LM Agent Software](http://helpcenter-lm73.intelitek.com/learnmate/lmAgentSetup.exe) : The LM Agent enables students to lincense and operate the RobotCell software. The required simulation and control software can be launched and controlled directly from the LearnMate environment using the LM Agent. The LM Agent, which utilizes ActiveX technology, runs in the background until required by links in the modules.
	![lmagent](/engineering/courses/mae101/docs/lmagent.png)
	- Download ER-4U RobotCell simulation software {{% button href="https://downloads.intelitek.com/Software/Robotics/ER-4u/Robocell_Scorbase_Setup_2020%20B2.exe" icon="fas fa-download" icon-position="right" %}}From Here{{% /button %}}

{{% notice note %}}
In order to license and use the RobotCell Software, RoboCell needs to be launched from the course content. You don't need to remain logged into the content or even the site, but you must launch the software from one of the many links found within the course activity. Once that’s done, this process temporarily licenses the software for 3-4 hours, and at that point LearnMate can be exited, minimized, etc. When the temporary license expires, you can log back into the content, click another launch link again to re-apply the license and they’re good to go for another 3-4 hours. 
{{% /notice %}}

To launch the software go to activity 3 and navigate to **Running RoboCell and Opening a Project** (9/51) in the content click the link where it says "Click here to open the project for this activity in RoboCell." the software will launch without any licensing request.

More details in this short [manual](/engineering/courses/mae101/docs/robocell_install.pdf) 

![Robotcell](/engineering/courses/mae101/docs/robotcell.png)

