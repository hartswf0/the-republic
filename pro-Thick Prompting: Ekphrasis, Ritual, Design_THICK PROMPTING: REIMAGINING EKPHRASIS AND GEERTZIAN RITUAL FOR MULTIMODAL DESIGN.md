THICK PROMPTING: REIMAGINING EKPHRASIS AND GEERTZIAN RITUAL FOR MULTIMODAL DESIGN

Gaia Hartsoe & Jay David Bolter
Georgia Institute of Technology

═══════════════════════════════════════════════════════════════════
ABSTRACT
═══════════════════════════════════════════════════════════════════

Current evaluations of multimodal generative AI often judge success through the narrow lens of representational fidelity—how well an image matches a text description. However, for artists and designers seeking personal expression, this metric is insufficient. This paper positions prompting within the broader historical contexts of literary analysis and anthropology to propose a new methodology: Thick Prompting.

Drawing on the concept of ekphrasis (the verbal representation of visual art) and Clifford Geertz's notion of "thick description," we argue that prompting should be treated not as a simple command line, but as the construction of a "heterogeneous stack" comprising code, text, tags, and constraints. We first explore the theoretical relationship between text and image, using Homer's description of the Shield of Achilles to demonstrate how process-oriented description can "call forth a world" rather than merely describe a scene. We then operationalize this theory into a taxonomy of design techniques, demonstrating how Thick Prompting serves as a ritual to make high-dimensional latent spaces navigable and interpretable. Finally, we present design studies that apply these techniques to produce complex visual artifacts and 3D game environments, bridging the gap between classical theory and contemporary computational practice.

Keywords: generative AI, prompting, ekphrasis, thick description, multimodal design, text-to-image

═══════════════════════════════════════════════════════════════════
1. INTRODUCTION: THE PROBLEM OF FIDELITY
═══════════════════════════════════════════════════════════════════

Generative AI makes descriptions do work. A prompt is not merely an interpretation of what one wishes to see—it is an intervention that calls an artifact into view through a platformed procedure. In text-to-image and multimodal systems, words no longer simply represent; they generate. This shift from description-as-representation to description-as-operation marks a fundamental change in the relationship between text and image, one that demands new frameworks for understanding and practice. [bajohr_operative_2024]

Yet current discourse around multimodal AI largely judges success in prosaic terms: Does the generated image look like what I asked for? Did it get the number of fingers right? Is the text legible? This representational fidelity metric dominates both popular evaluation and academic benchmarking. While fidelity matters for certain applications, it provides an impoverished framework for artists, designers, and creators seeking to use these tools for personal expression, entertainment, and the production of meaningful visual culture.

This paper considers prompting practice specifically for making visual artifacts in contexts of art, personal expression, and entertainment—not prompting for code generation, data analysis, or conversational assistance. Within this scope, we argue that the relationship between prompt and output is better understood through the lens of ekphrasis than engineering.

We propose Thick Prompting: a method of treating prompts as heterogeneous stacks (code + text + tags + constraints) and their execution as a Geertzian ritual—a repeated, culturally-situated practice that makes the high-dimensional latent spaces of generative models navigable and interpretable. Our argument proceeds in two registers:

1. HISTORICAL/THEORETICAL: We position multimodal prompting within the long history of the relationship between text and image. Surprisingly, what computer engineers have built with their interfaces and multimodal models places prompting in contexts where literary history, art historical analysis, and anthropology become directly relevant.

2. PRACTICAL/DEMONSTRATIVE: We show how this theoretical perspective helps shape prompting as a practice for producing richer, more compelling visual artifacts—moving beyond the "mid" plateau that plagues naive prompting approaches.

The paper is structured to alternate between theory and demonstration. Section 2 establishes ekphrasis as our theoretical anchor, using Homer's Shield of Achilles to illustrate how description has long been understood as world-composition rather than mere depiction. Section 3 introduces Geertz's thick description as a methodological frame, distinguishing "thick" from "thin" prompting. Section 4 presents our taxonomy of Thick Prompting techniques. Sections 5 and 6 offer design studies and discussion, demonstrating how these techniques operate in practice and reflecting on design lessons learned.

