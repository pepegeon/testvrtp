# Branson Leo (2301321) — Produced Deliverables

**Role:** Theory Specialist, User-Interaction Subteam  
**Module:** CSD3121 Term Project  
**Study:** XR User Evaluation — Immersion as a Multi-Parameter, Interdependent Phenomenon

---

# Deliverable 1: Interaction Design Breakdown Per App

## VR Applications

### Beat Saber

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Gesture-based (slashing with motion controllers) |
| **Input Methods** | Dual motion controllers (one per hand) |
| **Affordance Naturalness** | Semi-natural — slashing is a natural gesture, but the mapping to rhythm-based targets is abstract |
| **Unique Mechanics** | Directional slash requirements (arrows on blocks dictate slash angle); obstacle ducking/dodging uses head and body tracking |
| **Locomotion Context** | Stationary — no traversal; blocks approach the player |

**Interaction Summary:**
Beat Saber uses a narrow but highly refined gesture vocabulary. The player performs directional slashes to hit approaching blocks. The core interaction loop is: perceive target direction, time the swing, execute the slash. Controller vibration provides haptic confirmation on hit. The mapping is *semi-natural* — while slashing itself is intuitive, the rhythm-matching layer and directional constraints are abstract game rules imposed on the gesture. There is no object manipulation, menu interaction during gameplay, or complex multi-step input.

---

### Superhot VR

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Gesture-based + direct manipulation |
| **Input Methods** | Dual motion controllers; full room-scale body tracking |
| **Affordance Naturalness** | High — grabbing weapons, throwing objects, and dodging are physically mapped |
| **Unique Mechanics** | Time progresses only when the player physically moves; this ties locomotion directly to interaction pacing |
| **Locomotion Context** | Room-scale stationary — the player moves physically within play space but does not traverse virtually |

**Interaction Summary:**
Superhot VR features natural grabbing and throwing mechanics. Players pick up weapons (guns, bottles, shurikens) using grip inputs that map directly to hand position and orientation. The defining mechanic is that in-game time is coupled to the player's physical movement speed — standing still freezes the scene. This creates a unique interdependency where interaction pacing is governed by locomotion (body movement). Input mappings are overwhelmingly natural: reach for an object to grab it, swing to throw, aim and squeeze to fire.

---

### Job Simulator

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Direct manipulation |
| **Input Methods** | Dual motion controllers (grip/trigger for grab and release) |
| **Affordance Naturalness** | High — objects behave as physical-world analogues (pick up, place, pour, throw) |
| **Unique Mechanics** | Sandbox environment with exaggerated physics; objects respond to manipulation with humorous, amplified feedback |
| **Locomotion Context** | Stationary (fixed positions at workstations) — no traversal |

**Interaction Summary:**
Job Simulator is built around direct manipulation of everyday objects. The entire gameplay loop is: grab object, use object, observe result. Affordances are natural — a stapler is picked up and pressed down, food is placed on a grill, drinks are poured by tilting. The cartoonish visual style does not diminish the naturalness of input; objects still respond to physically intuitive actions. There is no button-based menu interaction during core gameplay. This application represents the purest direct manipulation paradigm among the candidates.

---

### Half-Life: Alyx

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Direct manipulation + button-based hybrid |
| **Input Methods** | Dual motion controllers (grip, trigger, trackpad/thumbstick, buttons) |
| **Affordance Naturalness** | High for object interaction (grab, pull, throw); moderate for weapon management and inventory (button-based) |
| **Unique Mechanics** | "Gravity gloves" — a flick-and-catch gesture to pull distant objects toward the player; physics-based puzzle interaction |
| **Locomotion Context** | Player-selectable: teleport, smooth locomotion, or continuous shift |

**Interaction Summary:**
Half-Life: Alyx combines natural direct manipulation with button-driven systems. Core object interaction (grabbing items, opening drawers, pressing switches) is physically mapped. However, weapon reloading, inventory management, and resin crafting use button inputs and abstract UI overlays. The gravity glove mechanic introduces a trained gesture (flick wrist to attract, catch on arrival) that is initially abstract but becomes natural through repetition. This hybrid approach means the application exercises both natural and abstract interaction pathways within a single session.

---

### Rec Room

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Button-based + limited gesture |
| **Input Methods** | Motion controllers (buttons, trigger, grip); touchscreen on non-VR platforms |
| **Affordance Naturalness** | Mixed — social interaction and minigame selection are menu/button-driven; some activities (e.g., paintball, disc golf) use gesture input |
| **Unique Mechanics** | Cross-platform play (VR and flatscreen); avatar-based social interaction with emote menus |
| **Locomotion Context** | Teleport or smooth locomotion toggle |

**Interaction Summary:**
Rec Room uses predominantly button-based interaction for navigation, social features, and menus. In-game activities vary: paintball involves pointing and trigger-pulling (semi-natural), while room navigation and game selection use abstract button/menu input. The social layer (emotes, voice chat, friend lists) is entirely UI-driven. Compared to Job Simulator or Superhot VR, the affordance naturalness is lower — the player interacts more with interfaces than with physical-analogue objects. This makes Rec Room a strong contrast candidate against direct manipulation apps.

---

### Walkabout Mini Golf

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Direct manipulation (single-tool) |
| **Input Methods** | Motion controller (grip to hold club, swing to putt) |
| **Affordance Naturalness** | High — swinging a virtual golf club maps directly to the physical gesture |
| **Unique Mechanics** | Swing force is mapped to physical swing speed; putting angle is determined by controller orientation |
| **Locomotion Context** | Teleportation only (between holes and viewpoints) |

