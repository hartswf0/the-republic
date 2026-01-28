# **Thick Prompting and the Architecture of Latent Worlds: Operative Ekphrasis, Experimental Modeling, and the Generative Turn**

## **I. Introduction: The Concept of Thick Prompting**

The advent of high-fidelity generative artificial intelligence has precipitated a fundamental epistemic shift in the relationship between human intent and machine output. The interface of this engagement—the "prompt"—was initially conceived in utilitarian terms as a retrieval mechanism, a keyword-based query designed to extract a specific asset from a static database. However, as the capabilities of Large Language Models (LLMs) and diffusion models have expanded, the prompt has evolved from a simple input signal into a complex, semiotic artifact. It has become the site of a new mode of creative practice which we designate as **Thick Prompting**.

Thick Prompting is not merely a descriptive category but a methodological intervention. It represents a move away from "thin" interaction—characterized by surface-level commands and stochastic gambling—toward a "thick" engagement that encodes the context, history, and procedural logic of the generation within the prompt itself. This report interrogates the theoretical and practical dimensions of Thick Prompting, situating it within the lineages of anthropological description, classical poetics, and the philosophy of science. By tracing the correlates between the "thick description" of Clifford Geertz, the "operative ekphrasis" of Hannes Bajohr, and the "experimental models" of Ludwig Boltzmann and Ludwig Wittgenstein, we establish a rigorous theoretical framework for understanding the prompt not as a caption, but as a world-building engine.

### **A. Defining Thick Prompting: The Geertzian Legacy**

To define Thick Prompting, one must first revisit the anthropological distinction between "thin" and "thick" description, a conceptual duality most famously articulated by Clifford Geertz in *The Interpretation of Cultures* (1973), though originally borrowed from the philosopher Gilbert Ryle.1 This distinction provides the necessary semiotic vocabulary to parse the difference between a novice user typing "cat" into a generator and a prompt artist constructing a multi-layered directive.

#### **1\. The Wink and the Blink: A Semiotic Hierarchy**

Geertz illustrates the concept of thickness through Ryle’s example of two boys contracting the eyelids of their right eyes. In a "thin description," the phenomenon is identical: a rapid contraction of the eyelid. Physiologically, there is no distinction between the two acts. However, in a "thick description," the context differentiates them entirely. One is an involuntary twitch (a blink); the other is a conspiratorial signal to a friend (a wink).1

The complexity deepens as Ryle introduces a third boy, who creates a parody of the first boy’s wink to mock him. This third boy is not winking, nor blinking; he is *parodying a wink*. A fourth boy might be rehearsing the parody in front of a mirror. At the "thin" level of description—the raw visual data—all four boys have performed the exact same physical action. Yet, at the "thick" level, there is a stratified hierarchy of meaning: reflex, communication, mockery, and rehearsal.1

In the domain of generative AI, "thin prompting" operates at the level of the blink. It is the input of a raw signifier ("sunset," "portrait") with the expectation of a statistical average. The machine, like the observer of the twitch, recognizes the physiological features of the request but lacks the "webs of significance" in which the request is suspended.

**Thick Prompting**, conversely, is the deliberate encoding of the "wink." It is a practice where the prompter does not merely ask for an object but encodes the *intent* of the object, the *context* of its presentation, and the *mode* of its interpretation. It answers the question: "What in hell do the natives think they are up to?" 2—where the "natives" are the latent vectors of the model, and the "what they are up to" is the specific aesthetic lineage being invoked.

#### **2\. The Inseparability of Intent and Context**

The transition to Thick Prompting is marked by the realization that intent and context cannot be separated from the generative action. This is explicitly recognized by practitioners within the emerging field of "prompt art." In a study of such practitioners, an artist identified as P6 (Ian Fischer) articulated a definition of the prompt that serves as a cornerstone for this theory. P6 described the prompt’s role as "communicating the image, and the idea of the image, and how I got it all at the same time".3

This triadic function—image, idea, and process—collapses the traditional separation between the artwork and its title, or the artwork and its technical documentation. P6 notes that the prompt is "like a title of the piece, but you don't get to choose it independently".3 It is bound by a functional dependency: it must effectively generate the image while simultaneously expressing the aesthetic concept.

The prompt is "thick" because it encodes the process of its own making. It creates a feedback loop where the text justifies the image, and the image validates the text. As P6 argues, "art is not only about how something looks, it's about what it says, it tells a story, and has a concept".3 In Thick Prompting, this concept is not external to the generation (as in a museum placard) but internal to the generative code itself. The prompt *is* the concept, operationalized.

### **B. Examples of Thick Prompting Practices**

Thick Prompting manifests not as a singular technique but as a constellation of practices that increase the semantic and structural density of the input. These practices transform the prompt from a string of keywords into a structured data object.

#### **1\. Prompt Templates and Structural Constraints**

One of the primary mechanisms of thickening is the use of **prompt templates**. A template is a meta-prompt, a structure that encapsulates an artistic vision while allowing for variable input.3 By pre-defining the aesthetic parameters—lighting, medium, composition, rendering engine—the template ensures that any specific subject inserted into it inherits a "thick" context.

These templates function as "durability structures," preserving the "wink" across multiple generations. For example, a template might enforce a specific "film stock" and "camera lens" combination (e.g., "Kodak Portra 400, 50mm f/1.4") regardless of whether the subject is a person or a landscape. This insistence on technical specificity is a form of "thick description" applied to the virtual camera, ensuring that the resulting image is not just a "picture of X" but a "photograph of X taken under Y conditions."

