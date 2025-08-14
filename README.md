# 16-741: Mechanics of Manipulation (Fall 2025)

## Course Info

#### [Syllabus](https://docs.google.com/document/d/1Ra-eJYID1UHVQEjCREWakrx9h5TW2WKno_sdeM9qrmg/edit?usp=sharing)  

**Time**: Monday & Wednesday 11:00 AM - 12:20 PM  
**Location**: NSH 1305  
**Instructor**: [Zackory Erickson](https://zackory.com)  
**Office Hours**: Upon request  

---

## Course Description

Mechanics of Manipulation is a graduate level course that dives into the fundamentals of robotic manipulation. Through this course you will learn the kinematics, statics, and dynamics of robotic manipulators as they interact with the world to accomplish tasks. You will gain experience with the intelligent use of kinematic constraint, gravity, and frictional forces. Additional topics include rigid body mechanics, automatic planning based on mechanics, deformable manipulation, and simulation of dynamic manipulation. Applications of robotic manipulation are drawn from physical human-robot interaction, manufacturing, and other domains.

## Textbooks

Mechanics of Robotic Manipulation, by Matthew T. Mason. MIT Press, 2001.  
[PDF textbook](https://direct.mit.edu/books/book/3869/Mechanics-of-Robotic-Manipulation)  
[Errata page](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/Errata.txt)

Robotic Manipulation, by Russ Tedrake. 2023.  
[PDF textbook](https://manipulation.csail.mit.edu/index.html)  
[Lecture videos](https://youtube.com/playlist?list=PLkx8KyIQkMfWr191lqbN8WfV08j-ui8WX&si=qR_BSYDIyRHOjkw-)

Modern Robotics: Mechanics, Planning, and Control, by Kevin M. Lynch and Frank C. Park. Cambridge University Press, 2017.  
[PDF textbook](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf)  
[Lecture videos](https://modernrobotics.northwestern.edu/nu-gm-book-resource/introduction-autoplay/)

## Additional Resources
[Toward Robotic Manipulation](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/Mason2018.pdf). Matthew T. Mason. _Annual Review of Control, Robotics, and Autonomous Systems_, 2018.


## Schedule

| Date | Topic | Notes |
|---|---|---|
| **Week 1** <br> Mon, <br> Aug 25 | Introduction | [Syllabus](https://docs.google.com/document/d/18LLbaWV4n5VTQ_BaUNIG60inzvl8auBHWeLrcKfUpIc/edit?usp=sharing) <br> Install [Manipulation Engine](https://github.com/Zackory/mengine) |
| **Week 1** <br> Wed, <br> Aug 27 | Let's get you a robot | [Modern Robotics, Chapter 11.4](https://modernrobotics.northwestern.edu/nu-gm-book-resource/11-4-motion-control-with-torque-or-force-inputs-part-3-of-3/) <br> [Robotic Manipulation, Chapter 2](https://manipulation.csail.mit.edu/robot.html) <br> [Manipulation Engine](https://github.com/Zackory/mengine/tree/main) |
| **Week 2** <br> Mon, <br> Sept 1 | No class; Labor Day |   |
| **Week 2** <br> Wed, <br> Sept 3 | Kinematic Foundations | **Assignment 1 released** <br> [Mechanics of Robotic Manipulation, Chapter 2.1](https://direct.mit.edu/books/monograph/3869/chapter-abstract/162858/Kinematics?redirectedFrom=fulltext) <br> [Modern Robotics, Chapter 2](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 3** <br> Mon, <br> Sept 8 | Spatial Rotation Representations | [Mechanics of Robotic Manipulation, Chapter 3](https://direct.mit.edu/books/monograph/3869/chapter-abstract/162859/Kinematic-Representation?redirectedFrom=fulltext) <br> [Robotic Manipulation, Chapter 3.3](https://manipulation.csail.mit.edu/pick.html#spatial_algebra) <br> [Modern Robotics, Chapter 3.2](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 3** <br> Wed, <br> Sept 10 | Forward and Inverse Kinematics | [Robotic Manipulation, Chapters 3.4 - 3.6](https://manipulation.csail.mit.edu/pick.html#kinematics) <br> [Modern Robotics, Chapters 4 and 6](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 4** <br> Mon, <br> Sept 15 | Quaternions | [Mechanics of Robotic Manipulation, Chapter 3.1](https://direct.mit.edu/books/monograph/3869/chapter-abstract/162859/Kinematic-Representation?redirectedFrom=fulltext) <br> [Modern Robotics, Appendix B.3](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 4** <br> Wed, <br> Sept 17 | Planar Kinematics | **Deadline: Assignment 1** <br> **Assignment 2 released** <br> [Mechanics of Robotic Manipulation, Chapter 2.2](https://direct.mit.edu/books/monograph/3869/chapter/162858/Kinematics) <br> [Modern Robotics, Chapter 2.2](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 5** <br> Mon, <br> Sept 22 | Spatial Kinematics I - Plucker Coordinates | [Mechanics of Robotic Manipulation, Chapter 2.3](https://direct.mit.edu/books/monograph/3869/chapter/162858/Kinematics) <br> [Modern Robotics, Chapter 3.3](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 5** <br> Wed, <br> Sept 24 | Spatial Kinematics II - Screw Coordinates | [Mechanics of Robotic Manipulation, Chapter 2.3](https://direct.mit.edu/books/monograph/3869/chapter/162858/Kinematics) <br> [Modern Robotics, Chapter 3.3](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 6** <br> Mon, <br> Sept 29 | Pick & Place and Path Planning (taught by Yufei Wang) | [Mechanics of Robotic Manipulation, Chapter 4.1](https://direct.mit.edu/books/monograph/3869/chapter/162860/Kinematic-Manipulation) <br> [Robotic Manipulation, Chapter 3](https://manipulation.csail.mit.edu/pick.html) |
| **Week 6** <br> Wed, <br> Oct 1 | Constraint and  Reuleaux's Method | **Deadline: Assignment 2** <br> **Assignment 3 released** <br> [Mechanics of Robotic Manipulation, Chapter 2.3](https://direct.mit.edu/books/monograph/3869/chapter/162858/Kinematics) <br> [Modern Robotics, Chapter 2.5](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) |
| **Week 7** <br> Mon, <br> Oct 6 | Representing Constraint | [Mechanics of Robotic Manipulation, Chapter 3.3](https://direct.mit.edu/books/monograph/3869/chapter/162859/Kinematic-Representation) |
| **Week 7** <br> Wed, <br> Oct 8 | Manipulation in Clutter | **Deadline: Project Proposal** <br> [Mechanics of Robotic Manipulation, Chapter 4.3](https://direct.mit.edu/books/monograph/3869/chapter/162860/Kinematic-Manipulation) |
| **Week 8** <br> Mon, <br> Oct 13 | No class; Fall break |   |
| **Week 8** <br> Wed, <br> Oct 15 | No class; Fall break |   |
| **Week 9** <br> Mon, <br> Oct 20 | Imitation Learning (taught by Yufei Wang) |   |
| **Week 9** <br> Wed, <br> Oct 22 | Deformable manipulation and Model-Predictive Control (taught by Yufei Wang) | **Deadline: Assignment 3** <br> **Assignment 4 released** |
| **Week 10** <br> Mon, <br> Oct 27 | Foundations of Statics |   |
| **Week 10** <br> Wed, <br> Oct 29 | Polyhedral Convex Cones |   |
| **Week 11** <br> Mon, <br> Nov 3 | Friction |   |
| **Week 11** <br> Wed, <br> Nov 5 | Planar Sliding | **Deadline: Assignment 4** <br> **Assignment 5 released** |
| **Week 12** <br> Mon, <br> Nov 10 | Pushing |   |
| **Week 12** <br> Wed, <br> Nov 12 | Grasps, Fixtures, Closures |   |
| **Week 13** <br> Mon, <br> Nov 17 | Force Control |   |
| **Week 13** <br> Wed, <br> Nov 19 | Rigid Body Dynamics |  |
| **Week 14** <br> Mon, <br> Nov 24 | Dynamics and Frictional Contact; Impact | **Deadline: Assignment 5** |
| **Week 14** <br> Wed, <br> Nov 26 | No class; Thanksgiving break | **Deadline (Nov 30): Google Slides for <br> your project presentation** |
| **Week 15** <br> Mon, <br> Dec 1 | Course Project Presentations |  |
| **Week 15** <br> Wed, <br> Dec 3 | Course Project Presentations | **Deadline: Course project paper** |



## Course Project
Each student must do a course project. This project is due by the end of the semester. The project will begin with a proposal, which should be a page or less. It should clearly describe what you intend to do. Students should expect to spend from 20 to 40 hours on the project. Course project reports will be due at the end of the semester. The final report will be in IEEE format and should detail your project motivation, methodology, implementation, and results. You will also be given the option to upload a video to accompany your report (optional, but can be very helpful if your work is visual, and most robotics applications are quite visual). Projects may be a small manipulation problem to which you will apply some techniques learned in class, some extension or variation of a technique learned in class, or a review and implementation of a research paper related to the class material.

Experimental projects are encouraged, using any accessible robotic equipment. If you are interested in using a robotic arm but do not have access to one, please contact me. We can get you access to the AI Maker Space on campus, which has several robotic manipulators you can use. Experimental projects can be time-consuming, and if you choose this option the 20-40 hour guideline above does not apply.

Team projects are also fine, with up to 2 students.

Your project may be related to your outside research project or another class project, but should be clearly separate from it.

How do you find a good topic? Life is full of manipulation problems, most of which have never been studied. Or if you want to view locomotion as auto-manipulation, you can study a locomotion problem. Cooking, cleaning, origami are all sources of numerous different manipulation techniques. Games are also good sources. Paper football, tiddly-winks, curling, bowling, shuffleboard, horseshoes, eraser wars, are all manipulation problems in competitive settings. Every such application gives rise to numerous little research problems, when you look at it carefully enough.

If you have some ideas but could use some help focusing on a clearly defined manageable problem, I'd be glad to discuss it with you.

Below are a few final project submissions from prior years:  
(2023): [Sample 1](papers/final_logstructures.pdf), [Sample 2](papers/final_flow.pdf)  
(2016) (not in IEEE format): [Sample 1](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/sample_projects/yifanh_project.pdf), [Sample 2](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/sample_projects/spurushw_report.pdf)

1. Here are some titles of recent projects, to give you some ideas of suitable topics:
    * Data-driven approach to object centric hand-grasp classification
    * Study of human writing process
    * Stir-frying
    * Touch based exploration of object inertial properties for grasping
    * Dynamic modeling and control of push-roll locomotion
    * Coordinated manipulation
    * RoboCup SSL non-kicker manipulation
    * Hand kinematics of piano playing
    * Contact force optimization for trunk stabilization in snake monster (Hexapod)
    * Design a fully automated stair climbing robot luggage
    * 3D object shape, position and trajectory estimation for manipulation
    * Object pose estimation from visual and tactile sensors
    * Drum master
    * Prehensile analysis using first-person video
    * Manipulating moving objects
    * Manipulating buttons, zippers, or other elements that require fine-motor control
    * Manipulation of cloth
    * Pouring liquid or manipulating deformable materials (such as dough)
    * Using chopsticks
2. Here is a proposal to give you an idea of the expected level of detail and organization:

    > Title: Pouring liquids  
    > Team: Moe, Curly
    > 
    > We have seen some videos of robots pouring liquids, but they do not look as good as people pouring liquids, for example:  
    > (A video of a human pouring)  
    > (A video of a robot pouring)
    > 
    > It is obvious the person is better, but not obvious exactly why. What is the objective that should be optimized? To explore that, we will devise a very simple two-dimensional simulator that pours liquid from one container into another. The pouring motion will be represented as a path in the container configuration space interpolating through a set of control points. We will formulate several different objective functions, and optimize the choice of control points for each objective, and then compare the outcomes.
    > 
    > The objectives we will explore are:
    > * minimum time to fill the receptacle
    > * least spillage within a given time
    > * (and some others)
    > 
    > This project is close to my research with Professor Groucho, but that work is focused entirely on inviscid beverages, and this project will focus on molasses.

## Credit

This course was originally developed by [Prof. Matthew Mason](https://www.ri.cmu.edu/ri-faculty/matthew-t-mason/), which he taught for over 30 years at CMU.
