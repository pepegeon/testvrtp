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

---

## Overload (6DOF Shooter)

### Frame Rate Stability
- Can maintain rock-solid 90 FPS on high-end hardware.
- Mid-range systems often drop to 45 FPS with reprojection, especially in CPU-heavy scenes.
- Performance highly dependent on CPU capability and scene complexity.
- Stability improves significantly with powerful GPUs and optimized settings.

### Visual Clarity
- Default VR resolution is very high, often too demanding for many systems.
- Reducing supersampling is necessary for smooth performance on mid-range hardware.
- When tuned correctly, visuals are crisp with high-quality lighting and textures.
- Certain post-processing effects (ambient occlusion, lens flares) should be disabled for clarity and performance.

### Visual Consistency
- Generally consistent stereo rendering once problematic effects are disabled.
- Incorrect stereo post-processing effects can break immersion if left on.
- Reprojection systems can introduce micro-stutter during motion, affecting consistency.

### Latency (Perceived)
- Very low latency at full frame rate, supporting fast-paced movement comfortably.
- At 45 FPS with reprojection, perceived latency increases noticeably.
- Disabling reprojection improves motion responsiveness when hardware allows.

---

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