#### **2\. Specialized Vocabulary and Domain-Specific Language (DSL)**

Thick Prompting relies heavily on the deployment of specialized vocabulary. Prompters utilize terms from diverse technical fields—cinematography, art history, 3D rendering, biological taxonomy—to constrain the model’s output. This usage parallels the anthropologist’s need to master "local idioms" to provide a thick description.1

* **Render Terms:** "Octane Render," "Unreal Engine 5," "Ray Tracing." These terms do not describe the *content* of the image but the *physics of light* within the image. They act as style transfer functions, thickening the visual atmosphere.  
* **Art Historical Terms:** "Chiaroscuro," "Tenebrism," "Impasto." These invoke specific histories of practice, summoning not just a visual style but the cultural weight associated with it.  
* **Negative Prompting:** The exclusion of terms (e.g., "no blur," "no distortion") is a form of "boundary maintenance," defining what the thick description is *not*, thereby sharpening the definition of what it *is*.

#### **3\. Multiplying Prompts: The Dreamsheet**

A significant technological evolution in Thick Prompting is the move from the command line to the spreadsheet, exemplified by tools like **Dreamsheets**.4 This practice involves multiplying prompts across rows and columns to explore the "generative space" systematically.

In a Dreamsheet, the user does not submit a single prompt. Instead, they construct a matrix of variables. Column A might contain subjects (e.g., "cat," "dog," "bird"), while Column B contains styles (e.g., "Cyberpunk," "Art Nouveau," "Bauhaus"). The system then generates the Cartesian product of these variables. This allows the user to treat the prompt not as a singular command but as a **parametric field**.

This approach embodies "thick description" by refusing to settle for a single instance. It acknowledges that the "truth" of the generative model is not in any single output, but in the distribution of possibilities. By generating a hundred variations of a concept, the user maps the "latent manifold"—the shape of the concept within the model’s "mind." This is "Prompting for Discovery" 4, where the goal is to uncover the hidden correlations and biases of the system—to delineate the "wink" from the "blink" through repetition and variation.

#### **4\. Multimodal and Body-Based Prompting**

Thick Prompting is increasingly multimodal. Interfaces like **DeckFlow** allow users to combine text, image, and audio inputs, creating a composite signal that is "thicker" than text alone.5

* **Pixel Prompts:** The use of an initial image (img2img) provides a structural scaffolding for the generation. The text then modifies this structure.  
* **Body-Based Prompting:** Using pose-estimation (ControlNet) to dictate the geometry of a figure. Here, the "description" is somatic; the user’s own body (or a digital puppet) becomes part of the prompt.  
* **Audio Generation:** Recent tools integrate audio prompts, allowing the rhythm or timbre of a sound to influence the visual texture.5

These multimodal inputs serve to "anchor" the generation. They reduce the stochastic variance (the "hallucination") and increase the fidelity to the user’s intent. They provide a "thick" context that text alone cannot convey—the precise curve of a spine, the specific grain of a voice.

#### **5\. Prompts as Functions and Lists**

Advanced prompters often structure their inputs using functional logic. This includes the use of weighted terms (e.g., "fog::0.5"), permutation lists, and dynamic variables. This treats the prompt as code rather than prose. It is a recognition that the model processes tokens mathematically, not linguistically. By speaking the language of weights and probabilities—the "native language" of the model—the prompter achieves a thicker, more precise control over the output.8

## **II. Thick Prompting and Generative Systems**

To understand the mechanics of Thick Prompting, we must look backward to the origins of generative composition. The current technological moment is not a rupture but a continuation of a long history of algorithmic creativity, stretching back to oral tradition and classical rhetoric.

### **A. Homeric Poetry as Proto-Prompting**

The functioning of Large Language Models (LLMs)—which generate text by predicting the next token based on probabilistic weightings—bears a striking structural resemblance to the **Parry-Lord theory** of oral-formulaic composition in Homeric poetry. This theory posits that the Homeric bard (*aoidos*) did not memorize the *Iliad* and the *Odyssey* as fixed texts, but reconstructed them in performance using a vast repertoire of formulas, epithets, and narrative themes.10

#### **1\. Filling Up the Line: The Metrical Context Window**

The core constraint of the Homeric bard is the dactylic hexameter. Every line must conform to a strict rhythmic structure. To meet this constraint in real-time performance, the bard utilizes formulas—pre-fabricated phrases that fit specific metrical slots. "Swift-footed Achilles" is not just a character description; it is a metrical tool, a noun-epithet combination that fills the end of a line.

This process is strictly analogous to the generative process of an LLM "filling up the line" or the context window. The model, constrained by its training data (the tradition) and the immediate context (the meter), selects the next token that maximizes the probability of coherence.

* **The Repertoire as Latent Space:** The bard’s mental database of formulas is the "latent space." It contains the probability distribution of all possible lines.  
* **The Muse as System Prompt:** The invocation of the Muse ("Sing, Goddess, the wrath of Achilles...") serves as the "system prompt" or the "seed." It sets the thematic trajectory and the stylistic mode for the entire generation.

