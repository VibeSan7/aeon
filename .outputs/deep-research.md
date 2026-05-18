*Deep Research — 2026-05-18*

Topic: AI agents
Mode: deep — 26 sources (T1:12 T2:11 T3:3) — 8 papers

The market has scale (51% of enterprises in production per LangChain; 15× YoY agent growth in Microsoft 365) but reliability is lagging capability. Princeton's Kapoor & Narayanan document reliability improving at half the rate of accuracy on general benchmarks; one-seventh on customer service. Datadog telemetry shows 5% of LLM call spans erroring in Feb 2026, 60% from rate limits. Only 14% of pilots have scaled to org-wide use.

Key findings:
- Reliability gap widening (Conf: High): autonomy demands <1% end-to-end failure; agents aren't there.
- Multi-agent "deliberation cascade" (Conf: High): arXiv 2605.16205 shows combining hierarchy with distributed deliberation degrades performance up to 3.4× across five LLM families — directly contradicts vendor narrative.
- Identity/security is the visible blocker (Conf: High): two-thirds of orgs suspect agents have already accessed out-of-scope data (Akeyless, n=400).

Strongest data point: Multi-agent independent operation amplified errors 17.2× vs 4.4× with coordination (AscentCore, 2026-05-04, T2).
Biggest open question: What error rate operationally defines an "autonomous" agent — no consensus exists.

Full report: articles/deep-research-2026-05-18.md
