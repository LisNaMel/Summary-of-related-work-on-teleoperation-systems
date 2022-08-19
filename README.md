# Summary-of-related-work-on-teleoperation-systems

# Teleoperation System

## 1. Common Educational Teleoperation Platform for Robotics Utilizing Digital Twins: [source](https://www.mdpi.com/2075-1702/10/7/577/htm)
published: 17 July 2022
#### Note: 
Based on my opinion, this paper is very similar to what we are currently doing. It's well explained how they develop their platform, but the purpose of their lessons and how they evaluate the result of students is vaguely mentioned. 
1. Reason for the study
 - Aim to decrease educational inequality
 - Prepare a solution to an impractical situation for doing laboratories with happen more frequently, 
   such as pandemic restrictions, natural disasters
 - To provide robotics knowledge via teleoperation platform 
2. Hypothesis
 - By providing a platform that allows teleoperation, remote programming, and near real-time monitoring of controlled robots, 
   and social interaction between users will improve the accessibility of high-cost equipment and the learning of robotics. 
3. Method
  - Method utilized in this work [source](https://www.mdpi.com/machines/machines-10-00577/article_deploy/html/images/machines-10-00577-g002.png)
  - Result of requirement determination is shown as [function requirement](https://www.mdpi.com/2075-1702/10/7/577/htm#:~:text=Table%201.%20Functional%20requirements.) and [non-functional requirement](https://www.mdpi.com/2075-1702/10/7/577/htm#:~:text=Table%202.%20Non%2Dfunctional%20requirements.)
  - System architecture ![](https://www.mdpi.com/machines/machines-10-00577/article_deploy/html/images/machines-10-00577-g003.png)
  - After implementing the proposed platform, it's evaluated by a group of 20 students on the same course
4. Result
  - Based on the feedback, the platform provides the required functionalities and is suitable for robotics online education and training.

## 2. Web Compliant Open Architecture For Teleoperation of Industrial Robots : [source](https://ieeexplore.ieee.org/document/8842847/metrics#metrics)
published: 22 August 2019
#### Note:
This paper focuses on the compatibility and efficiency of the technology used to develop a teleoperated system.
1. Reason for the study
  - Aim to find a suitable combination of industrial robotic teleoperation systems.
2. Hypothesis
  - This paper proposes eight parameters for comparing teleoperation systems. 
  - They present eight parameters as follows: P1 Security, P2 Manufacturing applications, P3 Open Source, P4 Proprietary robotic system compatibility, P5 Network connectivity, P6 Industrial robot application, P7 Real validation with robots, and P8 non-dependency solution.
3. Method
- Develop [proposed architecture](https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/8827189/8842826/8842847/toqui1-P0225-large.gif)
- To validate the result, it was implemented with the industrial robot to perform a specific task in both virtual and physical environments.
4. Result
- Capable of implementing proposed architecture which includes all eight comparing parameters. 

## 3. Hands-on experiences of undergraduate students in Automatics and Robotics using a virtual and remote laboratory: [source](https://www.sciencedirect.com/science/article/pii/S0360131511001515)
published: December 2011
#### Note: 
The expected knowledge of the student is described in detail. They also present variant perspectives of how virtual laboratories affect students.
1. Reason for the study
- Aim to provide sufficient real laboratory experiences, which simulation tools cannot substitute for the student.
2. Hypothesis
- Implementing a VRL (Virtual Remote Laboratory) for learning Robotics which allows users to simulate and command a robot with augmented reality support, will increase accessibility and give practical laboratory experimentation to students.
3. Method
- Develop [hardware and software of VRL](https://ars.els-cdn.com/content/image/1-s2.0-S0360131511001515-gr1.jpg)
- Set up lesson components such as Kinematics, path planning, environment modeling, Dynamics, and Programming
- Collect several statistical studies from Computer Science Engineering students between 2003 and 2010
4. Result 
- Capable of increasing students' study hours by 50 percent and improving in other aspects as shown below.
![](https://ars.els-cdn.com/content/image/1-s2.0-S0360131511001515-gr6.jpg).

# Manipulator Control

## 1. Augmented reality-assisted robot programming system for industrial applications : [source](https://www.sciencedirect.com/science/article/pii/S0736584519300250#sec0002)
published: February 2020
#### Note:
An interesting alternative to robot programming which is simpler, faster, and more intuitive.
1. Reason for the study
- Aim to reduce the difficulty for small and medium enterprises to program robots to perform diverse tasks which require high cost and necessary skills.
- To propose faster and more intuitive robot programming than conventional techniques
2. Hypothesis
- Augmented Reality assisted robot programming system (ARRPS) that the authors proposed will allow users with little robot programming knowledge to program tasks for a serial robot.
3. Method
- Implement ARRPS as shown:
![](https://ars.els-cdn.com/content/image/1-s2.0-S0736584519300250-gr4.jpg)
- Using an HMD and a handheld pointer for robot motion planning.
- Using a Kinect2 sensor to track and reconstruct physical objects.
- The Open Motion Planning Library (OMPL) is used in robot motion planning module.
- Kinematics and Dynamics Library (KDL) is used to generate the motion of a virtual robot based on the path demonstrated by the user through manipulating the handheld pointer.
- A prototype of ARRPS has been implemented and applied to two applications, welding, and pick-and-place operations.
4. Result
- The average time to complete for the wilding and pick-and-place through ARRPS is 63s and 34s, respectively, while using teach pendant took an average of 347s and 177s. 

## 2. Strategies for remote control and teleoperation of a UR robot: [source](https://upcommons.upc.edu/handle/2117/333559)
published: 3 August 2020
#### Note: 
This project presents pros and cons of each methodology for teleoperaing Universal Robot (UR).
1. Reason for study
- Want to promote the use of the UR robot
2. Hypothesis
- By creating a tookit easy to understand which allow students to develop their projects with this toolkit as a base, will promote the use of the UR robot.
3. Method
- Determines project objective
- Explores different options of methodoloies, then classify those options to their suitable tasks.
- UR3 Teleoperation methods comparison table: [link](https://gist.github.com/LisNaMel/d091e20c70c0d69514f9b27a978a55db)
- Selects the following protocols to develop toolkit:
Data acquisition → Modbus
Remote control → TCP/IP Real Time
Dynamics → XML-RPC
Remote Maintenance → TCP/IP Dashboard & FTP (SFTP)
Remote Access → SSH
- Develops an application using the toolkit as a demonstration of toolkit functionalities.
- Evaluates utility of the whole project compare to current commercial solutions.  
4. Result
The toolbox can be download from [authors' github](https://github.com/SergiPonsa/UR-Communication-SergiPonsa).
Toolkit is proved to be useful and compete with commercial options at lower cost.


# Article

## 1. Special issue on educational robotics : [source](https://www.sciencedirect.com/science/article/pii/S0921889015003164)
published: March 2016
#### Note:
Educational Robotics is a growing field of interest that has revealed great potential in education at all levels, from kindergarten to university. Despite the remarkable progress made in recent years, several issues are still open:
 - Difficulties synergize with school curricula, including lack of creativity and flexibility.
 - Most uses of robotics in school do not support the development of 21st-century skills as intended.
 - The Bias on an accessible group that focuses on gifted children or is gender-biased.
 - Lack of reliable experimental design on how robotics can affect learning achievements.
