# CSQ-VR Analytical Responsibility Tagging

This document maps each CSQ-VR questionnaire item to potential sources of cybersickness responsibility.  
Each question is tagged according to three analytical factors:

- **Locomotion Factors** – Movement method and artificial motion
- **Rendering Stability** – Frame rate, latency, visual stability
- **User Interaction Mismatch** – Sensory or control mismatch between input, motion, and perception

---

## Q1. Primary Locomotion Method  
*Teleport / Smooth Locomotion / Physical (Room-Scale)*

**Tags:**
- Locomotion Factors: ✅
- Rendering Stability: ❌
- User Interaction Mismatch: ⚠️

**Rationale:**  
Locomotion method is the primary independent variable affecting cybersickness. Smooth locomotion introduces continuous visual motion without corresponding physical movement, which can also lead to interaction mismatch.

---

## Nausea Subscale

### Q2. Nausea A – Stomach discomfort or urge to vomit

**Tags:**
- Locomotion Factors: ✅
- Rendering Stability: ✅
- User Interaction Mismatch: ⚠️

**Rationale:**  
Nausea is commonly associated with continuous artificial movement and unstable rendering performance. Input–motion mismatch may contribute secondarily.

---

### Q3. Nausea B – Dizziness or spinning sensation

**Tags:**
- Locomotion Factors: ✅
- Rendering Stability: ✅
- User Interaction Mismatch: ⚠️

**Rationale:**  
Dizziness is strongly linked to artificial rotation, acceleration, and frame rate instability. Input methods such as thumbstick rotation can amplify this effect.

---

## Vestibular Subscale

### Q4. Vestibular A – Disorientation or spatial confusion

**Tags:**
- Locomotion Factors: ✅
- Rendering Stability: ⚠️
- User Interaction Mismatch: ✅

**Rationale:**  
Disorientation often results from sensory conflict between expected physical motion and virtual movement. Interaction mismatch is a primary contributor.

---

### Q5. Vestibular B – Postural instability or imbalance

**Tags:**
- Locomotion Factors: ⚠️
- Rendering Stability: ❌
- User Interaction Mismatch: ✅

**Rationale:**  
Postural instability is primarily caused by lack of proprioceptive feedback and mismatch between physical posture and virtual motion.

---

## Oculomotor Subscale

### Q6. Oculomotor A – Visual fatigue or tiredness

**Tags:**
- Locomotion Factors: ❌
- Rendering Stability: ✅
- User Interaction Mismatch: ⚠️

**Rationale:**  
Visual fatigue is most strongly linked to rendering issues such as low frame rate, latency, or visual jitter.

---

### Q7. Oculomotor B – Eyestrain, blurred vision, or headache

**Tags:**
- Locomotion Factors: ❌
- Rendering Stability: ✅
- User Interaction Mismatch: ⚠️

**Rationale:**  
This item is a strong indicator of rendering instability, including reprojection artifacts and inconsistent frame pacing.

---

## Summary Responsibility Matrix

| Question | Locomotion Factors | Rendering Stability | Interaction Mismatch |
|--------|------------------|--------------------|---------------------|
| Q1 | ✅ | ❌ | ⚠️ |
| Q2 | ✅ | ✅ | ⚠️ |
| Q3 | ✅ | ✅ | ⚠️ |
| Q4 | ✅ | ⚠️ | ✅ |
| Q5 | ⚠️ | ❌ | ✅ |
| Q6 | ❌ | ✅ | ⚠️ |
| Q7 | ❌ | ✅ | ⚠️ |

**Legend:**
- ✅ Primary contributor  
- ⚠️ Secondary contributor  
- ❌ Minimal contributor  

---

This tagging framework supports causal analysis of cybersickness by linking reported symptoms to design responsibility domains.
