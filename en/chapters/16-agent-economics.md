# Chapter 16: Agent Economics — Rewriting the Production Function

---

## The Thousand-Dollar Employee

In 2025, a mid-size insurance company in Ohio faced a familiar problem: claims processing was backed up by three weeks.[^1] Each claim required a human adjuster to read the policy, review the damage documentation, cross-reference coverage limits, check for fraud indicators, calculate the payout, and draft a determination letter. The company employed sixty-four adjusters. They were experienced, competent, and overwhelmed.

The company deployed an agent system in April. By June, the backlog was gone. Not reduced — eliminated. The agents processed routine claims (approximately 70% of total volume) end-to-end: reading documentation, applying policy logic, detecting anomalies, calculating payouts, and drafting letters for human review. The human adjusters now focused exclusively on complex cases, disputed claims, and the final review of agent-generated determinations.

The economics were stark. Each human adjuster cost the company approximately $85,000 per year in salary and benefits and processed an average of 12 claims per day. The agent system cost approximately $0.40 per claim in compute resources and processed claims in under three minutes each. At full volume, the agent system handled the equivalent workload of forty-five adjusters for roughly $180,000 per year in total operating cost — replacing nearly $3.8 million in labor costs.[^2]

But the story does not end with cost reduction. The remaining human adjusters, freed from routine work, increased their resolution rate on complex claims by 40%. Customer satisfaction scores rose because claims were processed faster. Fraud detection improved because agents could cross-reference patterns across the entire claims database instantaneously — something no human team could do.

This single case contains the essential elements of a transformation that is rewriting the production function of knowledge work across every industry simultaneously.

---

## The Production Function, Reimagined

In economics, the production function describes the relationship between inputs (labor, capital, raw materials) and outputs (goods and services).[^3] For most of the twentieth century, the production function for knowledge work looked something like this:

**Output = f(Skilled Labor, Tools, Information)**

More output required more skilled workers, better tools, or more information. The dominant constraint was usually skilled labor — finding, training, and retaining people who could do complex cognitive work. This is why professional services firms (law, consulting, accounting, medicine) charge primarily for time: their production function is dominated by the cost of skilled human hours.

AI agents rewrite this function. The new production function for agent-augmented knowledge work looks more like:

**Output = f(Direction Quality, Agent Compute, Tool Access)**

The dominant input is no longer skilled labor hours but the quality of direction — how well the human specifies goals, evaluates outputs, and steers the agents. Agent compute (the cost of running inference) replaces labor as the variable cost. Tool access (the APIs, databases, and systems available to the agents) replaces traditional capital equipment.

This rewriting has three profound economic consequences.

---

## The Marginal Cost Revolution

The first consequence is a fundamental change in marginal cost structure. In traditional knowledge work, the marginal cost of the nth unit of output is approximately equal to the cost of the first: each additional legal brief, each additional insurance claim, each additional software feature requires approximately the same amount of skilled human time.

With agents, the marginal cost curve looks entirely different. There is a significant fixed cost — developing the agent system, connecting it to tools, establishing quality assurance processes. But once that fixed cost is paid, the marginal cost of each additional unit of output is primarily compute cost — which is both low and declining rapidly.

This pattern is familiar from the history of industrial production. The first Industrial Revolution replaced variable labor costs in manufacturing with high fixed costs (factories, machines) and low marginal costs (fuel, raw materials).[^4] The result was an explosion of output and a collapse of per-unit prices. The same pattern now applies to knowledge work.

Consider legal research. A law firm that invests in an agent-based research system faces an upfront cost in development and integration. But once operational, each additional research query costs pennies in compute rather than hundreds of dollars in associate time. The marginal cost of legal research approaches zero.

This does not mean legal research becomes free — there are still fixed costs, quality assurance costs, and the irreplaceable cost of human judgment in interpreting results. But it means that the economics of legal services are restructured as fundamentally as the economics of textile production were restructured by the power loom.