═══════════════════════════════════════════════════════════════════
2. EKPHRASIS: DESCRIPTION AS WORLD-COMPOSITION
═══════════════════════════════════════════════════════════════════

2.1 What is Ekphrasis?

Ekphrasis, in its contemporary scholarly usage, refers to the verbal representation of visual representation—words describing images, texts evoking artworks. The term derives from the Greek ἔκφρασις (ekphrasis), meaning "description," and has accumulated a rich theoretical literature examining the fraught relationship between linguistic and visual modes of meaning-making. [heffernan_museum_2004]

For James Heffernan, ekphrasis constitutes a "paragone"—a struggle for mastery between word and image, where "the silent image" confronts "the speaking word." This agonistic framing captures something essential: ekphrasis is not neutral transcription but active transformation. The verbal does something to the visual; description is an intervention. [heffernan_museum_2004]

W.J.T. Mitchell extends this analysis through his concepts of "ekphrastic hope" and "ekphrastic fear." Ekphrastic hope names the desire for perfect union between word and image—that language might achieve complete adequacy to visual experience. Ekphrastic fear names the anxiety that the image might overwhelm language, that the visual might escape or exceed the verbal. Mitchell opposes the naive belief that word and image are naturally separate domains; they are, he argues, always already intertwined in complex "imagetexts." [mitchell_picture_1994]

More recent scholars have pushed beyond representational frameworks entirely. Claus Clüver argues for understanding ekphrasis not as "representation" but as "encounter" or "configuration"—a term that accommodates abstraction, architecture, and forms of art that resist depiction. [cluver_new_2017] Cecilia Lindhé and Daniel Jansson explore how digital ekphrasis introduces multisensory and tactile dimensions, while Liliane Louvel theorizes the "iconotext" or "pictorial third"—a hybrid entity that emerges from the encounter between verbal and visual. [louvel_types_2018] [jansson_ekphrasis_2018]

2.2 Homer's Shield: The Originary Case

The shield of Achilles, described in Book 18 of the Iliad, serves as the foundational example of ekphrasis in Western literature. Homer devotes over 130 lines to describing the shield that Hephaestus forges for Achilles, and this passage has anchored discussions of ekphrasis from Lessing's Laocoön (1766) to contemporary theory.

What makes Homer's shield particularly instructive for our purposes is not merely its canonical status but three specific features:

FIRST: PROCESS-FOREGROUNDING. Homer does not describe a finished object but depicts Hephaestus in the act of making. The shield is described "as it is being made"—Lessing noted this temporal dimension in the eighteenth century as Homer's solution to the problem of describing a spatial, simultaneous artwork in sequential, temporal language. [heffernan_museum_2004] This process-orientation prefigures contemporary prompting, where the artifact emerges through an iterative procedure rather than appearing fully formed.

SECOND: NARRATIVE ACTION. The shield does not depict static scenes but actions, events, narratives. Two cities are shown: one at peace with weddings and legal disputes, one at war with ambush and battle. Farmers plow, vintners harvest, dancers perform. The shield is filled with movement, with people doing things. This emphasis on action over stasis resonates with the "operative" turn in contemporary description—prompts that do things rather than merely depict them.

THIRD: WORLD-COMPOSITION. Most significantly, Homer's shield describes a world. It presents the cosmos (earth, sea, sky, sun, moon, constellations), human society (city and country, peace and war, labor and celebration), and the encircling Ocean. The shield is not an image of a thing but a model of everything—a world in miniature. Media scholars have noted this world-building dimension, but generative AI makes it operative: the prompt that describes a world can now generate one. [bajohr_operative_2024]

This is the crucial insight: the first ekphrasis describes, calls forth a world. Homer does not ask us to picture a shield; he composes an entire cosmos through description. Gen AI makes this ancient capacity operative—description now literally produces the worlds it evokes.

2.3 From Imagetext to Worldtext

