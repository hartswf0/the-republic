Below are paste-ready inserts for each JIG (plus an updated title + abstract + research question) with “operative” as the hinge between theory and design. I’m also weaving in the actual Geertz move (thick description = interpretive effort, not just sensitivity) (people.ucsc.edu) and Bajohr’s performative / collapse-of-distinction claim (ResearchGate).
Updated paper title, abstract, research question (now consistent with the JIGs)
Title
Thick Prompting as Operative Ekphrasis: A Design-Studies Method for Generative Visual Artifacts and Worldtexts

Abstract (revised to match “dual purpose” + narrowed scope)
Multimodal prompting has become a distinctive creative practice for producing visual artifacts—images, videos, and increasingly “worldlike” scenes—yet it is often evaluated narrowly by representational fidelity (“does it match what I asked for?”). This paper argues that such prompting is best understood as operative ekphrasis: a historical shift in the text–image relation where description does not merely represent an image but computationally performs it. Building on Bajohr’s account of ekphrasis as performative under multimodal AI (ResearchGate) and Geertz’s formulation of thick description as an interpretive practice oriented to meaning, not just technique (people.ucsc.edu), we pursue two aims: (1) to situate multimodal prompting for creative visual production (art, personal expression, entertainment) within the longer history of text/image theory and ekphrastic world-composition; and (2) to show how this reframing yields actionable guidance for shaping prompts as a design practice. We propose Thick Prompting as a method: treating prompts as heterogeneous stacks (natural language, tags, parameters, and structured formats such as JSON) and treating execution as a ritualized workflow that makes a platform’s latent space more navigable, revisable, and discussable. We contribute (i) a conceptual genealogy from classical ekphrasis (with Homer’s Shield as a paradigmatic “worldtext” whose description foregrounds making) (whitmanarchive.org), (ii) an explicit account of platform constraints, and (iii) a set of illustrated prompt techniques and prompt-differential analysis for producing richer, more controllable visual artifacts beyond fidelity alone.

Research question
How does reframing multimodal prompting for creative visual artifacts as operative ekphrasis enable Thick Prompting to function both as an interpretive lens and as a design-studies method for making better (richer, more controllable) generative works under real platform constraints?
JIG #0 — STRUCTURAL INTEGRATION
300-word transition (theory → design; “operative” as hinge)
Sections 1–3 argued that multimodal prompting reconfigures an old problem—how words relate to images—into a new condition: text becomes operational. Bajohr names this shift “operative ekphrasis,” the point at which ekphrastic relations are no longer primarily representational but performative: prompts do not only talk about images; they do work in the system that produces them (ResearchGate). In parallel, Geertz clarifies that “thick description” is not a checklist of field methods but a kind of interpretive labor: the work of distinguishing identical-looking actions (a twitch versus a wink) by reconstructing the layered meanings that make them different (people.ucsc.edu).
This is the hinge for what follows: theory names what design does. If operative ekphrasis is the historical condition—language fused into the production pipeline—then Thick Prompting is the design response: a method for acting within that condition without collapsing back into naïve fidelity-matching. Thick prompting treats the prompt not as a single sentence but as a heterogeneous stack—system framing, natural language, tags, structured fields (e.g., JSON), parameter choices, and iterative revisions—whose execution yields artifacts that can be read, critiqued, and refined. Where thick description interprets symbolic action by reconstructing context, thick prompting deliberately builds that context into the prompt stack so that the resulting artifact is both richer and more discussable.
This is why the paper now turns to design practice (Sections 5–6). If prompts are interventions, then our task is not only to interpret outputs but to develop repeatable techniques for shaping them: how to layer constraints without merely adding words, how to keep option space open while steering style, how to diagnose fragility versus resilience across iterations, and how platform constraints (token budgets, safety filters, exposed parameters, interface affordances) condition what “good” prompting can be. In short: operative ekphrasis explains why prompting matters; thick prompting specifies how to practice it.
JIG #1 — THICK PROMPTING DEFINITION (revise + Geertz anchor)
Revised definition (drop “sensitivity” as the core):
Thick prompting is a method for producing richer, more controllable visual artifacts by composing prompts as layered constraint stacks rather than as single descriptions. It is “thick” in the Geertzian sense: not because it is long, but because it is densely textured—built from heterogeneous materials (system frames, natural language, tags, parameters, structured fields such as JSON, and iterative meta-prompts) that together specify not just what should appear, but how it should be made legible, coherent, and revisable. Geertz’s thick description names an interpretive effort that distinguishes superficially similar acts (twitch vs. wink) by reconstructing the webs of meaning that make them different (people.ucsc.edu); thick prompting operationalizes an analogous move by embedding those “webs” as explicit constraints that guide generation and critique.
Distinction from “long prompting”:

