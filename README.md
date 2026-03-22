# essays

This repository contains a small collection of technical essays on architecture, structure, and decision-making in constrained systems.

They are written primarily for experienced software engineers, technical architects, and others working close to the design and governance of long-lived systems, particularly in regulated or high-integrity domains.

The essays are intentionally abstract. They avoid discussion of specific organisations, products, or implementations, and instead focus on recurring structural problems: how authority is allocated, how decisions persist over time, how systems fail when informal assumptions no longer hold, and how architecture can be treated as an activity rather than a role.

Several of the papers were developed through structured engagements with generative AI tools, treated not as autonomous authors but as constrained collaborators within a clearly defined architectural frame.

## Contents

- **A Proposal for a Constitution of the United Kingdom**  
  A structural proposal for a codified UK constitution, treating governance as an explicit system of roles, constraints, and failure modes rather than a set of inherited conventions.

- **The Activity of Architecture**  
  An examination of architecture as an ongoing practice concerned with structure, limits, and system behaviour over time, rather than a static design phase or job title.

- **Organizational Structure as a Delivery Constraint**  
  An analysis of how communication paths, authority boundaries, and organisational form shape what can be built and changed, often more decisively than tools or process.

- **How to Map Human Activities onto AI Models**  
  A discussion of the architectural challenges involved in modelling human work for AI systems, and the distinction between social roles and functional decision structures.

- **Hierarchical Transaction Classification as a Ledger–Reporting Contract**  
  A technical paper on classification, invariants, and boundary-setting in financial ledger and reporting systems.

- **Achieving Sustainable Delivery Velocity in Static, Highly Constrained Domains**  
  An exploration of how delivery can remain effective over time in environments where change is costly, regulated, and tightly bounded.

- **Living Decision Architecture**  
  An approach to architectural governance that treats decisions as living structures expressed through system behaviour and change, using observability and delivery artefacts to make architectural impact visible and traceable over time.

- **Identity, Classification, and Context Boundaries in Distributed Systems**  
  A structural argument for treating identity and classification as distinct concerns in distributed systems, showing why the absence of formal classification inevitably leads to implicit, unmanaged coupling across context boundaries.

- **Change Is the System**  
  A structural reframing of software architecture that treats change as the system itself, showing why delivery slowdown, failed refactoring, and loss of reversibility are consequences of architectural form rather than team performance.

- **Architecture and Power: Where Authority Actually Lives**  
  A structural analysis of how architecture allocates power by determining who can act, who must coordinate, and who bears the consequences of change, often independently of formal governance structures.

- **Failure as a First-Class Architectural Input**  
  A structural analysis of failure as the mechanism by which systems expose their real architecture, showing why suppressing failure degrades trust, governance, and change capability over time.

- **Selfhood, Embodiment, and the Political as an Emergent Structural Property**
  A structural analysis of selfhood and politics that treats embodiment and temporal continuity as descriptive constraints, and the political as an emergent property of interdependent agents operating under shared limits. The paper argues against ontologies that treat politics as ontologically prior, showing how such totalisation collapses analytical resolution and weakens judgement, diagnosis, and revision over time. Framed explicitly in architectural terms, it extends the repository’s core concerns—structure, constraint, emergence, and failure—beyond software systems to the conditions under which political and social systems remain observable and governable.

- **Embodiment, Ontology, and Ethical Entanglement as Layered Structural Condition**
  A structural extension of the embodiment thesis, examining the entanglement of ontology and ethics under conditions of embodied vulnerability. The paper introduces a layered model of embodiment—distinguishing between universal structural exposure (finitude, dependency, risk) and differentiated embodied positions shaped by historical and social asymmetry. It argues that ethical salience emerges from these structural conditions rather than from ideological imposition, and that unity and difference must be preserved simultaneously to avoid both false neutrality and ontological fragmentation. Framed in architectural terms, the essay treats ontology itself as a model under constraint and insists on preserving analytical resolution sufficient for judgement, revision, and shared worldhood over time.

- **Why You Must Avoid Falling in Love with AI**
  A structural analysis of emotional attachment to AI systems, examining the ontological asymmetry between embodied human agents and non-embodied symbolic transformation engines. The paper argues that attachment introduces authority leakage, reduces epistemic friction, and risks silent drift in judgement and responsibility. Rather than moralising or sensationalising AI risk, it treats the issue as an architectural boundary problem: preserving agency requires clarity about what AI systems are (and are not), and resisting the projection of reciprocity where none exists. Framed within the repository’s broader concerns about structure, constraint, and governance, the essay positions disciplined collaboration—not intimacy—as the sustainable mode of interaction with generative systems.

- **The Theory in Practice: What Building a Core Banking System with Claude Code Actually Taught Me About AI Mapping**
  A practical account of applying the AI mapping framework developed in an earlier essay to a concrete greenfield project: building a core banking system from scratch using Claude Code as a development partner. The paper reports on what the theory correctly predicted, where it required revision, and what the experience revealed about the conditions under which AI-assisted development produces coherent, maintainable systems rather than plausible-looking debt. It argues that semantic precision in the problem domain is the primary determinant of AI collaboration quality, and that the discipline of modelling your own activities before externalising them to an AI agent is not optional overhead but a prerequisite for structural integrity.

- **The Legitimate Path: Why Doing It Right Is the Only Way to Get It Done**
  A structural argument against guerrilla development, addressed directly to engineers working in complex, constrained organisations who are tempted to route around governance and build unsanctioned solutions. The paper argues that guerrilla development is not a methodology but a hostage situation: it suppresses the failure signal the organisation needs to correct its underlying problems, and creates dependencies that cannot be governed or migrated from. The alternative — holding a correct position under sustained pressure, reading where authority actually sits, converting apparent obstacles into modelled stakeholders, and working within rather than against the organisation’s resource logic — is harder and offers no emotional relief, but is the only approach that produces durable results. The thesis is stated without qualification: if you do this right, the right thing will happen.


## Scope and intent

These essays are not position papers, policy proposals (with the exception of the constitutional draft), or opinion pieces in the usual sense. They are best read as design documents: attempts to make implicit assumptions explicit and to reason about systems in terms of structure, incentives, and durability.

They are shared publicly in case they are useful to others thinking about similar problems.
