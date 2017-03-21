---
layout: page
title: Projects
permalink: /projects/
---

## Current

Most of my open-source software development effort over the last few years has been dedicated to [DART](http://dartsim.github.io/) (Dynamic Animation and Robotics Toolkit). DART began as a collaborative effort at Georgia Tech between the labs of [Mike Stilman](http://robotics.gatech.edu/hg/item/295611) and [Karen Liu](http://www.cc.gatech.edu/~karenliu/Home.html). Since then, the community has been growing, and we are now joined by the [Personal Robotics Lab](https://personalrobotics.ri.cmu.edu/) at CMU.

My role in DART has been as one of the primary contributors and co-maintainers for the last two and half years (my official title is *project co-director*). For DART-5.0, I made major revisions to the API, implemented lazy evaluation, modernized the memory management system, introduced "frame semantics" (which allows all kinematic data to be handled in arbitrary reference frames), created an extensible whole body inverse kinematics module, and wrote an [OpenSceneGraph](http://www.openscenegraph.org/) interface which allows users to create customizable 3D GUIs for visualizing and interacting with DART simulations. In DART-6.0, I rolled out an extensible `State` and `Properties` system which allows users to augment the native dynamics information of DART with their own custom state and model data.

DART was recently awarded the Grand Prize of the [2016 Open Source Software World Challenge](http://ossaward.org/eng/m0101.do).

{% include image.html file="dart_logo_big.jpg" url="https://dartsim.github.io/" alt="DART Logo" max-width="360" caption="" %}

## Past

I was one of the primary contributors and maintainers of [hubo-ach](https://github.com/hubo/hubo-ach), which was a low-level teleoperation software layer used during the DARPA Robotics Challenge trials by Team DRC-HUBO. The code was written on a tight schedule by programmers with little knowledge or experience, but it did what it needed to do. The work taught me some valuable lessons in recognizing anti-patterns and the importance of maintainable design.

Following the DRC Trials, the Georgia Tech sub-team (of which I was a member) withdrew from Team DRC-HUBO so that our lab could return its focus to academic research. At that time, I began solo work on [HuboCan](https://github.com/golems/HuboCan/), meant to replace hubo-ach and leverage the lessons that I learned along the way. Due to unfortunate circumstances, HuboCan was never completed, and the project is now defunct. If you happen to be interested in potentially using HuboCan to operate a Hubo, you are welcome to contact me, but the amount of time that I can dedicate to technical support will be very limited.