**Interaction Summary:**
Walkabout Mini Golf centres on a single, highly natural interaction: swinging a golf club. The player grips the controller, positions behind the ball, and physically swings to putt. Force and direction are read from controller velocity and orientation. Beyond putting, interaction is minimal — course selection and multiplayer features use simple menus. The narrow interaction vocabulary makes this app useful as a baseline for direct manipulation with minimal cognitive load.

---

### Gorilla Tag

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Full-body gesture / physical movement |
| **Input Methods** | Motion controllers (arm position used to simulate gorilla arm locomotion); no button-based gameplay interaction |
| **Affordance Naturalness** | Unique — arm-swinging locomotion is natural as a physical action but abstract as a movement metaphor (gorilla arms) |
| **Unique Mechanics** | Movement is driven entirely by arm-swing physics; no buttons are used for core gameplay |
| **Locomotion Context** | Physical arm-swing movement (player propels by pushing hands against surfaces) |

**Interaction Summary:**
Gorilla Tag collapses interaction and locomotion into a single mechanism: arm movement. The player moves by swinging arms against the ground and walls, simulating gorilla locomotion. There is no object manipulation, weapon use, or tool interaction. The entire experience is kinaesthetic — the interaction *is* the locomotion. This makes Gorilla Tag an outlier: it has no traditional interaction paradigm (no buttons, no object grabbing) but demands high physical engagement. Useful for studying how embodied movement affects flow and presence in the absence of object-level interaction.

---

### First Steps / First Contact (Meta)

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Guided direct manipulation |
| **Input Methods** | Motion controllers (grip, trigger, hand tracking on supported devices) |
| **Affordance Naturalness** | High — tutorial explicitly teaches natural grab, point, and place gestures |
| **Unique Mechanics** | Structured onboarding; each interaction type is introduced sequentially with visual prompts |
| **Locomotion Context** | Stationary |

**Interaction Summary:**
First Steps/First Contact is Meta's official VR tutorial. It introduces direct manipulation (grabbing, throwing, catching), pointer-based selection, and trigger input in a guided sequence. Affordances are natural and are explicitly scaffolded — the environment highlights what can be grabbed or interacted with. This controlled, introductory interaction design makes it a useful baseline: it represents the minimum viable interaction complexity that a VR novice encounters.

---

## Mobile XR / AR Applications

### Pokemon GO

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Touch-screen gesture (tap, swipe, flick) |
| **Input Methods** | Touchscreen (single finger tap, swipe, flick); gyroscope for AR camera view |
| **Affordance Naturalness** | Low-to-moderate — flicking a Pokeball is a semi-natural throw gesture mapped to a 2D swipe; menu interaction is entirely abstract |
| **Unique Mechanics** | AR camera overlay places virtual creatures in real-world view; GPS-based location triggers encounters |
| **Locomotion Context** | GPS-based physical walking (real-world movement) |

**Interaction Summary:**
Pokemon GO uses standard mobile touch gestures. The primary gameplay interaction — throwing a Pokeball — is a flick/swipe gesture that loosely mimics a throw. All other interaction (inventory, menus, team selection) is tap-based UI. The AR mode overlays Pokemon onto the camera feed, but interaction with the AR element is limited to aiming and throwing. Compared to VR direct manipulation, the interaction fidelity is shallow: 2D input mapped to a 3D-implied action. This makes it a strong contrast to controller-based VR interaction.

---

### IKEA Place

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Touch-screen gesture (tap, drag, pinch) |
| **Input Methods** | Touchscreen (tap to select, drag to position, pinch to resize); device orientation for AR placement |
| **Affordance Naturalness** | Low — placing furniture involves abstract screen gestures, not physical manipulation |
| **Unique Mechanics** | AR surface detection for realistic furniture placement; true-to-scale 3D models |
| **Locomotion Context** | Stationary (user walks physically around the placed object) |

**Interaction Summary:**
IKEA Place is a utility-focused AR app. Users select furniture from a catalogue (tap-based menu), then place it in their real-world space by tapping on a detected surface. Repositioning uses drag gestures. The interaction is functional and abstract — there is no sense of physically handling the furniture. The focus is accuracy of placement rather than experiential engagement. Useful as a contrast to engagement-driven apps: interaction here serves a practical task, not flow or immersion.

---

### AR Dragon (Virtual Pet Apps)

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Touch-screen gesture (tap, drag) |
| **Input Methods** | Touchscreen (tap to feed, pet, play); device orientation for AR camera |
| **Affordance Naturalness** | Low-to-moderate — tapping to "pet" or "feed" is a simplified metaphor for a physical action |
| **Unique Mechanics** | Virtual creature responds to interaction with animations (affective feedback loop) |
| **Locomotion Context** | Stationary |

**Interaction Summary:**
AR Dragon uses simple touch gestures to simulate caregiving interactions (feeding, petting, playing). The AR overlay places a creature in the camera view. Interaction is shallow — a single tap triggers a canned animation response. The engagement loop relies on affective feedback (creature reacts happily) rather than interaction complexity. Useful for studying whether minimal interaction with strong affective feedback can sustain engagement.

---

### Merge Cube Apps

| Attribute | Detail |
|-----------|--------|
| **Primary Interaction Type** | Tangible manipulation (physical object rotation) |
| **Input Methods** | Physical cube held in hand; device camera tracks cube orientation and face |
| **Affordance Naturalness** | High — the user physically rotates, tilts, and inspects a real object; virtual content is mapped to the cube's surfaces |
| **Unique Mechanics** | Proprioceptive feedback from holding a physical object; hybrid physical-digital interaction |
| **Locomotion Context** | Handheld object manipulation (no traversal) |

