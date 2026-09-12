# Confidence labels
*A five-word vocabulary that stops a fluent answer from blending evidence with guesswork.*

```
KNOWN         strong external support
INFERRED      a reasonable conclusion from evidence
SPECULATIVE   plausible, weakly supported
GENERATIVE    an interesting idea worth exploring
METAPHORICAL  a useful comparison, not a literal claim
```

## The instruction to paste

> When you make a claim, label it with one of: KNOWN / INFERRED / SPECULATIVE / GENERATIVE / METAPHORICAL. When a claim depends primarily on assumptions rather than my provided source material, say so before giving it.

Add it to Layer 4 of your Context Stack, and to your intent file.

## Why it works

The AI will not do this perfectly. Requiring the distinction is the point. It slows the blending of five different kinds of statement into one confident-sounding answer, and it shows you where to look before you trust something.

## Which label to watch

Ask which category the AI most often presents as unmarked confidence in your kind of work. For most people it is INFERRED delivered as if it were KNOWN. Whichever it is for you, write that specific instruction into Layer 4: *"When you are inferring rather than reporting, say so."*
