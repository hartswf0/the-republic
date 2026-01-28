THICK PROMPTING: AN OPERATIVE METHOD FOR VISUAL WORLDMAKING WITH GENERATIVE AI

Gaia Hartsoe & Jay David Bolter
Georgia Institute of Technology

═══════════════════════════════════════════════════════════════════
ABSTRACT
═══════════════════════════════════════════════════════════════════

Current discourse on text-to-image generation often judges success by representational fidelity, treating the prompt as a mere technical instruction. This paper argues for a more expansive view, framing prompting for art, personal expression, and entertainment as a cultural practice with deep roots in the literary tradition of ekphrasis—the vivid description of a visual scene that calls forth a world. We draw a specific parallel to the shield of Achilles in the Iliad, noting its depiction of a process (Hephaestus forging), its composition of a narrative world, and its function as a backdrop for action.

To make this historical perspective operative for contemporary design, we introduce Thick Prompting. This method adapts Clifford Geertz's anthropological concept of "thick description," treating prompts not as singular instructions but as heterogeneous, layered stacks (combining natural language, code, JSON structures, and system prompts) whose iterative execution functions as a meaning-making ritual. The paper has two interconnected aims: first, to position multimodal prompting within a long history of text-image relationships; and second, to demonstrate how this perspective shapes concrete practice. Through a design study that moves from static images to interactive 3D environments, we illustrate Thick Prompting techniques—including meta-prompting, differential analysis (Δ/ΔΔ), and constraint stacking—showing how they navigate platform limitations to produce resilient, option-rich visual "worldtexts." Ultimately, we propose Thick Prompting as a necessary bridge, turning theoretical insight into a design methodology that prioritizes deliberateness, richness, and interpretive depth over mere descriptive precision.

Keywords: generative AI, prompting, ekphrasis, thick description, worldtext, visual worldmaking

═══════════════════════════════════════════════════════════════════
1. INTRODUCTION: THE ACCIDENTAL OPERATIONALIZATION
═══════════════════════════════════════════════════════════════════

1.1 The Core Claim

Generative AI has accidentally operationalized ancient rhetorical and anthropological concepts. Text-to-image systems now do what ekphrasis has always claimed to do: they make description generative, calling forth visual worlds from verbal specification. By consciously reclaiming these concepts—ekphrasis as world-making description and thick description as interpretive method—practitioners can move beyond a naive, instrumental view of prompting toward a richer practice we call Thick Prompting.

1.2 Scope

This paper considers prompting for visual artifacts in contexts of art, personal expression, and entertainment—not prompting for code generation, data analysis, or conversational assistance. Within this scope, we observe that current discourse judges prompts primarily by representational fidelity: Does the image match the description? Did the model follow instructions? This criterion, while useful for certain applications, treats prompting as mere technical instruction—a command line for images.

We argue for an alternative view: prompting as cultural practice. Like ekphrasis in literary tradition, prompting describes in order to evoke. Like thick description in anthropology, prompting interprets through layered, contextual specification. These are not metaphors but structural parallels that reveal prompting's expressive potential.

1.3 Research Question

How can reframing AI prompting through the dual lenses of ekphrasis (as world-describing text) and thick description (as interpretive ritual) generate both a critical framework and a practical method—"Thick Prompting"—for creating richer, more intentional visual artifacts?

1.4 Two Interconnected Aims

The paper pursues two aims that cannot be separated:

AIM ONE (THEORETICAL): Position multimodal prompting within the long history of text-image relationships. We show that what engineers have built accidentally connects to what poets and anthropologists have always done: describe in ways that generate meaning.

AIM TWO (PRACTICAL): Demonstrate how this theoretical perspective shapes concrete practice. We present techniques—meta-prompting, differential analysis, constraint stacking—that emerge from taking the historical parallel seriously.

The bridge between theory and practice is the method itself: Thick Prompting.

1.5 Definition

