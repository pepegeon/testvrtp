# Rendering Fidelity Summary in Selected VR Games

This document summarizes rendering fidelity across selected VR titles, organized by four key categories:
Frame Rate Stability, Visual Clarity, Visual Consistency, and Perceived Latency.

---

## Shattered Lights (VR Horror, Room-Scale)

### Frame Rate Stability
- Struggles to maintain the target 90 FPS on mid-range VR PCs.
- Frequently dips below 90 FPS, triggering Oculus ASW.
- ASW introduces visible warping and jitter; developers recommend disabling it.
- Without ASW, performance is more consistent but still occasionally choppy.

### Visual Clarity
- Best visual clarity achieved at 100% SteamVR supersampling (1:1 pixel ratio).
- Increasing resolution significantly impacts performance and causes frame spikes.
- Native resolution is reasonably sharp but offers little headroom for improvement.

### Visual Consistency
- Stable art style and lighting when running near target frame rate.
- No texture popping or stereo rendering issues reported.
- Visual inconsistency mainly introduced by ASW-induced warping during frame drops.

### Latency (Perceived)
- Low latency and responsive tracking when frame rate is stable.
- ASW-related jitter increases perceived latency and discomfort.
- Disabling ASW improves tracking consistency despite occasional dropped frames.

// what would be the take away?
// were vr gamme developers able   to make a game that they wanted?
// were they contraint by current vr hardware and development.
// is there a certain charm/precision like games of mario/small gaming console,
// where all ram and display is used to make the game good and lasting.
// or does VR games being created comes from the standard game engine like unity/unreal.
// Are they efforts or intention to have a VR (Game) Engine.

---

## Overload (6DOF Shooter)

### Frame Rate Stability
- Can maintain rock-solid 90 FPS on high-end hardware.
- Mid-range systems often drop to 45 FPS with reprojection, especially in CPU-heavy scenes.
- Performance highly dependent on CPU capability and scene complexity.
- Stability improves significantly with powerful GPUs and optimized settings.

//I wish this could be written in words and not so techno-robot.
//so average playing experience was not good and not many got to play at the best quality?

### Visual Clarity
- Default VR resolution is very high, often too demanding for many systems.
- Reducing supersampling is necessary for smooth performance on mid-range hardware.
- When tuned correctly, visuals are crisp with high-quality lighting and textures.
- Certain post-processing effects (ambient occlusion, lens flares) should be disabled for clarity and performance.

// is this a learning lesson? or managing resolution
// or maybe a crutch of supersampling
        // is VR headset too good to be a display? in that it is too much parameters to tune  
        // sort of like simulating with eyes in mind instead of like a projection in 3d space.

### Visual Consistency
- Generally consistent stereo rendering once problematic effects are disabled.
- Incorrect stereo post-processing effects can break immersion if left on.
- Reprojection systems can introduce micro-stutter during motion, affecting consistency.

### Latency (Perceived)
- Very low latency at full frame rate, supporting fast-paced movement comfortably.
- At 45 FPS with reprojection, perceived latency increases noticeably.
- Disabling reprojection improves motion responsiveness when hardware allows.

// what is this "Perceived" tag put onto latency about?
// what is perceiving what and resulting in what.


---

// From here I am gazing through.
// without pictures of video previews, Idk what you are talking about.
// and it is highly specific where it is not elaboration or explained 
// other than some technical lingo.
// can't tell if it is a good or bad example.

## Sam & Dan: Floaty Flatmates (Co-op Puzzle)

### Frame Rate Stability
- Performance is inconsistent despite simple visuals.
- CPU bottlenecks cause frame time spikes even on powerful systems.
- Some users experience frequent stutter regardless of graphics settings.
- Optimization issues acknowledged by developers.

### Visual Clarity
- Cartoon art style is clear and readable at default resolution.
- No major clarity complaints, but visuals are not high-detail.
- Supersampling is rarely viable due to CPU-bound performance.
- Clarity is adequate but not a defining strength.

### Visual Consistency
- Stable stereo rendering with no major graphical artifacts.
- Interaction inconsistencies (object grabbing, physics lag) break immersion.
- Performance drops can cause minor reprojection artifacts.
- Main consistency issues stem from physics and networking rather than rendering.

### Latency (Perceived)
- Notable latency in in-game voice chat compared to external solutions.
- Object interaction can feel delayed or “heavy.”
- Rendering latency increases when frame rate drops.
- Experience improves significantly with stable FPS and external voice chat.

---

## Mission: ISS (Simulation)

### Frame Rate Stability
- Exceptionally stable and well-optimized for VR.
- Maintains 90 FPS even at extremely high supersampling on high-end GPUs.
- Rarely triggers reprojection under normal conditions.
- Designed to scale smoothly across hardware tiers.

### Visual Clarity
- High-fidelity models and textures developed with NASA collaboration.
- Excellent clarity; small text and fine details are readable.
- Supports very high supersampling without performance degradation.
- One of the strongest examples of visual clarity in VR.

### Visual Consistency
- Highly consistent visuals with correct stereo rendering.
- No noticeable LOD popping, flicker, or lighting inconsistencies.
- Baked lighting ensures stable shading throughout the experience.
- Polished presentation reinforces immersion.

### Latency (Perceived)
- Very low perceived latency due to stable frame rate.
- Head and controller tracking feel immediate and natural.
- Any discomfort reported is due to motion design, not technical latency.
- Represents best-practice VR latency performance.

---

## Dagon: by H. P. Lovecraft (Narrative VR)

### Frame Rate Stability
- Poorly optimized for VR, even on high-end systems.
- Frequently runs at ~45 FPS with heavy GPU usage.
- VR mode significantly more demanding than non-VR mode.
- Performance instability is a major weakness.

### Visual Clarity
- Atmospheric visuals, but clarity is limited by performance constraints.
- Increasing resolution dramatically worsens frame rate.
- Visuals appear better on OLED headsets than LCD due to color grading.
- Often requires sacrificing clarity to maintain basic performance.

### Visual Consistency
- Static scenes reduce traditional rendering artifacts.
- Severe head-tracking stutter causes major visual inconsistency.
- Differences in appearance across headset display types.
- Inconsistent synchronization between headset and desktop view reported.

### Latency (Perceived)
- High perceived latency due to head-tracking stutter.
- Some users describe VR mode as unusable.
- Passive nature of the experience makes latency more tolerable for some.
- Overall latency performance falls below acceptable VR standards.

---

## Overall Takeaway

- **Mission: ISS** sets the benchmark for VR rendering fidelity across all categories.
- **Overload** excels when properly tuned and paired with strong hardware.
- **Shattered Lights** and **Sam & Dan** suffer mainly from performance instability.
- **Dagon** demonstrates how poor VR optimization can undermine otherwise strong artistic content.

Stable frame rate, consistent stereo rendering, and low latency remain the most critical factors for high-quality VR experiences.


//idk if this achieve the mark of the secondary research.
// there is no features or concepts I can latch on as it is very example-first.

### Frame Rate Stability
### Visual Clarity
### Visual Consistency
### Latency (Perceived)
seems like these are your concepts, double check this and
//then, explain these concepts with how VR games/app achieve these stuff.
//then can play more with the parameters of immersion: presence, flow, immersion and cybersickness
// and speculate/hypothesis some correlation.

//// ORH I DID NOT SEE THE REPORT, I shall read it tmr
// "Rendering Fidelity in Selected VR Games" 