Mitchell's influential concept of the "imagetext" names the hybrid entity that emerges when word and image combine. We propose an extension: "worldtext."

A worldtext is a prompt (or prompt stack) that compiles into a spatially navigable or procedurally structured media object. Where imagetexts produce pictures, worldtexts produce environments—3D spaces, game worlds, interactive experiences that viewers can inhabit rather than merely observe. These worlds are, as one reviewer noted, "more or less game worlds... visually expressed, ultimately as 3D environments that the viewer/player/user can inhabit."

This shift from imagetext to worldtext is not a replacement but an addition. The textual description of a shield produces an image (imagetext); the textual description of a world produces an environment (worldtext). Contemporary multimodal pipelines—combining text-to-image, image-to-3D, and procedural generation—make worldtext production increasingly practical. [rajewsky_intermedialitat_2002]

═══════════════════════════════════════════════════════════════════
3. THICK DESCRIPTION: FROM ANTHROPOLOGY TO PROMPTING
═══════════════════════════════════════════════════════════════════

3.1 Geertz's Method

Clifford Geertz introduced "thick description" in his influential essay "Thick Description: Toward an Interpretive Theory of Culture" (1973). Drawing on Gilbert Ryle's philosophical example, Geertz distinguishes between "thin" and "thick" description through the case of the wink:

A thin description of a wink might note: "the boy rapidly contracted his right eyelid." This captures the physical behavior but misses everything important. A thick description unpacks the layers: Is he winking conspiratorially? Practicing? Parodying someone else's wink? Twitching involuntarily? The same physical movement carries radically different meanings depending on context, intention, and cultural code. [geertz_thick_1973]

For Geertz, ethnography is thick description—the interpretive unpacking of meaningful action. The ethnographer does not merely record behavior but reads intention in action, situating events within webs of significance that constitute culture. Thickness is not verbosity but interpretive depth: the layering of context, meaning, and significance that transforms raw observation into cultural understanding.

3.2 Thin Prompting vs. Thick Prompting

We appropriate Geertz's distinction for prompting practice:

THIN PROMPTING treats the prompt as a simple command: "Make a shield." "Generate a landscape." "Create a portrait." The thin prompt specifies an outcome without context, intention, or constraint. It is the equivalent of noting that a boy contracted his eyelid—technically accurate but interpretively empty.

THICK PROMPTING treats the prompt as a heterogeneous stack comprising multiple layers:

Layer 1 - DESCRIPTION: What is being depicted? (The surface content)
Layer 2 - INTENTION: What cultural/symbolic meaning does this carry?
Layer 3 - CONTEXT: What system, history, and constraints shape production?
Layer 4 - RITUAL: What repeated practice refines the output?
Layer 5 - RECURSION: How does output feed back into input?

This matters because "thick prompting" is often mistaken for long prompting. That mistake blocks good practice. Thickness, in our sense, is constraint quality, not word count. A thick prompt might be shorter than a thin one if its constraints are more precisely calibrated.

3.3 The Geertzian Stack

We visualize thick prompting as a stack:

┌─────────────────────────────────────┐
│ SYSTEM PROMPT (Cultural Frame)      │
│ Establishes interpretive context,   │
│ aesthetic sensibility, constraints  │
├─────────────────────────────────────┤
│ REFERENCE IMAGES (Visual Prior)     │
│ Anchors style, composition, mood    │
├─────────────────────────────────────┤
│ DESCRIPTIVE TEXT (Ekphrasis)        │
│ The verbal evocation of the visual  │
├─────────────────────────────────────┤
│ STRUCTURAL TAGS (JSON/Parameters)   │
│ Technical specifications, weights   │
├─────────────────────────────────────┤
│ ITERATIVE REFINEMENT (Ritual)       │
│ Repeated generation and selection   │
└─────────────────────────────────────┘

Each layer adds thickness. The system prompt establishes what Geertz would call the "cultural frame"—the interpretive context within which subsequent prompts gain meaning. Reference images provide visual priors that anchor style without requiring verbose description. The descriptive text is the ekphrastic core—the verbal evocation. Structural tags (JSON objects, weighted terms, parameters) provide technical precision. And iterative refinement—the ritual of generating, evaluating, adjusting, regenerating—provides the temporal depth that transforms prompting from command into practice.

