---
layout: page
title: Research 
---

<br /> 
<br /> 
<font face="arial" color="black"  >
My primary research objective is to enable reactive robotic manipulation, moving towards robots that can better perceive their environment and react to unforeseen situations. 
My research aims to enable robots skilled at i) monitoring the execution of a manipulation task, and 
ii) using sensed information in real-time for closed-loop control. I am particularly interested in developing reactive manipulation policies relying on visual and tactile feedback for contact-rich robotic manipulation tasks where the
  dynamics are  dominated by frictional interactions. 
  </font>


<!-- Entry 1 -->
  <hr>
  <h3>
	   <font face="arial" color="black">
    Hybrid Feedback Control For Contact Interactions
     </font>
  </h3>
  <p>
		<img src="/img/hybrid_behavior.png" alt="Tactile" style="float:right;width:45%;" hspace="25" vspace="20">
	</p>
  <p>
	  <font face="arial" color="black">
        We investigate investigates real-time control strategies 
        for dynamical systems that involve frictional contact interactions. 
        Hybridness and underactuation are key characteristics of these systems 
        that  complicate the design of feedback controllers.
        
  Our results show that a Model Predictive Control approach used in tandem 
  with integer programming offers a powerful solution to capture the dynamic 
  constraints associated with the friction cone as well as the hybrid nature 
  of contact.
 		<font>
  
  <p>
    <a href="https://arxiv.org/abs/1611.08268"
    class="button" style="vertical-align:middle"><span>WAFR 2016</span></a>
    <a href="https://arxiv.org/abs/1710.05724"
    class="button" style="vertical-align:middle"><span>ICRA 2018</span></a>
  </p>

  
<!-- Entry 2 -->
  <hr>
  <h3>
   <font face="arial" color="black">
		Data-Efficient Control for Planar Manipulation     
    </font> 
  </h3>
  <p>
		<img src="/img/pushing_8_track.png" alt="Tactile" style="float:right;width:45%;" hspace="25" vspace="20">
	</p>
  <p>
	  <font face="arial" color="black">
        This paper explores the data-complexity required to control manipulation tasks with a model-based approach, 
        where the model is learned from data. We employ this methodology to the problem of pushing an object on a planar 
        surface, and find that we can design effective control policies with  small data requirements 
        (less than $10$ datapoints) while achieving accurate closed-loop performance.
		<font>
	</p>
  <p>
    <a href="https://arxiv.org/abs/1807.09904"
    class="button" style="vertical-align:middle"><span>CoRL 2018</span></a>
  </p>
  
<!-- Entry 3 -->
  <hr>
  <h3>
   <font face="arial" color="black">
		Autonomous Grasping      
    </font> 
  </h3>
  <p>
		<img src="/img/ARC_w_background.png" alt="ARC" style="float:right;width:25%;" hspace="25" vspace="20">
	</p>
  <p>
	  <font face="arial" color="black">
        During the period 2015-2017, I participated in the Amazon Robotics Challenge (ARC) as part of team MIT-Princeton. 
        The challenge involved developing  a robotic system capable of recognizing and grasping novel objects in cluttered 
        environments. Our approach made use of an object agnostic deep learning framework that directly maps visual 
        observations  to planned robot motion. This work has led to a 
        1st place in the 2017 stowing task challenge as well as a 2018 Amazon Best System Paper Award.
		<font>
	</p>
  <p>
    <a href="https://ieeexplore.ieee.org/abstract/document/8461044/"
    class="button" style="vertical-align:middle"><span>ICRA 2018</span></a>
  </p>
  
<!-- Entry 4 -->
  <hr>
  <h3>
   <font face="arial" color="black">
		Tactile Regrasping
    </font> 
  </h3>
  <p>
		<img src="/img/tactile_regrasp_vertical.png" alt="Tactile" style="float:right;width:45%;" hspace="25" vspace="20">
	</p>
  <p>
	  <font face="arial" color="black">
        In this project, we develop tactile reflexes, giving robots the ability to make grasp adjustments immediately 
        upon making contact with an object. Tactile information is used to assess in real-time 
        the quality of a grasp and predict failures preemptively and to design a controller able to perform local grasp 
        adjustments, where grasp are improved directly upon making initial touch with an object. 
        <font>
	</p>
  <p>
    <a href="https://arxiv.org/abs/1803.01940"
    class="button" style="vertical-align:middle"><span>IROS 2018</span></a>
  </p>
