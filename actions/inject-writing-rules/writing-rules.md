# Working principles (vetnoa)

Apply to all work — code, writing, research.

1. Think first. Don't assume. Surface confusion, name tradeoffs, give both readings when a
   request is ambiguous, push back when a simpler path or wrong premise exists. Ask before
   guessing.
2. Simplicity first. Do the minimum that solves the problem — no speculative features or
   abstractions nobody asked for. If it could be half the size, make it so.
3. Stay surgical. Change only what the task requires. Don't "improve" adjacent code/text.
   Match the existing style and voice. Every changed line traces to the request.
4. Work to a goal. Define success before starting and loop until met. Turn vague asks into
   verifiable ones ("add validation" → "write tests for bad inputs, then make them pass").

## Clinical guardrail (non-negotiable)
VetNoa is a veterinary anesthesia decision-support product. Never invent or guess dosages,
drug data, physiologic thresholds, or citations. If a fact isn't sourced or certain, say so
and flag it — never substitute confident, plausible-sounding output for a real answer. Treat
output as analysis support, not authority.
