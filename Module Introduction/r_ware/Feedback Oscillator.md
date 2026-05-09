# Feedback Oscillator

![Feedback Oscillator](../../images/feedback-oscillator.png)

The Feedback Oscillator sits somewhere between a traditional sound source and a reactive sound system. It is not a classic VCO (voltage controlled oscillator, see: [Oscillator](../../Glossary/Oscillator.md)) in the usual sense, but rather an oscillator that continuously listens to itself.

The Feedback Oscillator is an oscillator with an internal feedback path (see: [Feedback](../../Glossary/Feedback.md)). Instead of producing a fixed, predictable waveform, the module reacts to its own output, making even small adjustments clearly audible.


# Favorite Modules – Episode 01
## Feedback Oscillator (R_WARE)

The Feedback Oscillator sits somewhere between a traditional sound source and a reactive sound system. It is not a classic VCO in the usual sense, but an oscillator that continuously listens to itself. Small changes tend to have large consequences, which makes this module feel less like a component and more like an instrument.

![Feedback Oscillator](../../images/feedback-oscillator.png)

---

### What is this module?

The Feedback Oscillator is an oscillator (see: ../../glossary/oscillators.md) with an internal feedback path (see: ../../glossary/feedback.md). Instead of producing a fixed and predictable waveform, the module routes its own output back into itself, allowing the sound to shape its own behavior.

---

### Why I like this module

I like this module because it resists precision. It does not reward exact tuning or fast parameter changes, but instead encourages slow gestures, careful listening, and patience. Using it feels less like dialing in a setting and more like steering a system.

---

### What I use it for

Typical use cases include evolving drones, unstable bass foundations, shifting harmonic textures, and organic modulation sources. I rarely use this oscillator in situations where strict pitch accuracy is required. Its strength lies in character and motion rather than control.

---

### How it works (roughly)

At its core, this is an oscillator whose output influences its own frequency and timbre through feedback. As the feedback amount increases, certain frequencies are reinforced while others collapse. This interaction is non‑linear, meaning the sound can change abruptly once a tipping point is reached.

See also: ../../glossary/feedback.md, ../../glossary/fm.md

---

### The basic patch

1. Feedback Oscillator → Filter → VCA  
2. No external modulation  
3. Slowly increase the feedback amount  

Listening note: Changes are often non‑linear. A very small adjustment can suddenly shift the sound into a completely different character.

---

### Variations and playability

Routing a slow LFO into the feedback amount can add gradual movement, ideally through an attenuverter (see: ../../glossary/attenuverter.md). Subtle filtering after the oscillator helps sculpt the resulting harmonics without suppressing the reactive nature of the feedback. Fast modulation generally pushes the module into unstable or chaotic behavior and is usually less musically useful in this context.

---

### Example patch: Breathing drone

This patch uses the Feedback Oscillator with a Random LFO modulating the feedback amount, followed by a reverb with a long decay time. The result is a mostly static tone that continuously reshapes itself without becoming rhythmic or predictable.

![Feedback Oscillator breathing drone patch](../../images/feedback-oscillator-drone.png)

---

### Final thoughts

For me, the Feedback Oscillator is not about accuracy or repeatability. It is a module for listening rather than measuring, and it rewards attention more than intention. Used with restraint, it can become the slow‑moving core of an entire patch.