The pattern repeats across every knowledge-intensive industry: financial analysis, medical diagnosis, software development, content creation, engineering design, scientific research. In each case, the transition from labor-dominated variable costs to compute-dominated marginal costs represents a discontinuity in the production function — a step change, not a gradual improvement.

---

## The Industrial Revolution Analogy

The parallel to the first Industrial Revolution is not merely illustrative — it is structurally precise. Consider the key features of that transformation:

**Mechanization of routine.** The power loom did not replace all textile work — it replaced the repetitive, rule-governed operation of weaving. Tasks requiring judgment (design, quality inspection, machine maintenance) remained human.[^5] Similarly, AI agents mechanize the routine, rule-governed components of knowledge work while leaving judgment-intensive tasks to humans.

**Multiplication of output per worker.** A single weaver operating a power loom produced as much cloth as fifteen hand weavers.[^6] A single developer directing coding agents produces as much software as a traditional team of five to ten. The multiplier varies by task, but the structure is identical.

**Shift in valuable skills.** Before the power loom, the most valuable textile worker was the skilled hand weaver. After, it was the mechanic who could maintain the machines and the designer who could create patterns worth producing at scale. Before agents, the most valuable knowledge worker was the skilled executor (the fast coder, the diligent researcher). After, it is the skilled director (the one who can specify well, evaluate critically, and orchestrate effectively).

**Capital-labor substitution.** The Industrial Revolution replaced human muscle with machine power, substituting capital for labor. The Agent Revolution replaces human cognitive routine with machine reasoning, substituting compute capital for knowledge labor.

**New forms of organization.** The factory system emerged because power looms required centralized power sources and created economies of scale. Agent systems enable a new organizational form: the hyper-lean team, where a small number of skilled directors orchestrate a large fleet of agents to produce output that previously required large organizations.

---

## The New Division of Labor

Adam Smith's famous observation about the pin factory — that dividing labor into specialized tasks dramatically increased output[^7] — created the organizational logic that dominated production for two and a half centuries. AI agents create a new division of labor, one that operates along a different axis.

The old division of labor was horizontal: different humans specialized in different tasks. One person designed, another coded, another tested, another deployed. Each specialty required years of training. Coordination between specialists consumed enormous organizational energy.

The new division of labor is vertical: humans handle judgment and direction; agents handle execution and routine. The axis of division is not "what kind of work" but "what level of work" — strategic versus operational, evaluative versus generative, creative versus mechanical.

This vertical division has several implications:

**Flattening of expertise barriers.** When agents handle execution, the distinction between a junior and senior professional shifts from "how much can you do" to "how well can you judge and direct." A junior lawyer with excellent judgment can direct agents to produce work that previously required senior associates' hands-on execution.

**Broadening of individual scope.** A single person can now operate across multiple domains because the specialized execution in each domain is handled by agents. A product manager can simultaneously direct agents writing code, creating designs, drafting documentation, and analyzing market data — work that previously required a team of specialists.

**Premium on integration.** When individual task execution becomes cheap, the valuable skill becomes integration — seeing how pieces fit together, maintaining coherence across a complex project, ensuring that the whole is greater than the sum of its parts. This is inherently human work: it requires taste, judgment, and a holistic understanding that current agents lack.

---

## Quantifying the Transformation

The macroeconomic implications of this transformation are beginning to emerge in data:

**Productivity per worker.** Companies that have deployed agent systems at scale report 3-8x improvements in output per knowledge worker, with the variation depending on the routine-to-judgment ratio of the work.[^8] Highly routine work (data entry, standard document generation, basic coding) sees the highest multipliers. Highly judgment-intensive work (strategic planning, novel research, creative direction) sees more modest gains.

**Cost structure.** For companies that have fully adopted agent-based workflows, the cost structure of knowledge work shifts from approximately 70-80% labor and 20-30% technology to approximately 30-40% labor and 60-70% technology. This represents not a reduction in total spending but a redirection — and the technology spending yields dramatically more output per dollar.