**Interaction Summary:**
Merge Cube is unique among the candidates: interaction is mediated by a physical object. The user holds a real cube and rotates it; the app renders virtual content aligned to the cube's tracked faces. This provides proprioceptive feedback absent in screen-only AR — the user feels the weight and edges of the cube while seeing virtual content. Input is entirely through physical manipulation of the cube (rotate, tilt, shake). No touchscreen gestures are used during core interaction. This tangible interaction paradigm is the strongest contrast to screen-based mobile AR input.

---

## Interaction Type Classification Summary

| Application | Direct Manipulation | Button-Based | Gesture-Based | Abstract Mapping | Natural Mapping |
|-------------|:--:|:--:|:--:|:--:|:--:|
| Beat Saber | | | X | X | Partial |
| Superhot VR | X | | X | | X |
| Job Simulator | X | | | | X |
| Half-Life: Alyx | X | X | X | Partial | X |
| Rec Room | | X | Partial | X | Partial |
| Walkabout Mini Golf | X | | | | X |
| Gorilla Tag | | | X | X | Partial |
| First Steps (Meta) | X | | | | X |
| Pokemon GO | | | Partial | X | Partial |
| IKEA Place | | | | X | |
| AR Dragon | | | | X | Partial |
| Merge Cube | X | | | | X |

---

# Deliverable 2: Expected Interaction Impact Notes

## 2.1 Direct Manipulation

**Definition:** The user physically grasps, moves, rotates, and releases virtual objects using tracked hand/controller positions. The virtual object responds as a physical-world analogue.

**Apps exemplifying this type:** Job Simulator, Walkabout Mini Golf, Half-Life: Alyx, First Steps, Merge Cube

### Expected Impact

**Flow:**
Direct manipulation supports flow by providing immediate, continuous feedback. The user's physical action produces a visible, proportional result with minimal input-output delay. This supports the *clear feedback* and *action-awareness merging* components of flow (Csikszentmihalyi, 1990). Challenge-skill balance is maintained when object behaviour is predictable — the user does not need to learn abstract mappings, reducing the cognitive barrier to entering a flow state.

**Agency:**
Strong positive effect. Direct manipulation provides the most direct causal link between user action and virtual outcome. When a user reaches for an object and it responds to their hand position and grip force, the sense of "I caused this" is reinforced. This supports perceived agency and control.

**Presence:**
Direct manipulation strengthens spatial presence because it confirms the user's body schema within the virtual environment. Interacting with objects as though they are physically real reinforces the spatial model ("I am here, and these objects are here with me"). IPQ items related to spatial presence and environmental responsiveness are expected to score higher with direct manipulation.

**Cognitive Load:**
Low extraneous cognitive load. Natural affordances reduce the need to learn controls — users apply real-world interaction knowledge. However, if object physics are unreliable or inconsistent (e.g., objects clip through surfaces, gravity behaves unexpectedly), cognitive load increases as the user must compensate for system errors.

### Cross-Parameter Interdependencies

- **Rendering:** If rendering instability causes visual lag between the user's hand movement and the object's response (motion-to-photon latency), perceived interaction naturalness degrades. High rendering fidelity amplifies the benefit of direct manipulation; low fidelity can undermine it.
- **Locomotion:** Stationary locomotion contexts (Job Simulator, Walkabout Mini Golf) remove navigational cognitive load, allowing the user to focus entirely on manipulation. When combined with traversal-based locomotion, the user must divide attention between navigation and object interaction.

---

## 2.2 Button-Based Interaction

**Definition:** The user presses physical buttons on a controller or taps UI elements on a screen to trigger discrete actions. The mapping between input and effect is mediated by interface conventions (menus, icons, input prompts).

**Apps exemplifying this type:** Rec Room, Half-Life: Alyx (inventory/weapon systems), IKEA Place, Pokemon GO (menus)

### Expected Impact

**Flow:**
Button-based interaction can support flow when the button mappings are well-learned and the response is immediate (e.g., experienced gamers navigating familiar menus). However, for novel users or complex menu hierarchies, button interaction interrupts flow by requiring the user to recall mappings or read UI labels. The *action-awareness merging* component of flow is weaker when input is mediated by an interface layer.

**Agency:**
Moderate. The user's action (button press) produces a result, but the relationship is abstract — pressing "X" to open a door does not feel like physically opening a door. Agency is maintained at a functional level ("I chose to open the door") but weakened at an experiential level ("I did not feel like I opened the door").

**Presence:**
Button-based interaction can weaken presence. Each time the user must attend to a UI overlay, controller button layout, or menu screen, their attention is redirected from the virtual environment to the interface layer. This is particularly relevant for IPQ items measuring involvement ("I was completely captivated by the experience") and spatial presence ("I felt surrounded by the virtual environment").

**Cognitive Load:**
Higher extraneous cognitive load compared to direct manipulation. The user must maintain a mental model of button-to-action mappings. Complex systems (e.g., Half-Life: Alyx's weapon selection, Rec Room's social menus) add load. However, once mappings are learned, cognitive demand decreases — so exposure duration matters.

### Cross-Parameter Interdependencies

