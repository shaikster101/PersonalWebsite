+++
title = "Research"
date = "2014-04-09"
aliases = ["work","research","publications"]
+++

## ***Kinect VR Rehabilitation/Exercise System***

**Status:** In-Progress

**Description:** Research Project to integreate a Kinect 2 Sensor with a VR Headset to give the user realtime feedback on excercise posture using `Fast Dynamic Time Warping` to compare the user pose to that of a professional. The Goal of this project is to validate the use of such a system for remote rehabilitation uses. 

---

## ***Mobile, Egocentric Human Body Motion Reconstruction Using Only Eyeglasses-mounted Cameras and a Few Body-worn Inertial Sensors***

**Status:** Submitted to IEEEVR2021

**Abstract:** We present a standalone real-time system for the 3D capture of an individual, relying only on cameras embedded into a `head-worn device` and `Inertial Measurement Units` (IMUs) worn on the wrists and ankles of the user. We envision that head-worn augmented reality (AR) systems would one day shrink to the size of everyday prescription eyeglasses with a wide-field-of-view (FOV) AR display, and that the proposed 3D capture of user experiences could become a commonplace feature of such head-worn devices.

Our goal is a fully mobile telepresence system, relying on widely available wearable technology, embedded in commonly worn accessories: cameras in eyeglasses, IMUs in wristwatches and shoes. While this approach allows for convenient, unobtrusive capture, reconstruction and communication of experiences at any indoor or outdoor location, it also introduces new challenges.

When using an eyeglasses-frame form factor headset for video capture, the user's limb motions are frequently unobservable by the head-worn cameras, due to self-occlusion, occlusion by the body, or being outside the camera views. Prior egocentric capture head gear featured cameras obtrusively mounted farther away from the face, which allowed better body and limb visibility, but are unacceptable for daily use. Similarly, prior approaches for 3D pose reconstruction using IMUs require too many sensors to be adopted in daily use, even with miniaturization. On the other hand, reducing the number of sensors results in pose ambiguities.

Our egocentric reconstruction of the wearer's geometry is performed via learning-based pose estimation, which fuses inputs from visual and inertial sensors that complement each other, overcoming problems such as inconsistent limb visibility, as well as IMU pose ambiguity and measurement noise. At each time instant, the user's pose is re-targeted to a surface model, resulting in a high-fidelity reconstruction.

We demonstrate our system by reconstructing various human body movements and show that our visual-inertial learning-based method, which runs at 30 Hz, outperforms both visual-only and inertial-only approaches. We captured an egocentric visual-inertial 3D human pose dataset, which we plan to make publicly available for training and evaluating similar reconstruction methods.

![](/img/research/ego-out.PNG)

--- 

## ***Project North Star***

**Status:** On-Hold

**Description:** The goal of this project was to build an opensource AR headset with a 90 degree FOV and augment it with 6 Degrees of Freedom to test how wider FOV could be levraged in AR training excercises. 

--- 

## ***Data-driven modeling of group entitativity in virtual environments***
**Status:** Accepted at CPVR 2018

**Abstract:** We present a data-driven algorithm to model and predict the socio-emotional impact of groups on observers. Psychological research finds that highly entitative ie cohesive and uniform groups induce threat and unease in observers. Our algorithm models realistic trajectory-level behaviors to classify and map the motion-based entitativity of crowds. This mapping is based on a statistical scheme that dynamically learns pedestrian behavior and computes the resultant entitativity induced emotion through group motion characteristics. We also present a novel interactive multi-agent simulation algorithm to model entitative groups and conduct a VR user study to validate the socio-emotional predictive power of our algorithm. We further show that model-generated high-entitativity groups do induce more negative emotions than low-entitative groups.

![](/img/research/enti.PNG)