3.4 Platform Constraints

Thick prompting operates within platform constraints—the affordances and limitations of specific generative systems:

- MODEL ARCHITECTURE: What the neural network can and cannot represent, its training biases, its failure modes
- SAFETY FILTERS: Content policies that shape permissible outputs
- TOKEN LIMITS: Context windows that bound prompt length
- API PARAMETERS: Temperature, CFG scale, sampling methods
- TRAINING DATA: The cultural and historical biases embedded in the model

These constraints are not obstacles to be overcome but materials to be worked with. The thick prompter learns the grain of their platform—where it excels, where it struggles, what it assumes—and crafts prompts that leverage this knowledge.

═══════════════════════════════════════════════════════════════════
4. A TAXONOMY OF THICK PROMPTING TECHNIQUES
═══════════════════════════════════════════════════════════════════

The following taxonomy emerges from practice. These are not arbitrary categories but design techniques that have proven useful across multiple projects. Each technique addresses a specific problem in prompt construction.

4.1 Inception Prompts (Prompts That Prompt Prompts)

An inception prompt is a meta-prompt: a prompt designed to generate other prompts. Rather than directly describing the desired output, the inception prompt instructs the model to construct a description, which is then used for generation.

Example:
"You are a production designer for a film set in ancient Greece. Describe in vivid detail the shield you would create for the hero, including materials, imagery, and symbolic meaning. Write as if briefing a master craftsman."

The model's output becomes the actual generation prompt. This technique leverages the model's language capabilities to produce richer descriptions than most users write manually, while embedding intentionality (the production designer's purpose) and context (ancient Greece, hero's shield) into the description.

Why inception? Because direct prompting often produces "mid" results—technically adequate but aesthetically flat. Inception prompts recruit the model's knowledge to thicken the description.

4.2 JSON Structures for Precision

JSON-formatted prompts provide structured control over generation parameters:

{
  "scene": "shield forging",
  "subject": {
    "type": "circular bronze shield",
    "diameter": "three cubits",
    "ornamentation": "five concentric rings"
  },
  "style": {
    "rendering": "classical oil painting",
    "palette": "warm bronze, deep blue, crimson",
    "reference_artists": ["John Flaxman", "Frederic Leighton"]
  },
  "composition": {
    "perspective": "frontal, slight tilt",
    "lighting": "forge-fire from left, divine radiance from above"
  }
}

This technique separates concerns: content, style, and composition each get explicit specification. It also enables version control—JSON prompts can be tracked, diffed, and systematically varied.

4.3 Prompt Differentials (Δ and ΔΔ)

We borrow notation from calculus to describe systematic prompt variation:

Δ (Delta): A single-variable change between prompts
ΔΔ (Delta-Delta): The rate of change of change—how variation patterns shift

Example Δ trace:
- Prompt A: "Bronze shield with battle scene"
- Prompt B: "Bronze shield with peaceful harvest scene"
- Δ = content variation (war → peace)

Example ΔΔ trace:
- Series 1: Varying content while holding style constant
- Series 2: Varying style while holding content constant
- ΔΔ = comparing the effect of content variation vs. style variation

This technique enables systematic exploration of latent space, revealing how different prompt elements contribute to output characteristics.

4.4 Evaluation Metrics for Thickness

How do we evaluate prompts and their outputs? We propose several metrics:

RESILIENCE: Does the completion maintain the same center of gravity across regenerations? A resilient prompt produces consistent outputs; a fragile prompt produces wild variation.

OPTION SPACE: How many live alternatives remain? A closed prompt collapses to one outcome; an open prompt preserves generative possibility.

OBLIGATION: How much duty or necessity does the prompt install? Strong constraints obligate specific outcomes; weak constraints permit drift.

REVERSIBILITY: Does the prompt allow backtracking? Can you undo or redirect, or has the generation committed to an irreversible path?