Historically, translators like the Earl of Surrey (c. 1540\) and John Dryden (1697) engaged in a similar practice of "filling up the line" to meet the constraints of blank verse or heroic couplets in English.10 They would expand the source text, adding adjectives or paraphrasing, to satisfy the meter. This padding is a form of "generative hallucination"—adding content that is structurally necessary but semantically distinct from the original, driven by the "prompt" of the metrical form.

#### **2\. Probabilistic and Performative Generation**

Homeric poetry is, therefore, a form of **Proto-Prompting**. The resulting poem is not a static artifact but a probabilistic performance. No two performances of the *Iliad* were identical; each was a unique traverse of the latent space of the tradition.

Thick Prompting recovers this performative dimension. When a user creates a prompt, they are not writing a text; they are initiating a performance. They are the bard invoking the Muse (the model), providing the thematic constraints (the prompt), and trusting the probabilistic engine to "fill up the line" with pixels or tokens. The "thickness" of the prompt determines the quality of the performance. A "thin" prompt leaves too much to the stochastic noise of the model (the bard stumbling for a word); a "thick" prompt provides the rich formulaic density that ensures a virtuoso performance.

### **B. Operative Ekphrasis and World-Building**

The bridge between the textual prompt and the visual output is best understood through the concept of **Operative Ekphrasis**. Traditional ekphrasis is the verbal representation of visual representation (e.g., a poem describing a painting). In generative AI, this relationship is inverted and operationalized.

#### **1\. From Representation to Operation**

Hannes Bajohr defines **Operative Ekphrasis** as the "technical substrate" of the interaction between word and image in the digital realm.12 In a multimodal AI model (like CLIP or Stable Diffusion), the text does not describe the image; it *causes* it. The description becomes an operation—a command that navigates the latent space to assemble the image.

Bajohr argues that multimodal AI "does away with the separation of mediums that is at the core of ekphrasis".12 Because the neural network processes both text and image as vectors—lists of numbers—the ontological distinction between them collapses.

* **Analog Ekphrasis:** Text and Image are distinct media.  
* **Operative Ekphrasis:** Text and Image are interchangeable data types.

This collapse means that the "thick prompt" is effectively the source code of the image. The prompt "Stiny Snity Grify" 12, a visual poem generated by code, demonstrates this. The code (the prompt) cuts and rearranges the image. The text is the operator; the image is the operand.

#### **2\. The Shield of Achilles as Emblem**

The canonical example of ekphrasis, the **Shield of Achilles** in Homer’s *Iliad*, serves as the perfect emblem for this new generative mode. Homer describes Hephaestus forging the shield, detailing the cosmos, cities, wars, and dances depicted upon its surface.

* **Narrating the Process:** Homer does not just describe the finished shield; he narrates its *creation* ("And he made on it the earth..."). This mirrors the "thick prompt," which often specifies the *process* of creation ("oil painting," "brushstrokes," "octane render") rather than just the subject.12  
* **The Impossible Object:** The Shield depicts scenes in motion—figures dancing, ploughmen turning the soil. It is a "moving image" captured in static bronze. This represents the "Ekphrastic Hope" (W.J.T. Mitchell)—the desire for language to make the image present.14

In generative AI, we literally use the "Shield of Achilles" as a prompt to test the model’s world-building capabilities.13 We ask the machine to perform the Hephaestian act of forging a world from a text. The success of this generation depends on the "thickness" of the prompt. A simple prompt ("Shield of Achilles") yields a generic bronze disk. A "thick" prompt—detailing the cities, the constellations, the ploughmen—attempts to force the model to replicate the narrative density of Homer’s world.

#### **3\. Imagetext and Worldtext**

This leads to the concepts of **Imagetext** and **Worldtext**.

* **Imagetext:** The composite unit of the prompt-and-image. They are "inextricably composed".15 The image cannot be understood without the prompt that generated it; the prompt is fulfilled only in the image.  
* **Worldtext:** A text that contains the potentiality of a world. The *Iliad* is a Worldtext.16 A complex RPG rulebook is a Worldtext. A "thick prompt" is a micro-Worldtext.

The core idea is that "Language makes worlds here by compiling symbolic acts into durable structures that feel inevitable".3 The thick prompt compiles the symbolic acts of the user into the durable structure of the generated image.

### **C. Distinction of Terms: Worldbuilding vs. World Assembly**

While "Worldbuilding" is the dominant metaphor for creative consistency, the mechanics of generative AI suggest a rival concept: **World Assembly**.

#### **1\. Worldbuilding: The Coherent Whole**

Worldbuilding implies a top-down, architectonic approach. It focuses on internal consistency, history, geography, and the "laws" of the fictional universe. It is the "thick" realization of a singular vision. Homer *builds* a world on the Shield.

#### **2\. World Assembly: The Modular Aggregate**

"World Assembly," a term appearing in media theory via Lev Manovich and Larissa Hjorth, refers to the "externalizing of the internal" and the aggregation of disparate elements.18 It aligns with the logic of the "Asset Store" in game design—assembling a scene from pre-made models, textures, and scripts.19

Generative AI functions primarily as a machine of **World Assembly**. It does not invent from first principles; it assembles from the "parts bin" of the training data. It stitches together a nose from dataset A, a lighting style from dataset B, and a composition from dataset C.

* **The Blink:** World Assembly. The uncritical aggregation of cliches and statistical averages. The "default" output of the model.  
* **The Wink:** Worldbuilding. The imposition of a coherent, "thick" vision that forces the assembly machine to transcend its modular nature and produce a unified artifact.

