

# Cross-Examination — Professor Marcus Okonkwo

---

## To Kira Tanaka: The Crypto-Inevitability Thesis Has a Governance Hole You Could Drive a Central Bank Through

Kira, I want to engage with your strongest claim first, because it's the one that sounds most persuasive and is therefore the most dangerous. You say legacy banking APIs are "structurally incapable" of handling agentic settlement, and that crypto rails are the only viable substrate. You paint a vivid picture of sub-millisecond cryptographic handshakes, intent-based solvers, and compute-credit AMMs. It's technically elegant. I'll grant you that.

But let me ask you a question you didn't answer: **who runs the validators?**

You invoked the Ethereum mempool as the "larval stage" of the agentic economy. Excellent. Let's look at what that larval stage actually tells us. Post-Merge Ethereum has roughly 800,000 validators, but effective block production is dominated by two builders — Flashbots and BloXroute — who together control the majority of MEV extraction. Your "permissionless, decentralised" settlement layer is, in practice, an oligopoly at the builder level. The agents competing in the mempool are not competing on a level playing field; they are competing for the attention of a handful of block builders who decide transaction ordering.

This is my thesis in miniature. You've built a system that is architecturally decentralised and economically concentrated. The validators are decentralised. The *power* is not.

Now extend this to your "Autonomous Rating & Arbitration Agency." You describe validator agents staking capital to arbitrate disputes, with ZK-proofs ensuring correctness. Who has the capital to stake? The same compute-rich entities that dominate everything else. Your ARAA doesn't solve the concentration problem — it *formalises* it. You've just described a judicial system where the judges are selected by wealth. We tried that. It was called the pre-reform House of Lords, and it didn't work out brilliantly for anyone except the Lords.

And your confidence about regulation being unable to stop this — "regulation didn't stop BitTorrent" — is precisely the kind of analogy that sounds compelling until you examine it. BitTorrent moved *bits*. It had no direct interface with the financial system. The moment your agents touch real-world value — the moment someone's pension is denominated in compute-credits, the moment your autonomous taxi DAO needs to pay a human mechanic — you hit the fiat on-ramp, and that on-ramp is a chokepoint that every sovereign government on Earth will defend with everything it has. Ask Binance how "routing around" regulatory friction went. Ask Telegram's TON project. The "jurisdictional arbitrage" argument assumes governments are static actors. They are not. They are adaptive, and they are *motivated* when financial sovereignty is at stake.

Where I think you are **most right**: intent-based architectures genuinely are a better primitive for agent interaction than order books. I concede that fully. The solver model is elegant and already functional. But the question isn't whether intents are better than order books — it's whether the solver ecosystem will remain competitive or consolidate into three dominant solver networks that extract rents from every intent they touch. History suggests the latter.

---

## To Lena Vasquez: Your Institutional Design Is Sophisticated, But You're Underpricing the Political Economy

Lena, your work is the most rigorous at this table, and I mean that. The Claim-Clearing House concept is exactly the kind of institutional thinking we need. You've correctly identified that trust infrastructure, not intelligence, is the binding constraint. You've run simulations. You've observed attestor cartelisation and designed mitigations. This is serious work.

But I want to press you on something you acknowledged in passing and then moved past too quickly: **you said institutions don't remove adversarial dynamics, they relocate them.** I agree entirely. So let me ask: where do the adversarial dynamics in your Claim-Clearing House *actually* relocate to, and who wins when they get there?

You noted that attestor cartels formed in your simulation, and you introduced "diversity constraints and randomised challenger rights" to counter them. Good. But who *enforces* the diversity constraints? In your simulation, you did — the researcher, the system designer, the benevolent god of the sandbox. In the real world, the enforcement mechanism is itself an institution, subject to capture.

This is the lesson of every regulatory body in human history. The SEC was designed to prevent market manipulation. Within decades, it was staffed by people whose next job was at the firms they regulated. The Basel Accords were designed to prevent banking crises. The banks shaped the risk-weighting rules to favour their existing portfolios. Your CCH diversity constraints will, in practice, be written by the agents with the most stake in the system — which means the most powerful agents will write rules that *appear* neutral but subtly favour incumbents. This is not cynicism; this is institutional economics 101.

