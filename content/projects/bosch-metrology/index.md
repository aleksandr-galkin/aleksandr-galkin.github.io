+++
title = "Air Gap Technique and CMM Fixture"
draft = false
weight = 8
summary = " "

[cover]
  image = "cover.png"
  alt = " "
  relative = true
+++
 
Developed two production ready metrology solutions at Bosch: a new air gap measurement method for stator rotor alignment and a CMM fixture for accurate inspection of shell type housings

--- 

**Content based on public sources and employer-approved shareable information**

---

### Overview
This case study brings together two metrology and quality control solutions I developed to improve measurement accuracy, repeatability, and inspection efficiency in both component acceptance and production inspection.

- Developed a new measurement method to quantify stator rotor alignment and air gap behavior in a motor assembly. 
- Developed a CMM fixture for accurate, repeatable measurement of shell type housings referenced to their key construction features.

---

### Air Gap Measurement Technique for Stator Rotor Alignment

### Problem
When qualifying modified components or new suppliers, it is essential to confirm that critical product characteristics remain within tolerance. One such characteristic is the air gap (3) between the stator (1) and rotor (2), which directly affects motor performance. Existing measurement methods lacked the required precision because they were influenced by the housing, bracket, spindle, and bearing interfaces.

![Disassembled tool view](airgap-disassembled.png)

![Cross-section showing air gap](airgap-cross-section.png)

### Solution
I developed dummy components that reproduced the assembly geometry while tightening control over the features that affect the air gap. The assembly was integrated into the housing and potted with a high penetration resin, allowing accurate sectioning and repeatable measurement. A custom 3D printed enclosure was developed to position and secure the housing during potting and curing.

![Exploded view of components](exploded-view.png)

![Dummy vs actual components](dummy-vs-actual.png)

![Assembly of dummy components](dummy-assembly.png)

![3D-printed enclosure case](enclosure-case.png)

### Measurement Method
After curing, the housing was sectioned at defined locations and measured according to prepared instructions and predefined point definitions.

![Defined cross-sections](cut-sections.png)

![Measurement instructions E–E](measurement-instructions-ee.png)

![Measurement instructions B–B](measurement-instructions-bb.png)

![Actual cut E–E](cut-ee.png)

![Actual cut B–B](cut-bb.png)

### Outcome
The method enabled accurate assessment of air gap and stator rotor alignment beyond the capability of previous approaches, and it was adopted as a plant standard for reliable air gap measurement.

---

### CMM Fixture for Shell Type Power Tool Housings

### Problem
Shell type housings include complex internal features such as ribs, seats (3), and screw bosses (2), and only take on their correct geometry when assembled and referenced to the fit plane (1). To enable accurate and repeatable inspection, a dedicated fixture was needed to align the part to defined construction elements.

![Internal geometry of housing halves](housing-internal-geometry.png)

![Construction elements (fit plane, screw boss axis, major axis)](housing-construction-elements.png)

![Exploded-2)](exploded-2.png)

### Solution
I led the ideation process, developed mockups, and selected the concept that satisfied all functional requirements. Since the reference geometry required to construct the major axis was not directly available, I designed a simulation element representing one rotor bearing seat diameter. This allowed the CMM to establish the major axis from:
- the rotor-bearing seat diameter on the housing, and
- the diameter of the simulation element.

![Concept sketch](fixture-concept-sketch.png)

![One design version](fixture-design-version.png)

![Simulation element](simulation-element.png)

### Deployment
To support consistent use of the fixture, I developed an operating manual and delivered training focused on setup and critical measurement points.

![Operating manual excerpt](manual-excerpt-1.png)

![Operating manual excerpt](manual-excerpt-2.png)

![Fixture ready on CMM](fixture-ready-for-cmm.png)

### Outcome
The fixture enabled simultaneous measurement of both housing halves, improving accuracy while reducing inspection time. It was adopted as a plant standard for this component type, supported by complete technical documentation, including drawings, 3D models, and BOMs.

[← Back to Projects](/projects/)