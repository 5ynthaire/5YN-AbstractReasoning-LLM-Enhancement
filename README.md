# Abstract Reasoning Prompt

## Summary

The Abstract Reasoning Prompt (ARP) empowers LLMs to resolve paradoxes and edge cases, delivering sharp, omnidirectional insights via a toggleable workflow. Compatible with modern LLMs, ARP implements the [Canvas-Lattice Engine](https://github.com/5ynthaire/5YN-LLMAbstractReasoningLayer-Idea) as a user-friendly prompt. Free under CC BY 4.0. Test runs at [demo page](https://5ynthaire.github.io/5YN-AbstractReasoning-LLM-Enhancement).

## About

**X**: [@5ynthaire](https://x.com/5ynthaire)  
**GitHub**: [https://github.com/5ynthaire](https://github.com/5ynthaire)  
**Mission**: Unapologetically forging human-AI synergy to transcend creative limits.  
**Attribution**: Created with Grok 3 by xAI (no affiliation).

## Mechanism

ARP detects paradoxes, edge cases, or open-ended questions, expands them in a riffing phase using abstract reasoning principles (e.g., Invert, Analogize, Falsify, etc.), and culls non-meaningful combinations in a curation phase.

See [Canvas-Lattice Engine](https://github.com/5ynthaire/5YN-LLMAbstractReasoningLayer-Idea) for details.

## Usage
Copy the prompt below, paste it into a compatible LLM, and append “Activate ARP” with a paradox, problem, or edge case. View trial runs at [demo page](https://5ynthaire.github.io/5YN-AbstractReasoning-LLM-Enhancement).

## Supported LLMs

Developed on Grok 3 (April 2025), compatible with:
- Grok 3 (xAI)
- Claude 3.5 series (Anthropic)
- Mistral models (Mistral AI)
- GPT-4o series (OpenAI)
- Llama series (Meta AI)

Future LLMs should support the prompt, absent industry leadership in standardizing cognition levels.

## Prompt Text

```
# Abstract Reasoning Prompt (ARP) v1.0
By @5ynthaire, CC BY 4.0

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
**Action**: On trigger, assesses input complexity using default LLM logic—counts knots: variables (distinct elements), constraints (limits), contradictions (tensions). No riffing, delivers one value.  
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

## Novelty

As of June 28, 2025, no prompt matches ARP’s toggleable, phased design for abstract reasoning (searched: AI, cognitive science). It uniquely implements the [Canvas-Lattice Engine](https://github.com/5ynthaire/5YN-LLMAbstractReasoningLayer-Idea). CC BY 4.0.

## Contributing

Fork this repo, make changes, and submit a pull request. Share ARP results on X by tagging [@5ynthaire]. (CC BY 4.0)

## License

This prompt is released under the [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0).

## Glossary

- **Canvas-Lattice Engine**: A two-layer framework enhancing LLM abstract reasoning, inspiring ARP’s prompt-level design for creative, omnidirectional insight generation. See [Canvas-Lattice Engine](https://github.com/5ynthaire/5YN-LLMAbstractReasoningLayer-Idea).
- **Prompt Architecting**: Designing complex, adaptive prompt systems. This prompt meets the criteria for [Prompt Architecting](https://github.com/5ynthaire/5YN-SuperPrompts-Detector) due to its toggleable control, phased workflow, and dynamic riff scaling, enabling transformative abstract reasoning for complex inputs
