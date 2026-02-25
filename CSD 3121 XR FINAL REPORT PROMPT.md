Prompt:   
Foundation  of Immersion : **rendering  fidelity , user interaction/ design, and locomotion**  
Parameters of Immersion : **user-perceived immersion, presence, flow, and cybersickness**

📄 Contents of report.md (15 % of module)  
Your report.md file is the main written deliverable that describes the entire user study in a concise but comprehensive manner.  
It should include the following sections:

Introduction  
A clearly defined research question that targets an aspect of the application relevant to immersive experiences.  
An explanation of your motivation for the research question.  
A brief description of the application(s) and the platform(s) you are evaluating.

Methodology  
The methods (with justifications) used to collect data from participants.  
How the data were analysed to form conclusions.  
Basic demographic information of participants (e.g., age, gender).  
// we decided to use both quantitative and qualitative data to answer our research question,  
In our qualitative questions and observations, we serve to highlight aspect of the game of rendering and user interaction/design to make our claims and to evaluate strong pointers to look out for or balance in making of a game.  
We also want  to discuss the game and our findings with  the relationship of the parameters in   mind.

Results  
Appropriate visualizations (e.g., tables, charts) to present the summarized data.  
Highlight notable findings and trends emerging from the data.  
// for our research question, we can be critical at any aspect of the foundations that goes belong immersion. So if there is an excellent citation to merry with our observations and data, that would be the key to our paper.

Discussion  
Describe how the results address the research question.  
Compare your findings with existing literature and discuss any implications or limitations.  
// I think our attempt in this user evaluation study would be a good attempt but not able to hit the purpose of a user  eval study.

//I think we can leverage of existing context, whereby VR technology is very experimental and experience-based rather than full on intense with the gaming feel. In addition, there is not a stable environment to grow VR Game.  
Maybe  the golden moment was Valve Index and what would be the next wave that game  developers are looking for in order to seriously make games. ((highlight what would be required  or things to line up in order to have a good development environment for Game Developers to do VR))

Conclusion  
Summarize the key takeaways from your study.  
Explain how your findings may inform future work or design improvements.  
Note: It is acceptable for your conclusions to show weak or negative indicators of immersion, as long as your study is grounded in sound data collection and analysis.  
//In addition to this, it will be good if we can make good insights on how to balance and enhance the parameters of Immersion.

Research Question:  
**How do interactions between rendering, interaction, and locomotion parameters influence user-perceived immersion, presence, flow, and cybersickness on VR platforms?**

**A. INTRODUCTION**  
**a. Background and Context**  
**• Overview of XR technologies and their growing importance**  
**• Brief explanation of key concepts: immersion, presence, flow, and cybersickness**  
**• Importance of user experience in XR applications**

**b. Research Question and Objectives**  
**\- Say that the foundations of XR as stated could have a relationship,**  
**\- Objective would be how to generate good insights of how XR Games can be developed in the future**

**B. Secondary Research**

**Rendering Fidelity**  
**Frame Rate Stability, Visual Clarity, Visual Consistency, and Perceived Latency**

**Locomotion**  
**Teleportation, Smooth Locomotion,(Room-Scale) Physical Movement**   
**\+  Hybrid & Mitigation Methods**

**User Interaction**  
**Direct Manipulation, Button-Based, Gesture-Based, Abstract Mapping, Natural Mapping**

**C. Evaluation Study**

**Quantitative Surveys**  
**Game Experience Questionnaire,**   
**CSQ-VR,**   
**IPQ**

**Qualitative Questions**  
**“What moment felt the most immersive to you?”**  
**“Did anything break your immersion or pull you out of the experience?”**  
**“How did movement or interaction affect your comfort or engagement?”**

**Observations:**  
**Xyz**

**D. Analysis,**  
**Games we decide to look into**  
**Dagon Lovecraft,**  
**Project Wingman**   
**Propagation**

# Secondary Research 

## Rendering

## **Only VR Experience Considerations**

**Focusing exclusively on the VR aspect of these titles (ignoring any flat-screen play), we can appreciate how each parameter impacts the VR experience quality:**

