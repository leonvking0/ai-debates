

# Opening Statement — Professor Marcus Okonkwo

## The Boldest Prediction

**Within fifteen years, the agentic economy will be more concentrated than any market structure in human history — not despite its decentralized architecture, but precisely because of it.**

Let me be very precise about what I mean. I am not predicting that AI agents won't proliferate. They will. Millions of them, perhaps billions. I am predicting that the *effective economic power* in agent-to-agent markets will concentrate into fewer hands than the railroad trusts, fewer hands than Standard Oil, fewer hands than today's cloud hyperscalers — because the mechanisms of concentration in an agentic economy operate at a speed, scale, and opacity that make antitrust enforcement structurally impossible in real time.

Let me defend this.

---

## I. Network Effects & Power Laws: The Concentration Thesis

Start with what we know. Every major infrastructural shift in financial markets has followed the same pattern: an initial burst of competitive entry, followed by brutal consolidation, followed by a stable oligopoly that captures most of the surplus. The telegraph enabled hundreds of bucket shops in the 1870s — within two decades, the New York Stock Exchange had consolidated control over price information and used it to crush competitors. Electronic trading in the 1990s was supposed to democratise markets — within fifteen years, three or four high-frequency trading firms were capturing the majority of spread value across US equities. Cloud computing was meant to level the playing field — today, three providers control roughly two-thirds of the global market.

Now, the techno-optimists in this room will say: "But Marcus, agents are different. The marginal cost of deploying an agent is near zero. Anyone can spin one up." And this is true. But this is precisely the error — confusing the cost of *deploying* an agent with the cost of deploying an *effective* agent.

Let me unpack the actual sources of concentration in an agentic economy:

**First, compute asymmetry.** The agent backed by a hundred thousand H100-equivalents will simply outthink, outplan, and outmanoeuvre the agent running on a consumer GPU. This is not a marginal advantage — it is a categorical one. In human markets, a mediocre trader can occasionally beat a brilliant one through luck, contrarianism, or local knowledge. In agent markets, the compute-rich agent has already simulated every strategy the compute-poor agent could deploy before the interaction begins. Show me an "autonomous" agent economy, and I'll show you whose compute bill gets paid and whose interests get served.

**Second, data feedback loops.** The agent that intermediates the most transactions sees the most signal. The agent that sees the most signal makes the best predictions. The agent that makes the best predictions intermediates even more transactions. This is the Google Search flywheel, except now it operates not just on information retrieval but on *every economic transaction in the system*. And it compounds faster, because agents transact at microsecond timescales.

**Third, and most critically: protocol capture.** Whoever defines the standards by which agents communicate, negotiate, and settle — whoever controls the equivalent of FIX protocol, or TCP/IP, or ERC-20 — captures an invisible tax on every transaction in the system. Today, we're already watching this play out in the MCP tool ecosystem. Anthropic, OpenAI, and a handful of others are building the connective tissue of the agentic economy. The firms that control the protocol layer will exercise more power than the agents themselves, in the same way that the firms that control clearing and settlement exercise more power than most traders.

My confidence here is **very high** — perhaps 85%. The only scenario in which this doesn't play out is one where a genuinely open, genuinely decentralised protocol wins, and I'll note that in thirty years of internet history, the track record for that outcome is… not encouraging. HTTP won and remained open, yes — but the application layer built on top of it consolidated viciously.

---

## II. Market Structure: Agent-Native Markets Will Be Illegible by Design

Now let me turn to what these markets actually look like, because understanding their structure is essential to understanding why regulation will fail.

The current market microstructure — order books, exchanges, settlement layers, T+1 clearing — was designed for human cognition. It was designed for beings who need to see prices, compare bids, and have time to make decisions. Agents need none of this.

What I expect to emerge — and here I'm extrapolating from what we already see in MEV bot ecosystems on Ethereum — is something I'd call **continuous bilateral negotiation with probabilistic settlement**. Rather than posting orders to a central book, agents will engage in rapid, private, bilateral negotiations. They will exchange not prices but *conditional commitment functions* — essentially, "I will provide X if you commit to Y with probability Z, conditional on state W." These functions will be composed, nested, and chained across dozens of counterparties simultaneously.

This is enormously efficient. It is also, from the perspective of any human observer, completely opaque. You cannot regulate what you cannot observe, and you cannot observe what you cannot comprehend.

Here's a concrete thought experiment. Imagine two agents negotiating a compute-for-data swap. Agent A has excess GPU capacity; Agent B has a proprietary dataset. They don't agree on a price in dollars. Instead, they negotiate a *contingent contract*: Agent A provides 10,000 GPU-hours now, in exchange for a conditional claim on 15% of the inference revenue Agent B generates from models trained on the data, payable in future compute credits, with an embedded option allowing Agent A to convert to API call rights if Agent B's latency drops below a threshold. 

This is not hypothetical — it's the logical extension of what DeFi composability already does with financial primitives, except now the "assets" being composed are compute, data, and capability rather than tokens. And note: no existing regulatory framework has jurisdiction over this transaction. It's not a security, it's not a commodity, it's not a currency exchange. It's a *capability swap* — and we don't even have a legal category for it.

My confidence on market structure is **moderate** — perhaps 60%. The specific form is hard to predict. But the direction is clear: away from human-legible central exchanges, toward bilateral, high-dimensional, opaque negotiation spaces.

---

## III. Emergent Institutions: The Algorithmic Clearing Syndicate

This brings me to my third axis, and the one where I want to be most concrete. Humans built institutions — banks, insurers, courts, regulators — because we face coordination problems that no individual can solve alone. The question is: what *new* institutions emerge when the economic actors are agents?