THICK PROMPTING is defined by:
1. The quality and arrangement of constraints (the "heterogeneous stack")
2. The ritualistic process of iterative execution
3. The goal of opening rich possibility spaces ("option space") rather than closing toward single outputs
4. The criterion of coherent world-invocation ("resilience") rather than representational matching

This definition appears here, at the outset, because Thick Prompting is not the paper's conclusion but its proposition. What follows is explication and demonstration.

═══════════════════════════════════════════════════════════════════
2. EKPHRASIS: THE LITERARY ROOTS OF VISUAL DESCRIPTION
═══════════════════════════════════════════════════════════════════

2.1 What Ekphrasis Does

Ekphrasis, in its contemporary scholarly usage, refers to the verbal representation of visual representation—words describing images. The term derives from the Greek ἔκφρασις, meaning "description," and has accumulated a rich theoretical literature on the relationship between linguistic and visual modes.

For our purposes, the essential insight is this: ekphrasis has never been neutral transcription. To describe an image is to transform it, interpret it, and—in a certain sense—remake it in language. The description does something; it is not merely about something.

James Heffernan's influential definition captures this: ekphrasis is "the verbal representation of visual representation," where the verbal does not simply reflect but actively constitutes. W.J.T. Mitchell extends this with his concept of the "imagetext"—the hybrid entity that emerges when word and image combine, neither reducible to the other. [heffernan_museum_2004] [mitchell_picture_1994]

2.2 The Shield of Achilles: Foundational Anchor

Homer's description of the shield of Achilles (Iliad, Book 18) serves as the foundational example of ekphrasis in Western literature and the conceptual anchor for this paper. In over 130 lines, Homer describes the shield that Hephaestus forges for Achilles before his final battle with Hector.

What makes this passage significant for Thick Prompting is not merely its antiquity but three specific features that prefigure contemporary prompting practice:

FEATURE ONE: DEPICTION OF PROCESS

Homer does not describe a finished object. He depicts Hephaestus in the act of making:

"First he made a shield, great and heavy,
decorating it everywhere with art,
and around it he set a shining rim, triple,
glittering, and from it a silver baldric."

The shield is described AS IT COMES INTO BEING. Lessing noted this in the eighteenth century: Homer converts the spatial, simultaneous artifact into a temporal, sequential process. [lessing_laocoon_1766]

This process-orientation prefigures prompting. The artifact emerges through iterative procedure. The maker is present in the description. Generation is not instantaneous but staged, refined, worked.

FEATURE TWO: COMPOSITION OF A NARRATIVE WORLD

The shield does not depict static scenes but a world in motion:

- Two cities: one at peace (weddings, law courts), one at war (ambush, battle)
- Agricultural cycle: plowing, harvest, vintage
- Pastoral life: herds threatened by lions
- Celebration: dancers, musicians

The shield is filled with people DOING things. It presents not images but narratives, not objects but actions. This emphasis on action resonates with what we call the "operative" dimension of prompting: prompts that do things, not merely depict.

FEATURE THREE: FUNCTION AS BACKDROP

The shield serves a narrative function: it is the backdrop against which Achilles goes to his death. Homer does not describe it for its own sake but as preparation for the drama to come. The description creates a context—a world—within which meaning becomes possible.

This contextual function is crucial. Thick Prompting likewise creates contexts—system prompts, cultural frames, stylistic anchors—within which subsequent generations gain meaning.

2.3 From Ekphrasis to Operative Description

Hannes Bajohr's concept of "operative ekphrasis" names the shift that generative AI introduces. Traditional ekphrasis describes an image that exists (actual ekphrasis) or might exist (notional ekphrasis). Operative ekphrasis GENERATES the image through description. [bajohr_operative_2024]

The prompt does not represent; it produces. Generative AI makes the Homeric capacity literally operative: the description that calls forth a world now actually creates one.

═══════════════════════════════════════════════════════════════════
3. THICK DESCRIPTION: THE ANTHROPOLOGICAL METHOD
═══════════════════════════════════════════════════════════════════

3.1 Geertz's Concept

