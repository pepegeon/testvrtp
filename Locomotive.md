# Locomotion Subteam: Comprehensive Research & Evaluation Framework

## 1. Study Intent & Philosophy
In this evaluation, locomotion is not merely a "way to move" but a core system parameter that dictates how a user's perceptual, cognitive, and motor resources are allocated. We evaluate locomotion to understand how it aligns with human cognition and where it creates friction (e.g., cybersickness) that limits the immersive experience.

// perception and human cognition.
// where there is a disconnect or a stark difference where it causes some imbalance.

---

## 2. Parameter Impact Analysis (Theoretical Foundation)

This section details how locomotion design interacts with the core user experience outcomes.

### 2.1 Impact on Immersion (Resource Allocation)
In this study, immersion is the degree to which a user’s resources are allocated to the mediated environment rather than the physical world.

//"allocated" as a term: to be put oneself in the "mediated environment.

* **Perceptual Allocation**: Locomotion affects whether the user's senses (visual/vestibular) stay locked into the virtual world; sensory conflict (sickness) triggers a "pull" back to the physical body, *fragmenting* immersion.
* **Cognitive Allocation**: Non-natural locomotion (e.g., complex UI-based teleportation) increases cognitive load, reminding the user of the system's constraints and breaking the "mediated" illusion.
* **Motor Allocation**: Physical movement methods (Room-scale) align system parameters with human motor resources, preventing the "motor-perceptual gap" that often occurs with joystick movement.
* **Immersion vs. Realism**: A locomotion method can be highly immersive (e.g., a well-designed teleportation in a stylized game) without being realistic, as long as it maintains the user's focus.


//A locomotion method can be highly immersive : what is one game/example? maybe can be as str fwd like dashing/dodging.
//"motor-perceptual gap" -- does high refresh rate/ latency count in FPS? where gamers can have high sensitivity to settings.

### 2.2 Impact on Presence (IPQ)
* **Spatial Integrity**: Continuous locomotion (Physical/Smooth) support the "Place Illusion" by allowing users to build a mental map of the space.
* **Break-in-Presence (BiP)**: Teleportation often causes "Spatial Disorientation". The lack of self-motion cues during the jump forces the user to re-process their surroundings, which can pull perceptual resources back to the physical world.
* **Agency**: Methods that align with natural motor resources (Physical walking) increase the sense of "acting in" the space (IPQ SP2).

//This is a good point of deciding and designing a means of movement to be interactive and engaging.
//like zelda's stamina: where you can hitch on a chance/possibility to scale a terrain and play the game unexpectedly.
        // does expliotation  of movements in games seems something that can occur in VR gaming? 
// or a more physics-based movement like XYZ.



### 2.3 Impact on Flow & Engagement (GEQ)
* **Cognitive Load**: Teleportation requires conscious "point-and-click" decisions, which can act as a secondary task; if the interface is too prominent, it disrupts the deep absorption required for Flow.
* **Challenge-Skill Balance**: *Smooth* locomotion provides high agency and responsiveness; for experienced users, this supports Flow; for novices, the difficulty of controlling motion may exceed their skill, leading to frustration.
    //keyword is on smooth.

### 2.4 Impact on Cybersickness (SSQ)
* **The Limiting Factor**: Cybersickness is treated as a constraint on immersion; high SSQ scores indicate that the user's resources are being diverted to physical discomfort.
* **Vestibular-Visual Conflict**: Smooth locomotion creates the highest conflict (eyes see motion, ears feel none), leading to high Nausea (SSQ-N) scores.
* **Mitigation Trade-offs**: Techniques like vignetting (FOV restriction) reduce sickness but may also suppress spatial presence, illustrating the multi-parameter interdependence of the system.

---

## 3. Locomotion Methods & Implementation

### 3.1 Teleportation (Point-and-Click)
* **Implementation**: User points a raycast and "blinks" to a target.
* **System Parameter**: High rendering stability; it generates no optical flow.
* **Impact**: Minimizes cybersickness but can cause **spatial disorientation** as users must re-orient after the jump.
// e.g or example?

### 3.2 Smooth Locomotion (Joystick/Artificial)
* **Implementation**: Sliding the virtual camera via thumbstick, common in FPS games.
* **System Parameter**: High continuous rendering fidelity is required to maintain motion coherence.
* **Impact**: High potential for spatial presence but poses the highest risk for SSQ symptoms due to sustained sensory conflict.
// e.g or example?

### 3.3 Physical Movement (Room-Scale)
* **Implementation**: 1:1 mapping of physical steps to virtual movement.
* **Impact**: Maximum "Place Illusion" and minimal sickness due to perfect sensory alignment.
// e.g or example?

### 3.4 Hybrid & Mitigation Methods
* **Implementation**: Includes gestures (arm-swinging) or **Vignetting** (dynamic FOV restriction) during motion.
* **Impact**: Reduces peripheral optical flow to mitigate sickness, though it may slightly reduce peripheral immersion.
// e.g or example?

---
## 4. Survey Question → Locomotion Tag Mapping
These mappings allow the team to interpret raw data through the lens of locomotion design.

### 4.1 IPQ (Presence & Immersion)
| Item Code | Focus            | Locomotion Tag            | Research Significance                                          |
| :-------- | :----------------| :------------------------ | :------------------------------------------------------------- |
| **SP2**   | Spatial Presence | **Agency**                | Does the locomotion feel like a natural extension of the user? |
| **SP3**   | Spatial Presence | **Perceptual Allocation** | Do physical constraints pull the user out of immersion?        |
| **INV3**  | Involvement      | **Visual Continuity**     | Do "blink" transitions break environmental captivation?        |

### 4.2 SSQ (Cybersickness)
| Item Code | Symptom        | Locomotion Tag          | Research Significance                                           |
| :-------- | :------------- | :---------------------- | :------------------------------------------------------------- |
| **SSQ-N** | Nausea         | **Vestibular Conflict** | Indicator of sickness from artificial visual motion.           |
| **SSQ-D** | Disorientation | **Spatial Integrity**   | Common in teleportation if the "blink" lacks directional cues. |
| **SSQ-O** | Oculomotor     | **Visual Stability**    | Relates to rendering stability during artificial motion.       |

---

## 5. Expected Outcomes (Hypotheses)
Pre-testing benchmarks based on the Reality–Virtuality continuum.

| Method            | Cybersickness (SSQ)                         | Presence (IPQ)                                  | Flow (GEQ)                                         |
| :---------------- | :------------------------------------------ | :---------------------------------------------- | :--- ----------------------------------------------|
| **Teleportation** | **Low**: Avoids visual-vestibular conflict. | **Fragmented**: Sudden jumps break continuity.  | **Variable**: High usability but may feel "gamey". |
| **Smooth**        | **High**: Risk of nausea/dizziness.         | **High**: Strong spatial presence if tolerated. | **High**: Continuous movement supports absorption. |
| **Physical**      | **Minimal**: Perfect sensory alignment.     | **Maximal**: Highest "Place Illusion".          | **High**: Natural alignment of skill and action.   |

---

## 6. Deliverables Tracking

### 6.1 Locomotion Method Breakdown (Per App)
| Application Name | Primary Method | Implementation Detail           |
| :--------------- | :------------- | :------------------------------ |
| [App Name]       | [Method]       | [e.g., Joy-stick with vignette] |

### 6.2 Expected vs. Observed Comparison
*To be populated post-testing to identify candidate new dimensions of immersion.*