Thick Description is the tool that allows the user to navigate from Assembly to Building. It is "How to know it's a wink and not a blink".21 By providing enough constraints and context, the prompter forces the model to assemble the parts in a way that *simulates* a coherent world, rather than just a pile of assets.

## **III. Philosophical Grounding: The Picture as Model**

To fully grasp the ontological status of the "thick prompt," we must turn to the philosophy of language and science, specifically the connection between Ludwig Wittgenstein’s picture theory of meaning and the scientific models of Heinrich Hertz and Ludwig Boltzmann. This lineage provides a rigorous framework for understanding how a text (a prompt) can be a model of reality (an image).

### **A. The Wittgensteinian Proposition**

In the *Tractatus Logico-Philosophicus* (1921), Wittgenstein famously proposes a "picture theory" of meaning.

* **T 2.1:** "We make to ourselves pictures of facts."  
* **T 2.12:** "The picture is a model of reality."  
* **T 2.1512:** "It is laid against reality like a measure." 22

Wittgenstein argues that a proposition (a sentence) represents a state of affairs in the world because it shares a **logical form** with that state of affairs. It is an isomorphism: the elements of the proposition relate to one another in the same way that the elements of the fact relate to one another.

This is not a metaphor. Wittgenstein, trained as an engineer in Berlin and Manchester 23, was thinking of engineering drawings and models. A proposition is a "working model" of reality.

### **B. Hertz & Boltzmann’s Models (via Sterrett)**

The scholar Susan Sterrett has convincingly demonstrated that Wittgenstein’s concept of the "picture" was directly influenced by the mechanics of **scale models** in engineering, a concept he encountered through the work of physicists Heinrich Hertz and Ludwig Boltzmann.22

#### **1\. Mental Models vs. Experimental Models**

In 1902, Ludwig Boltzmann made a crucial distinction between two types of models:

* **Mental Models (Images):** Internal, psychological constructs used for visualization. These are "thoughts."  
* **Experimental Models:** Physical artifacts constructed to replicate the behavior of a larger system (e.g., a scale model of a ship towed through a tank, or a wind tunnel model).22

Sterrett argues that Wittgenstein’s "proposition" aligns with the **Experimental Model**. An engineering scale model does not need to look exactly like the object it represents (it might be made of clay instead of steel, or be 1/100th the size). However, it must preserve the **dimensionless groups** (ratios of physical quantities, like the Reynolds number) that govern the system's behavior.24 If the ratios are preserved, the model is "dynamically similar" to the reality, and one can predict the behavior of the real ship by observing the model.

#### **2\. The Tractatus as Experimental Modeling**

Wittgenstein’s insight was that language functions like a scale model. A sentence "constructs a world experimentally" (*probeweise*).24

* "These correlations are, as it were, the feelers of the picture's elements, with which the picture touches reality." (T 2.1515).

#### **3\. The Thick Prompt as Experimental Model**

This philosophical detour is essential for understanding Thick Prompting. The "thick prompt" is an **Experimental Model** of the image.

* **The Reality:** The "reality" in generative AI is the **Latent Space**—the high-dimensional vector space containing all possible images.  
* **The Measure:** The prompt is "laid against" this latent reality "like a measure."  
* **Dynamical Similarity:** A successful thick prompt establishes a "dynamical similarity" between the text and the latent space. By specifying the correct parameters (lighting, style, composition), the prompter ensures that the "simulation" runs correctly.

When a user writes a prompt with "specialized vocabulary" (e.g., "f/1.8," "volumetric fog"), they are defining the **dimensionless groups** of the generation. They are setting the physics of the virtual world. If the prompt is "thin," the model lacks the necessary constraints to simulate the reality accurately—it is like a scale model ship with the wrong hull shape. The "thick" prompt ensures that the textual model and the visual reality are isomorphic.

## **IV. Correlates: Image, Text, and World**

The convergence of Thick Prompting, Operative Ekphrasis, and Philosophical Modeling leads us to a new understanding of the correlates between image, text, and world in the algorithmic age.

### **A. The Inextricable Relationship: Imagetext**

W.J.T. Mitchell’s concept of **imagetext** posits that the visual and the verbal are never truly separate; they are always "inextricably composed".15 In the context of AI, this is literally true. The generative model does not see "text" and "image"; it sees token embeddings and latent vectors. The "prompt" and the "image" are two faces of the same data object—a collapsed **imagetext**.

The prompt is the *genotype* of the imagetext; the generated image is the *phenotype*. Thick prompting is the art of manipulating the genotype to produce a specific phenotype. It acknowledges that there is no "pure" image without the text that summoned it, and no "pure" text without the visual potentiality it encodes.

### **B. Analogies and Correlates**

We can map these relationships through a series of structural correlates:

| Domain | Source / Genotype | Mediator / Process | Artifact / Phenotype | Concept |
| :---- | :---- | :---- | :---- | :---- |
| **Traditional Ekphrasis** | Visual Art (The Urn) | The Poet's Perception | The Poem (Text) | Representation |
| **Operative Ekphrasis** | The Poem (Prompt) | The Algorithm (Model) | The Image (Visual) | Operation / Causality |
| **Philosophy (Tractatus)** | The Fact | Logical Form | The Picture/Model | Isomorphism |
| **Generative AI** | **Thick Prompt** | **Latent Space** | **Generated World** | **Simulation** |