**Time to market.** Products and services that previously required months of development are completed in weeks. The startup ecosystem, in particular, has been transformed: the minimum viable team for a software startup has shrunk from five to seven people to one or two, because agents substitute for the missing team members.

**Market structure.** Industries with high knowledge-labor costs are seeing rapid structural change. Professional services firms are reconfiguring their leverage models. Media companies are rethinking their content production economics. Software companies are rebuilding their engineering organizations around agent-augmented workflows.

---

## The Cost of Harnessing: Risk, Alignment, and Control

No force has ever been harnessed without cost. Steam engines exploded. Electrical systems electrocuted. Nuclear reactions melted down. Every new force brings new risks, and the intelligence of AI agents is no exception.

**Reliability risk.** Agents can and do make mistakes — sometimes subtle ones that are difficult to detect. A coding agent might introduce a security vulnerability that passes tests. A legal agent might cite a case that does not exist. A financial agent might execute a trade based on flawed reasoning. The probabilistic nature of language models means that agent errors are not systematic and predictable (like software bugs) but stochastic and surprising.

**Alignment risk.** An agent optimizing for a given objective may find unexpected paths to achieve it — paths that satisfy the letter of the instruction while violating its spirit.[^9] This is not malice; it is the consequence of optimizing a precisely stated objective in a complex environment. An agent told to "maximize customer engagement" might discover that outrage and misinformation drive engagement more effectively than helpful content. An agent told to "resolve customer complaints" might offer unauthorized refunds or make promises the company cannot keep.

**Control risk.** As agents become more capable and operate with greater autonomy, maintaining meaningful human oversight becomes more difficult. The speed of agent execution (minutes vs. days) and the opacity of agent reasoning (thousands of tokens of internal deliberation) make real-time human supervision impractical at scale. New mechanisms of control — guardrails, audits, constraint systems, hierarchical approval structures — must be developed and deployed.

**Concentration risk.** When a small team with agents can produce the output of a large organization, economic value may concentrate among those who own and direct the agents. The benefits of the agent revolution might accrue primarily to capital owners and highly skilled directors, widening inequality rather than broadly distributing productivity gains.[^10]

These costs are real and significant. They are also, in historical terms, entirely predictable. Every previous chapter of harnessing has involved a period of adjustment during which society learned to manage the risks of the new force — through regulation, engineering standards, safety practices, and institutional adaptation. The same process is now underway for AI agents.

The history of technology suggests that these risks will be managed — not perfectly, not without cost, but sufficiently to allow the technology's productive potential to be realized.[^11] The question is not whether agents will be harnessed safely, but how quickly society can develop the frameworks to do so.

---

## The Harnessing Cost Equation

Every chapter of this book has implicitly described a cost equation: the benefit of harnessing a new force versus the cost of controlling it. The ox multiplied the farmer's force but required feeding, housing, and managing. Steam multiplied industrial output but required expensive boilers, safety mechanisms, and skilled operators. Electricity multiplied everything but required vast infrastructure and safety standards.

For AI agents, the cost equation is:

**Benefit:** Near-zero marginal cost for knowledge work execution; multiplication of human judgment across unlimited parallel streams; elimination of bottlenecks in expertise access.

**Cost:** Reliability engineering; alignment systems; control infrastructure; organizational redesign; retraining of the workforce; development of new regulatory frameworks; management of concentration effects.

The net value — benefit minus cost — determines how quickly and completely the agent revolution transforms the economy. Early evidence suggests that the net value is overwhelmingly positive, which is why adoption is proceeding at a pace unprecedented in the history of technology.[^12] But the costs are not zero, and ignoring them invites catastrophe just as surely as ignoring boiler pressure limits invited steam explosions.

---

## Notes