Clifford Geertz introduced "thick description" in his 1973 essay of the same name, drawing on philosopher Gilbert Ryle. The concept distinguishes levels of interpretive depth.

The canonical example: A thin description of a wink notes "the boy rapidly contracted his right eyelid." A thick description asks: Is he winking conspiratorially? Practicing? Parodying? Twitching? The same physical behavior carries radically different meanings depending on context, intention, and cultural code. [geertz_thick_1973]

For Geertz, ethnography IS thick description—the layered interpretation of meaningful action. The ethnographer does not record behavior but reads significance, situating events within webs of meaning that constitute culture.

3.2 What "Thickness" Means

Thickness is NOT:
- Word count (long prompts are not thick prompts)
- Detail accumulation (more specifics are not more thickness)
- Technical precision (exact parameters are not thickness)

Thickness IS:
- Interpretive depth (layered meaning)
- Contextual richness (webs of significance)
- Intentional arrangement (structured constraint)
- Ritualistic execution (repeated, refined practice)

This distinction is crucial because "thick prompting" can be mistaken for "long prompting." The mistake blocks good practice. A thick prompt might be shorter than a thin one if its constraints are more precisely calibrated.

3.3 Adaptation to Prompting

We adapt Geertz's method to prompting practice:

THIN PROMPTING treats the prompt as singular instruction: "Make a shield." The prompt specifies outcome without context, intention, or arrangement. It is the equivalent of noting eyelid contraction—technically accurate but interpretively empty.

THICK PROMPTING treats the prompt as heterogeneous stack whose iterative execution functions as meaning-making ritual:

┌─────────────────────────────────────────────────────────────┐
│ SYSTEM PROMPT (Cultural Frame)                              │
│ Establishes interpretive context, "web of significance"    │
├─────────────────────────────────────────────────────────────┤
│ META-PROMPTS (Inception Layer)                              │
│ Prompts that generate prompts, recruiting model knowledge   │
├─────────────────────────────────────────────────────────────┤
│ STRUCTURED DATA (JSON / Code)                               │
│ Parameterized constraints enabling version control          │
├─────────────────────────────────────────────────────────────┤
│ NATURAL LANGUAGE (Ekphrastic Core)                          │
│ The vivid description that evokes the visual                │
├─────────────────────────────────────────────────────────────┤
│ TAGS AND WEIGHTS (Platform Syntax)                          │
│ Platform-specific modulations of attention                  │
├─────────────────────────────────────────────────────────────┤
│ ITERATIVE EXECUTION (Ritual Dimension)                      │
│ Repeated generation, selection, refinement over time        │
└─────────────────────────────────────────────────────────────┘

Each layer adds interpretive depth. The arrangement matters as much as the content. The execution—repeated, selective, responsive—transforms prompting from command into practice.

═══════════════════════════════════════════════════════════════════
4. THICK PROMPTING: THE METHOD
═══════════════════════════════════════════════════════════════════

4.1 The Heterogeneous Stack

Thick Prompting operationalizes the theoretical frameworks through a specific technical structure: the heterogeneous stack. This stack combines multiple modalities and constraint types:

NATURAL LANGUAGE: The ekphrastic core. Vivid description that evokes rather than specifies. "A shield that tells stories of a world" rather than "a circular bronze object."

CODE / JSON: Parameterized constraints that enable precision, version control, and systematic variation:

{
  "artifact": {
    "type": "shield",
    "structure": "concentric_zones",
    "zones": 5
  },
  "style": {
    "materiality": "bronze_relief",
    "reference": "John Flaxman",
    "period": "classical Greek"
  },
  "emphasis": {
    "focus": "action_over_stasis",
    "quality": "world_model_not_decoration"
  }
}

SYSTEM PROMPTS: Cultural frames that establish interpretive context:

"You are assisting an artist-scholar who studies the relationship between ancient Greek visual culture and AI-generated art. Your outputs should capture cosmological ambition—world-building, not mere illustration. The goal is to translate Homer's world-composing ekphrasis into visual form."