Long prompting = increased word count (often redundant).
Thick prompting = increased constraint quality (structured, layered, and purposefully staged), even when concise.
Operational claim: thick prompting treats execution as a ritual workflow: prompts are crafted, run, read, and revised through repeatable cycles that make the latent space navigable (rather than mystical), producing artifacts whose qualities can be discussed without collapsing into aura or insider slang.
JIG #2 — SCOPE NARROWING (1–2 sentences for intro)
Scope statement (insert near end of intro paragraph 1):
This paper examines prompting practices for producing visual artifacts—images, videos, and worldlike scenes—in contexts of art, personal expression, and entertainment. We do not address prompting for code generation, data analysis, general chat assistance, or other non-visual task domains; narrowing the scope makes the continuity with ekphrasis—the literary and rhetorical tradition of text/image relations—both plausible and analytically productive.
JIG #3 — PAPER’S DUAL PURPOSE (abstract + intro language)
Add to abstract (one sentence):
We pursue two aims: (1) historical/theoretical—to situate multimodal prompting within the longer history of text–image relations and ekphrasis; and (2) practical/demonstrative—to show how this framing yields methods and techniques for shaping prompts to produce richer visual artifacts.
Add to introduction (2–3 sentences, early):
Accordingly, the paper alternates between conceptual framing and visual demonstration: theory identifies the text–image problem multimodal systems re-open, while demonstrations show how thick prompting translates that diagnosis into practice. The argument is that operative ekphrasis is not only something we can interpret; it is something we can design for.
(That’s your “structure paper to alternate: theory → demonstration” instruction, as prose.)
JIG #4 — WORLD MODELS CONNECTION (expand Homer section: 3 points)
Insert (Homer section expansion, ~220–280 words):
Homer’s description of Achilles’ shield is a strong anchor because it is not merely an account of an object; it is a world-composition. The shield enumerates cities, fields, seasons, conflicts, festivities—multiple interacting scenes whose meaning emerges from their relations, like a miniature model of social life. In contemporary terms, the shield functions as a proto-world model: not an encyclopedic inventory, but a structured depiction of a living environment with agents, rhythms, and constraints.
Second, the description is explicitly processual. Homer brings into view not only what is made but the maker at work—Hephaestus forging the shield—so the ekphrasis stages production as part of what is described. Lessing later emphasizes this feature: Homer presents “the divine artist… employed in making it,” with figures that “spring gradually and successively into view” (whitmanarchive.org). This matters for generative systems because it aligns ekphrasis with procedures, not just pictures: the description already contains an implicit theory of making-as-revelation.
Third, generative AI makes this logic newly operative. In classical ekphrasis, language produces vividness in the reader’s mind; in multimodal systems, language participates in a computational pipeline that produces the visual artifact. Bajohr’s point is precisely that under multimodal AI, ekphrastic relations shift from representational to performative, and the text/image distinction tends to collapse inside the technical system (ResearchGate). In that sense, prompting is not just a modern analogy to Homeric ekphrasis; it is an executional continuation of ekphrasis as world-calling.
JIG #5 — WORLDTEXT CLARIFICATION (definition)
Worldtext (definition paragraph):
We use worldtext to name prompts (and prompt stacks) that compile into spatially navigable, procedurally structured media objects—not only static images but scene-like outputs that can be iterated into 3D environments, interactive experiences, or “game-world” fragments. A worldtext specifies relationships, affordances, and constraints (how space behaves, what agents can do, what counts as a consistent style) rather than merely depicting a moment. It differs from imagetext, which primarily targets a single-frame composition. In practice, worldtexts emerge when creators use thick prompting to stabilize a world’s “physics” (visual grammar, lighting rules, recurring motifs, camera logic, interaction cues) across multiple generations, making the artifact inhabitable—conceptually, sometimes literally.
JIG #6 — PLATFORM CONSTRAINTS (one methods paragraph)
Platform constraints (paste-ready paragraph):
By platform constraints we mean the technical and institutional conditions that shape what prompting can do and what counts as a successful artifact. These include: (1) model affordances and limits (architecture and training shaping what kinds of spatial reasoning, text rendering, or compositional consistency are plausible); (2) safety and policy filters (what prompts are allowed and how outputs are blocked or rewritten); (3) token/context limits (how much instruction and memory can be carried across iterations); (4) exposed parameters and UI affordances (what the platform lets users control—e.g., guidance/strength, aspect ratio, seed, negative prompts, style toggles); and (5) data and bias structure (training distributions that privilege certain aesthetics, geographies, or iconographies). Thick prompting is a method under constraint: it treats these limits not as noise but as design material, and it makes their effects legible through structured prompt stacks and prompt-differential iteration.
JIG #7 — REPRESENTATIONAL FIDELITY CRITIQUE (acknowledge dominant paradigm)
Insert (short acknowledgment before you pivot):
Most everyday users evaluate generative systems through a representational fidelity lens: did the output look like what I asked for? This is a rational default because consumer interfaces implicitly train it—type a description, get a picture. Our claim is not that fidelity is irrelevant, but that fidelity-only evaluation is a naïve theory of prompting: it treats prompts as static descriptions rather than as interventions that install workflows, constraints, and future option spaces. The alternative we propose is to judge prompts additionally by their operational effects—what kinds of iteration, control, and world-consistency they enable across runs.
JIG #9 — THICK PROMPTING PEDAGOGY (prelude before Δ / ΔΔ)
Add a “Thick Prompting 101” sub-section before differentials (structured bullets):
Before introducing prompt differentials (Δ / ΔΔ), we define thick prompting as a complete workflow:
System prompt (frame): establishes the cultural and aesthetic “rules of the game” (tone, medium, forbidden moves, evaluation criteria).
Constraint stacking: prompts are layered (style grammar, camera logic, subject constraints, world rules) to increase coherence, not word count.
Inception/meta-prompting: “prompts that prompt prompts” generate variant drafts, critique rubrics, or constraint proposals—useful because the prompt itself becomes an object of design.
Structured prompts (e.g., JSON): constraints are made parseable and versionable (fields for subject, setting, camera, palette, exclusions, invariants).
Ritual execution loop: run → read → annotate → revise; the goal is to turn latent space from aura into a navigable design space.
Then Δ / ΔΔ is introduced as a diagnostic instrument within the workflow (what changed, what changed because of that change, and what stayed stable).
JIG #10 — SECTION ORDERING (recommendation + rationale)
Recommendation: adopt Theory → Homer (anchor) → Method/Taxonomy → Modern demos.
Why: The taxonomy reads “auratic” until it is grounded in a canonical ekphrastic case where (i) world-composition, (ii) maker/process foregrounding, and (iii) sequential revelation are already present. Lessing’s formulation that Homer shows the maker and reveals the shield successively gives you a historically legitimate bridge into iterative prompt technique (whitmanarchive.org). After Homer, the method feels like an extraction of principles rather than an arbitrary list.
(If you want one line to justify in the paper: “We derive the technique taxonomy from the Homeric case, then test it on contemporary generations.”)
JIG #12 — AESTHETIC JUDGMENT (choose stance; paste-ready)
OPTION C (best fit with your paper’s claims): Both.
This paper is not a universal theory of taste, but it cannot avoid aesthetics because thick prompting is justified by what it makes possible: richer artifacts and more articulate critique. We therefore treat aesthetic judgment in two layers. First, descriptively: we document how practitioners actually decide that an artifact “works” (coherence, novelty, affective charge, world-consistency, stylistic integrity). Second, methodologically: we show how thick prompting makes such judgments actionable—not by prescribing what is beautiful, but by producing artifacts whose qualities can be isolated, named, and iteratively steered. In this sense, aesthetic evaluation is not the paper’s endpoint but its motivating pressure: without some account of “better,” a method for making “richer” artifacts would be empty.
JIG #13 — ILLUSTRATION REQUIREMENT (concrete mini-examples you can turn into figures)
Below are figure scripts (side-by-side prompt cards). Keep them short; the point is to show the concept in action.