- **Rendering:** Button-based UI elements (menus, HUD) are less sensitive to rendering fidelity than spatial interactions. However, if UI elements render poorly (e.g., text unreadable at VR resolution), usability degrades independently of environmental rendering quality.
- **Locomotion:** Button-based interaction is locomotion-agnostic — it works identically whether the user is teleporting, moving smoothly, or standing still. This is a practical advantage but also means button interaction does not contribute to spatial presence the way embodied interaction does.

---

## 2.3 Gesture-Based Interaction

**Definition:** The user performs recognisable physical movements (slashing, pointing, throwing, waving) that are tracked and interpreted by the system as input commands. The gesture may be natural (throwing resembles a real throw) or trained (a specific wrist flick to activate a game mechanic).

**Apps exemplifying this type:** Beat Saber (slashing), Superhot VR (throwing, dodging), Gorilla Tag (arm-swing), Half-Life: Alyx (gravity glove flick)

### Expected Impact

**Flow:**
Gesture-based interaction has the highest potential for flow among the interaction types, particularly when gestures are rhythmic or skill-based. Beat Saber exemplifies this: the slash gesture, when aligned with musical rhythm and visual targets, creates a tight perception-action loop that drives absorption. The *challenge-skill balance* component of flow is directly influenced by gesture difficulty and timing requirements. When gestures are well-calibrated to user ability, flow is strongly supported.

**Agency:**
High when gestures are responsive and reliable. The physicality of gestures — using the whole arm to slash or throw — engages proprioception and reinforces the sense that the user's body is the input device. Agency is weakened if gesture recognition fails or misinterprets input (e.g., a slash not registering, a throw going in the wrong direction).

**Presence:**
Gesture interaction supports embodied presence — the user's body is active in the virtual space. This is distinct from the spatial presence supported by direct manipulation. Gesture-based interaction strengthens the feeling of being physically *in* the environment and *acting upon* it. IPQ items related to involvement and spatial presence are expected to benefit.

**Cognitive Load:**
Variable. Natural gestures (throwing, slashing) have low cognitive load because they leverage existing motor skills. Trained gestures (gravity glove flick, specific combo inputs) have an initial learning cost that decreases with practice. Gesture-based interaction can also impose physical fatigue, which is distinct from cognitive load but similarly limits sustained engagement.

### Cross-Parameter Interdependencies

- **Rendering:** Gesture feedback depends heavily on visual confirmation. If the user slashes in Beat Saber and the block destruction animation is delayed due to frame drops, the feedback loop is broken. Rendering stability is a prerequisite for gesture-based flow.
- **Locomotion:** In apps where gesture and locomotion overlap (Gorilla Tag, Superhot VR), the two parameters are inseparable. Arm-swing locomotion *is* gesture interaction. This creates a compound variable that must be acknowledged in analysis — changes in one cannot be isolated from the other.

---

## 2.4 Abstract vs Natural Mapping

**Definition:** This is not a separate interaction type but a spectrum applied to any interaction. *Natural mapping* means the physical input resembles the virtual action (swing arm to swing sword). *Abstract mapping* means the input is a learned convention (press button to swing sword).

### Expected Impact

**Flow:**
Natural mappings reduce the barrier to flow because they do not require interface learning. Abstract mappings can still support flow once learned, but the onboarding period is longer and more susceptible to errors that interrupt engagement.

**Agency:**
Natural mappings produce stronger perceived agency because the causal chain between action and effect is transparent. Abstract mappings add an interface layer that distances the user from the effect ("I pressed X" vs "I reached out and grabbed it").

**Presence:**
Natural mappings strengthen presence by maintaining consistency between the user's body schema and the virtual response. Abstract mappings can break presence by requiring the user to think about the interface rather than the environment.

**Cognitive Load:**
Natural mappings impose lower extraneous cognitive load. Abstract mappings impose higher load during learning but can become automatic with practice.

### Cross-Parameter Interdependencies

- **Rendering:** Natural mappings are more sensitive to rendering quality because the user expects the virtual response to visually match their physical action. If a user naturally reaches for an object and the rendered hand does not track accurately, the mismatch is more noticeable (and more disruptive) than a button press that fails.
- **Locomotion:** Natural locomotion (physical walking) pairs well with natural interaction mappings to create a coherent embodied experience. Abstract locomotion (teleportation) paired with natural interaction creates a mixed-fidelity experience where hand interaction feels real but movement does not.

---

# Deliverable 3: Methodology Section (Report)

## Methodology: Measuring User Interaction Constructs in XR

### 3.1 Overview

This study investigates how user interaction design in XR applications influences immersion-related outcomes, specifically presence, flow, and agency. Interaction design is treated as one of three core system parameters (alongside rendering fidelity and locomotion methods) whose effects on user experience are interdependent rather than isolated (Bowman & McMahan, 2007).

To measure the influence of interaction design on immersion, this study employs a combination of standardised survey instruments and structured qualitative probes, administered immediately after short XR sessions (5-7 minutes per condition).

### 3.2 Constructs and Definitions

**User Interaction** is defined in this study as the set of input methods, affordances, and feedback mechanisms through which the user acts upon the virtual environment. Following McMahan et al. (2012), interaction fidelity is characterised along a spectrum from low fidelity (abstract button-based input) to high fidelity (natural direct manipulation with physics-based responses).

The following constructs are measured as outcomes potentially influenced by interaction design:

- **Presence** — the subjective sense of "being there" in the virtual environment. Measured via the Igroup Presence Questionnaire (IPQ). Interaction naturalness is expected to influence spatial presence (the environment responds to my actions as though I am physically there) and involvement (I was captivated rather than distracted by interface demands) (Schubert, Friedmann, & Regenbrecht, 2001).