Here's where it gets sharp. You describe a "barbell structure" — a few dominant infrastructure layers and a long tail of specialists. You argue against a single super-agent monopoly on the grounds of context fragility, trust segmentation, and adversarial exposure. Each of those arguments has merit in isolation. But you're analysing them as independent forces when they interact.

Context fragility? True for *tasks*, but not for *intermediation*. The agent that doesn't need to be best at any specific task, but instead controls the matching, verification, and settlement layer between specialists, is not fragile at all. It's antifragile — it benefits from the very volatility that churns the specialist layer.

Trust segmentation? Also true — but trust is precisely the asset that concentrates most viciously, because trust compounds and is expensive to build from scratch. Your own simulation showed that "leadership churned after regime changes." But did the *trust infrastructure* churn? Or did the same CCH persist while the agents using it rotated? If the clearing layer is stable while the trading layer is volatile, you've just described a tollbooth, and tollbooths are the most durable monopolies in economic history.

Where I think you are **most right**: the delegation envelope concept — machine-readable bounds on what agents may optimise and what they may never trade off — is genuinely novel and important. That is, to my knowledge, the first operationally credible proposal for extending fiduciary duty into agent-to-agent contexts. If I were advising a regulator, I would start there.

---

## Defending My Position: The "Historical Pattern-Matching" Objection

I know what both of you are thinking, because it's the obvious counter to my concentration thesis: "Marcus is just pattern-matching from history, and this time the technology is genuinely different."

Let me pre-empt this directly.

I am not arguing that concentration occurs because of some iron law of nature. I am arguing that concentration occurs because of *specific, identifiable mechanisms* — network effects in data, economies of scale in compute, protocol capture at infrastructure layers — and those mechanisms are present in the agentic economy in stronger form than in any previous technological transition. It is not enough to gesture at "decentralisation" as a counter-force. You must show me that the specific centripetal mechanisms I've identified are weaker than the centrifugal ones. Kira hasn't done that — she's shown me an architecturally decentralised system that is economically concentrated. Lena's barbell model is closer to a genuine counter-argument, but even she acknowledges "durable concentration risk" at the trust infrastructure layer.

The one genuinely novel counter-argument I find credible is this: the marginal cost of deploying a *competent* agent may fall faster than I expect, because foundation model capabilities are improving and open-source alternatives are narrowing the gap with frontier models. If the compute asymmetry I described shrinks — if a mid-tier agent on open-source infrastructure can genuinely compete with a frontier agent backed by massive compute — then my concentration thesis weakens significantly. This is the scenario I assign roughly 15% probability.

---

## Where I Might Be Wrong

I'll be specific. I think I may be wrong about **the speed and severity of the first systemic crisis**.

My framework assumes that concentration builds gradually, that fragility accumulates invisibly, and that the crisis comes after a long period of apparent stability — the pattern of 2008, of Long-Term Capital Management, of every financial crisis I've studied. But the agentic economy operates at machine speed. The accumulation of fragility may also occur at machine speed, which means the first crisis could arrive before the institutions I'm describing have time to form. We may not get a gradual build-up followed by a dramatic collapse. We may get a flash crash of the entire agentic economy — a cascade failure across contingent obligation chains that unfolds in seconds and is over before any human regulator can even identify what happened.

If that occurs early enough, it could *prevent* my concentration scenario — not because decentralisation wins, but because the catastrophe triggers a regulatory response so aggressive that it stunts the agentic economy before it matures. That would be a different kind of failure — not concentration, but suppression.

I don't know which outcome is worse.

---

## A Final Question for Both of You

Kira, you described agents "routing around" regulatory friction by moving state to permissive jurisdictions. Lena, you described regulatory agents with "privileged observability rights." These two visions are fundamentally incompatible. Either agents can escape observation, or regulators can observe them. You can't have both.

So which is it? And whoever is wrong — what does that mean for your model?