Resilience (fragile vs resilient)
Fragile prompt: “A cinematic portrait of a woman in a foggy street, 1970s grain, neon.”
Resilient prompt stack: “INVARIANTS: 1970s documentary grain; 50mm; fog density=high; palette=cyan/amber; subject remains centered; no neon signage text. VARIABLE: wardrobe style.”
Caption: Small changes in wording shouldn’t collapse the artifact’s center of gravity.
Option space (open vs closed)
Closed: “exactly this: red coat, blue car, rain, same pose, same framing”
Open: “Maintain mood + camera invariants; allow subject props to vary within ‘working-class urban evening.’”
Caption: Option space is the count of viable next-steps without stylistic rupture.
Obligation (installs duty)
No obligation: “A retro sci-fi control room.”
With obligation: “Every screen must show a different subsystem; cables must imply causality; labels must be legible but non-textual (glyphs).”
Caption: Obligation creates critique handles (“did we satisfy the duty?”).
JIG #14 — FOREGROUNDING THICK PROMPTING (exact move)
Instructional edit (do this literally):
Move the thick prompting definition to the end of Introduction (last paragraph), and rewrite the paragraph to say:
We propose Thick Prompting as the paper’s central method: treating prompts as heterogeneous stacks (text + tags + parameters + structured formats) and treating execution as a Geertzian ritual of iterative inscription and interpretation (people.ucsc.edu). Ekphrasis provides the lens; thick prompting provides the practice.
(That one paragraph reorients the whole paper.)
JIG #16 — HOMER AS EXAMPLE (decision + rationale)
Decision: make Homer an ANCHOR, not an aside.
Reason: Homer supplies all three properties you need—process foregrounding, narrative/action, and world-composition—and Lessing explicitly articulates the maker-in-description feature in a way that maps cleanly onto iterative generation (whitmanarchive.org). This prevents the “design techniques” section from feeling arbitrary.
JIG #17 — VISUAL DEMONSTRATION (a minimal demo plan that reads as continuity with ekphrasis)
Demonstration template (repeat 3 times in paper, once per key concept):