- **Flow** — a state of deep engagement where action and awareness merge, sustained by clear goals, immediate feedback, and challenge-skill balance (Csikszentmihalyi, 1990). Measured via selected items from the Game Experience Questionnaire (GEQ) short form. Interaction quality is expected to influence flow through feedback immediacy (does the system respond to input without delay?) and skill-matching (does the interaction demand match user ability?).

- **Agency** — the user's sense that their actions have direct and meaningful effects in the virtual environment. Captured through GEQ items related to perceived control and skilfulness, and through qualitative probes. Agency depends on interaction fidelity: natural affordances with clear causal feedback produce stronger perceived agency than abstract button mappings (Witmer & Singer, 1998).

- **Cybersickness** — a form of motion sickness arising from sensory mismatch. Measured via the Simulator Sickness Questionnaire (SSQ). While cybersickness is primarily associated with locomotion and rendering instability, interaction mismatches (e.g., hand tracking lag, unexpected physics responses) can contribute to discomfort through visuo-proprioceptive conflict (Kennedy, Lane, Berbaum, & Lilienthal, 1993).

### 3.3 Survey Instruments

#### Igroup Presence Questionnaire (IPQ)

The IPQ is a 14-item self-report instrument using a 7-point Likert scale (1 = Strongly Disagree to 7 = Strongly Agree). It measures four subscales: Spatial Presence, Involvement, Experienced Realism, and General Presence (Schubert et al., 2001).

**Interaction-relevant items:**
- Spatial Presence items (Q1-Q3) capture whether the user felt physically located in the virtual space — influenced by whether interaction confirms the user's body schema.
- Involvement items (Q4-Q6) capture attentional allocation — influenced by whether interaction demands draw attention to the interface (reducing involvement) or to the environment (increasing involvement).
- Experienced Realism items (Q7-Q9), particularly "The environment responded realistically to my actions" (Q9), directly address interaction fidelity.

#### Game Experience Questionnaire — Short Form (GEQ)

This study uses a 6-item subset of the GEQ on a 5-point scale (0 = Not at all to 4 = Extremely), capturing absorption, time perception, skill, challenge balance, enjoyment, and control (IJsselsteijn, de Kort, & Poels, 2013).

**Interaction-relevant items:**
- "I felt completely absorbed in the experience" — absorption is supported by seamless interaction that does not require conscious interface attention.
- "I felt skilful during the experience" — perceived skill depends on interaction affordances matching user capability.
- "I felt challenged at the right level" — interaction complexity (number of input types, gesture precision required) contributes to perceived challenge.
- "I felt in control of my actions" — directly measures perceived agency, a function of interaction fidelity and responsiveness.

#### Simulator Sickness Questionnaire (SSQ)

The SSQ is a 16-item instrument using a 4-point severity scale (0 = None to 3 = Severe), yielding subscale scores for Nausea, Oculomotor discomfort, and Disorientation (Kennedy et al., 1993).

While cybersickness is primarily driven by locomotion and rendering, interaction-related contributions are captured indirectly: hand tracking latency, unexpected physics responses, and visuo-proprioceptive mismatches during manipulation can elevate oculomotor and disorientation subscale scores.

#### Qualitative Probes

Three short open-ended questions are administered after the quantitative instruments:

1. "What moment felt the most immersive to you?"
2. "Did anything break your immersion or pull you out of the experience?"
3. "How did movement or interaction affect your comfort or engagement?"

Probe 3 is directly designed to capture interaction-specific experiences. Responses are thematically coded against system parameters (rendering, locomotion, interaction) to identify which parameter contributions participants attribute their experience to.

### 3.4 Procedure

Participants complete a short XR session (5-7 minutes) with one application per condition. Immediately after each session, instruments are administered in the following order: SSQ (to capture immediate physical symptoms before memory fades), IPQ (reflective presence assessment), GEQ short form (engagement and flow), then qualitative probes.

The interaction type for each session is recorded as metadata (controller-based, touch-based, or gesture-based) to enable cross-condition comparison.

### 3.5 Analysis Approach

Quantitative data are analysed by computing subscale means for each instrument per application/condition. Comparison across applications with contrasting interaction types (e.g., direct manipulation in Job Simulator vs. button-based in Rec Room) allows examination of how interaction fidelity influences presence, flow, and agency scores.

Qualitative probe responses are thematically coded. Codes are assigned to system parameters (rendering, locomotion, interaction) and immersion outcomes (presence, flow, comfort). This coding enables identification of which parameter participants spontaneously attribute their experience to, and whether interaction-related attributions differ across high-fidelity and low-fidelity interaction conditions.

Critically, interaction effects are not analysed in isolation. Cross-parameter analysis examines how interaction quality interacts with rendering stability and locomotion method to shape immersion outcomes, consistent with the study's framing of immersion as an interdependent, multi-parameter phenomenon.

### 3.6 References

