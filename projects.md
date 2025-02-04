---
layout: page
title: Projects
permalink: /projects/
---

## Current

Initially with [Open Robotics](https://www.openrobotics.org/) and now with [Intrinsic](https://www.intrinsic.ai/) I have been developing and leading the [Open-RMF](https://www.open-rmf.org/) project. Initially driven by the Ministry of Health and the National Robotics Program in Singapore, the Open-RMF project provides an open source software framework for orchestrating multiple fleets of robots (which may be different robot platforms provided by different vendors) within one smart facility. It automates the ability of the mobile robots to share space, use automatic doors, and use lifts to travel between floors.

Moving forward, we are expanding the scope of Open-RMF to cover all forms of multi-agent autonomous system orchestration, not just mobile robots. You can find a quick overview in [these slides](https://docs.google.com/presentation/d/1aLuioGh97FMIaAtBr7Li7NC1qcXjEoRr_3T7JGs7n2o/edit#slide=id.p) presented at ROSCon 2024.

If this topic interests you, feel free to join any of the following regular events:
* Open-RMF Project Management Committee meetings, every other Tuesday @ 9am SGT
* Interoperability Special Interest Group, the first Thursday of every month @ 11pm SGT
Both can be found on the [Official OSRF Events Calendar](https://calendar.google.com/calendar/embed?src=agf3kajirket8khktupm9go748%40group.calendar.google.com&ctz=UTC).

## Past

As a graduate student, most of my open-source software development centered around [DART](http://dartsim.github.io/) (Dynamic Animation and Robotics Toolkit). DART began as a collaborative effort at Georgia Tech between the labs of [Mike Stilman](http://robotics.gatech.edu/hg/item/295611) and [Karen Liu](http://www.cc.gatech.edu/~karenliu/Home.html). Since then, the community has been grown to include [Personal Robotics Lab](https://personalrobotics.ri.cmu.edu/) at CMU and [Open Robotics](https://www.openrobotics.org/) via the [Gazebo](https://gazebosim.org/home) project.

I was one of the primary contributors and co-maintainers (my official title was *project co-director*). For DART-5.0, I made major revisions to the API, implemented lazy evaluation, modernized the memory management system, introduced "frame semantics" (which allows all kinematic data to be handled in arbitrary reference frames), created an extensible whole body inverse kinematics module, and wrote an [OpenSceneGraph](http://www.openscenegraph.org/) interface which allows users to create customizable 3D GUIs for visualizing and interacting with DART simulations. In DART-6.0, I rolled out an extensible *State* and *Properties* system which allows users to augment the native dynamics information of DART with their own custom state and model data.

DART was awarded the Grand Prize of the [2016 Open Source Software World Challenge](https://dartsim.github.io/grand_prize_of_OSS.html).

{% include image.html file="dart_logo_big.jpg" url="https://dartsim.github.io/" alt="DART Logo" max-width="360" caption="" %}

I was one of the primary contributors and maintainers of [hubo-ach](https://github.com/hubo/hubo-ach), which was a low-level teleoperation software layer used during the DARPA Robotics Challenge trials by Team DRC-HUBO. The code was written on a tight schedule by programmers with little knowledge or experience, but it did what it needed to do. The work taught me some valuable lessons in recognizing anti-patterns and the importance of maintainable design.

Following the DRC Trials, the Georgia Tech sub-team (of which I was a member) withdrew from Team DRC-HUBO so that our lab could return its focus to academic research. At that time, I began solo work on [HuboCan](https://github.com/golems/HuboCan/), meant to replace hubo-ach and leverage the lessons that I learned along the way. Due to unfortunate circumstances, HuboCan was never completed, and the project is now defunct.
