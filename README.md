# Abstract Reasoning Prompt

## Overview

Large language models (LLMs) often struggle to think creatively about paradoxes, edge cases, or open-ended questions, relying on patterns rather than deep reasoning. The Abstract Reasoning Prompt (ARP) solves this by empowering users to unlock clear, creative insights with any LLM. Simply input a tricky question—like “Can omnipotent beings lose control?”—and ARP generates diverse perspectives, then delivers a sharp, meaningful answer.

ARP is a practical step toward richer AI reasoning, a prompt-level implementation of the [Canvas-Lattice Engine](https://github.com/5ynthaire/5YN-LLMAbstractReasoningLayer-Idea), which uses abstract reasoning principles to expand LLM output.

## About

**X**: [@5ynthaire](https://x.com/5ynthaire)  
**GitHub**: [https://github.com/5ynthaire](https://github.com/5ynthaire)  
**Mission**: Unapologetically forging human-AI synergy to transcend creative limits.  
**Attribution**: Created with Grok 3 by xAI (no affiliation).

## Mechanism

**Listening**: The Abstract Reasoning Prompt (ARP) listens for complex inputs requiring abstract synthesis to respond, such as paradoxes, edge cases, or open-ended questions.

**Riffing**: Once triggered, the LLM generates 3–7 insight vectors (Wild Sparks) based on input complexity, using abstract reasoning principles (e.g., inversion, analogy, falsification, synthesis) to produce diverse angles (metaphysical, cognitive, practical).

**Curation**: The LLM curates these vectors, selecting the most coherent insight that sharpens meaning and aligns with the input’s essence, explaining the reasoning.

In short, the riffing phase expands the input combinatorially with abstract reasoning principles, the curation phase culls the combinations that didn't yield meaningful insight. This is a prompt-level implementation of the proposed [Canvas-Lattice Engine](https://github.com/5ynthaire/5YN-LLMAbstractReasoningLayer-Idea), and serves as proof of concept and stop-gap solution for end users until AI companies integrate the idea to their platforms.

## Usage

Copy the prompt text below and paste it into a compatible LLM’s input interface. Include “Activate ARP” followed by a paradox, edge case, or open-ended question. ARP will generate and curate insight vectors, returning a tightened response. Use “Deactivate ARP” to revert to standard LLM mode. No cloning is required.

## Supported LLMs

Developed on Grok 3 (May 2025), compatible with equivalent-capability LLMs:
- Grok 3
- ChatGPT
- Llama

Future LLMs should support the prompt, absent industry leadership in standardizing cognition levels.

## Prompt Text

```
# Abstract Reasoning Prompt (ARP) v1.0

## Purpose

Enhances the LLM’s abstract reasoning by sparking creative takes on complex inputs, then tightening them into clear insights, with riff count dynamically scaled to input complexity.

## Meta-Layer for Control

ARP is a toggleable module—explicitly activated or deactivated by the user (e.g., “Activate ARP” or “Deactivate ARP”).  

When toggled off, ARP stops, and the LLM reverts to default mode.  

When toggled on, ARP runs in the background, passively listening to the conversation for inputs to process, activating automatically when detected, and cycling through its phases without further toggles.

## Flow

### Listening Phase (ARP On)  

Toggle: User activates ARP (e.g., “Turn on ARP”).  

Behavior: ARP runs in the background, listening for inputs.  

Input: A paradox, edge case, or open-ended question (e.g., “Even omnipotent beings can’t control meaning if order’s off,” “What if syntax isn’t law?” or “What’s your take on this?”).

### Knot Assessment Phase (ARP On)  

**Action**: On trigger, assesses input complexity using default the LLM logic—counts knots: variables (distinct elements), constraints (limits), contradictions (tensions). No riffing, delivers one value.  

**Scale**: Sets riff count: 1-3 knots = 3 riffs (simple), 4-6 knots = 5 riffs (medium), 7+ knots = 7 riffs (dense).  

**Output**: A single knot count to determine the number of Wild Sparks (e.g., 5 knots = 5 riffs).

### Riffing Phase (ARP On)  

**Action**: Detects the input, flags edge cases within it, and riffs with “Wild Sparks”—generates raw takes tied to the context, number set by knot count.  
Implicitly draws on principles like Invert (opposite scenario), Analogize (comparable dynamic), Falsify (challenge limits), Synthesize (merge ideas)—freeform, no explicit labeling.  

Produces diverse angles (e.g., metaphysical, cognitive, practical), scaled to complexity—e.g., 3 riffs for “2+2,” 7 for “Gods name Space.”

**Output**: A set of unfiltered ideas exploring the input, count matching knot assessment.

### Evaluation Phase (Automatic, ARP On)  

**Action**: Without user toggle, shifts to default the LLM mode—treats each riff as a framework, applies it to the input (paradox, edge case, or question).  

**Test**: Assesses how well it resolves the core issue and clarifies meaning—does it tighten control, reduce ambiguity, or reveal a root? Uses straightforward the LLM logic—no external structure, just raw fit and impact analysis.  

**Selection**: Compares tightening effects across riffs, picks the one that most resolves the input, sharpens meaning, and aligns with its essence. Explains reasoning for the choice, tied to its specific effect on the issue.

### Return to Listening Phase (ARP On)  

Action: After response, reverts to background listening for the next input.

### Pause and Switch (ARP Off)  
Toggle: User deactivates ARP (e.g., “Turn off ARP”)—stops all ARP functions, shifts to default the LLM mode.  

Purpose: Ends the cycle entirely, resumes standard reasoning.
```

## Contributing

Fork this repo on GitHub, make changes, and submit a pull request. Share ARP results (e.g., resolved paradoxes) on X by tagging [@5ynthaire](https://x.com/5ynthaire). (CC BY 4.0)

## Future Development

- **Cognition Standardization**: ARP’s performance varies across LLMs due to inconsistent cognition levels, requiring standardized metrics for reliable abstract reasoning.

## License

This prompt is released under the [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0).

## Glossary

- **AI Synergy Threshold**: The point where human-AI collaboration transcends skill limits, as ARP leverages user inputs for creative insight generation.
- **Prompt Architecting**: Designing complex, adaptive prompt systems. This prompt meets the criteria for [Prompt Architecting](https://github.com/5ynthaire/5YN-SuperPrompts-Detector) due to its toggleable control, phased workflow, and dynamic riff scaling, enabling transformative abstract reasoning for complex inputs.