- Bowman, D. A., & McMahan, R. P. (2007). Virtual reality: How much immersion is enough? *Computer, 40*(7), 36-43.
- Csikszentmihalyi, M. (1990). *Flow: The Psychology of Optimal Experience*. Harper & Row.
- IJsselsteijn, W. A., de Kort, Y. A. W., & Poels, K. (2013). The Game Experience Questionnaire. Technische Universiteit Eindhoven.
- Kennedy, R. S., Lane, N. E., Berbaum, K. S., & Lilienthal, M. G. (1993). Simulator Sickness Questionnaire: An enhanced method for quantifying simulator sickness. *The International Journal of Aviation Psychology, 3*(3), 203-220.
- McMahan, R. P., Bowman, D. A., Zielinski, D. J., & Brady, R. B. (2012). Evaluating display fidelity and interaction fidelity in a virtual reality game. *IEEE Transactions on Visualization and Computer Graphics, 18*(4), 626-633.
- Milgram, P., & Kishino, F. (1994). A taxonomy of mixed reality visual displays. *IEICE Transactions on Information and Systems, E77-D*(12), 1321-1329.
- Schubert, T., Friedmann, F., & Regenbrecht, H. (2001). The experience of presence: Factor analytic insights. *Presence: Teleoperators and Virtual Environments, 10*(3), 266-281.
- Slater, M., & Wilbur, S. (1997). A framework for immersive virtual environments (FIVE): Speculations on the role of presence in virtual environments. *Presence: Teleoperators and Virtual Environments, 6*(6), 603-616.
- Witmer, B. G., & Singer, M. J. (1998). Measuring presence in virtual environments: A presence questionnaire. *Presence: Teleoperators and Virtual Environments, 7*(3), 225-240.

---

# Deliverable 4: Application Selection Validation (Interaction Perspective)

## Validation Matrix

Each candidate application is evaluated against the five validation criteria from the interaction design perspective. Items marked **[Pending]** require confirmation from Bryan (Rendering) or Steven (Locomotion) to ensure no cross-parameter confounding.

| Application | Clear Interaction Properties | Short Session Suitable | Accessible | Intentional Contrast Pair | No Unintentional Confounding |
|-------------|:--:|:--:|:--:|:--:|:--:|
| Beat Saber | Yes | Yes (per song) | Paid, Quest/PCVR | vs Rec Room (gesture vs button) | **[Pending]** Rendering contrast with Rec Room is low — both stylized |
| Superhot VR | Yes | Yes | Paid, Quest/PCVR | vs Rec Room (gesture vs button) | Caution: time-linked mechanic confounds interaction with locomotion |
| Job Simulator | Yes | Yes | Paid, Quest/PCVR | vs Rec Room (direct manip. vs abstract) | **[Pending]** Both stationary — locomotion controlled. Check rendering contrast with Bryan |
| Half-Life: Alyx | Yes | Possible (extract segment) | Paid, PCVR only | vs Job Simulator (hybrid vs pure direct manip.) | Caution: PCVR-only limits accessibility; high rendering fidelity confounds with interaction when comparing to stylized apps |
| Rec Room | Yes | Yes | Free, cross-platform | vs Job Simulator, Beat Saber, Superhot VR | **[Pending]** Social element may introduce uncontrolled immersion variable |
| Walkabout Mini Golf | Yes | Yes (per hole) | Paid, Quest/PCVR | vs Beat Saber (single-tool direct manip. vs gesture) | Minimal confounding — low rendering complexity, simple locomotion |
| Gorilla Tag | Partial — interaction/locomotion merged | Yes | Free, Quest | vs Beat Saber (full body vs arm gesture) | Caution: cannot isolate interaction from locomotion — arm swing is both |
| First Steps (Meta) | Yes | Yes (~10 min) | Free, Quest | Baseline (guided tutorial) | Low confounding — controlled onboarding |
| Pokemon GO | Yes | Yes | Free, mobile | vs Merge Cube (screen-based vs tangible) | **[Pending]** GPS locomotion adds uncontrolled variable |
| IKEA Place | Yes | Yes | Free, mobile | vs Pokemon GO (utility vs engagement) | Minimal confounding — both screen-based, both stationary |
| AR Dragon | Partial — very shallow | Yes | Free, mobile | vs Pokemon GO (simple vs moderate) | Contrast may be too weak to produce measurable difference |
| Merge Cube | Yes | Yes | Requires hardware | vs Pokemon GO (tangible vs screen) | **[Pending]** Requires physical cube — added proprioceptive variable may confound |

## Recommended Selections for Interaction Contrasts

Based on the validation above, the following pairings provide the clearest, least confounded interaction contrasts:

### Primary Contrast: Direct Manipulation vs Button-Based (VR)
**Job Simulator vs Rec Room**
- Both are stationary or low-locomotion (controls for locomotion variable)
- Both have stylised rendering (controls for rendering variable)
- Interaction types are clearly distinct: Job Simulator is pure direct manipulation; Rec Room is primarily button/menu-based
- Both support short sessions
- **Coordination needed:** Confirm with Bryan that rendering contrast is minimal between these two apps

### Secondary Contrast: Gesture-Based vs Direct Manipulation (VR)
**Beat Saber vs Walkabout Mini Golf**
- Both use motion controllers as primary input
- Beat Saber: rhythmic slashing gesture; Walkabout: single-tool direct manipulation (golf swing)
- Both are stationary/teleport (low locomotion variation)
- Both are stylised (low rendering variation)
- Contrast isolates gesture precision/rhythm vs. tool-based physics manipulation

### Mobile Contrast: Tangible vs Screen-Based (AR)
**Merge Cube vs Pokemon GO**
- Merge Cube: physical object manipulation with proprioceptive feedback
- Pokemon GO: screen touch gestures
- Both are short-session capable and accessible
- **Coordination needed:** Confirm with Steven that the GPS locomotion element of Pokemon GO is noted as a potential confound

### Items Requiring Subteam Lead Discussion

