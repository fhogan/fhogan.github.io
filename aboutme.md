---
layout: page
title: Research Projects
subtitle: Research Projects
---

My primary research objective is to enable reactive robotic manipulation. The ability to perceive the environment and react to unanticipated events is of paramount importance to deploy robots that are to interact with the physical world, which is difficult to observe and predict. Whereas humans effectively process and react to sensing information, robot manipulation skills are most often programmed in an open- loop fashion, incapable of correcting their motion based on detected errors.
My research aims to enable robots skilled at i) monitoring the execution of a task, and ii) using sensed information in real-time for closed-loop control. Giving robots the ability to identify mistakes and correct their behavior in a timely fashion is essential for them to purposefully interact with their environment.

---


<!-- Entry 1 -->
  <hr>
  <h3>
    Tactile Regrasps
  </h3>
  <p>
		<img src="/img/tactile_regrasp_horizontal.png" alt="Tactile" style="float:right;width:40%;" hspace="25" vspace="50">
	</p>
  <p>
		Endowing robots with reactive capabilities requires a tight integration of sensors, actuators, and computation. 
        These requirements have led to the design and fabrication of an optical-based tactile sensor inspired from 
        Gelsight [2] that renders high resolution images of the contact surface geometry.
        In [3], we develop tactile reflexes, giving robots the ability to make grasp adjustments immediately 
        upon making contact with an object. Tactile information shown in Fig. 1(b) is used to assess in real-time 
        the quality of a grasp and predict failures preemptively. 
	</p>
  <p>
Results show that tactile signatures captured 
        during a grasp are discriminative and can predict the outcome of grasps with an accuracy of 85%. 
        Moreover, we leverage the grasp stability metric to design a controller able to perform local grasp 
        adjustments, where grasp are improved directly upon making initial touch with an object. In Fig. 1(c), 
        after making an initial grasp on the object, the gripper adjusts its position to improve the grasp 
        quality of the tactile imprint. This re-positioning allows the robot to secure a better grasp on the 
        object and improves the overall grasping accuracy by 70%. The ability to react to contact information 
        is crucial to identify failures preemptively and make corrections in real-time.
	</p>
  <p>
    test
  </p>