META-PROMPTS (Inception Prompts): Prompts that generate prompts, recruiting the model's own knowledge to thicken description:

"Describe, as if you were Hephaestus briefing an apprentice, the shield you would forge: five zones moving from cosmos to ocean, filled with ACTIONS not objects, emphasizing the making."

The model's output becomes the generation prompt. This leverages model capabilities to produce richer descriptions than most users write manually.

TAGS AND WEIGHTS: Platform-specific syntax that modulates attention and priority:

[bronze materiality:1.3], [classical Greek:1.2], [narrative density:1.1]

The heterogeneity is essential. Each modality contributes what it does best: natural language evokes; code structures; system prompts contextualize; tags tune.

4.2 Ritualistic Execution

The stack alone is insufficient. Thick Prompting also requires ritualistic execution—repeated, iterative practice that refines output over time.

We draw explicit parallel to Alvin Lucier's "I Am Sitting in a Room" (1969), where the composer recorded himself speaking, then played the recording into the room and re-recorded the result, repeating until the room's resonant frequencies transformed speech into pure tone.

THICK PROMPTING RITUAL:
1. Generate multiple outputs from initial stack (e.g., 50 images)
2. Select promising candidates (e.g., 3)
3. Use selections as reference for next iteration
4. Adjust stack based on observations
5. Repeat, allowing the model's "resonant frequencies" to emerge

Through repetition:
- Consistent elements amplify (what the model "wants" to produce)
- Inconsistent elements decay (what the model struggles with)
- The practitioner learns the platform's grain

Thickness accrues temporally. A single prompt, however elaborate, cannot achieve what iterated practice produces.

4.3 Platform Constraints as Material

Thick Prompting operates within platform constraints—not as obstacles but as materials:

MODEL ARCHITECTURE: Diffusion vs. autoregressive, conditioning mechanisms, resolution limits. The thick prompter learns what their platform can and cannot do.

SAFETY FILTERS: Content policies that shape permissible outputs. Understanding triggers enables working within constraints rather than against them.

TOKEN LIMITS: Bounds on prompt length that require prioritization. Long prompts are not thick prompts; thickness means knowing what matters.

API PARAMETERS: Temperature, CFG scale, sampling methods. Technical settings interact with textual prompts in complex ways that practice reveals.

TRAINING DATA: Cultural and historical biases embedded in model weights. The platform's "resonant frequencies"—its tendencies, defaults, blind spots—become visible through ritual.

4.4 Evaluative Concepts

Thick Prompting introduces evaluative concepts that shift criteria from fidelity to practice:

OPTION SPACE: How many live possibilities remain after prompting? Open prompts preserve generative potential; closed prompts collapse to single outcomes. The thick prompter manages option space deliberately—opening during exploration, closing during refinement.

RESILIENCE: Does the prompt produce consistent outputs across regenerations? High resilience means the prompt has found a stable region of latent space. Low resilience (fragility) indicates boundary conditions or chaos. Neither is inherently better; both are useful for different purposes.

OBLIGATION: How much duty does the prompt install? Strong obligation demands specific features (failure is checkable). Weak obligation permits drift (no clear failure mode). The thick prompter calibrates obligation to intent.

These concepts shift evaluation from "Does it match?" to "Does it enable?"

═══════════════════════════════════════════════════════════════════
5. DIFFERENTIAL ANALYSIS: Δ AND ΔΔ
═══════════════════════════════════════════════════════════════════

5.1 The Method

Prompt Differentials provide a systematic technique for analyzing how constraint changes affect outputs. We borrow notation from calculus:

Δ (DELTA): A single-variable change between prompts. Isolates the contribution of one element.

ΔΔ (DELTA-DELTA): The rate of change of change. Compares how sensitivity differs across dimensions.

5.2 Δ Trace Example

We analyze the shield prompt through systematic variation:

┌──────────────────────────────────────────────────────────────┐
│ BASE PROMPT: "Bronze shield with concentric narrative zones" │
├──────────────────────────────────────────────────────────────┤
│ Δ₁: Change CONTENT                                           │
│     "Bronze shield with battle scene" → "with harvest scene" │
│     Effect: Composition shifts, palette warms, mood changes  │
├──────────────────────────────────────────────────────────────┤
│ Δ₂: Change STYLE                                             │
│     "...in classical Greek style" → "...in Art Nouveau"      │
│     Effect: Line quality shifts, organic forms emerge        │
├──────────────────────────────────────────────────────────────┤
│ Δ₃: Change MATERIALITY                                       │
│     "Bronze shield" → "Glass shield"                         │
│     Effect: Lighting transforms, transparency introduces     │
├──────────────────────────────────────────────────────────────┤
│ Δ₄: Remove SYSTEM PROMPT                                     │
│     (No cultural frame)                                      │
│     Effect: Cosmological ambition lost, generic fantasy      │
└──────────────────────────────────────────────────────────────┘

Each Δ reveals which elements carry weight and which are negligible.

5.3 ΔΔ Trace Example

We compare sensitivity across dimensions:

Series 1: Vary CONTENT while holding style constant
Series 2: Vary STYLE while holding content constant

ΔΔ = Compare the magnitude of change

OBSERVATION: For shield prompts, style changes produce larger visual shifts than content changes. The style dimension is more determinative than the content dimension for this prompt structure.

This finding is not universal—it depends on prompt architecture. But the ΔΔ method reveals the dependency structure, enabling practitioners to invest effort where it matters.

5.4 Practical Application

Differential analysis serves multiple purposes:

DEBUGGING: When outputs fail, Δ traces identify which element is responsible.

OPTIMIZATION: ΔΔ reveals where to invest prompt-crafting effort.

DOCUMENTATION: Δ traces create legible records of prompt evolution.

TEACHING: Differentials make implicit knowledge explicit and shareable.

═══════════════════════════════════════════════════════════════════
6. DESIGN STUDY: FROM STATIC IMAGE TO WORLDTEXT
═══════════════════════════════════════════════════════════════════

6.1 Overview

We present a design study that moves from static images to interactive 3D environments, demonstrating Thick Prompting across the trajectory. The study uses the shield as running example, progressing through three phases:

PHASE 1: Static Image (imagetext)
PHASE 2: Animated Sequence (temporal extension)
PHASE 3: Navigable Environment (worldtext)

6.2 Phase 1: The Shield as Imagetext

THIN BASELINE:
Prompt: "A shield with battle scenes"
Result: Generic fantasy shield. No cosmological structure. No process-foregrounding. Representationally "correct" but interpretively empty.

THICK ALTERNATIVE:

System: "You are assisting an artist-scholar studying Homeric ekphrasis. The goal is to translate world-building ambition into visual form—not to illustrate Homer but to capture his method: describing process, composing world, providing backdrop for action."

Inception: "As Hephaestus, describe the shield you forge: five zones from cosmos to ocean, filled with ACTIONS not objects."

JSON:
{
  "zones": [
    {"ring": 1, "content": "cosmos—sun, moon, stars, earth, sea, sky"},
    {"ring": 2, "content": "city at peace—wedding, law court"},
    {"ring": 3, "content": "city at war—ambush, battle, mourning"},
    {"ring": 4, "content": "agricultural cycle—plow, harvest, vintage"},
    {"ring": 5, "content": "Ocean encircling all"}
  ],
  "style": "bronze relief, classical line quality",
  "emphasis": "action and process, not static depiction"
}

Tags: [bronze:1.3], [Flaxman:1.2], [world model:1.0]

Result: Shield with coherent symbolic program. Material consistency. Compositional logic. Narrative density. The shield presents a cosmos, not a decoration.

DIFFERENTIAL ANALYSIS:
- Removing system prompt → loses cosmological ambition
- Removing inception → loses process-foregrounding
- Removing JSON → loses compositional logic

6.3 Phase 2: Temporal Extension

We extend the shield into animated sequence, testing whether Thick Prompting techniques transfer across modalities.