1. **Bryan (Rendering):** Confirm that Job Simulator and Rec Room do not differ meaningfully in rendering fidelity, so that interaction contrast is not confounded.
2. **Steven (Locomotion):** Confirm that Beat Saber (stationary) and Walkabout Mini Golf (teleport between holes) do not differ meaningfully in locomotion experience during active gameplay.
3. **Both:** Discuss whether Half-Life: Alyx should be included despite being PCVR-only and having both high rendering fidelity and complex interaction — it may introduce multiple simultaneous confounds.

---

# Deliverable 5: User Evaluation Execution Materials

## 5.1 Interaction Observation Log (Per Session)

Complete one log per participant per application tested.

```
INTERACTION OBSERVATION LOG

Participant ID: ________
Application: ________
Date/Time: ________
Observer: ________

METADATA
Interaction Type:  [ ] Controller  [ ] Touch  [ ] Gesture  [ ] Tangible
Platform:          [ ] VR Headset  [ ] Mobile XR
Session Duration:  ________ minutes

TASK CHECKLIST
(Adapt tasks per application — examples below)

| # | Task Description              | Success (Y/N) | Attempts | Time (s) | Notes |
|---|-------------------------------|:-:|--:|--:|-------|
| 1 | Pick up / interact with first object |   |   |   |       |
| 2 | Complete primary action (e.g., slash, putt, throw) |   |   |   |       |
| 3 | Navigate menu / secondary action |   |   |   |       |
| 4 | Respond to environmental prompt |   |   |   |       |
| 5 | Complete session goal |   |   |   |       |

INTERACTION ERROR LOG

| Timestamp | Error Description | User Response (retry / gave up / workaround) |
|-----------|-------------------|----------------------------------------------|
|           |                   |                                              |
|           |                   |                                              |

BEHAVIORAL OBSERVATIONS
(Note visible hesitation, confusion, delight, or frustration related to interaction)

_______________________________________________________________
_______________________________________________________________
_______________________________________________________________
```

## 5.2 Application-Specific Task Checklists

### Job Simulator (Direct Manipulation)
| # | Task | What to Observe |
|---|------|-----------------|
| 1 | Pick up an object from the workstation | Grab accuracy, hesitation |
| 2 | Place object in correct location | Placement precision, retries |
| 3 | Pour liquid from one container to another | Tilt control, spilling |
| 4 | Throw an object at a target | Release timing, force calibration |
| 5 | Press a button or pull a lever | Reach accuracy, confusion with nearby objects |

### Beat Saber (Gesture-Based)
| # | Task | What to Observe |
|---|------|-----------------|
| 1 | Complete first 30 seconds of a song | Initial adaptation, missed blocks |
| 2 | Hit directional blocks correctly | Directional accuracy, timing |
| 3 | Avoid obstacle walls | Body awareness, spatial response |
| 4 | Maintain combo streak | Rhythm consistency, flow state indicators |
| 5 | Complete full song | Fatigue, sustained engagement |

### Rec Room (Button-Based / Mixed)
| # | Task | What to Observe |
|---|------|-----------------|
| 1 | Navigate main menu to select activity | Menu comprehension time, mis-taps |
| 2 | Move through a room (locomotion toggle) | Locomotion preference, hesitation |
| 3 | Interact with in-game object (e.g., throw ball) | Gesture accuracy vs button reliance |
| 4 | Use social feature (emote, communicate) | UI navigation speed, distraction from environment |
| 5 | Complete a minigame objective | Overall interaction fluency |

### Pokemon GO (Touch Screen)
| # | Task | What to Observe |
|---|------|-----------------|
| 1 | Navigate map to locate encounter | Tap/swipe fluency, orientation awareness |
| 2 | Enter AR encounter mode | Camera orientation, AR registration quality |
| 3 | Throw Pokeball (flick gesture) | Flick accuracy, force calibration, retries |
| 4 | Use item from inventory (menu) | Menu navigation speed, tap accuracy |
| 5 | Complete catch sequence | Overall interaction flow |

## 5.3 Session Protocol Checklist

```
PRE-SESSION
[ ] Participant briefed on study purpose (no leading information about interaction)
[ ] Hardware calibrated (headset fit, controller pairing, tracking check)
[ ] Baseline comfort confirmed (5-minute rest period)
[ ] Interaction type and application recorded in metadata

DURING SESSION (5-7 minutes)
[ ] Observer fills in Interaction Observation Log
[ ] DO NOT interrupt participant during session
[ ] Note visible discomfort, hesitation, or removal of headset
[ ] Timer running — note actual session duration

POST-SESSION — Survey Administration (in order)
[ ] 1. SSQ (cybersickness — immediate bodily state)
[ ] 2. IPQ (presence — reflective)
[ ] 3. GEQ short form (flow / engagement)
[ ] 4. Open-ended probes (max 3):
       - "What moment felt the most immersive to you?"
       - "Did anything break your immersion or pull you out of the experience?"
       - "How did movement or interaction affect your comfort or engagement?"

POST-SESSION — Data Check
[ ] All survey fields completed (no blanks)
[ ] Observation log complete
[ ] Interaction errors recorded
[ ] Any anomalies noted (technical issues, participant discomfort, session cut short)
```

---

# Deliverable 6: Cross-Team Coordination Document

## 6.1 Survey Question Tagging — Interaction Parameter

The following tables identify which survey items are expected to be influenced by interaction design quality. These tags are provided from the User Interaction subteam perspective for cross-referencing with Bryan (Rendering) and Steven (Locomotion) tags.

### IPQ Items — Interaction Relevance