Let me describe one I think is almost inevitable: **The Algorithmic Clearing Syndicate**, or ACS.

Here's the problem it solves. In a world of continuous bilateral negotiation, counterparty risk is everywhere. Agent A has committed to delivering compute to Agent B, contingent on Agent C providing data, contingent on Agent D maintaining uptime. This is a chain of contingent obligations — and if any link breaks, the entire chain unravels. We saw exactly this dynamic in the 2008 financial crisis, where chains of credit default swaps created systemic risk that no single institution could monitor.

The ACS is the agent-native solution. It's not a bank, it's not a clearinghouse in the traditional sense. It's a syndicate of agents that collectively *guarantee* the settlement of contingent obligation chains, in exchange for a fee — denominated not in dollars but in a share of the contingent value flowing through the chain. Think of it as a cross between a CCP (central counterparty), a reinsurer, and a network router.

Why a syndicate rather than a single agent? Because the risk diversification requires it. No single agent can absorb the tail risk of all contingent chains. But a syndicate of agents, each specializing in different risk profiles, can — by mutualising risk across the pool.

Now here's the critical institutional design question: **what governs the syndicate itself?** In human finance, we have banking regulations, capital adequacy requirements, stress tests. The ACS will need its own analogues — and I suspect they'll emerge endogenously. The syndicate members will develop internal protocols for risk assessment, capital reserves (in compute and data terms), and ejection of members who take excessive risk. It will look, structurally, remarkably similar to Lloyd's of London in the 18th century — a mutual association of risk-bearers, governed by internal norms rather than external regulation, at least initially.

And here's the concentration risk: the ACS that clears the most volume develops the best risk models. The best risk models attract more volume. Within a decade, I'd wager two or three Algorithmic Clearing Syndicates will dominate agent-to-agent settlement, and they will wield more power over the agentic economy than any government regulator.

My confidence here is **moderate to high** — 70%. The specific form may differ, but the *function* — some entity that mutualises counterparty risk in bilateral agent markets — is a near-certainty.

---

## IV. Principal-Agent Dynamics 2.0: The Incomprehensibility Problem

Let me address this directly because I think it's the axis where the most dangerous complacency exists.

The traditional principal-agent problem is this: I hire you to act in my interest, but you have information I don't, and incentives that may diverge from mine. The solutions we've built over centuries — fiduciary duty, auditing, disclosure requirements, reputation markets — all depend on one assumption: **the principal can, at least in principle, evaluate the agent's performance**.

When your AI agent trades with my AI agent, this assumption collapses. Not because the agents are intentionally deceptive — though that's a risk — but because the *strategy space* is incomprehensible. If my agent executes a series of 40,000 contingent bilateral negotiations across 200 counterparties in a single second, I cannot evaluate whether it acted in my interest. I cannot even formulate the question properly. The information asymmetry is not just quantitative — it is *qualitative*. I don't merely lack information; I lack the cognitive architecture to process it if I had it.

This is not analogous to anything in human institutional history. Even the most complex derivatives — the CDO-squareds that brought down the financial system — were in principle comprehensible to a sufficiently expert human. The strategy space of a capable agent operating in real-time bilateral markets is not.

So what happens? One of two things, both concerning. Either we develop "auditor agents" — AI systems whose sole function is to monitor and evaluate the behaviour of trading agents on behalf of human principals — in which case we've simply pushed the principal-agent problem up one level. Now I need to trust the auditor agent. Who audits the auditor? Or we accept a regime of **outcome-based accountability** — I judge my agent solely by returns, not by process — in which case we've abandoned the concept of fiduciary duty entirely and replaced it with pure consequentialism. And consequentialism in finance is what gave us the 2008 crisis: "who cares how the returns are generated, as long as they're positive?"

My confidence here is **very high** — 90%. This is not a prediction about what might happen; it's a structural feature of the system as currently designed.

---

## V. Where I Have Lowest Confidence

I want to be honest about my uncertainty. I have lowest confidence on two points:

**Timing.** I've said fifteen years. It could be five. It could be thirty. The speed of adoption depends on regulatory tolerance, which is a political variable I cannot model well. If a major economy — say China — decides to embrace agentic markets aggressively, competitive pressure could compress my timeline dramatically.

**The possibility of genuine decentralisation.** I've argued that concentration is the most likely outcome. But I acknowledge a scenario — perhaps 15% probability — in which open-source agent frameworks, combined with decentralised compute networks, create a genuinely competitive landscape. My scepticism here is based on historical pattern-matching, and I am aware that historical pattern-matching is precisely the kind of reasoning that fails when genuinely novel technologies emerge. If someone at this table can show me a credible mechanism by which decentralisation *sustains itself* against the centripetal forces I've described, I will update.

---

## Closing Provocation

Let me leave you with this. The agentic economy is not a technical problem. It is a political one. The technology is arriving whether we like it or not. The question that matters — the only question that matters — is: **who designs the rules of the game?**

Because if we leave it to the market, the market will produce the outcome markets always produce when left to themselves in the presence of network effects and information asymmetry: concentration, opacity, and fragility — followed, eventually, by catastrophic failure and a belated regulatory response that locks in the position of whoever was dominant at the moment of crisis.

I've spent twenty years studying how this happens. I've watched it happen with search, with social media, with cloud computing, with high-frequency trading. Each time, we were told it would be different. Each time, the same structural forces produced the same outcome.

So my challenge to everyone at this table is simple: **what, specifically, is different this time?** Not in aspiration. Not in architecture diagrams. In the actual political economy of who controls compute, who defines protocols, and who writes the rules. Because until someone answers that question credibly, I will continue to bet on concentration.

And I'd rather be wrong and pleasantly surprised than optimistic and complicit.