PROMPT STACK ADAPTATION:

System: [retained from Phase 1]

Temporal specification:
{
  "sequence": "forging process",
  "duration": "60 seconds",
  "stages": [
    {"time": "0-15s", "action": "Hephaestus shapes bronze disc"},
    {"time": "15-30s", "action": "cosmos zone emerges under hammer"},
    {"time": "30-45s", "action": "cities and farms take form"},
    {"time": "45-60s", "action": "Ocean rim completes the world"}
  ],
  "emphasis": "making visible—the process Homer describes"
}

OBSERVATION: The process-foregrounding that Homer achieves through temporal narration becomes literal animation. The ekphrastic tradition's solution to spatial-vs-temporal representation becomes direct technique.

6.4 Phase 3: The Worldtext

We extend from imagetext to worldtext: a spatially navigable, procedurally structured environment.

PIPELINE: text → image → 3D mesh → navigable environment

WORLDTEXT PROMPT STACK:

System: "You are world-building for an interactive experience. The environment must be NAVIGABLE—the viewer moves through, not just looks at. The world should feel inhabited, with evidence of process and narrative."

Description: "A world modeled on the shield of Achilles: at center, the cosmos is visible through an oculus; moving outward, zones transition from celestial to agricultural to urban to oceanic. The world is circular, bounded, complete. Signs of the maker are everywhere—tool marks, unfinished edges, the presence of craft."

Structural constraints:
{
  "navigability": "first-person traversal",
  "scale": "human-sized, with vista points for overview",
  "zones": "concentric, with transition thresholds",
  "coherence": "consistent material logic throughout",
  "evidence_of_process": "visible throughout"
}

RESULT: Environment demonstrates worldtext characteristics:
- SPATIAL NAVIGABILITY: Viewer explores, not just observes
- PROCEDURAL STRUCTURE: Description generated rules, not just instances
- PROCESS VISIBILITY: The world shows signs of its making
- HOMERIC LOGIC: Concentric structure, world-bounding ocean, cosmic center

6.5 Comparative Analysis

Across all three phases:

WHAT TRANSFERS:
- System prompt establishes consistent cultural frame
- JSON structure adapts to each modality
- Process-foregrounding remains central
- Compositional logic (concentric, bounded, complete) persists

WHAT CHANGES:
- Temporal dimension becomes explicit in Phase 2
- Navigability requires new constraint types in Phase 3
- Platform constraints differ across image/video/3D pipelines

THICK PROMPTING CONSISTENCY: The heterogeneous stack and ritualistic execution remain constant even as output modality changes.

═══════════════════════════════════════════════════════════════════
7. DISCUSSION: THEORY AS BRIDGE TO PRACTICE
═══════════════════════════════════════════════════════════════════

7.1 The Accidental Connection

Generative AI has accidentally created conditions where ancient rhetorical and anthropological concepts become directly applicable. Engineers building text-to-image systems did not set out to operationalize ekphrasis, but they have. Prompt interfaces did not intend to create conditions for thick description, but they do.

Consciously reclaiming these concepts enables practitioners to:
- Move beyond naive, instrumental views of prompting
- Access deep traditions of thinking about text-image relations
- Develop vocabulary for articulating and teaching practice
- Position contemporary work within longer histories

7.2 The Fidelity Critique

We do not dismiss representational fidelity but contextualize it. Fidelity matters for certain applications: illustration, matching, specification. The criterion "does it look like what I described?" is legitimate when matching is the goal.

But for expressive, exploratory, and world-building work, fidelity is insufficient. The artist needs resonance, surprise, productive error. The designer needs navigability, coherence, inhabitability. These criteria require different evaluation frameworks:

FIDELITY: Does the output match the description?
OPTION SPACE: Does the output enable further possibilities?
RESILIENCE: Does the output invoke a coherent world?
RICHNESS: Does the output reward sustained attention?

Thick Prompting provides vocabulary and technique for the latter criteria without abandoning the former when appropriate.