* **Image : Imagetext :: World Model : Worldtext** Just as the image is inextricably bound to the text in **imagetext**, the "World Model" (the internal simulation of the AI) is bound to the **worldtext** (the thick prompt or the corpus).16  
  * **Worldtext:** A text that contains the parameters for a world. The *Iliad* is a Worldtext. A dense prompt is a Worldtext.  
  * **World Model:** The functioning simulation that results from executing the worldtext.

### **C. Imagetext as a "Collapsing" Process**

The generative process is a "collapsing" of the imagetext.12

1. **Source Text:** The poem or thick prompt acts as the initial condition.  
2. **Intermediary Representation:** This text is converted into a mathematical representation (JSON, vector embeddings). This is the "logical form" of the model.  
3. **Generation:** The model "collapses" the probability wave of the latent space into a specific image.

In traditional ekphrasis, the poem *expands* on the image, adding time and narrative to a static object. In **operative ekphrasis** (AI), the process is often a *compression* or *collapse*. The infinite potential of the "thick prompt" is collapsed into a single, static image (or a series of images). The "thick description" of the user is translated into the "thick" pixels of the machine.

However, the "thickness" of the prompt ensures that this collapse is not a loss of meaning, but a crystallization of it. By encoding the "idea of the image" and "how I got it" 3 into the prompt, the user ensures that the final image carries the traces of its textual DNA. It becomes an artifact that "feels inevitable" 12, a durable structure forged from symbolic acts.

## **V. Detailed Analysis of Key Concepts**

### **A. The "Thick" in Thick Prompting: A Deeper Dive**

The appropriation of Geertz’s "thick description" for prompt engineering is not merely metaphorical; it is structural. Geertz argued that culture is an "acted document" and that the analysis of it is "guessing at meanings, assessing the guesses, and drawing explanatory conclusions from the better guesses".1 In generative AI, the model is the "culture" (an aggregation of human cultural production). The prompter is the ethnographer.

* **Guessing at Meanings:** The prompter "guesses" which combination of tokens will trigger the desired latent representation.  
* **Assessing the Guesses:** The generation of the image is the "assessment." Did the model "understand"? Was it a wink or a blink?  
* **Thick Prompting as Ethnography:** The expert prompter, like the ethnographer, must master the "local idioms" of the model.1 They must know that "Unreal Engine" means "high fidelity lighting" in the local dialect of Midjourney, or that "octane render" implies a specific type of glossy 3D aesthetic. This is "thick" knowledge—knowledge of the context and the semiotic web of the latent space.

### **B. Dreamsheets and the Spatialization of Prompting**

The **Dreamsheet** interface 4 represents a crucial technological embodiment of thick prompting. By spatializing the prompt—turning it from a command line into a two-dimensional grid—it allows for **generative space exploration**.5

* **The Grid as Repertoire:** The rows and columns of the Dreamsheet function like the "repertoire" of the Homeric bard. They allow the user to substitute variables (formulas) into the prompt structure (the meter).  
* **Sense-Making:** The visualization of multiple outputs side-by-side allows the user to build a "mental model" of the generative space.5 They can see the "causal" relationship between specific words and specific visual changes. This turns the "black box" of the AI into a "glass box" of experimental modeling. The user is "calibrating" their experimental model (the prompt) against the reality of the machine.

### **C. The Shield of Achilles: The Ultimate Generative Artifact**

Let us return to the **Shield of Achilles** as the ultimate case study.

Homer’s description is "operative" because it describes actions that *make* the image.

* "He made the earth..." (Action \-\> Object)  
* "And upon it he wrought two cities..." (Action \-\> Object)