These metrics do not measure aesthetic quality directly—that remains a judgment call. Rather, they characterize the prompt's behavior, helping practitioners understand and refine their techniques.

═══════════════════════════════════════════════════════════════════
5. DESIGN STUDIES
═══════════════════════════════════════════════════════════════════

5.1 Study 1: The Shield of Achilles Revisited

Our first design study takes Homer's shield as a direct prompt challenge: Can thick prompting produce a visual artifact that captures the world-building character of the original ekphrasis?

We constructed a Geertzian stack:

SYSTEM PROMPT: "You are assisting an artist-scholar who studies the relationship between ancient Greek visual culture and contemporary AI art. Your task is to help generate images that capture the cosmological ambition of Homeric ekphrasis—not illustrating Homer, but translating his world-building ambition into visual form."

DESCRIPTIVE TEXT: Adapted directly from Richmond Lattimore's translation, segmented into five concentric zones (cosmos, city at peace, city at war, agricultural cycle, Ocean).

STRUCTURAL TAGS: Specified bronze materiality, circular composition, relief-like depth, classical line quality.

RITUAL: 50 generations per zone, curated to 3 candidates each, then composed into unified shield image.

Results demonstrated that thick prompting produced outputs qualitatively different from thin prompting ("a shield with battle scenes"). The thick-prompted shields exhibited:
- Coherent symbolic programs (not random imagery)
- Material consistency (bronze throughout)
- Compositional logic (concentric organization)
- Narrative density (multiple events readable in single image)

5.2 Study 2: Worldtext—From Image to Environment

Our second study extends from imagetext to worldtext: Can thick prompting produce not just images but inhabitable 3D environments?

We used a pipeline combining text-to-image, image-to-3D, and procedural terrain generation. The prompt stack described a world rather than a scene:

"A world where the distinction between natural and artificial has collapsed. Architecture grows from the ground like coral. Rivers follow paths laid by ancient machines now overgrown. The sky carries two suns—one warm, one cool—that never set simultaneously. Inhabitants have adapted their bodies to this environment, wearing it as much as living in it."

The resulting environment demonstrated worldtext characteristics:
- Spatial navigability (the world could be explored, not just viewed)
- Procedural structure (the description generated rules, not just instances)
- Internal consistency (the two-sun lighting propagated throughout)

5.3 Study 3: Iterative Ritual

Our third study examined the ritual dimension—how repeated generation and refinement produces thickness over time.