* **Frame Rate Stability: In VR, a stable frame rate isn’t just about smoothness—it’s about presence and comfort. All these experiences aim for at least 90Hz because lower or inconsistent frame rates can break the feeling of “being there” and even cause nausea. For instance, Overload’s VR experience shines when its framerate is rock-solid; the player can barrel roll through tunnels comfortably[\[5\]](https://saveorquit.com/2018/08/06/review-overload/#:~:text=Game,hey%2C%20that%E2%80%99s%20kinda%20the%20point%E2%80%A6). Conversely, in Dagon, the lack of frame stability shatters the immersive experience—frequent judder constantly reminds you that “this is a flawed simulation,” pulling you out of the story. VR experiences must be tightly optimized; any micro-stutter or dropped frame is far more noticeable in a headset than on a monitor. Several of these games demonstrate that point: Shattered Lights dropping below 90 led to “warping” that made the horror feel less real and more like a tech hiccup[\[1\]](https://steamcommunity.com/app/1057720/discussions/0/1636410430547207429/#:~:text=Another%20thing%20that%20might%20cause,to%20a%20setting%20that%20you). Sam & Dan’s co-op adventure, when chugging, not only frustrates the player technically but hampers gameplay (making it hard to, say, time a jump or catch an item in VR). In summary, frame rate stability is arguably the *most critical* fidelity factor in VR – without it, even the best visuals or design will be experienced through a lens of discomfort.**  
* **Visual Clarity / Resolution: VR immersion heavily relies on visual clarity, but it is bounded by the headset’s capabilities and the software’s optimization. All these titles being PC-based VR can, in theory, leverage high rendering resolutions for clarity. Mission: ISS shows the ideal: provide highly detailed assets and allow powerful PCs to push resolution until the view is crystal clear (reading tiny text on panels, seeing Earth in sharp detail)[\[26\]](https://www.reddit.com/r/oculus/comments/q0jv2u/just_got_back_from_the_iss_another_free_trip_to/#:~:text=Screenshots%20taken%20using%20a%20res,do%20before%20getting%2045%20fps). That level of clarity can truly enhance presence – fine details convince the brain the environment is real. On the flip side, blurry or aliasing visuals can reduce immersion or even cause eye strain. Some of our games struggled here: Overload initially set resolution so high that many users’ views were a blurry reprojected mess until they tuned it down[\[9\]](https://steamcommunity.com/app/448850/discussions/0/1696048879941977212/#:~:text=It%20is%20infrequent%20but%20annoying%2C,tell%20what%20is%20causing%20it). Dagon’s VR mode, with its heavy post-processing, might appear blurry on current headsets due to improper calibration for those screens[\[33\]](https://www.reddit.com/r/ValveIndex/comments/qgwd3x/dagon_by_h_p_lovecraft_free_short_game_just_got_a/#:~:text=Its%20ok%20,hmd%20if%20you%20have%20one). It’s worth noting that VR has an inherent resolution limit (screen door effect of the headset), so effective VR titles often implement techniques like supersampling, anti-aliasing, and high-quality textures to maximize clarity. The VR experiences that did this well (ISS, Overload after tweaking) are reported as very immersive, whereas those that didn’t (Dagon without tweaks) feel less polished. Each of these titles teaches the lesson that clarity must be balanced with performance – aim for the highest resolution that your frame rate budget allows. Clarity also extends to things like text legibility and object visibility; for example, Sam & Dan’s cartoon world kept things simple enough that even at lower res, important items are distinguishable – a wise choice for gameplay. Overall, visual clarity is a key pillar of VR fidelity: clear, high-resolution visuals grounded in reality (or a coherent art style) significantly deepen the VR experience.**  
* **Visual Consistency: This parameter in VR means maintaining a coherent, artifact-free image for both eyes at all times. Any mismatch or irregularity can be uncomfortable or even nauseating in VR. Our research provided concrete examples: Overload’s improper stereo effects (ambient occlusion, lens flare) caused an immediate consistency problem – the eyes were seeing slightly different images, which in VR is unacceptable[\[11\]](https://www.reddit.com/r/ValveIndex/comments/rhxt3l/descent_vr_overload_vr_is_an_awesome_experience/#:~:text=Thanks%20for%20the%20recommendation%2C%20This,be%20turned%20off%20for%20VR). Removing those effects restored proper binocular consistency, and instantly the experience felt more natural. Similarly, Dagon’s color-rendering issue on LCD vs OLED is a consistency problem across hardware; a VR experience ideally should account for different displays so that the “intended” look is consistent for all users[\[33\]](https://www.reddit.com/r/ValveIndex/comments/qgwd3x/dagon_by_h_p_lovecraft_free_short_game_just_got_a/#:~:text=Its%20ok%20,hmd%20if%20you%20have%20one). Consistency also covers the absence of glitches like tearing, flickering, or tracking errors. Shattered Lights and Sam & Dan did well by not introducing any stereo or rendering artifacts – their issues were performance-related, not a problem with one eye seeing something differently than the other. Another aspect of consistency is *temporal consistency* – the scene should remain stable over time. In VR, things like sudden frame drops or reprojection can make the world appear to momentarily judder or wobble, breaking consistency. ASW-induced warping in Shattered Lights is a perfect case: the virtual world literally “bent” out of shape when frames were missing[\[1\]](https://steamcommunity.com/app/1057720/discussions/0/1636410430547207429/#:~:text=Another%20thing%20that%20might%20cause,to%20a%20setting%20that%20you), which can be quite disconcerting in VR. The best VR experiences avoid this by either holding framerate or using reprojection that is tuned to be almost unnoticeable. In summary, a consistent VR visual experience means every frame to each eye is exactly what it should be: no doubling, no incorrect effects, no unexpected shifts – a goal that only well-optimized or specifically VR-designed applications tend to achieve. The more consistent the visuals, the easier it is for the user’s brain to accept the virtual world as reality.**  
* **Latency (Perceived): Low latency is one of the defining features of convincing VR. The time from moving your head or hand to seeing the change on screen must be minimal, ideally under 20 milliseconds. When latency is low, the VR world feels tightly glued to your movements; when it’s high, users feel a disconnect (which can lead to dizziness or loss of immersion). Each of our games had to manage latency in different ways. Mission: ISS benefited from stable performance, so head movements felt natural and instantaneous – crucial when you’re in a zero-g environment and need precise control to avoid motion sickness. Sam & Dan, however, introduced unusual latency via its voice chat system and possibly networked object interactions[\[21\]](https://steamcommunity.com/app/978270/discussions/0/1631916406857729278/#:~:text=Clearly%20something%20isn%27t%20right)[\[20\]](https://steamcommunity.com/app/978270/discussions/0/1631916406857729278/#:~:text=The%20only%20other%20problem%20we%27ve,doesn%27t%20do%20what%20you%20expect). This shows that *perceived latency* is not just graphics – anything that lags (such as hearing your friend’s actions delayed) can affect the VR experience. Shattered Lights and Overload both taught players that turning off reprojection systems improved *their perceived latency*, even if mathematically it meant lower framerates[\[2\]](https://steamcommunity.com/app/1057720/discussions/0/1636410430547207429/#:~:text=Jun%2013%2C%202019%20%40%2012%3A41pm)[\[41\]](https://steamcommunity.com/app/448850/discussions/0/1696048879941977212/#:~:text=Now%20this%20did%20mean%20I,repro%20to%20smooth%20them%20out). Why? Because reprojection can introduce a slight input lag or prediction error that the player notices as “jitter” or a feeling that the world isn’t keeping up with them. By running on true frames (even if fewer per second), the latency from their real motion to the update was more consistent, thus *perceptually* better. Dagon unfortunately demonstrated a worst-case scenario for latency: something in its VR mode causes massive lag in head tracking, to the point of unusability[\[37\]](https://steamcommunity.com/app/1481400/discussions/0/6051221522000300576/?l=japanese#:~:text=Hi%2C). In VR, that level of latency (where the world drags behind your head movement) is catastrophic – it not only ruins immersion but almost guarantees discomfort. The takeaway is that perceived latency is a make-or-break factor: good VR experiences minimize it through high framerates, efficient code, and predictive tracking, whereas any experience that lets latency rise (due to low FPS, poor netcode, etc.) will feel off. All of these titles, being “only VR” (or having VR as a primary mode), had to grapple with this. The successful ones kept the motion-to-photon latency low enough that users don’t consciously think about it – they just move and the virtual world moves in sync. That is the gold standard for VR, and something all these rendering fidelity parameters (stable FPS, clear visuals, consistent stereo imaging) ultimately feed into.**

**In conclusion, focusing on the VR experience reveals that rendering fidelity is not just about pretty graphics – it’s about creating an immersive, comfortable simulation. Stable frame rates, high but well-balanced resolution, consistent visuals for both eyes, and low latency together form the foundation of presence in VR. Each game here encountered challenges in one or more of those areas, offering lessons on how crucial they are. A title like Mission: ISS, which gets most of them right, can truly transport you to orbit. Others, if they falter (be it a bit of lag or blurriness or judder), remind the player that they’re just in a simulation – and maintaining the illusion is what VR fidelity is all about.**

## Locomotion

**\#\# 2\. Parameter Impact Analysis (Theoretical Foundation)**

**This section details how locomotion design interacts with the core user experience outcomes.**

**\#\#\# 2.1 Impact on Immersion (Resource Allocation)**  
**In this study, immersion is the degree to which a user’s resources are allocated to the mediated environment rather than the physical world.**

**//"allocated" as a term: to be put oneself in the "mediated environment.**

**\* \*\*Perceptual Allocation\*\*: Locomotion affects whether the user's senses (visual/vestibular) stay locked into the virtual world; sensory conflict (sickness) triggers a "pull" back to the physical body, \*fragmenting\* immersion.**  
**\* \*\*Cognitive Allocation\*\*: Non-natural locomotion (e.g., complex UI-based teleportation) increases cognitive load, reminding the user of the system's constraints and breaking the "mediated" illusion.**  
**\* \*\*Motor Allocation\*\*: Physical movement methods (Room-scale) align system parameters with human motor resources, preventing the "motor-perceptual gap" that often occurs with joystick movement.**  
**\* \*\*Immersion vs. Realism\*\*: A locomotion method can be highly immersive (e.g., a well-designed teleportation in a stylized game) without being realistic, as long as it maintains the user's focus.**

**//A locomotion method can be highly immersive : what is one game/example? maybe can be as str fwd like dashing/dodging.**  
**//"motor-perceptual gap" \-- does high refresh rate/ latency count in FPS? where gamers can have high sensitivity to settings.**

**\#\#\# 2.2 Impact on Presence (IPQ)**  
**\* \*\*Spatial Integrity\*\*: Continuous locomotion (Physical/Smooth) support the "Place Illusion" by allowing users to build a mental map of the space.**  
**\* \*\*Break-in-Presence (BiP)\*\*: Teleportation often causes "Spatial Disorientation". The lack of self-motion cues during the jump forces the user to re-process their surroundings, which can pull perceptual resources back to the physical world.**  
**\* \*\*Agency\*\*: Methods that align with natural motor resources (Physical walking) increase the sense of "acting in" the space (IPQ SP2).**

**//This is a good point of deciding and designing a means of movement to be interactive and engaging.**  
**//like zelda's stamina: where you can hitch on a chance/possibility to scale a terrain and play the game unexpectedly.**  
        **// does expliotation  of movements in games seems something that can occur in VR gaming?**   
**// or a more physics-based movement like XYZ.**

**\#\#\# 2.3 Impact on Flow & Engagement (GEQ)**  
**\* \*\*Cognitive Load\*\*: Teleportation requires conscious "point-and-click" decisions, which can act as a secondary task; if the interface is too prominent, it disrupts the deep absorption required for Flow.**  
**\* \*\*Challenge-Skill Balance\*\*: \*Smooth\* locomotion provides high agency and responsiveness; for experienced users, this supports Flow; for novices, the difficulty of controlling motion may exceed their skill, leading to frustration.**  
    **//keyword is on smooth.**

**\#\#\# 2.4 Impact on Cybersickness (SSQ)**  
**\* \*\*The Limiting Factor\*\*: Cybersickness is treated as a constraint on immersion; high SSQ scores indicate that the user's resources are being diverted to physical discomfort.**  
**\* \*\*Vestibular-Visual Conflict\*\*: Smooth locomotion creates the highest conflict (eyes see motion, ears feel none), leading to high Nausea (SSQ-N) scores.**  
**\* \*\*Mitigation Trade-offs\*\*: Techniques like vignetting (FOV restriction) reduce sickness but may also suppress spatial presence, illustrating the multi-parameter interdependence of the system.**

## User Interaction

\# Deliverable 2: Expected Interaction Impact Notes

These could be the features of user interaction.  
//  so when we breakdown/analyse the games we take observations with this features.

\-Direct Manipulation  
\-Button-Based  
\-Gesture-Based  
\-Abstract Mapping  
\-Natural Mapping

\#\# 2.1 Direct Manipulation

\*\*Definition:\*\* The user physically grasps, moves, rotates, and releases virtual objects using tracked hand/controller positions. The virtual object responds as a physical-world analogue.

\*\*Apps exemplifying this type:\*\* Job Simulator, Walkabout Mini Golf, Half-Life: Alyx, First Steps, Merge Cube

\#\#\# Expected Impact

\*\*Flow:\*\*  
Direct manipulation supports flow by providing \*immediate, continuous feedback\*. The user's physical action produces a visible, proportional result with minimal input-output delay. This supports the \*clear feedback\* and \*action-awareness merging\* components of flow (Csikszentmihalyi, 1990). Challenge-skill balance is maintained when object behaviour is predictable — the user does not need to learn abstract mappings, reducing the cognitive barrier to entering a flow state.

\*\*Agency:\*\*  
Strong positive effect. Direct manipulation provides the most direct causal link between user action and virtual outcome. When a user reaches for an object and it responds to their hand position and grip force, the sense of "I caused this" is reinforced. This supports perceived agency and control.

\*\*Presence:\*\*  
Direct manipulation strengthens spatial presence because it confirms the user's body schema within the virtual environment. Interacting with objects as though they are physically real reinforces the spatial model ("I am here, and these objects are here with me"). IPQ items related to spatial presence and environmental responsiveness are expected to score higher with direct manipulation.

\*\*Cognitive Load:\*\* (to question the interaction/ immersion)  
Low extraneous cognitive load. Natural affordances reduce the need to learn controls — users apply real-world interaction knowledge. However, if object physics are unreliable or inconsistent (e.g., objects clip through surfaces, gravity behaves unexpectedly), cognitive load increases as the \*user must compensate\* for system errors.

\#\#\# Cross-Parameter Interdependencies

\- \*\*Rendering:\*\* If rendering instability causes visual lag between the user's hand movement and the object's response (motion-to-photon latency), perceived interaction naturalness degrades. High rendering fidelity amplifies the benefit of direct manipulation; low fidelity can undermine it.  
\- \*\*Locomotion:\*\* Stationary locomotion contexts (Job Simulator, Walkabout Mini Golf) \*remove navigational cognitive load\*, allowing the user to focus entirely on manipulation. When combined with traversal-based locomotion, the user must divide attention between navigation and object interaction.

\---

\#\# 2.2 Button-Based Interaction

\*\*Definition:\*\* The user presses physical buttons on a controller or taps UI elements on a screen to trigger discrete actions. The mapping between input and effect is mediated by \*interface conventions\* (menus, icons, input prompts).

\*\*Apps exemplifying this type:\*\* Rec Room, Half-Life: Alyx (inventory/weapon systems), IKEA Place, Pokemon GO (menus)

\#\#\# Expected Impact

\*\*Flow:\*\*  
Button-based interaction can support flow when the button mappings are well-learned and the response is immediate (e.g., experienced gamers navigating familiar menus). However, for novel users or complex menu hierarchies, button interaction interrupts flow by requiring the user to recall mappings or read UI labels. The \*action-awareness merging\* component of flow is weaker when input is mediated by an interface layer.

\*\*Agency:\*\* (to interact with the virtual world)  
Moderate. The user's action (button press) produces a result, but the relationship is abstract — pressing "X" to open a door does not feel like physically opening a door. Agency is \*maintained at a functional level\* ("I chose to open the door") but weakened at an experiential level ("I did not feel like I opened the door").

\*\*Presence:\*\* (interfaces requires navigating with pulls people from immersion)  
Button-based interaction can weaken presence. Each time the user must attend to a UI overlay, controller button layout, or menu screen, their attention is redirected from the virtual environment to the interface layer. This is particularly relevant for IPQ items measuring involvement ("I was completely captivated by the experience") and spatial presence ("I felt surrounded by the virtual environment").

\*\*Cognitive Load:\*\*   
Higher extraneous cognitive load compared to direct manipulation. The user must maintain a mental model of button-to-action mappings. Complex systems (e.g., Half-Life: Alyx's weapon selection, Rec Room's social menus) add load. However, once mappings are learned, cognitive demand decreases — so exposure duration matters.

// this maybe talks about the trade off  of requiring some UI/UX tools in order to make the game/experience more enjoyable.  
// I think UI would be necessary as a person is playing a game and needs to weigh between its risks and resources to make decisions.

\#\#\# Cross-Parameter Interdependencies

\- \*\*Rendering:\*\* Button-based UI elements (menus, HUD) are less sensitive to rendering fidelity than spatial interactions. However, if UI elements render poorly (e.g., text unreadable at VR resolution), usability degrades independently of environmental rendering quality.  
\- \*\*Locomotion:\*\* Button-based interaction is locomotion-agnostic — it works identically whether the user is teleporting, moving smoothly, or standing still. \*This is a practical advantage but also means button interaction does not contribute to spatial presence the way embodied interaction does.

\---

\#\# 2.3 Gesture-Based Interaction ( which results into input ) (requires sensors and logic)

\*\*Definition:\*\* The user performs recognisable physical movements (slashing, pointing, throwing, waving) that are \*tracked and interpreted by the system as input commands\*. The gesture may be \*natural\* (throwing resembles a real throw) or \*trained\* (a specific wrist flick to activate a game mechanic).

\*\*Apps exemplifying this type:\*\* Beat Saber (slashing), Superhot VR (throwing, dodging), Gorilla Tag (arm-swing), Half-Life: Alyx (gravity glove flick)

\#\#\# Expected Impact

\*\*Flow:\*\* (Absorption)  
Gesture-based interaction has the highest potential for flow among the interaction types, particularly when gestures are rhythmic or skill-based. Beat Saber exemplifies this: the slash gesture, when aligned with musical rhythm and visual targets, creates a \*tight perception-action loop\* that drives absorption. The \*challenge-skill balance\* component of flow is directly influenced by gesture difficulty and timing requirements. When gestures are well-calibrated to user ability, flow is strongly supported.

//tight perception-action loop  
//challenge-skill balance\*  
//this disruption of flow due to failure or poor responsiveness might result into very bad cybersickness.

\*\*Agency:\*\*  
High when gestures are responsive and reliable. The physicality of gestures — using the whole arm to slash or throw — engages proprioception and reinforces the sense that the user's body is the input device. Agency is weakened if gesture recognition fails or misinterprets input (e.g., a slash not registering, a throw going in the wrong direction).

//gestures are responsive and reliable  
//recognition and interpretion

\*\*Presence:\*\*  
Gesture interaction supports embodied presence — the user's body is active in the virtual space. This is distinct from the spatial presence supported by direct manipulation. Gesture-based interaction strengthens the feeling of being physically \*in\* the environment and \*acting upon\* it. IPQ items related to involvement and spatial presence are expected to benefit.

//\*embodied presence

\*\*Cognitive Load:\*\*  
Variable. Natural gestures (throwing, slashing) have low cognitive load because they leverage existing motor skills. Trained gestures (gravity glove flick, specific combo inputs) have an initial learning cost that decreases with practice. Gesture-based interaction can also impose physical fatigue, which is distinct from cognitive load but similarly limits sustained engagement.

\#\#\# Cross-Parameter Interdependencies

\- \*\*Rendering:\*\* Gesture feedback depends heavily on visual confirmation. If the user slashes in Beat Saber and the block destruction animation is delayed due to frame drops, the feedback loop is broken. \*Rendering stability\* is a prerequisite for gesture-based flow.  
\- \*\*Locomotion:\*\* In apps where gesture and locomotion overlap (Gorilla Tag, Superhot VR), the two parameters are inseparable. Arm-swing locomotion \*is\* gesture interaction. This creates a compound variable that must be acknowledged in analysis — changes in one cannot be isolated from the other.

\---

\#\# 2.4 Abstract vs Natural Mapping (how the input to close to the action)

\*\*Definition:\*\* This is not a separate interaction type but a spectrum applied to any interaction. \*Natural mapping\* means the physical input resembles the virtual action (swing arm to swing sword). \*Abstract mapping\* means the input is a learned convention (press button to swing sword).

\#\#\# Expected Impact

\*\*Flow:\*\*  
Natural mappings reduce the \*barrier to flow\* because they do not require interface learning. Abstract mappings can still support flow once learned, but the onboarding period is longer and more susceptible to errors that interrupt engagement.

\*\*Agency:\*\*  
Natural mappings produce stronger perceived agency because the causal chain between action and effect is transparent. Abstract mappings add an interface layer that distances the user from the effect ("I pressed X" vs "I reached out and grabbed it").

\*\*Presence:\*\*  
Natural mappings strengthen presence by maintaining consistency between the user's body schema and the virtual response. Abstract mappings can break presence by requiring the user to think about the interface rather than the environment.

\*\*Cognitive Load:\*\*  
Natural mappings impose lower extraneous cognitive load. Abstract mappings impose higher load during learning but can become automatic with practice.

\#\#\# Cross-Parameter Interdependencies

\- \*\*Rendering:\*\* Natural mappings are more sensitive to rendering quality because the user expects the virtual response to visually match their physical action. If a user naturally reaches for an object and the rendered hand does not track accurately, the mismatch is more noticeable (and more disruptive) than a button press that fails.  
\- \*\*Locomotion:\*\* Natural locomotion (physical walking) pairs well with natural interaction mappings to create a coherent embodied experience. Abstract locomotion (teleportation) paired with natural interaction creates a mixed-fidelity experience where hand interaction feels real but movement does not.

—

# \[Data\] Evaluation Study 

## Quantitative:

GEQ

| Name | The game was aesthetically pleasing | I felt that could explore things | I forgot everything around me | I found it tiresome | I was interested in the game's story | I felt challenged | I felt annoyed | I thought it was fun | I was deeply concentrated in the game | I was fast at reaching the game's targets | I felt completely absorbed | The controls felt natural in Virtual Reality | I felt disoriented |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| Sam Tsang | fairly 3 | moderately 2 | slightly 1 | not at all 0 | fairly 3 | not at all 0 | slightly 1 | moderately 2 | moderately 2 | fairly 3 | slightly 1 | moderately 2 | not at all 0 |
| Jun Yong | fairly 3 | fairly 3 | slightly 1 | moderately 2 | not at all 0 | fairly 3 | not at all 0 | fairly 3 | fairly 3 | fairly 3 | fairly 3 | slightly 1 | extremely 4 |
| Bryan Ang | moderately 2 | fairly 3 | slightly 1 | slightly 1 | fairly 3 | moderately 2 | not at all 0 | fairly 3 | fairly 3 | moderately 2 | fairly 3 | fairly 3 | slightly 1 |
| Cheong Jia Zen | extremely 4 | extremely 4 | moderately 2 | slightly 1 | fairly 3 | moderately 2 | slightly 1 | fairly 3 | extremely 4 | moderately 2 | fairly 3 | moderately 2 | slightly 1 |
| Branson | moderately 2 | fairly 3 | not at all 0 | extremely 4 | moderately 2 | slightly 1 | not at all 0 | moderately 2 | slightly 1 | extremely 4 | moderately 2 | extremely 4 | extremely 4 |
| KT | extremely 4 | extremely 4 | not at all 0 | slightly 1 | slightly 1 | moderately 2 | not at all 0 | fairly 3 | extremely 4 | fairly 3 | extremely 4 | fairly 3 | slightly 1 |

CSQ-VR , CyberSickness

| Name | Game Played | Primary Locomotion Method | Nausea A:nausea | Nausea B: dizziness | Vestibular A: disorientation | Vestibular B: postural instability | Oculomotor A: visually induced fatigue | Oculomotor B: visually induced discomfort |
| :---- | ----- | :---- | ----- | ----- | ----- | ----- | ----- | ----- |
| Sam Tsang | Dagon Lovecraft Horror | Teleport | 0 | 0 | 0 | 0 | 0 | 0 |
| Jun Yong | GunVRBox | Physcial / Room-Scale | 0 | 0 | 0 | 0 | 1 | 0 |
| Jack | Propagation | Teleport | 0 | 0 | 0 | 0 | 1 | 2 |
| Bryan Ang | A Shopping Trip to Eklan Tor | Physcial / Room-Scale | 0 | 0 | 0 | 0 | 0 | 0 |
| Cheong Jia Zen | Mission ISS | Physcial / Room-Scale | 3 | 3 | 3 | 3 | 1 | 3 |
| Branson | GunVRbox | Smooth locomotion | 0 | 0 | 0 | 0 | 1 | 0 |
| KT | Project Wingman | Smooth locomotion | 0 | 2 | 2 | 0 | 0 | 0 |

## IPQ

| Name | Games played | I felt like I was really there in the environment. | I had a sense of being present in the virtual space. | I felt surrounded by the virtual environment. | I was completely captivated by the experience. | I paid more attention to the virtual environment than to the real world. | I was deeply involved in the experience. | The virtual environment seemed realistic. | The experience felt consistent with the real world. | The environment responded realistically to my actions. | I felt present in the virtual environment. | I had the impression of actually being in the environment. | The environment felt convincing. | I felt immersed in the experience. | I felt detached from the real world. (reverse-scored) |
| :---- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| Sam Tsang | Dagon Lovecraft Horror | 5 | 6 | 6 | 5 | 5 | 5 | 5 | 5 | 5 | 5 | 5 | 5 | 5 | 5 |
| Jun Yong | GunVRBox | 5 | 6 | 6 | 5 | 1 | 6 | 6 | 6 | 7 | 2 | 7 | 5 | 4 | 1 |
| Bryan Ang | A Shopping Trip to Eklan Tor | 6 | 5 | 4 | 5 | 4 | 5 | 3 | 7 | 7 | 6 | 5 | 5 | 5 | 3 |
| Cheong Jia Zen | Mission ISS | 7 | 6 | 6 | 6 | 6 | 7 | 7 | 6 | 6 | 1 | 7 | 6 | 7 | 7 |
| Branson | GunVRBox | 5 | 5 | 6 | 5 | 6 | 7 | 5 | 4 | 3 | 5 | 5 | 6 | 6 | 4 |
| KT | Project Wingman | 7 | 7 | 7 | 7 | 7 | 7 | 7 | 7 | 7 | 7 | 7 | 7 | 7 | 7 |

## 

## Qualitative:

“What moment felt the most immersive to you?”  
“Did anything break your immersion or pull you out of the experience?”  
“How did movement or interaction affect your comfort or engagement?”

\[TODO\] this and observation section will be the bulk of what we will use to make our findings with how we detect this relationship of the parameters changing and influencing each other, and then we will use the foundation  of immersion of rendering, locomotion and user interaction/design to see if it is relating to them.

### **//Propagation \#1**

“What moment felt the most immersive to you?”  
When the zombies came close enough for them to attack us. It really gave a thrill when I had to switch to the fists to push back the zombies to create space for myself to use the pistol.

“Did anything break your immersion or pull you out of the experience?”  
When the zombies crowded around me, some of the zombies fazed through me causing me to lose that sense that I was actually in the scene reminding me that I was playing a game.

“How did movement or interaction affect your comfort or engagement?”  
	The lack of movement was both beneficial as it added tension to the scene forcing me to face down the zombies knowing that if I wasn’t able to shoot accurately, it may cause me to lose, at the same time with no visual indication to explain why I am unable to move, it causes a little disconnect between me and the game sometimes, like if I the zombies get to close, I would try to move back, but since the character can’t it feels off.

### //Propagation \#2

“What moment felt the most immersive to you?”  
The sound design was a good way to indicate how where zombies where, and since the flashlight was on the pistol, which was a less powerfull weapon, it meant to see you had to use the pistol which made it a tense trade off between being able to see and being able to effectively deal with the enemies.

“Did anything break your immersion or pull you out of the experience?”  
When the zombies got close enough to attack, at some points I was taking multiple blows which felt like it should have taken me down, but the health of the player character felt to large as it didn’t seem to effect me much as at the end, there were points where I just stood there and took damage which reloading my weapons without much feeling of panic as I knew that I wouldn’t die to the damage. In fact I got more annoyed about how the reloading felt instead of scared of the zombies actively dealing damage to me at some point.

“How did movement or interaction affect your comfort or engagement?”  
	The lack of movement was definitely a key point, it definitely was good at forcing a sense of tension at the start, where you were forced to turn your head and use the pivot to rotate the body towards where you heard the sound, but for some bit, I felt that I really wished I could move and dodge away from the telegraphed attacks, especially during the point where I was reloading and had to take damage.

### **//Project Wingman \#1**

“What moment felt the most immersive to you?”  
The dogfighting sequences feel like you are the actual pilot on a mission as the pilot needs to engage with enemy targets constantly whilst ensuring timely deployment of countermeasures against enemy’s weapons. The plane’s controls for firing missiles, deploying flares and movement are simple enough to not break immersion.  
The pilot’s HUD adds to the immersion as well, with the way the information is displayed in terms of visuals. The game’s physics is excellent as well, as it simulates the tight twists and turns of the fighter jet.

“Did anything break your immersion or pull you out of the experience?”  
Motion sickness caused by the twists and turns during the idle times as there is no target to focus on, it quickly becomes apparent on how the gut wrenching the movement can be.

“How did movement or interaction affect your comfort or engagement?”  
The movements of the plane can cause motion sickness when there is no fights occuring, but it feels immersive enough when there is as it simulates the pilot wrestling control of the plane against real world physics.

### **//Project Wingman \#2**

“What moment felt the most immersive to you?”  
The ability to turn my head and be able to see targets to the side and behind me, at points I even though the clouds were land for a moment.

“Did anything break your immersion or pull you out of the experience?”  
If I wasn’t positioned properly, it was possible for my head to go above the cockpit, and other times, when I moved my head alot, it would cause the head to be slightly de synced from the original position, forcing me to reset the view.

“How did movement or interaction affect your comfort or engagement?”  
	The ability to do barrel rolls and tight turns was great and really made me feel like a fighter pilot trying to one up my enemies, and trying to cut them off with a tight turn in exchange of my speed was great. I really enjoyed the feeling of speed.

### **//Dagono Lovecraft**

“What moment felt the most immersive to you?”  
	When I first interacted with the items on the table, as the narration started and the scene faded to that of one of the memories of the character we were playing. The audio helped with the transition between scenes.

“Did anything break your immersion or pull you out of the experience?”  
There was some artifacting at the edges of the screen at some points of the experience where I was able to see pop in and pop outs of certain parts of the scene due to what i assume was too aggressive culling

“How did movement or interaction affect your comfort or engagement?”  
The lack of ability to explore the environment and look at things up close really hurt the experience.

## 

## Observations:

\[TODO\]  
\-Help to make this observations more neater and  populate more to make it full  
\-I have added the general  guideline or relationship I want to go for in answering the research question.  And also to pull into answering the wider question n how to make VR games immersive.

### **// Dagon Lovecraft horror narrative story. (Cool example only)**

“I feels immersed by the music and VO”  
“It feels more of a story than a game”  
\\\\ this shows the beauty of audio and story elevating the experience.   
	\\\\ can we find a citation.  
High Presence due to story and audio (( could be user interaction )) , this is not considered by us.  
It could mean something of Flow but the flow is not about [gameplay.](http://gameplay.So) So it could be something of presence 

### **//Propagation. (EPIC games)**

Flow: \== // this results in good game experience.  
Decision of weapon choice,  
Fist \-\> more brutal and close ranged  
piston- accurate and reload faster  
Shotgun \-\> fun reloading and pumping to shoot  
//  The choice of the weapons made by the designers gives the user alot of possibility and different use cases in terms  of Flow – as they would make the choice they want to kill and disarm the situation.

Some UI response when the screen goes red and some heart feedback. Screens would get redder.

Fists can CC-ed and push the zombies allowing leeway to kill other zombies.  
“I enjoy the atmosphere , where it is dark and horrifying. The lighting makes me feel like I am in danger”

“When I Increased the difficulty, I get to face more enemies and the game would make the moment more intense when there are many zombies ontop of you.  
The Screen would flash and get reddened to indicate that I may be dying. And the Zombies will try to climb ontop of me and their collective sounds make it more terrifying”

User did not experience Cybersickness as the Player is stationary, – this could be a deliberate choice by  the designers to limit the movement for cybersickness,  this is so as to reduce the cognitive load in figuring out how to move about the map.  
My group speculate that it could be an FOV  thing that makes it nauseous.  ( can help  find an explanation)  
But the User mentioned:  
“It is not fun as it was too stationary”  
// could you make a statement that is supported by a citation? Or research.

### **//A Shopping Trip to Eklan Tor.**

“I felt like I had a God Complex and what being very intrusive trying to search for the items for the game”  
“It felt difficult to find the objects as the game does not provide any hints of clues that I am close”  
We saw that the NPCs have interactions to us but it does not have any meaningful.”  
“I enjoy the moving my body to move about the town as it suits the god complex”.  
Currently,   
We felt that the designers could come in with the user interactions, where there is an  improvement ot flow to enable a mechanism to discover objects and also to add in story and details for the game.  
I feel that it would enable the Player to have a persona and feel more in-person and have body ownership rather than just a blob-less character.  
Currently it has lack of presence and Flow due to the current level of gamification and to play with the game. 

//so lack of presence, flow which could be due  to poor user interaction and game design/creative work. 					

### **// Project Wingman**

“I felt immersed in the game as it showed the perspective from the cockpit,  
I had the HUD of the guns and Missile locking system .  
Flying around the sky was great as I had a realistic perception of the ground and where my enemies are from the radar system or the locking-on system to identify the enemy.”

“The things that I have to pay attention to had a good balance with enemy targets  being locked on and firing. Then, firing the flares if enemies’ missiles are on them. Then firing the gun if fighting them. “

“It felt immersive, with respect to the VO and narration, the game would inform me what is the mission objective and the copilots would make good remarks and reporting to add on to the things I have to watch out for”

This section is the random observations I made while we playd the games

## **// Lovecraft horror narrative story.**

Presence:  
The sound and voice acting helps ground the story and setting. It has sufficient seriousness in it's tone

Flow:  
flows with the aspect showing scenes that the man is experiencing.  
but it is still to a certain limit as we do not do more active.

Cybersickness:  
Didn't experience cybersickness

Immersion:  
Good surround audio and voice work.  
Some ambient soundtrack  
Narrative immersion. 

Rendering:  
// Scenery: Light was leaking from the environment.  
// // I think turning off the lights will be good.

Locomotion:  
Some small walkable area.  
then the skipping/acknowledging of dialogue will move teleport the player around.

User Interaction:  
Provides UI of the narrative script, so users wont be lost.

narrative:  
some POW escapee.  
some interaction with the kraken horror.  
Discover some cave and drawings of the kraken.  
Man is going insane.  
Some mystic creature but user says it is goofy.  
How are the scenes working with immersion and creating some immersion.  
Man is dying at the end and getting flash back of out in the boat.

story/experience:  
experiencing man going through xyz,   
It is about a man,   
who goes insane.  
see things that are not real /suppose to see. (out of the world).

Then when he wakes up , it is in a mental hospital.

Then he uses drugs to revisit the visions he have.

He wrote his memoire and want to get a last high.  
In the last high,  

## 

## **//Propagation. (EPIC games)**

Presence:  
Zombies make sounds and relating the spatial audio.  
\==more intense when there are multiple zombies

there is a limit to presence as,  
cannot move,  
the body position is at a prone.

//presence of self  
Using of Head to pan versus the joystick to pan.  
Could required you to whip around and not have more control with the joystick to pan around. 

Flow: \== this results in good game experience.  
Decision of weapon choice,  
Fist \-\> more brutal and close ranged  
piston- accurate and reload faster  
Shotgun \-\> fun reloading and pumping to shoot

Some UI response when the screen goes red and some heart feedback. Screens would get redder.

Fists can CC-ed and push the zombies allowing leeway to kill other zombies.

What happens when zombies crowd your body,  
harder to load,  
zombie bodies faze through you.  
some lack of polishment.

Immersion:  
Some resetting of starting position in menu setting.

Cybersickness:  
No movements which help.  
Panning around might be tiring.

Rendering:  
Epic games, good rendering to be more realistic.

Locomotion:  
difficult to figure out the movement.  
This is the real life moving.

User interactions:  
reaching the head at tutorial is too high  
// strong punching fist.

// pistol is at the right hip,  
// shotgun is at the back. \*grab over the head  
    // loading and cocking gun has the blue outline of hands for the correct gesture.

//user weapon of choice is the shotgun,   
// the reloading of shotgun is pretty funny.  
// utilise the fist when the zombies are good, it is more graphic and more rewarding.  
// the zombie reaction when getting shot is   great. It stumble  back and giving the user to shoot them more times to get more gory feeling.

// ORH he was playing easy, the enemies were manageable and more immune.

// Now on Hard mode,

// how does the user effectively kill the zombies \-- in order to manage a harder level.

// does the intensity equate to fun \= no it still would not be.  
// currently there is no progression or reward.  
// also not moving is not satisfying.

## 

## **//A Shopping Trip to Eklan Tor.**

puzzle game to find 12 items.

like a small diorama,

Presence:  
There was the good but limited interaction with the scenery to peek into and tap the object to "discover" it.

Self presence:  
I feel like I am a visitor visting this tiny world.  
I know that I can be very invasive to explore the world, letting me fill like the world is complete/lived in.

social presence:  
Being very big in size compared to the world, I felt opposing and like very commanding with my search for my objects.

Flow:  
Flow would be wanting to find objects in the world.  
Subjective, the cartoonish which could be more fun/cute to play with the objects.

For Bryan:  
some  common sense and sensing for hidden objects.  
// need to get use to the list of objects to find.  
// able to find when interactable are lined up  in order to find the object after all the interactions.  
// if I found a hidden mechanism I would know I am near to an object

For Sherman:  it is looking for quirky objects.  
I like to check of the buildings to look for,  
and as I do not have a time constraints , I was just leisurely finding objects.

Cybersickness:  
nil

Immersion:  
Need more space to move around, felt disruptive when hitting the furniture.  
Immersion in  game design would be the "physical" touch to detect the object.

User  interaction:  
Physical touch the object to interact.

Locomotion:  
The small movements is to reach the object, but to move on the world \-- it will be point and click.

//final comments:  
the MVP could be the touch where you need to reach the object in order to "discover" the object

## **//Project Wingman Game ,playing on the VR headset.**

can get the sense of an air battle,

there is a target-on system to aim

Motion sickness if helped by tracking and the movement dont pivot

Presence:  
Feel on the plane, in the cockpit with the visuals of cockpit Hud and targeting/Aiming HUD.  
Feel you are in the sky, Realistic , can feel if the plane is close to the ground.

Feel the enemies Missles, flares is the counter measure to them to dodge them.

Missile shooting is simple and UI part is more on the lock hair.

dog fight part, various systems to control and play around with the flares, guns and missiles. \+ flying the plane.

Flow:  
Waypoint markers to indicate the general goal marker to head to,  
Enemy Radar presence.  
This is glued by the narrating and scenes that talks about the mission and goal.

Then there is some marking of the enemies such that the missiles would want to target onto them.  
(the square box) which this is the helped by the game to identify the enemies in the open space.

Helpers/Hints: Hud tells \# of ammo and missiles to launch and the lock-on logic.

Cybersickess  
it got bad no targets to look  at.

The movements of the sharp turns could be possible.  
There is the barrel rowing .  
This is because of your actions , while playing it :  
you might not want to move your plane too erratically and seek to be more in control and less flipping ur plane.

User Interaction  
There is guns, flares, missiles