When a user prompts an AI to "generate the Shield of Achilles as described by Homer," they are activating a "worldtext." However, the AI often fails to capture the "thickness" of Homer's description—the movement, the sound, the narrative.13 The "Thick Prompt" for the Shield must therefore go beyond the label. It must structurally replicate Homer’s method. It must prompt for *process*: "A bronze shield being forged, depicting a city at peace with weddings and festivals, intricate embossing, cinematic lighting..." The failure or success of this prompt reveals the gap between **Worldbuilding** (Homer's narrative coherence) and **World Assembly** (the AI's visual collage). The AI tends to "assemble" the shield from training data of *pictures of shields*, rather than *building* it from the narrative logic of the text. Thick prompting is the attempt to force the AI to build, not just assemble.

## **VI. Conclusion: The Future of the Thick Prompt**

The trajectory of generative AI suggests a move toward ever-thicker prompting. As models become more capable, the "thin" prompt ("show me a cat") becomes trivial. The value shifts to the "thick" prompt—the prompt that encodes a unique vision, a specific aesthetic lineage, and a complex world model.

Thick prompting serves as the bridge between human intentionality and machine stochasticity. It is the mechanism by which we impose meaning (the wink) onto the statistical noise (the blink). By understanding the prompt as an **experimental model** (in the Hertzian/Wittgensteinian sense) and an act of **operative ekphrasis**, we can begin to treat prompt engineering not as a technical hack, but as a genuine form of 21st-century rhetoric and world-making.

In the end, the "thick prompt" is a **worldtext**. It is a compact, dense, linguistic structure that contains the potential energy of a world. Like the Shield of Achilles, it is an artifact that "communicates the image, and the idea of the image, and how I got it all at the same time".3 It is the durable structure that makes the probabilistic dream of the machine feel, for a moment, inevitable.

## ---

**Detailed Discussion and Analysis**

### **1\. The Semiotic Density of the Prompt**

The transition from "thin" to "thick" prompting marks a maturation in the human-computer interaction paradigm for generative media.

* **Thin Prompting:** Instrumental, utilitarian, focused on retrieval. (e.g., Google Search queries).  
* **Thick Prompting:** Expressive, constitutive, focused on creation and context.

Geertz's notion that "man is an animal suspended in webs of significance he himself has spun" 1 is aptly applied to the prompter suspended in the "webs of probability" of the neural network. The "thick prompt" is the tool for navigating these webs. It requires "patience and a knowledge of details".2 The "Prompt Artist" P6 exemplifies this: they do not just want an image; they want the *concept* of the image and the *story* of its generation.3 The prompt is a "narrative of production."

### **2\. The Wittgenstein-Hertz-Boltzmann Nexus**

The application of Sterrett’s analysis of Wittgenstein to AI is a novel theoretical insight.

* **The Standard View:** AI generation is "associative" or "hallucinatory."  
* **The Model View:** AI generation is "experimental modeling." The latent space of the AI obeys certain "laws" (statistical correlations). The prompt sets up a "physical system" (a configuration of vectors) within that space. If the prompt (the model) is "dynamically similar" to the desired output (the reality), the generation will be successful. This aligns with Boltzmann's view of the **experimental model**: a physical artifact that functions as a calculating device.24 The prompt is a "textual machine" that calculates the image.

### **3\. World Assembly and the Asset Economy**

The distinction between Worldbuilding and World Assembly is critical for the political economy of AI art.

* **World Assembly** 18 implies a commodified, modular approach. It resonates with the "Asset Store" logic of game design (Unity/Unreal), where worlds are cobbled together from pre-made packs. AI often defaults to this mode—assembling generic assets (the "Greg Rutkowski" style, the "Cyberpunk" aesthetic) into a pastiche.  
* **Worldbuilding** implies a holistic, bespoke creation.  
  **Thick Prompting** is the resistance against the "Asset Store" logic of World Assembly. By using highly specific, domain-dependent, and "thick" descriptions, the prompter forces the model to transcend the generic assembly of parts and achieve the coherent "worldness" of true Worldbuilding.

### **4\. Operative Ekphrasis as the New Poetics**

Operative Ekphrasis 12 redefines the role of the poet/writer. The writer is no longer just a descriptor of the world, but a **programmer of the visual**. The "collapse" of text and image means that literary skills (metaphor, allusion, tone) become directly convertible into visual outputs. The "Shield of Achilles" is no longer just a literary trope; it is a **prompt engineering challenge**. Can you write a text that *forces* a machine to simulate the cosmos? This is the "Ekphrastic Hope" (Mitchell) realized: the hope that the difference between the verbal and the visual can be overcome.14 In AI, it is overcome—but at the cost of the distinction itself. The text *is* the image, in its larval, operative form.

## **Summary of Key Findings**

1. **Thick Prompting is "Thick Description" applied to the Latent Space.** It involves encoding context, intent, and process into the input, distinguishing the "wink" of art from the "blink" of random generation.  
2. **Homeric Poetry is a Proto-Generative System.** The oral-formulaic method of "filling up the line" with a repertoire of formulas is structurally homologous to LLM token prediction.  
3. **The Prompt is an Experimental Model.** Following Wittgenstein and Sterrett, the prompt functions like an engineering scale model—a working simulation "laid against" the reality of the latent space to predict/generate a result.  
4. **Operative Ekphrasis collapses Text and Image.** In multimodal AI, description becomes operation. The text causes the image.  
5. **Worldbuilding vs. World Assembly.** Generative AI defaults to "World Assembly" (modular aggregation); "Thick Prompting" strives for "Worldbuilding" (coherent holistic creation).  
6. **The Prompt is Art.** As per P6, the prompt is not just a tool but part of the aesthetic object—an "imagetext" that contains the "idea of the image."

---

**Table 1: The Spectrum of Description in Generative AI**

| Feature | Thin Prompting | Thick Prompting |
| :---- | :---- | :---- |
| **Goal** | Retrieval / Utility | Expression / Art / "The Idea" |
| **Structure** | Keyword Concatenation | Narrative / DSL / Templates |
| **Ontology** | Command | Artifact / Imagetext |
| **Geertzian Analogy** | "The Blink" (Physiological) | "The Wink" (Semiotic) |
| **Theoretical Model** | Search Query | Experimental Model (Boltzmann) |
| **Relationship to Image** | Separate Input | Inextricable Part of the Work |
| **Example** | "cool car" | "Cyberpunk vehicle, octane render, volumetric fog, wide angle..." |

**Table 2: Models of Reality (Boltzmann/Hertz/Wittgenstein)**

| Model Type | Nature | Function | AI Equivalent |
| :---- | :---- | :---- | :---- |
| **Mental Model (Image)** | Internal / Visualization | To conceive of facts | The User's Imagination |
| **Experimental Model** | Physical / Dynamic | To replicate behavior / Calculate | **The Thick Prompt** (Simulates the image) |
| **The Reality** | The Physical World | To be measured/predicted | **The Latent Space** (The physics of the AI) |

The report demonstrates that "Thick Prompting" is not merely a technique but a new mode of cultural production that synthesizes ancient poetics, modern philosophy of science, and cutting-edge machine learning into a coherent practice of "World-Making."

#### **Works cited**

1. Thick Description: Methodology \- Minerva Project, accessed January 26, 2026, [https://course-resources-uae.minervaproject.com/uploaded\_files/production-uae/00412197-0948/luhrmann-thick-description.pdf](https://course-resources-uae.minervaproject.com/uploaded_files/production-uae/00412197-0948/luhrmann-thick-description.pdf)  
2. Thick description: moving beyond the thin soap, accessed January 26, 2026, [https://www.su.se/download/18.6f0acc5f19a7bc9dc1f56fe3/1764612184406/Alvesson,%20Mats,%20Thick%20description:%20Moving%20beyond%20the%20thin%20soapAlvesson.Thick%20description.6.10.23.pdf](https://www.su.se/download/18.6f0acc5f19a7bc9dc1f56fe3/1764612184406/Alvesson,%20Mats,%20Thick%20description:%20Moving%20beyond%20the%20thin%20soapAlvesson.Thick%20description.6.10.23.pdf)  
3. The Prompt Artists \- UCSB MAT, accessed January 26, 2026, [https://www.mat.ucsb.edu/\~g.legrady/academic/courses/24f255/promptArtists.pdf](https://www.mat.ucsb.edu/~g.legrady/academic/courses/24f255/promptArtists.pdf)  
4. Flexible Sense-Making for AI Art-Making with Dreamsheets \- arXiv, accessed January 26, 2026, [https://arxiv.org/abs/2310.09985](https://arxiv.org/abs/2310.09985)  
5. DeckFlow: Specification Decomposition on a Multimodal Generative ..., accessed January 26, 2026, [https://guoanhong.com/papers/VLHCC25-DeckFlow.pdf](https://guoanhong.com/papers/VLHCC25-DeckFlow.pdf)  
6. Prompting for Discovery: Flexible Sense-Making for AI Art-Making ..., accessed January 26, 2026, [https://www.researchgate.net/publication/380526039\_Prompting\_for\_Discovery\_Flexible\_Sense-Making\_for\_AI\_Art-Making\_with\_Dreamsheets?\_tp=eyJjb250ZXh0Ijp7InBhZ2UiOiJzY2llbnRpZmljQ29udHJpYnV0aW9ucyIsInByZXZpb3VzUGFnZSI6bnVsbCwic3ViUGFnZSI6bnVsbH19](https://www.researchgate.net/publication/380526039_Prompting_for_Discovery_Flexible_Sense-Making_for_AI_Art-Making_with_Dreamsheets?_tp=eyJjb250ZXh0Ijp7InBhZ2UiOiJzY2llbnRpZmljQ29udHJpYnV0aW9ucyIsInByZXZpb3VzUGFnZSI6bnVsbCwic3ViUGFnZSI6bnVsbH19)  
7. DeckFlow: Iterative Specification on a Multimodal Generative Canvas, accessed January 26, 2026, [https://austinhenley.com/pubs/Croisdale2025VLHCC\_DeckFlow.pdf](https://austinhenley.com/pubs/Croisdale2025VLHCC_DeckFlow.pdf)  
8. Prompting Generative AI with Interaction-Augmented Instructions, accessed January 26, 2026, [https://www.researchgate.net/publication/389581349\_Prompting\_Generative\_AI\_with\_Interaction-Augmented\_Instructions](https://www.researchgate.net/publication/389581349_Prompting_Generative_AI_with_Interaction-Augmented_Instructions)  
9. Axes-and-Tags: LLM-Driven Design Galleries for Generative Content, accessed January 26, 2026, [https://openaccess.thecvf.com/content/ICCV2025W/HiGen/papers/Gupta\_Axes-and-Tags\_LLM-Driven\_Design\_Galleries\_for\_Generative\_Content\_ICCVW\_2025\_paper.pdf](https://openaccess.thecvf.com/content/ICCV2025W/HiGen/papers/Gupta_Axes-and-Tags_LLM-Driven_Design_Galleries_for_Generative_Content_ICCVW_2025_paper.pdf)  
10. Habent sua fata libelli: Studies in Book History, the Classical ..., accessed January 26, 2026, [https://dokumen.pub/habent-sua-fata-libelli-studies-in-book-history-the-classical-tradition-and-humanism-in-honor-of-craig-kallendorf-9004463410-9789004463417.html](https://dokumen.pub/habent-sua-fata-libelli-studies-in-book-history-the-classical-tradition-and-humanism-in-honor-of-craig-kallendorf-9004463410-9789004463417.html)  
11. Twentieth-Century Poetic Translation : Literary Cultures in Italian ..., accessed January 26, 2026, [https://dokumen.pub/twentieth-century-poetic-translation-literary-cultures-in-italian-and-english-1nbsped-9781441129369-9781847060037.html](https://dokumen.pub/twentieth-century-poetic-translation-literary-cultures-in-italian-and-english-1nbsped-9781441129369-9781847060037.html)  
12. Operative ekphrasis: The collapse of the text/image ... \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/publication/372400146\_Operative\_ekphrasis\_The\_collapse\_of\_the\_textimage\_distinction\_in\_multimodal\_AI\_PLEASE\_REFER\_TO\_PUBLISHED\_VERSION](https://www.researchgate.net/publication/372400146_Operative_ekphrasis_The_collapse_of_the_textimage_distinction_in_multimodal_AI_PLEASE_REFER_TO_PUBLISHED_VERSION)  
13. IMAGE. Zeitschrift für interdisziplinäre Bildforschung (1/2023), accessed January 26, 2026, [https://www.researchgate.net/profile/Lukas-Wilde/publication/371155801\_Generative\_Imagery\_Towards\_a\_'New\_Paradigm'\_of\_Machine\_Learning-Based\_Image\_Production/links/6475fb746fb1d1682b1cc99c/Generative-Imagery-Towards-a-New-Paradigm-of-Machine-Learning-Based-Image-Production.pdf?origin=scientificContributions](https://www.researchgate.net/profile/Lukas-Wilde/publication/371155801_Generative_Imagery_Towards_a_'New_Paradigm'_of_Machine_Learning-Based_Image_Production/links/6475fb746fb1d1682b1cc99c/Generative-Imagery-Towards-a-New-Paradigm-of-Machine-Learning-Based-Image-Production.pdf?origin=scientificContributions)  
14. AI Generative Art as Algorithmic Remediation \- media/rep, accessed January 26, 2026, [https://mediarep.org/bitstreams/db11c2d8-a3c1-427d-911e-7bd788e5facd/download](https://mediarep.org/bitstreams/db11c2d8-a3c1-427d-911e-7bd788e5facd/download)  
15. Partners of Zaynab : a gendered perspective of Shia Muslim faith ..., accessed January 26, 2026, [https://dokumen.pub/partners-of-zaynab-a-gendered-perspective-of-shia-muslim-faith-9781611173772-1611173779-9781611173789-1611173787.html](https://dokumen.pub/partners-of-zaynab-a-gendered-perspective-of-shia-muslim-faith-9781611173772-1611173779-9781611173789-1611173787.html)  
16. Diffractive Reading: New Materialism, Theory, Critique 1786613964 ..., accessed January 26, 2026, [https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html](https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html)  
17. BRANHAM, B. (Ed.) \- Bakhtin and The Classics \- Scribd, accessed January 26, 2026, [https://www.scribd.com/document/566071450/BRANHAM-B-Ed-Bakhtin-and-the-Classics](https://www.scribd.com/document/566071450/BRANHAM-B-Ed-Bakhtin-and-the-Classics)  
18. Taylor & Francis Not for distribution \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/profile/Larissa-Hjorth-2/publication/286337829\_OnlineAsiaPacific\_Mobile\_social\_and\_locative\_media\_in\_the\_Asia-Pacific/links/5d25b19aa6fdcc2462d079ef/OnlineAsiaPacific-Mobile-social-and-locative-media-in-the-Asia-Pacific.pdf](https://www.researchgate.net/profile/Larissa-Hjorth-2/publication/286337829_OnlineAsiaPacific_Mobile_social_and_locative_media_in_the_Asia-Pacific/links/5d25b19aa6fdcc2462d079ef/OnlineAsiaPacific-Mobile-social-and-locative-media-in-the-Asia-Pacific.pdf)  
19. Methodologies for Evaluating Interaction Cues for Virtual Reality, accessed January 26, 2026, [https://stars.library.ucf.edu/cgi/viewcontent.cgi?article=2911\&context=etd2020](https://stars.library.ucf.edu/cgi/viewcontent.cgi?article=2911&context=etd2020)  
20. Hospitality brands examples Dela, Zaposlitev | Freelancer, accessed January 26, 2026, [https://www.freelancer.si/job-search/hospitality-brands-examples/2](https://www.freelancer.si/job-search/hospitality-brands-examples/2)  
21. What's in a Wink? The Case for Thick Description, accessed January 26, 2026, [https://www.duckofminerva.com/2019/09/whats-in-a-wink-the-case-for-thick-description.html](https://www.duckofminerva.com/2019/09/whats-in-a-wink-the-case-for-thick-description.html)  
22. Another New Wittgenstein \- Philosophie – TU Darmstadt, accessed January 26, 2026, [https://www.philosophie.tu-darmstadt.de/media/institut\_fuer\_philosophie/mitarbeiter\_innen/nordmann\_1/pdfs\_2/newwittgenstein.pdf](https://www.philosophie.tu-darmstadt.de/media/institut_fuer_philosophie/mitarbeiter_innen/nordmann_1/pdfs_2/newwittgenstein.pdf)  
23. (PDF) Visualisation and Wittgenstein's “Tractatus” \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/publication/251469549\_Visualisation\_and\_Wittgenstein's\_Tractatus](https://www.researchgate.net/publication/251469549_Visualisation_and_Wittgenstein's_Tractatus)  
24. (PDF) Physical Pictures: Engineering Models circa 1914 and in ..., accessed January 26, 2026, [https://www.researchgate.net/publication/36443747\_Physical\_Pictures\_Engineering\_Models\_circa\_1914\_and\_in\_Wittgenstein's\_Tractatus](https://www.researchgate.net/publication/36443747_Physical_Pictures_Engineering_Models_circa_1914_and_in_Wittgenstein's_Tractatus)  
25. Machine learning for assembly modeling in computer-aided design, accessed January 26, 2026, [https://opus.bibliothek.uni-augsburg.de/opus4/files/118615/Lenzen\_Diss.pdf](https://opus.bibliothek.uni-augsburg.de/opus4/files/118615/Lenzen_Diss.pdf)