We documented a 30-day practice of generating images from the same base prompt, adjusting parameters, selecting outputs, and feeding selected images back as references for subsequent generations. This "I Am Sitting in a Room" approach (after Alvin Lucier's 1969 sound piece) revealed how the model's "resonant frequencies"—its biases, tendencies, default solutions—emerge through repetition, and how the practitioner learns to work with or against these tendencies.

Key finding: Thickness accrues temporally. A single prompt, no matter how elaborated, cannot achieve what iterated practice produces. The ritual dimension is essential, not supplementary.

═══════════════════════════════════════════════════════════════════
6. DISCUSSION: DESIGN LESSONS
═══════════════════════════════════════════════════════════════════

6.1 Theory Names What Design Does

A central challenge in this paper has been integrating theoretical frameworks (ekphrasis, thick description) with practical design work (prompt construction, image generation). We resolve this by treating theory not as prescription but as naming.

Ekphrasis names what prompters already do: they describe images in order to produce them. The history of ekphrasis provides concepts (paragone, imagetext, notional vs. actual) that illuminate aspects of prompting practice. Similarly, thick description names what skilled prompters learn through experience: that context, intention, and iteration matter more than surface specification.

Theory does not dictate practice; theory provides vocabulary for articulating practice. This vocabulary enables critique, pedagogy, and refinement.

6.2 The Operative Turn

Hannes Bajohr's concept of "operative ekphrasis" captures the fundamental shift: prompts do things, they don't just describe. The text/image distinction collapses in neural networks that treat both as vectors in shared latent space. What traditional ekphrasis represented, operative ekphrasis generates. [bajohr_operative_2024]

This has consequences for evaluation. If prompts are operative, judging them by representational fidelity is category error—like judging a recipe by how accurately it describes the finished dish rather than how well it guides cooking. The relevant question is not "Does this look like what I described?" but "Does this do what I needed?"

6.3 Beyond Representational Fidelity

We acknowledge that most users of generative AI do judge by representational fidelity. They want the image to match their mental picture; they want control over specifics (how many fingers, whether the text is legible). This dominant paradigm is not wrong but limited.

Our argument is not that fidelity doesn't matter but that fidelity is not sufficient for expressive work. The artist who uses these tools for personal expression needs more than accuracy—they need resonance, surprise, meaningful ambiguity, productive error. Thick prompting provides a framework for pursuing these goals while remaining rigorous about technique.

6.4 The Question of Aesthetic Judgment

A persistent question: How do we decide what is an aesthetically good artifact? Is that the point of thick prompting?

We offer a layered answer:

First, thick prompting is a method, not a guarantee. It provides techniques for navigating latent space, but navigation does not ensure arrival at valuable destinations. Aesthetic judgment remains the practitioner's responsibility.

Second, thick prompting produces richer artifacts. "Rich" here means: denser in meaning, more internally coherent, more open to interpretation, more surprising in execution. Richness is a formal property, not an aesthetic verdict.

Third, the proof is in practice. The design studies demonstrate that thick prompting produces outputs qualitatively different from thin prompting—more world-like, more coherent, more evocative. Whether these outputs are "better" depends on the practitioner's goals, but they are demonstrably different and arguably more interesting.

═══════════════════════════════════════════════════════════════════
7. CONCLUSION
═══════════════════════════════════════════════════════════════════

This paper has argued for repositioning multimodal prompting within the long history of the relationship between text and image. Ekphrasis—the verbal representation of visual art—provides a theoretical anchor that illuminates prompting as world-composition rather than mere command. Geertz's thick description provides a methodological frame that distinguishes thickness (interpretive depth, layered constraint) from length (word count).

We proposed Thick Prompting as a design methodology comprising:
- The Geertzian Stack (system prompt, reference images, descriptive text, structural tags, iterative refinement)
- Inception Prompts (prompts that generate prompts)
- JSON Structures (for precision and version control)
- Prompt Differentials (systematic variation)
- Evaluation Metrics (resilience, option space, obligation, reversibility)

Our design studies demonstrated thick prompting in practice: the Shield of Achilles as imagetext, worldtext environments, and iterative ritual.

The broader contribution is methodological. By treating prompting as a cultural practice—a ritual with history, theory, and technique—we move beyond the "prompt engineering" paradigm that treats prompts as technical problems to be solved. Prompting, we suggest, is an expressive medium with its own affordances, constraints, and aesthetic possibilities. Thick prompting is one way—not the only way—to take those possibilities seriously.

═══════════════════════════════════════════════════════════════════
REFERENCES
═══════════════════════════════════════════════════════════════════

[bajohr_operative_2024] Bajohr, H. (2024). Operative Ekphrasis: The Collapse of the Text/Image Distinction in Multimodal AI.

[cluver_new_2017] Clüver, C. (2017). A New Look at an Old Topic: Ekphrasis Revisited.

[geertz_thick_1973] Geertz, C. (1973). Thick Description: Toward an Interpretive Theory of Culture. In The Interpretation of Cultures.

[heffernan_museum_2004] Heffernan, J. A. W. (2004). Museum of Words: The Poetics of Ekphrasis from Homer to Ashbery.

[jansson_ekphrasis_2018] Jansson, D. (2018). Ekphrasis in the Digital Age.

[louvel_types_2018] Louvel, L. (2018). Types of Ekphrasis.

[mitchell_picture_1994] Mitchell, W. J. T. (1994). Picture Theory: Essays on Verbal and Visual Representation.

[rajewsky_intermedialitat_2002] Rajewsky, I. O. (2002). Intermedialität.