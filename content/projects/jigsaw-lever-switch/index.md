+++
title = "Jigsaw Lever Switch Quality Improvemen"
draft = false
weight = 7
summary = " "

[cover]
  image = "cover.png"
  alt = "Improved lever switch"
  relative = true
+++
 
Led root cause analysis and implemented validated geometry and tooling changes that eliminated recurring lever switch failures in a jigsaw SDS mechanism

--- 

**Content based on public sources and employer-approved shareable information**

---

### Overview
The lever switch used for blade release and replacement showed recurring failures during testing and representative use. I led the root cause analysis and implemented a validated design and production solution, supported by prototyping and FEA.

### Context
![The jigsaw](jigsaw.png)

![Lever switch fixing screw](lever-switch-screw.png)

![Lever switch](lever-switch.png)

![Exploded-view drawing with lever switch highlighted](exploded-view.png)

### Problem Statement
The issue was caused by a combination of design vulnerability, manufacturing variation, and in use deformation:
- A stepped inner-surface transition introduced a critical weak point
- Process deviations in production caused a key dimension to fall below tolerance
- User applied loads during sawing deformed the lever switch and led to interference near the lifting rod’s clamping sleeve

### User Interaction & Impact Evidence
![Normal position of the second hand during sawing](hand-normal.png)

![Second hand may be positioned lower, near the lever switch](hand-low.png)

![Close positioning to the lifting rod's clamping sleeve](close-to-sleeve.png)

![Impact marks on the lever switch](impact-marks.png)

![Key dimension of the lever switch](key-dimension.png)

### Observed Failure Modes
![Failure 1](failure-1.png)

![Failure 2](failure-2.png)

![Failure 3](failure-3.png)

### Solution Approach

Prototype Validation

To validate the solution, I built a prototype with revised internal geometry and an improved conditioning process, including an integrated 3D-printed insert:

![Prototype of the lever switch](prototype.png)

![Prototype mounted on the jigsaw](prototype-mounted.png)

![Test result showing impact mark, but part did not fail](test-result.png)

Design Finalization & Analysis

Following prototype validation, I finalized the revised 3D model and used FEA to confirm improved performance in the impact zone:

![Original internal geometry and direction for modification](original-geometry.png)

![Condition after the implementation of the modification](modified-geometry.png)

![Analysis of technical drafts](drafts-analysis.png)

![Analysis of deformation under load in the impact zone (FEA)](fea-impact-zone.png)

Tooling Implementation

To maintain the external design constraints, the increased wall thickness was offset by adjusting an internal process cavity. I prepared the technical specification and coordinated with the supplier to modify the mold core:

![Technological cavity on the opposite side of the part](tech-cavity.png)

![Wall thickness compensated by changing the technological cavity](tech-cavity-compensation.png)

![Core of the press mold for manufacturing the lever switch](mold-core.png)

![Surface highlighted for modification](mold-surface.png)

![Lever with improved geometry](lever-improved.png)

### Outcome
The updated lever switch passed functional and durability testing, addressing both design sensitivity and manufacturing variation while improving robustness under user handling and operating loads.

[← Back to Projects](/projects/)