7.3 Deliberateness Over Precision

The central shift Thick Prompting proposes is from precision to deliberateness:

PRECISION asks: How exactly can I specify what I want?
DELIBERATENESS asks: How carefully can I arrange constraints to enable what I need?

Precision optimizes for fidelity. Deliberateness optimizes for richness. Both have their place, but current discourse overweights precision.

The heterogeneous stack, ritualistic execution, and evaluative concepts we propose all serve deliberateness: careful arrangement, attentive iteration, principled evaluation.

7.4 Worldmaking as Goal

The ultimate reframing: prompting is not picture-making but worldmaking.

A picture represents. A world invites.
A picture is viewed. A world is inhabited.
A picture matches or fails. A world opens or closes.

Homer's shield is not an image but a cosmos. Thick Prompting aims at the same ambition: prompts that compose worlds, not depict scenes.

═══════════════════════════════════════════════════════════════════
8. CONCLUSION: THE NECESSARY BRIDGE
═══════════════════════════════════════════════════════════════════

This paper has argued for repositioning multimodal prompting within literary and anthropological traditions. Ekphrasis—the verbal evocation of visual worlds—provides a framework for understanding what prompts do: they call forth worlds through description. Thick description—the layered interpretation of meaningful action—provides a model for how to prompt well: through heterogeneous stacks, ritualistic execution, and deliberate arrangement.

The bridge between these theoretical frameworks and contemporary practice is Thick Prompting, defined by:

1. HETEROGENEOUS STACKS: Combining natural language, code, JSON, system prompts, and tags—each modality contributing what it does best.

2. RITUALISTIC EXECUTION: Iterative generation, selection, and refinement—allowing thickness to accrue temporally.

3. EVALUATIVE SHIFT: From fidelity to option space, resilience, and richness—judging prompts by what they enable, not what they match.

4. WORLDMAKING ORIENTATION: From picture-making to world-composing—prompts that invite habitation rather than observation.

Our design study demonstrated Thick Prompting across modalities: from static image to animated sequence to navigable environment. The techniques—meta-prompting, differential analysis, constraint stacking—prove applicable across this trajectory, while the Homeric anchor provides conceptual coherence.

The contribution is methodological. We do not claim that Thick Prompting guarantees aesthetic success or solves all prompting problems. We claim that it provides:

- A vocabulary for articulating prompting practice
- Techniques grounded in theoretical insight
- Evaluative criteria beyond fidelity
- Orientation toward richness and worldmaking

Ultimately, Thick Prompting is a necessary bridge: between theory and practice, between ancient tradition and contemporary technology, between instrumental use and expressive possibility. By consciously reclaiming the concepts that generative AI has accidentally operationalized, practitioners can move beyond naive prompting toward deliberate, rich, world-composing practice.

The shield of Achilles was always more than decoration. It was a world. Thick Prompting helps us compose worlds again.

═══════════════════════════════════════════════════════════════════
REFERENCES
═══════════════════════════════════════════════════════════════════

[bajohr_operative_2024] Bajohr, H. (2024). Operative Ekphrasis: The Collapse of the Text/Image Distinction in Multimodal AI.

[geertz_thick_1973] Geertz, C. (1973). Thick Description: Toward an Interpretive Theory of Culture. In The Interpretation of Cultures. Basic Books.

[heffernan_museum_2004] Heffernan, J. A. W. (2004). Museum of Words: The Poetics of Ekphrasis from Homer to Ashbery. University of Chicago Press.

[krieger_ekphrasis_1992] Krieger, M. (1992). Ekphrasis: The Illusion of the Natural Sign. Johns Hopkins University Press.

[lessing_laocoon_1766] Lessing, G. E. (1766/1984). Laocoön: An Essay on the Limits of Painting and Poetry. Trans. E. A. McCormick. Johns Hopkins University Press.

[mitchell_picture_1994] Mitchell, W. J. T. (1994). Picture Theory: Essays on Verbal and Visual Representation. University of Chicago Press.