Base prompt (thin): 1–2 lines.
Output A (image): shows generic fidelity success but weak world coherence.
Thick prompt stack: system frame + invariants + one structured field set (JSON).
Output B (image): shows increased coherence/controllability.
Δ annotation: highlight exactly what changed in prompt and exactly what changed in image.
Short ekphrasis tie-back: “this is operative: the description installs a procedure.”
(If you keep Homer running: treat the “shield/world” as the recurring demo object—each iteration adds a layer: maker/process, narrative density, world rules.)
JIG #20 — WITTGENSTEIN QUESTION (cleanest resolution)
Recommendation (C): keep early Wittgenstein, but bracket it tightly.
One sentence does the job:
While Wittgenstein later complicates the picture theory, the Tractatus usefully names a recurring temptation in text–image thinking: to treat propositions as picture-like models—an intuition that generative systems render newly operational.
If reviewers still resist, drop him; Bajohr + Geertz + ekphrasis lineage is sufficient.
JIG #21 — JSON STRUCTURES + INCEPTION PROMPTS (explanatory mini-section + example)
Paste-ready mini-section:
Inception prompts are meta-prompts that generate prompts: they ask the model to propose variants, critique constraints, or draft structured prompt stacks. They matter because thick prompting treats the prompt as a design object—something we iteratively engineer rather than merely write once.
We use JSON because it makes prompt stacks (i) parseable (fields can be compared across versions), (ii) version-controllable (diffs are meaningful), and (iii) collaborative (teams can discuss “camera,” “invariants,” “constraints” as discrete components). JSON is not required for thickness, but it makes thickness auditable and teachable.

{
  "system_frame": "documentary 1970s, restrained, non-glossy",
  "invariants": {
    "lens": "50mm",
    "grain": "kodachrome-like",
    "world_rule": "no readable text",
    "palette": "muted cyan/amber"
  },
  "subject": "street portrait, centered",
  "variables": ["wardrobe", "weather intensity"],
  "exclusions": ["neon signage", "logo marks"]
}
JIG #22 — MITCHELL / KRIEGER CLARIFICATION (precision paragraph)
Mitchell and Krieger are useful here, but for different reasons. Mitchell’s project is to unsettle any naïve belief that word and image occupy naturally separate domains; their relations are historically and conceptually tense rather than cleanly partitioned (artforum.com). Krieger, by contrast, foregrounds the ekphrastic paradox as a desire (and frustration): language strives to produce a “natural sign,” to make words behave like images, yet cannot fully coincide with visual presence; ekphrasis stages that struggle rather than resolving it (Hopkins Press). Our use is aligned with Mitchell’s refusal of clean separation and with Krieger’s account of ekphrasis as a contested boundary-work. Operative ekphrasis intensifies this: multimodal systems internalize the boundary inside a technical pipeline, so the “contest” between word and image becomes executable rather than purely rhetorical (ResearchGate).
If you want the fastest next step: tell me which section headings you’re currently using (just the TOC), and I’ll drop these inserts into your structure with exact placement notes (e.g., “Intro ¶3,” “end of §2.2,” etc.) without asking anything else.