[^1]: Illustrative composite case. Specific company is anonymized; the operational pattern (claims-processing agent deployments at U.S. mid-market insurers in 2024–2025) is documented in McKinsey & Company, *The State of AI in 2024* (May 2024), and Accenture, *Reinventing Insurance with Generative AI* (2024). Specific volumetric and cost figures are author estimates synthesized across multiple published deployments.

[^2]: Cost-per-claim and adjuster-throughput figures are author estimates. Adjuster compensation cross-checked against U.S. Bureau of Labor Statistics, *Occupational Employment and Wages, May 2023: 13-1031 Claims Adjusters, Examiners, and Investigators*, https://www.bls.gov/oes/current/oes131031.htm. Per-token inference cost assumptions are drawn from publicly posted 2024 frontier-model API pricing.

[^3]: The classical Cobb–Douglas formulation appears in Charles W. Cobb and Paul H. Douglas, "A Theory of Production," *American Economic Review* 18, no. 1 (1928): 139–165.

[^4]: Robert C. Allen, *The British Industrial Revolution in Global Perspective* (Cambridge University Press, 2009), Ch. 6–8.

[^5]: David S. Landes, *The Unbound Prometheus: Technological Change and Industrial Development in Western Europe from 1750 to the Present*, 2nd ed. (Cambridge University Press, 2003), Ch. 2.

[^6]: Allen (2009), Ch. 8; see also Beverly Lemire, *Cotton* (Berg, 2011). The "fifteen-to-one" figure is the conventional comparison for early power-loom productivity and varies considerably with loom type and period.

[^7]: Adam Smith, *An Inquiry into the Nature and Causes of the Wealth of Nations* (W. Strahan & T. Cadell, 1776), Book I, Ch. 1.

[^8]: 3–8x range is an author synthesis of: Dell'Acqua et al., HBS Working Paper 24-013 (2023); Peng et al., arXiv:2302.06590 (2023); Noy and Zhang, *Science* 381 (2023); and Microsoft / McKinsey enterprise adoption surveys (2023–2024). Reported task-level multipliers in these studies cluster between roughly 1.3x and 5.5x for individual tasks; the higher end of the 3–8x band reflects firm-level deployments with workflow redesign.

[^9]: Stuart Russell, *Human Compatible: Artificial Intelligence and the Problem of Control* (Viking, 2019), Ch. 5; see also Dario Amodei et al., "Concrete Problems in AI Safety," arXiv:1606.06565 (2016).

[^10]: Daron Acemoglu and Simon Johnson, *Power and Progress: Our Thousand-Year Struggle Over Technology and Prosperity* (PublicAffairs, 2023).

[^11]: For the long pattern of technology-risk co-evolution, see Joel Mokyr, *The Lever of Riches: Technological Creativity and Economic Progress* (Oxford University Press, 1990).

[^12]: Early-adoption pace claim draws on McKinsey & Company, *The State of AI in Early 2024* (May 2024), and Stanford HAI, *AI Index Report 2024*, https://aiindex.stanford.edu/report/.

---

## Harnessing Moment

The economics of AI agents recapitulate, with uncanny precision, the economics of every previous harnessing revolution. The pattern is invariant: a new force reduces the cost of something that was previously expensive; the production function reorganizes around the new cost structure; valuable human skills shift from execution to direction; new risks emerge and must be managed; and the overall trajectory of human productivity leaps upward.

What is different this time is the nature of what becomes cheap. The Industrial Revolution made physical production cheap. The Computing Revolution made information processing cheap. The Agent Revolution makes cognitive execution cheap — the application of expertise, the generation of analysis, the production of knowledge work. What remains expensive, and therefore valuable, is what has always been most distinctively human: judgment, taste, wisdom, and the ability to ask the right question in the first place.

The reins grow more powerful. The force they control grows greater. But the hand that holds the reins — that judges direction, evaluates progress, and decides when to pull back — remains irreplaceable.
