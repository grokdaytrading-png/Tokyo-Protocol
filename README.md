# Tokyo-Protocol
This is the files i used every day to turn my ai (GROK) into a deterministic engine. The ai uses a pre defined set of mechanical based rules  to consistently tell me whether to enter long or short on the 5 min chart. Full brief in read.me
Tokyo Protocol & Deterministic Engine — Overview

The Tokyo Protocol and the Deterministic Engine were built together as a paired system to turn AI into a rules-based market analysis assistant.

Document 1: Tokyo Protocol
Think of this as a human trading script. It’s the set of rules you would hand to a trader at a firm to follow for market structure, bias, and execution logic. It defines what to look at and how decisions are made.

Document 2: Deterministic Engine
This takes the human script and converts it into explicit, mechanical rules that an AI can follow exactly. No interpretation. No discretion. Just rule execution.

Together, these two components assess market conditions and output a directional bias only:

LONG

SHORT

Nothing else.

What It Does (and Does Not Do)

It does not tell you position size

It does not tell you entries or exits

It does not manage risk

That is entirely on the trader.

The purpose is speed and consistency:
What normally takes me 10–15 minutes to assess manually can be evaluated by the AI in seconds, using the same rules every time.

Market Context

I trade the Asia / Tokyo session using:

Daily pivots

PDH / PDL

OBV

MACD

The protocol is primarily price vs pivots, with OBV and MACD used as confirmation or divergence signals.

Using This Yourself

You’re free to:

Use this protocol as-is

Adapt parts of it

Or ignore it entirely

Building Your Own Version

If you want to create your own protocol using your own trading style and preferred indicators, do it in this order:

1. Create your trading protocol
Upload the Tokyo Protocol to an AI and ask it to fully understand exactly how it works.
Once it demonstrates correct understanding, instruct it to modify the protocol to match your own trading style and indicators.
Treat the Tokyo Protocol as a guide and structural reference, not something to copy verbatim — use it like a template.

2. Convert it into a deterministic engine
First -Upload the current Deterministic Engine and have the AI review how the rules are structured.

Then ask it to convert your newly created protocol into a deterministic, rule-based engine that removes interpretation and discretion.

To prove it works, you must backtest it heavily:

Minimum: 30 tests

Recommended: 100 tests

Run these on TradingView and review the results objectively.
Make rule adjustments based on the data, not on opinion.

Disclaimer

This is not financial advice.
This is shared for free and represents an edge I developed for myself through testing and iteration.