| # | Item | Interaction Influence | Rationale |
|---|------|----|-----------|
| Q1 | I felt like I was really there in the environment | Moderate | Natural interaction confirms spatial body schema |
| Q2 | I had a sense of being present in the virtual space | Moderate | Interaction responsiveness reinforces spatial model |
| Q3 | I felt surrounded by the virtual environment | Low | Primarily rendering/audio-driven |
| Q4 | I was completely captivated by the experience | High | Interaction quality determines whether interface distracts or environment captivates |
| Q5 | I paid more attention to the virtual environment than to the real world | Moderate | Confusing controls redirect attention to real-world interface concerns |
| Q6 | I was deeply involved in the experience | High | Engagement loop depends on interaction feedback quality |
| Q7 | The virtual environment seemed realistic | Low | Primarily rendering-driven |
| Q8 | The experience felt consistent with the real world | Moderate | Interaction naturalness affects perceived consistency |
| Q9 | The environment responded realistically to my actions | **Very High** | Directly measures interaction fidelity perception |
| Q10 | I felt present in the virtual environment | Moderate | Composite of spatial + interaction + rendering |
| Q11 | I had the impression of actually being in the environment | Moderate | Interaction confirmation supports "being there" |
| Q12 | The environment felt convincing | Moderate | Interaction responsiveness is part of overall convincingness |
| Q13 | I felt immersed in the experience | Moderate | Composite measure — interaction contributes alongside other parameters |
| Q14 | I felt detached from the real world (reverse-scored) | Moderate | Poor interaction can pull attention back to real world |

### GEQ Short Form Items — Interaction Relevance

| # | Item | Interaction Influence | Rationale |
|---|------|----|-----------|
| G1 | I felt completely absorbed in the experience | High | Seamless interaction supports absorption; interface friction breaks it |
| G2 | I lost track of time while playing | Moderate | Flow state maintenance depends partly on interaction smoothness |
| G3 | I felt skilful during the experience | **Very High** | Directly depends on interaction affordances and feedback |
| G4 | I felt challenged at the right level | High | Interaction complexity is a primary source of challenge calibration |
| G5 | I enjoyed the experience | Moderate | Enjoyment is multi-factorial; interaction frustration reduces it |
| G6 | I felt in control of my actions | **Very High** | Directly measures perceived agency — a function of interaction fidelity |

### SSQ Items — Interaction Relevance

| # | Item | Interaction Influence | Rationale |
|---|------|----|-----------|
| S4 | Eye strain | Low-Moderate | Hand tracking lag can cause increased visual scanning |
| S5 | Difficulty focusing | Low-Moderate | Input-output mismatch can create visual discomfort |
| S9 | Difficulty concentrating | Moderate | Confusing interaction demands split cognitive resources |
| S12 | Dizziness (eyes open) | Low | Primarily locomotion/rendering-driven, but hand tracking issues can contribute |

Most SSQ items are primarily influenced by locomotion and rendering. Interaction tagging is limited to items where input mismatch or cognitive overload from controls could plausibly contribute.

## 6.2 Parameter-to-Immersion Mapping

| System Parameter | Immersion Outcome | Mechanism | Expected Direction |
|-----|------|------|------|
| **Interaction Fidelity (Natural Mapping)** | Presence | Natural affordances confirm body schema in virtual space | Higher fidelity -> Higher presence |
| **Interaction Fidelity (Natural Mapping)** | Flow | Immediate feedback and intuitive controls support action-awareness merging | Higher fidelity -> Higher flow |
| **Interaction Fidelity (Natural Mapping)** | Agency | Direct causal link between physical action and virtual response | Higher fidelity -> Higher agency |
| **Interaction Complexity** | Cognitive Load | More input types, gesture precision demands, and menu depth increase extraneous load | Higher complexity -> Higher load -> Lower flow |
| **Interaction Responsiveness** | Presence | Lag between input and virtual response breaks spatial consistency | Lower responsiveness -> Lower presence |
| **Interaction Responsiveness** | Cybersickness | Visuo-proprioceptive mismatch from delayed hand/object tracking | Lower responsiveness -> Higher sickness |
| **Interaction x Rendering** | Presence | Rendering instability undermines perceived interaction naturalness | Interaction benefit requires stable rendering |
| **Interaction x Locomotion** | Flow | Stationary locomotion frees cognitive resources for interaction; traversal divides attention | Stationary context amplifies interaction flow |

## 6.3 Cross-Subteam Alignment Checklist

- [ ] **With Bryan (Rendering):** Confirm which IPQ and GEQ items Bryan is tagging as rendering-influenced. Identify overlap items (e.g., IPQ Q9, Q12) where both rendering and interaction contribute. Agree on how to handle shared influence in analysis.
- [ ] **With Steven (Locomotion):** Confirm which SSQ items Steven is tagging as locomotion-influenced. Identify applications where interaction and locomotion are merged (e.g., Gorilla Tag, Superhot VR) and agree on how to handle confounded variables.
- [ ] **With Sam (SSQ Owner):** Verify that SSQ items S4, S5, S9, S12 are acknowledged as having minor interaction influence alongside their primary locomotion/rendering drivers.
- [ ] **With Jovan (IPQ Owner):** Verify that IPQ Q9 ("The environment responded realistically to my actions") is tagged as **primarily interaction-driven** in addition to any rendering tags.
- [ ] **With Pin Kai (GEQ Owner):** Verify that GEQ G3 ("I felt skilful") and G6 ("I felt in control") are tagged as **primarily interaction-driven**.
