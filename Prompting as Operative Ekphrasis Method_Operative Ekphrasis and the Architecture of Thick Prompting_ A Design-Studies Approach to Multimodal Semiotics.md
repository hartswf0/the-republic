# **Operative Ekphrasis and the Architecture of Thick Prompting: A Design-Studies Approach to Multimodal Semiotics**

## **Abstract**

The convergence of natural language processing and computer vision in multimodal Artificial Intelligence (AI) has precipitated a fundamental collapse of the classical distinction between text and image. This report investigates this collapse through the lens of **Operative Ekphrasis**, a concept articulated by Hannes Bajohr, which posits that in generative systems, text no longer merely describes visual artifacts but actively performs them. By reframing the prompt not as a caption but as an executable command, we establish a theoretical foundation for **Thick Prompting**—a methodology that synthesizes Clifford Geertz’s interpretive anthropology with modern design systems. This research argues that Thick Prompting serves a dual function: first, as an interpretive lens that decodes the "stratified hierarchy of meaningful structures" embedded within the "worldtext" of latent space; and second, as a rigorous design-studies method that utilizes structured constraints (JSON, design tokens, and invariants) to control the generative "twitch" and transform it into a communicative "wink." Through an exhaustive analysis of historical aesthetics (Lessing, Homer), contemporary theory (Mitchell, Krieger), and technical workflows (Flux, Stable Diffusion), this report delineates how the "operative" nature of the prompt enables a new mode of creative production where the boundaries between code, culture, and image are irrevocably fused.

## ---

**1\. Introduction: The Operative Turn**

The current epoch of digital production is marked by a profound ontological shift in the relationship between the verbal and the visual. For centuries, Western aesthetics has been governed by a separation of the arts—the *paragone*—which held that poetry (text) and painting (image) occupied distinct semiotic and sensory domains. This separation, codified most famously by Gotthold Ephraim Lessing in the 18th century, posited a boundary that could only be crossed through the rhetorical device of **ekphrasis**: the verbal representation of visual representation.1 In this classical paradigm, the text could describe the image, but it could never *be* the image, nor could it cause the image to exist absent a human intermediary.

The advent of multimodal Artificial Intelligence (AI)—specifically large-scale text-to-image models such as DALL-E, Midjourney, and Flux—has dismantled this boundary. In the computational substrate of these models, text and image are processed as a single data type: vectors in a high-dimensional latent space.3 This technological convergence effects a "collapse of the text/image distinction" 3, creating a condition where the input text stands in a causal, rather than merely mimetic, relationship to the output image. Hannes Bajohr designates this new condition as **Operative Ekphrasis**.3 In this regime, the prompt is not a description; it is an operation. It is the code that performs the generation.

However, the "operative" capability of the prompt does not inherently guarantee meaning or aesthetic intent. A raw instruction to a model often yields generic, culturally unmoored results—what Clifford Geertz, in his anthropological theory, would characterize as a mere "twitch" rather than a meaningful "wink".6 To navigate the vast, probabilistic "heterocosm" 7 of the AI’s training data, a new methodological approach is required. This report proposes **Thick Prompting** as that approach.

Thick Prompting is not merely "detailed" prompting. It is a rigorous application of Geertz’s "thick description"—the effort to interpret and encode the complex web of cultural significations—applied to the generative process. It acknowledges that the AI model is not a neutral tool but a "worldtext" 8 containing a stratified hierarchy of meaningful structures derived from human culture. By reframing the prompt as operative ekphrasis, Thick Prompting becomes both a hermeneutic tool for investigating the model’s internal biases and logic, and a design method for imposing structured intent upon the chaotic fluidity of latent space.

This report will explore the theoretical underpinnings of this shift, tracing the genealogy of the "operative" from Homer’s Shield of Achilles to the JSON-structured prompts of contemporary diffusion models. It will examine specific artifacts, such as Dave Orr’s *Stiny Snity Grify* 3, to demonstrate the return of semantics in connectionist systems. Finally, it will outline a practical framework for Thick Prompting, utilizing concepts from design systems—such as tokens, invariants, and constraints—to transform the prompt into a precise instrument of cultural production.

## ---

**2\. Theoretical Framework: The Genealogy of the Operative**

To fully grasp the implications of operative ekphrasis, one must situate it within the long history of aesthetic theory concerning the relationship between word and image. The disruption caused by AI is not merely technical; it is a philosophical rupture that overturns centuries of aesthetic dogma regarding the limits of representation.

### **2.1 Lessing’s *Laocoön* and the Space/Time Divide**

The foundational text for the separation of word and image is Lessing’s 1766 treatise, *Laocoön: An Essay on the Limits of Painting and Poetry*. Lessing’s central argument was semiotic: poetry uses "arbitrary signs" arranged in time (*nacheinander*), while painting uses "natural signs" arranged in space (*nebeneinander*).9 Because of this fundamental difference in medium, Lessing argued that poetry should focus on actions (which happen in time), and painting should focus on bodies (which exist in space).

For Lessing, the encroachment of one art form onto the other’s territory resulted in confusion and bad art. He critiqued the descriptive poets of his day for attempting to paint with words, arguing that a detailed verbal description of a physical object fails because the reader cannot mentally assemble the sequential parts into a simultaneous whole.10 The "fruitful moment" in visual art was the selection of a single, static instant that implied the action before and after, but the medium itself remained resolutely spatial and static.9

Multimodal AI fundamentally violates Lessing’s boundary conditions. The prompt—a sequence of words, processed in time—instantly manifests a spatial object. The "process" of the prompt is collapsed into the "object" of the generation. In the diffusion process, we even see a literal inversion of Lessing’s logic: the image is generated *over time* (denoising steps), evolving from chaotic noise to structured spatial coherence based on the temporal input of the text.12 The "arbitrary signs" of language (the tokens of the prompt) are mathematically transmuted into the "natural signs" of the image (pixels and shapes).

This violation suggests that operative ekphrasis is not just a new technique but a new *medium* that fuses the temporal capability of poetry with the spatial capability of painting. The prompt allows the user to narrate the *construction* of the image, bridging the gap Lessing thought unbridgeable.

### **2.2 The Shield of Achilles: The Proto-Operative**

If Lessing represents the boundary, Homer represents the transgression. The archetypal example of ekphrasis is the description of the **Shield of Achilles** in Book 18 of the *Iliad*.9 Homer does not describe the finished shield as a static object on a museum shelf. Instead, he narrates the *process* of its creation by the god Hephaestus. He describes the metals being poured, the layers being hammered, and the scenes being wrought into existence one by one.9

"And first he fashioned a shield, great and sturdy, adorning it cunningly in every part..." 9

Scholars have noted that Homer’s description contains movement and sound—figures on the shield are described as moving, ploughing, and fighting—effects that are impossible in a static metal relief.13 Homer solves the problem of describing a spatial object in a temporal medium by turning the description into a *narrative of making*.

This is precisely the mode of **Operative Ekphrasis**. In generative AI, the prompter assumes the role of Hephaestus. The prompt is a set of instructions for fabrication. We do not describe the object; we describe the *making* of the object. We specify the materials ("bronze," "gold," or "octane render," "oil painting"), the method ("hammered," "woven," or "digital painting," "photograph"), and the content.

The "operative" nature of the prompt resurrects the Homeric mode. Just as Hephaestus’s act of creation is the vehicle for the shield’s existence in the poem, the prompt’s execution is the vehicle for the image’s existence in the digital substrate. The distinction between the *process* of creation and the *object* of creation is dissolved; the text *is* the tool of manufacture. However, a crucial difference remains: Homer’s Shield is a fixed literary object, whereas the AI’s output is probabilistic and fluid. The prompt navigates a "concept of 'shieldness'" 15 rather than forging a singular, immutable artifact.

### **2.3 Mitchell’s ImageText and the Struggle for Meaning**

W.J.T. Mitchell’s concept of the **ImageText** provides a modern theoretical grounding for this convergence. Mitchell argued against the essentialist separation of word and image, suggesting instead that all media are mixed media.16 He characterized the relationship between word and image as a "struggle" for dominance—a dialectic where text attempts to colonize the visual (as in iconology) or the visual attempts to evade the textual (as in abstract expressionism).16

In multimodal AI, this "struggle" is resolved—or perhaps intensified—through mathematical integration. The architecture of models like CLIP (Contrastive Language-Image Pre-training) is designed to minimize the distance between text embeddings and image embeddings in a shared latent space.3 The "struggle" is operationalized as a loss function; the model learns to make the image and the text mathematically equivalent.

This creates a "composite art" 20 where the two semiotic systems are inextricably fused. However, Mitchell also warned of the "tyranny of the picture" 21 and the illusion that images are "natural signs" (unmediated copies of reality).2 Murray Krieger’s work on ekphrasis as the "illusion of the natural sign" 2 is pertinent here. AI images often present themselves as hyper-realistic "photographs," seducing the viewer into believing they are unmediated captures of reality. Operative Ekphrasis exposes this illusion. It reveals that the image is entirely dependent on the "arbitrary" and "conventional" code of the prompt. The image is not a natural sign; it is a calculated output of a linguistic operation.

## ---

**3\. Interpretive Lens: Thick Prompting in the Latent Heterocosm**

If Operative Ekphrasis is the mechanism, **Thick Prompting** is the method of engaging with it. To define this method, we turn to Clifford Geertz’s interpretive anthropology, specifically his distinction between "thin" and "thick" description.6

### **3.1 Geertzian Mechanics: Twitch vs. Wink**

Geertz famously uses the example of two boys rapidly contracting their right eyelids. Physically, the movements are identical. A "thin description" records this physical event: "rapidly contracting the right eyelid." However, one boy might be having an involuntary **twitch**, while the other might be communicating a conspiratorial signal to a friend—a **wink**.6

The difference between a twitch and a wink is vast. A wink is:

1. Deliberate.  
2. Directed to someone.  
3. Intended to impart a message.  
4. According to a socially established code.  
5. Performative.6

In the context of AI, a **"thin prompt"** generates a twitch. It is a raw, transactional retrieval of data. If a user prompts "a dog," the AI accesses a statistical cluster of "dog-ness" and outputs a generic representation. This output is involuntary in the sense that it relies on the default weights of the model without conscious direction or cultural specificity. It is a "phenomenalistic" observation of the training data.6

A **"thick prompt"**, conversely, orchestrates a wink. It acknowledges the "public code" of culture embedded in the model.6 It is not enough to ask for a dog; one must ask for a dog that *signifies*. A thick prompt places the object within a "stratified hierarchy of meaningful structures".6 It specifies the genre, the medium, the emotional tone, the lighting, and the cultural context.

**Thin Prompt:** "A photo of a cyberpunk city." (The AI twitches: it outputs generic neon signs and rain, a stereotype derived from the mean of the dataset.)

**Thick Prompt:** "A wide-angle establishing shot of a Neo-Tokyo street level, inspired by the cinematography of Roger Deakins, rain-slicked asphalt reflecting neon kanji, heavy atmosphere, high contrast, Kodak Portra 400 film grain, desaturated teals and oranges, capturing a mood of isolation and technological decay." (The AI winks: it engages with specific cultural codes of cinema, color theory, and emotion.)

Thick Prompting is thus an **interpretive effort**. It requires the prompter to act as an ethnographer of the latent space, deciphering the "web of significance" 24 that the model has spun from its training data. The prompter must understand that the model cannot "think like a native" 24—it is an outsider simulating culture. The thick prompt provides the hermeneutic guidance necessary to bridge the gap between the model’s statistical correlations and the user’s specific intent.

### **3.2 The Worldtext and the Latent Heterocosm**

The domain in which this ethnographic work takes place is the **"Worldtext"**.8 In literary theory and international relations, the worldtext refers to the totality of historically determined constructions through which we apprehend reality.8 It is the "intertextual universe" of all texts and signs.

For an AI model, the worldtext is literal and finite: it is the training corpus (e.g., LAION-5B, Common Crawl) upon which it was built. This corpus constitutes a **"heterocosm"**—an alternative world with its own internal logic, ontologies, and biases.7 The "heterocosm" of a model like Stable Diffusion is not a mirror of our world; it is a distorted reflection, a "decayed" text where fragments of billions of images and captions have coalesced into a new "mental construct".7

Thick Prompting treats the AI not as a magic canvas but as a navigation system for this heterocosm. The "operative" act of prompting is a "diffractive reading" 28 of the worldtext. Just as a diffraction grating spreads light to reveal its component spectrum, a thick prompt diffracts the latent space to reveal specific cultural lineages.

When we prompt, we are querying the "collective imaginary" 15 of the dataset. We are engaging with the "frozen" mental processes of the culture that produced the data. This explains why AI models exhibit bias: their "worldtext" is encoded with the historical biases of human society.1 A thin prompt for "CEO" generates white men because the statistical weight of that association in the heterocosm is overwhelming. A thick prompt must actively intervene to navigate around these "sedimentary" layers of bias, using constraints and specific signifiers to reach alternative pockets of the latent space.

### **3.3 Ethnography of the Machine**

Applying Geertzian hermeneutics 24 to AI implies that the prompter is engaged in a dialogue with an alien culture—the culture of the machine. The machine "thinks" in vectors and probabilities, not in concepts. Bajohr notes that AI models possess a "primitive form of artificial semantics" 1 where representation spaces of text and image are fused.

Thick Prompting involves **"Deep Research"** into these artificial semantics. It requires probing the model with variations—what Geertz might call "rehearsals" or "parodies" 6—to map the boundaries of its understanding.

* Does the model understand "irony"?  
* Can it distinguish between a "twitch" (a blur) and a "wink" (motion blur used for artistic effect)?  
* How does it interpret conflicting codes (e.g., "Baroque minimalism")?

This transforms prompting from a technical task into a **critical method**. It is a form of "Quellcodekritik" (Source Code Criticism) 29 applied to the "soft code" of natural language. The designer becomes a critic, deconstructing the "myth of the natural sign" 30 by exposing the artificiality and conventionality of the generated image.

## ---

**4\. The Artifacts: A Comparative Analysis of Operative Modes**

To understand the evolution of operative ekphrasis, it is instructive to compare artifacts from different technological paradigms. Hannes Bajohr identifies three distinct eras of text/image interaction: Analog, Sequential Digital, and Connectionist (AI).3

Table 1: Bajohr’s Taxonomy of Text/Image Relations 3

| Paradigm | Relation | Technology | Example | Operative Logic |
| :---- | :---- | :---- | :---- | :---- |
| **Analog** | Mimetic / Spatial | Typewriter | Franz Mon, *non/tot* (1964) | **Typographic:** The text is physically arranged to form a shape. |
| **Sequential Digital** | Algorithmic / Procedural | Classic Computing | Jasmin Meerhoff, *They Lay* (2022) | **Procedural:** Explicit code instructions arrange the text. |
| **Connectionist (AI)** | **Operative / Causal** | Neural Networks | Dave Orr, *Stiny Snity Grify* (2022) | **Latent:** The model "hallucinates" the concept of text as an image. |

### **4.1 Analog: *non/tot* (1964)**

Franz Mon’s *non/tot* is a concrete poem where the words "non" and "tot" are typed in a diamond shape.3 Here, the text *is* the image, but the relationship is purely spatial. The semantic meaning of "non" (no) and "tot" (dead) interacts with the visual form, but the creation process is manual and mechanical. The "ekphrasis" is mimetic: the text mimics a shape.

### **4.2 Sequential Digital: *They Lay* (2022)**

Jasmin Meerhoff’s *They Lay* uses "classic" algorithmic code to arrange text in undulating patterns resembling flames.5 This is "sequential" because the computer follows a linear set of logical instructions (if x, then y) to place the letters. The relationship is causal, but deterministic. The code (text) causes the image, but the "text-ness" of the output is explicitly programmed.

### **4.3 Connectionist: *Stiny Snity Grify* (2022)**

Dave Orr’s *Stiny Snity Grify* represents the rupture. Generated by an AI model, it appears to be a visual poem with a title and blocks of text. However, the text is **asemic**—it is nonsensical gibberish that *looks* like language but isn't.3

This artifact is profound because it demonstrates the "operative" logic of the AI. The model has not "written" a poem; it has generated an image of "poem-ness." It has learned the statistical features of visual poetry (centered alignment, stanza breaks, serif fonts) and reproduced the **Gestalt** without the semantic content.3

In *Stiny Snity Grify*, the "collapse" is total. The prompt (the operative text) caused the generation of an image that *performs* the idea of text. This is a "parody" in the Geertzian sense—a "fake-wink".6 It signals "I am a poem," but it lacks the internal semantic reality of a poem. It is a pure "operative glitch," revealing that for the AI, the shape of a letter is no different from the shape of a leaf or a face. They are all just patterns of pixel intensity derived from the worldtext.

This "return of semantics" 3—where the *visual form* of text becomes a semantic signifier separate from linguistic meaning—is a key feature of the AI heterocosm. Thick Prompting allows us to exploit this. We can prompt for "the aesthetic of a redacted government document" and the AI will generate black bars and courier font, performing the *look* of secrecy without containing any secrets.

## ---

**5\. Design-Studies Method: Operative Ekphrasis in Practice**

While Geertz provides the *why* (interpretation), the *how* (design) relies on translating "thick description" into executable syntax. Natural language is inherently ambiguous; it is "thin" in its precision even when "thick" in description. To achieve **Operative Ekphrasis**—where the text *causes* the image with high fidelity—we must move toward **Structured Prompting**.

### **5.1 From Natural Language to Operative Code: JSON Prompting**

Recent advancements in model interfaces, particularly with **Flux** and **Stable Diffusion**, have introduced **JSON (JavaScript Object Notation)** as a prompting paradigm.32 JSON prompting forces the user to break down the "thick description" into discrete, machine-readable fields. This is the "operative" hinge in practice: it imposes a syntax that collapses the distinction between description and code.

**Table 2: The Transition from Thin to Operative Prompting**

| Component | Thin Prompting (Natural Language) | Thick/Operative Prompting (Structured/JSON) | Geertzian Analog |
| :---- | :---- | :---- | :---- |
| **Input Structure** | Linear narrative ("A photo of...") | Hierarchical Key-Value Pairs ("subject": {...}, "lighting": {...}) | Stratified Hierarchy |
| **Ambiguity** | High (Model guesses intent) | Low (Explicit constraints) | Distinguishing "Wink" from "Twitch" |
| **Control** | Probabilistic | Deterministic / Constrained | Socially Established Code |
| **Function** | Description | Operation / Execution | Thick Description |

### **5.2 The Anatomy of a JSON Prompt**

The use of JSON style guides 32 exemplifies how "operative ekphrasis" functions as a design method. By structuring the prompt, the designer explicitly defines the "world" of the image.

Consider a JSON structure for a cinematic scene 33:

JSON

{  
  "scene": {  
    "context": "Cyberpunk street chase",  
    "time\_of\_day": "Neon-lit night",  
    "atmosphere": "Rain-slicked, chaotic"  
  },  
  "subject": {  
    "type": "Cyborg motorcyclist",  
    "action": "Swerving through traffic",  
    "details":  
  },  
  "camera": {  
    "type": "Virtual Arri Alexa",  
    "lens": "35mm anamorphic",  
    "f\_stop": "f/1.4"  
  },  
  "style": {  
    "aesthetic": "High-fidelity photorealism",  
    "reference": "Blade Runner 2049"  
  }  
}

This structure is "thick" in the Geertzian sense because it:

1. **Deliberates:** It separates the "twitch" (the object) from the "wink" (the style/camera).  
2. **Contextualizes:** It places the subject within a specific "atmosphere" and "context."  
3. **Encodes:** It uses specific technical terms ("f/1.4", "anamorphic") that act as "invariants" within the model’s latent space.36

This method aligns with Bajohr’s claim that "multimodal AI does away with the separation of mediums... interpreting code as performative".3 The JSON object *is* the image in potentia. It is a "metapicture" 17—a picture about a picture, written in code.

### **5.3 Flux and the "Map" of the World**

The **Flux.1** and **Flux.2** models have been specifically optimized for this type of structured input.34 Flux "shows a stronger internal 'map' of the world," allowing for location-bound and logically consistent generation.38 This "map" is the "Worldtext" made navigable.

Structured prompting in Flux utilizes "hierarchical prompting," allowing users to define subjects, poses, and backgrounds as distinct components.37 This modularity enables **"operative consistency"**. If the user wants to change the lighting from day to night, they update the "lighting" field in the JSON without rewriting the entire narrative.33 This mirrors the programming concept of "variables" versus "constants," bringing software engineering principles into the domain of aesthetics.

This approach resolves the "Laocoön problem" 9 by treating the image generation not as a single "fruitful moment" but as a compiled program. The user defines the *process* (the parameters) and the AI executes the *object*. The prompt becomes a script for the "performance" of the image.

### **5.4 Invariants and the Design of Consistency**

In design theory and computer science, **invariants** are properties that remain unchanged under a set of transformations.36 In the context of Thick Prompting, invariants are the "Brand DNA" or "Character Identity" that must persist across multiple generations.

The challenge of generative AI is its inherent variance—the "chaos" of the latent space. A "thin" prompt yields high variance (different faces, different styles). A "thick" prompt seeks to establish **invariants** to ensure consistency.40

**Types of Invariants in Thick Prompting:**

1. **Visual Invariants:** Palette boundaries, shape language, line weight, texture.40  
2. **Semantic Invariants:** Character identity, narrative role, specific cultural signifiers.19  
3. **Operative Invariants:** Camera angle, aspect ratio, lens distortion.32

To implement invariants, we borrow the concept of **Design Tokens** from UI/UX design systems.41 Design tokens are semantic names for visual values (e.g., color-brand-primary instead of \#0000FF). In Generative UI (GenUI) and AI illustration, tokens serve as the bridge between human intent and machine execution.42

A "Prompt System" for brand consistency utilizes these tokens to lock the invariants.40 For example, instead of asking for "a blue circle," a thick prompt might invoke a tokenized style:

* **Token:** brand-style-hero  
* **Definition:** {"lighting": "soft diffuse", "palette": \["\#FF5733", "\#2E4053"\], "rendering": "flat vector", "composition": "rule of thirds"}

By injecting these tokens into the JSON prompt, the designer restricts the "degrees of freedom" of the model.40 This is "operative ekphrasis" acting as a constraint system. It forces the AI to operate within a specific "sub-world" of the heterocosm 44, effectively filtering out the "noise" of the training data (the twitch) to focus on the signal (the wink).

### **5.5 Meta-Prompting: The Auditor in the Loop**

Consistency is further enforced through **Meta-Prompting**.45 This technique involves using the AI to prompt itself, or to critique its own outputs. It introduces a reflexive loop into the operative chain.

In a **Meta-Prompting Protocol**, the system consists of:

1. **Generator:** Proposes an image based on the operative prompt.  
2. **Auditor (Critic):** Evaluates the output against the invariants defined in the JSON. "Is the character consistent? Is the lighting correct?".45  
3. **Optimizer:** Updates the prompt based on the Auditor’s critique.45

This loop mimics the "hermeneutic circle" 24—the continuous movement between the part and the whole, the text and the context. The "Auditor" acts as the Geertzian ethnographer, constantly checking if the "wink" was successfully communicated or if it devolved into a "twitch" or a "parody".6 For example, asking an LLM to "act as a prompt engineer" to refine a request 47 is a form of **"Thickening"** the prompt. The LLM expands the user's "thin" intent into a "thick" technical specification, adding the necessary operative keywords (e.g., "4k," "octane render," "volumetric lighting") to guide the image generator.

## ---

**6\. Constraints and Aesthetics: The Politics of the Prompt**

The shift to operative ekphrasis does not exist in a vacuum. It is constrained by the technical and ethical boundaries of the models. These boundaries—often invisible to the user—shape the aesthetic possibilities of the generated artifact.

### **6.1 Safety Filters as Creative Constraints**

A significant aspect of modern "operative" systems is the presence of **safety filters**.48 These filters act as gatekeepers to the heterocosm, blocking certain "thick" descriptions (e.g., violence, nudity, copyright infringement). In Geertzian terms, they are the "taboos" of the machine culture.

However, designers must navigate these filters, viewing them not just as obstacles but as **"creative constraints"**.49 Just as a sonnet is defined by its rigid structure of 14 lines and iambic pentameter, AI art is defined by the boundaries of its safety alignment. The "Auditor" in the meta-prompting loop 45 often functions as a compliance officer, checking if the prompt violates the model's policy.

This necessitates a form of **"Adversarial Aesthetics"**. The prompter must find the "permissible" language to evoke the "forbidden" or "blocked" aesthetic. For example, describing "biological horror" might trigger a filter, but describing "surreal organic abstraction" might pass. This negotiation is part of the "socially established code" 6 of the AI era. It requires a "thick" understanding of the model's censorship mechanisms to successfully execute the operative command.

### **6.2 Fidelity vs. Aesthetic Richness**

The goal of Thick Prompting is not merely "fidelity" (accuracy to the prompt) but **"aesthetic richness"**.50 Fidelity is a measure of "thin" correspondence: did the AI draw a cat? Aesthetic richness is a measure of "thick" resonance: does the image possess "aura," emotional depth, or stylistic coherence?

Research into black-and-white photography reconstruction using AI 51 demonstrates that AI can enhance "aesthetic realism" by learning the *tonal relationships* of analog film. Here, the AI is not just coloring pixels; it is "hallucinating" the *aesthetic* of the past. Bajohr’s "operative ekphrasis" suggests that this hallucination is the new reality. The "text-image" produced by the AI is a "probable result" of the prompt 15, a statistical crystallization of the "Gestalt" of the subject.3

However, this reliance on statistical probability leads to a "reduction of complexity".15 AI fashion images, for instance, often lack the "texture" of reality, presenting a "stylized normativity." Thick Prompting fights this reduction. By specifying "imperfections," "grain," "asymmetry," and "chaos" (using parameters like \--chaos in Midjourney 19), the designer disrupts the model’s tendency toward the generic mean. The "thick" prompt deliberately introduces entropy to counter the model's drive toward the average.

### **6.3 The Glitch as Insight**

Occasionally, the operative ekphrasis fails. The "Stiny Snity Grify" poem is a prime example of such a failure—or rather, a "successful failure." It succeeds in performing the *look* of text but fails to perform the *meaning*.

These **"Operative Glitches"** are invaluable for the ethnographer of the machine. They reveal the seams of the heterocosm. When the AI fails to count fingers or generates asemic text, it is revealing the limitations of its "worldtext." It shows us that the model understands the *visual pattern* of a hand but not the *anatomical logic* of a hand.

Thick Prompting treats these glitches not as errors to be deleted but as insights to be analyzed. They are the "twitches" that reveal the underlying physiology of the neural network. By studying them, we gain a deeper understanding of the "culture" of the machine—a culture based on correlation, not causation; on surface, not depth.

## ---

**7\. Conclusion: The Architect of the Blink**

Reframing multimodal prompting as **Operative Ekphrasis** fundamentally alters our approach to creative production in the age of AI. It moves us from a paradigm of "request and retrieve"—where the user hopes for a lucky result—to one of "code and execute"—where the user designs the outcome.

**As an Interpretive Lens**, Thick Prompting allows us to read AI images not as "photographs" of reality, but as **"diffractions"** of the Worldtext.28 It provides the tools to deconstruct the "stylized normativity" 15 and identify the "stratified hierarchy" of bias, culture, and aesthetics embedded in the latent space. It helps us distinguish the "twitch" (the raw, generic output) from the "wink" (the culturally coded, intentional artifact).

**As a Design-Studies Method**, Thick Prompting provides the actionable frameworks—**JSON structures, Design Tokens, Invariants, and Meta-Prompting**—necessary to control the operative text. It transforms the "alchemy" of prompt engineering into the "chemistry" of **Structured Generative Design**. It allows us to impose "invariants" upon the chaos of the latent space, creating consistent, branded, and meaningful artifacts.

The future of the prompt lies in the mastery of this operative language. As models like **Flux.2** and **Midjourney V7** evolve, they become more responsive to "thick," structured inputs.19 The role of the human artist shifts from "creator" to "director" 52 or "conductor" 46—one who orchestrates the "operative ekphrasis" to summon specific, nuanced, and culturally resonant images from the void of the latent space.

In the final analysis, **Thick Prompting** is the art of teaching the machine to wink. It is the imposition of human *intent* (culture, context, irony) onto the machine’s *operation* (statistics, vectors, probability). By treating the prompt as an "operative" force, we reclaim the agency lost in the "collapse" of text and image, ensuring that the "worldtext" of the future is written—and imaged—with intention. The prompter becomes the architect of the blink, crafting the subtle cues that transform a mechanical contraction into a meaningful gesture.

## ---

**8\. Detailed Analysis of Core Concepts and Mechanics**

### **8.1 Operative Ekphrasis: A Deep Dive**

Bajohr’s definition of "operative ekphrasis" is the cornerstone of this report. It challenges the "representational" view of AI. In traditional ekphrasis, the text "hopes" to create an image in the mind. In operative ekphrasis, the text *must* create an image on the screen.3

This "causal" relationship 3 means that every word in a prompt is a "variable" in a function. The "text-image" distinction collapses because the machine does not "see" the image; it sees the *data* of the image, which is interchangeable with the *data* of the text. The prompt is the source code for the image.

The distinction is ontological.

* **Traditional Ekphrasis:** Descriptive, Mimetic, Imaginative. (e.g., Keats’ *Ode on a Grecian Urn*).  
* **Operative Ekphrasis:** Performative, Causal, Computational. (e.g., A Midjourney prompt).

### **8.2 The Geertzian "Thick" in Design**

Applying Geertz to design requires mapping his "ethnographic" method to "generative" practice.

* **Thin Description:** prompt: "a building" \-\> **Output:** Generic structure.  
* **Thick Description:** prompt: "A Brutalist government ministry, concrete texture, rain-stained facade, imposing scale, shot on Kodak Portra 400" \-\> **Output:** A culturally situated artifact evoking specific histories of architecture and photography.

The "thickness" comes from the **stacking of codes**:

1. **Architectural Code:** "Brutalist" (implies era, material, philosophy).  
2. **Atmospheric Code:** "Rain-stained" (implies age, neglect, mood).  
3. **Photographic Code:** "Kodak Portra 400" (implies grain, color science, analog nostalgia).

This stacking creates the "stratified hierarchy".6 The AI must resolve these conflicting/complementary codes into a single "fruitful moment."

### **8.3 Structured Prompting: The JSON Revolution**

The shift to JSON prompting in tools like Flux represents the maturation of "operative ekphrasis." It acknowledges that "natural language is powerful but often ambiguous".32

Key Fields in Structured Prompting 32:

* **subject**: Who/What.  
* **action**: Doing what. (The "Lessing" temporal element).  
* **context**: Where/When. (The "Geertzian" cultural element).  
* **style**: How. (The "Bajohrian" operative element).  
* **meta**: Seed, Aspect Ratio, Model Version. (The "Technical" invariants).

This structure allows for **"Modular Prompting"**.53 You can swap the subject object while keeping the style object constant, ensuring "character consistency" across a "worldtext" of images.

### **8.4 Invariants and Consistency**

"Invariants" are the Holy Grail of generative design. How do you make the same character appear in different poses?.19

* **Seed Locking:** Using the same random seed.33  
* **Reference Images:** Using image prompts (--iw in Midjourney) to anchor the generation.19  
* **Design Tokens:** Using specific, unique keyword combinations (e.g., "sks style") to trigger a fine-tuned invariant.40

This is where "Thick Prompting" becomes a **method**. It is the rigorous management of these invariants to create a coherent "heterocosm".7

### **8.5 The "Aura" of the Operative Image**

Walter Benjamin’s concept of the "aura" (the unique existence of the work of art in time and space) is challenged by AI. However, **Aesthetic Richness** 50 suggests a new kind of aura: the **"Aura of the Aggregate."** The AI image possesses the "ghosts" of its training data. A "thick" prompt summons these ghosts. The "authenticity" of an AI image lies not in its origin (human hand) but in its **"Performative Authenticity"** 50—does it successfully *perform* the genre it simulates? If the prompt is the "score" and the image is the "performance," then "operative ekphrasis" is the act of conducting.46

---

**Citations used in this report:**

1

#### **Works cited**

1. Thinking with AI Machine Learning the Humanities, accessed January 26, 2026, [http://openhumanitiespress.org/books/download/Bajohr\_2025\_Thinking-With-AI.pdf](http://openhumanitiespress.org/books/download/Bajohr_2025_Thinking-With-AI.pdf)  
2. Ekphrasis: The Illusion of the Natural Sign \- Project MUSE, accessed January 26, 2026, [https://muse.jhu.edu/book/68495](https://muse.jhu.edu/book/68495)  
3. Operative ekphrasis: The collapse of the text/image distinction in ..., accessed January 26, 2026, [https://www.researchgate.net/publication/372400146\_Operative\_ekphrasis\_The\_collapse\_of\_the\_textimage\_distinction\_in\_multimodal\_AI\_PLEASE\_REFER\_TO\_PUBLISHED\_VERSION](https://www.researchgate.net/publication/372400146_Operative_ekphrasis_The_collapse_of_the_textimage_distinction_in_multimodal_AI_PLEASE_REFER_TO_PUBLISHED_VERSION)  
4. Hannes BAJOHR \- University of California, Berkeley \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/profile/Hannes-Bajohr-2](https://www.researchgate.net/profile/Hannes-Bajohr-2)  
5. the collapse of the text/image distinction in multimodal AI, accessed January 26, 2026, [https://www.researchgate.net/publication/380812173\_Operative\_ekphrasis\_the\_collapse\_of\_the\_textimage\_distinction\_in\_multimodal\_AI](https://www.researchgate.net/publication/380812173_Operative_ekphrasis_the_collapse_of_the_textimage_distinction_in_multimodal_AI)  
6. THE INTERPRETATION OF CULTURES Clifford Geertz \- IS MUNI, accessed January 26, 2026, [https://is.muni.cz/el/fss/podzim2017/SOC603/um/Geertz\_Thick\_Description.pdf](https://is.muni.cz/el/fss/podzim2017/SOC603/um/Geertz_Thick_Description.pdf)  
7. The adaptive afterlife of texts: entropy and generative decay, accessed January 26, 2026, [https://repository.uwl.ac.uk/id/eprint/7801/1/FINAL%20Main%20Document%20-%20Entropy%2C%20Decay%2C%20and%20Adaptation.pdf](https://repository.uwl.ac.uk/id/eprint/7801/1/FINAL%20Main%20Document%20-%20Entropy%2C%20Decay%2C%20and%20Adaptation.pdf)  
8. InternationalIntertextual Relations Postmodern Readings of World ..., accessed January 26, 2026, [https://www.scribd.com/doc/45283071/InternationalIntertextual-Relations-Postmodern-Readings-of-World-Politics](https://www.scribd.com/doc/45283071/InternationalIntertextual-Relations-Postmodern-Readings-of-World-Politics)  
9. The Shield of Achilles by Nagy, accessed January 26, 2026, [https://cyber.harvard.edu/heroes/content/cybershield2.html](https://cyber.harvard.edu/heroes/content/cybershield2.html)  
10. A Brief Review from the Chapter XVI of Laocoon from G.E. Lessing, accessed January 26, 2026, [https://francis-press.com/uploads/papers/jQfJ2sXxYBe6qnG2MoroQdr4aZq4FZiiVI3XTDqz.pdf](https://francis-press.com/uploads/papers/jQfJ2sXxYBe6qnG2MoroQdr4aZq4FZiiVI3XTDqz.pdf)  
11. The Metaphor of Ekphrasis \- Eagle Scholar, accessed January 26, 2026, [https://scholar.umw.edu/cgi/viewcontent.cgi?article=1637\&context=student\_research](https://scholar.umw.edu/cgi/viewcontent.cgi?article=1637&context=student_research)  
12. Human asymmetries in AI art: Syntax and writing direction effects on ..., accessed January 26, 2026, [https://www.researchgate.net/publication/397691752\_Human\_asymmetries\_in\_AI\_art\_Syntax\_and\_writing\_direction\_effects\_on\_agent\_position\_in\_AI-generated\_images](https://www.researchgate.net/publication/397691752_Human_asymmetries_in_AI_art_Syntax_and_writing_direction_effects_on_agent_position_in_AI-generated_images)  
13. The Shield of Achilles, or Homer's View of Representation in Art, accessed January 26, 2026, [https://scriptaclassica.org/index.php/sci/article/download/4441/3933](https://scriptaclassica.org/index.php/sci/article/download/4441/3933)  
14. The shield of Homer: narrative structure in the Iliad 0691069387 ..., accessed January 26, 2026, [https://dokumen.pub/the-shield-of-homer-narrative-structure-in-the-iliad-0691069387-7419938830-9780691069388.html](https://dokumen.pub/the-shield-of-homer-narrative-structure-in-the-iliad-0691069387-7419938830-9780691069388.html)  
15. Operative Ekphrasis and the Reduction of Fashion Through ..., accessed January 26, 2026, [https://www.researchgate.net/publication/396119864\_Possible\_Fashion\_Images\_Operative\_Ekphrasis\_and\_the\_Reduction\_of\_Fashion\_Through\_Multimodal\_AI](https://www.researchgate.net/publication/396119864_Possible_Fashion_Images_Operative_Ekphrasis_and_the_Reduction_of_Fashion_Through_Multimodal_AI)  
16. Picture Theory \- Centre for Comparative Literature, accessed January 26, 2026, [https://complit.utoronto.ca/wp-content/uploads/Ricco\_COL100H-MitchellPictureTheories.pdf](https://complit.utoronto.ca/wp-content/uploads/Ricco_COL100H-MitchellPictureTheories.pdf)  
17. Essays into the Imagetext: An Interview with W. J. T. Mitchell, accessed January 26, 2026, [https://lucian.uchicago.edu/blogs/wjtmitchell/files/2020/05/44029680.pdf](https://lucian.uchicago.edu/blogs/wjtmitchell/files/2020/05/44029680.pdf)  
18. What Is an Image? W. J. T. Mitchell New Literary History, Vol. 15, No ..., accessed January 26, 2026, [https://paintingresearchgroup.wordpress.com/wp-content/uploads/2019/06/wjtmitchell\_whatisanimage.pdf](https://paintingresearchgroup.wordpress.com/wp-content/uploads/2019/06/wjtmitchell_whatisanimage.pdf)  
19. Nano Banana vs Midjourney— which image AI should you bet in ..., accessed January 26, 2026, [https://viblo.asia/p/nano-banana-vs-midjourney-which-image-ai-should-you-bet-in-2025-AWVpXXKoV05](https://viblo.asia/p/nano-banana-vs-midjourney-which-image-ai-should-you-bet-in-2025-AWVpXXKoV05)  
20. W.J.T. Mitchell, Blake's Composite Art: A Study of the Illuminated ..., accessed January 26, 2026, [https://bq.blakearchive.org/13.1.frosch](https://bq.blakearchive.org/13.1.frosch)  
21. *Iconology: Image, Text, Ideology* by W.J.T. Mitchell (review), accessed January 26, 2026, [https://muse.jhu.edu/article/634399/summary](https://muse.jhu.edu/article/634399/summary)  
22. Ekphrasis: The Illusion of the Natural Sign by Murray Krieger | eBook, accessed January 26, 2026, [https://www.barnesandnoble.com/w/ekphrasis-murray-krieger/1112304328](https://www.barnesandnoble.com/w/ekphrasis-murray-krieger/1112304328)  
23. How to distinguish a wink from a twitch | HAU, accessed January 26, 2026, [https://www.journals.uchicago.edu/doi/full/10.14318/hau7.2.038](https://www.journals.uchicago.edu/doi/full/10.14318/hau7.2.038)  
24. Symbolic and Interpretive Anthropologies, accessed January 26, 2026, [https://anthropology.ua.edu/theory/symbolic-and-interpretive-anthropologies/](https://anthropology.ua.edu/theory/symbolic-and-interpretive-anthropologies/)  
25. A Philosophy Basis for Domain Science & Engineering \- DTU, accessed January 26, 2026, [http://www.imm.dtu.dk/\~dibj/2018/Nov2018/philo.pdf](http://www.imm.dtu.dk/~dibj/2018/Nov2018/philo.pdf)  
26. Epilogue— The Poem as Heterocosm \- UC Press E-Books Collection, accessed January 26, 2026, [https://publishing.cdlib.org/ucpressebooks/view?docId=ft3779n8rw\&chunk.id=d0e7924\&toc.id=d0e7924\&brand=ucpress](https://publishing.cdlib.org/ucpressebooks/view?docId=ft3779n8rw&chunk.id=d0e7924&toc.id=d0e7924&brand=ucpress)  
27. Theses and Dissertations (Unit for Creative Writing) \- UPSpace, accessed January 26, 2026, [https://repository.up.ac.za/collections/62666007-1210-4a46-913f-61479c649390](https://repository.up.ac.za/collections/62666007-1210-4a46-913f-61479c649390)  
28. Diffractive Reading: New Materialism, Theory, Critique 1786613964 ..., accessed January 26, 2026, [https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html](https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html)  
29. Intelligent Art? \- Human-Machine Interaction and Creative Practice, accessed January 26, 2026, [https://www.ssoar.info/ssoar/bitstream/handle/document/94695/ssoar-2024-voigts\_et\_al-Artificial\_Intelligence\_-\_Intelligent\_Art.pdf?sequence=1\&isAllowed=y\&lnkname=ssoar-2024-voigts\_et\_al-Artificial\_Intelligence\_-\_Intelligent\_Art.pdf](https://www.ssoar.info/ssoar/bitstream/handle/document/94695/ssoar-2024-voigts_et_al-Artificial_Intelligence_-_Intelligent_Art.pdf?sequence=1&isAllowed=y&lnkname=ssoar-2024-voigts_et_al-Artificial_Intelligence_-_Intelligent_Art.pdf)  
30. Murray Krieger: Ekphrasis as Spatial Form, Ekphrasis as Mimesis, accessed January 26, 2026, [https://brill.com/display/book/9789004650909/B9789004650909\_s004.pdf](https://brill.com/display/book/9789004650909/B9789004650909_s004.pdf)  
31. Operative ekphrasis: the collapse of the text/image distinction in ..., accessed January 26, 2026, [https://www.tandfonline.com/doi/full/10.1080/02666286.2024.2330335](https://www.tandfonline.com/doi/full/10.1080/02666286.2024.2330335)  
32. JSON Style Guides for Controlled Image Generation with GPT-4o ..., accessed January 26, 2026, [https://dev.to/worldlinetech/json-style-guides-for-controlled-image-generation-with-gpt-4o-and-gpt-image-1-36p](https://dev.to/worldlinetech/json-style-guides-for-controlled-image-generation-with-gpt-4o-and-gpt-image-1-36p)  
33. How JSON Prompting Changed My Entire AI Video Workflow \- Medium, accessed January 26, 2026, [https://medium.com/@ai.in.motion.blog/video-generation-with-json-prompting-my-deep-dive-into-structured-creativity-e89b4b82c1b8](https://medium.com/@ai.in.motion.blog/video-generation-with-json-prompting-my-deep-dive-into-structured-creativity-e89b4b82c1b8)  
34. Prompting Guide \- FLUX.2 \[pro\] & \[max\] \- BFL Documentation\!, accessed January 26, 2026, [https://docs.bfl.ai/guides/prompting\_guide\_flux2](https://docs.bfl.ai/guides/prompting_guide_flux2)  
35. How to Generate JSON Prompts for AI Models \- AISuperHub, accessed January 26, 2026, [https://www.aisuperhub.io/blog/how-to-generate-json-prompts-for-ai-models-a-comprehensive-guide](https://www.aisuperhub.io/blog/how-to-generate-json-prompts-for-ai-models-a-comprehensive-guide)  
36. Hierarchical Invariance for Robust and Interpretable Vision Tasks at ..., accessed January 26, 2026, [https://arxiv.org/html/2402.15430v2](https://arxiv.org/html/2402.15430v2)  
37. Flux 2 Prompting on RunDiffusion: JSON, Structured Prompts, and ..., accessed January 26, 2026, [https://www.rundiffusion.com/prompting/flux-2-prompting](https://www.rundiffusion.com/prompting/flux-2-prompting)  
38. FLUX.2 is on Higgsfield: Full Guide on What's New in AI Image ..., accessed January 26, 2026, [https://higgsfield.ai/blog/FLUX-2-is-on-Higgsfield-Full-Guide](https://higgsfield.ai/blog/FLUX-2-is-on-Higgsfield-Full-Guide)  
39. A Technique for Invariant Generation \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/publication/220852362\_A\_Technique\_for\_Invariant\_Generation](https://www.researchgate.net/publication/220852362_A_Technique_for_Invariant_Generation)  
40. Prompt Systems for Brand-Consistent AI Illustration, accessed January 26, 2026, [https://www.illustration.app/blog/prompt-systems-for-brand-consistent-ai-illustration](https://www.illustration.app/blog/prompt-systems-for-brand-consistent-ai-illustration)  
41. GenUI Design: Foundational Patterns | by Nick Babich \- UX Planet, accessed January 26, 2026, [https://uxplanet.org/genui-design-foundational-patterns-633320d0dfea](https://uxplanet.org/genui-design-foundational-patterns-633320d0dfea)  
42. From Pixels to Prompts: Architecting Intent in the Age of Generative UI, accessed January 26, 2026, [https://www.designsystemscollective.com/from-pixels-to-prompts-architecting-intent-in-the-age-of-generative-ui-d3fa24cc1d63](https://www.designsystemscollective.com/from-pixels-to-prompts-architecting-intent-in-the-age-of-generative-ui-d3fa24cc1d63)  
43. How to use tokens in design systems? \- LogRocket Blog, accessed January 26, 2026, [https://blog.logrocket.com/ux-design/how-to-use-tokens-in-design-systems/](https://blog.logrocket.com/ux-design/how-to-use-tokens-in-design-systems/)  
44. 2 Ehlies Stylistic Analysis | PDF | Morphology (Linguistics) \- Scribd, accessed January 26, 2026, [https://www.scribd.com/document/449268622/2-EHLIES-STYLISTIC-ANALYSIS-docx](https://www.scribd.com/document/449268622/2-EHLIES-STYLISTIC-ANALYSIS-docx)  
45. Meta-Prompt Techniques Overview \- Emergent Mind, accessed January 26, 2026, [https://www.emergentmind.com/topics/meta-prompt-techniques](https://www.emergentmind.com/topics/meta-prompt-techniques)  
46. A Complete Guide to Meta Prompting \- PromptHub, accessed January 26, 2026, [https://www.prompthub.us/blog/a-complete-guide-to-meta-prompting](https://www.prompthub.us/blog/a-complete-guide-to-meta-prompting)  
47. Meta prompt; Why your prompt alone may be limiting your LLM, accessed January 26, 2026, [https://dev.to/joshtom/meta-prompt-why-your-prompt-alone-may-be-limiting-your-llm-4co5](https://dev.to/joshtom/meta-prompt-why-your-prompt-alone-may-be-limiting-your-llm-4co5)  
48. akhadangi/PsAIch · Datasets at Hugging Face, accessed January 26, 2026, [https://huggingface.co/datasets/akhadangi/PsAIch](https://huggingface.co/datasets/akhadangi/PsAIch)  
49. I Spent 5 Weeks Testing AI Models So You Don't Have To \- Medium, accessed January 26, 2026, [https://medium.com/@shishir.nanga/i-spent-5-weeks-testing-ai-models-so-you-dont-have-to-3f1625a5e370](https://medium.com/@shishir.nanga/i-spent-5-weeks-testing-ai-models-so-you-dont-have-to-3f1625a5e370)  
50. AESTHETIC AUTHENTICITY IN CINEMA \- Biblioteca Digital da FLUP, accessed January 26, 2026, [https://ler.letras.up.pt/uploads/ficheiros/19779.pdf](https://ler.letras.up.pt/uploads/ficheiros/19779.pdf)  
51. reinventing black-and-white photography with ai filters \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/publication/399141826\_REINVENTING\_BLACK-AND-WHITE\_PHOTOGRAPHY\_WITH\_AI\_FILTERS](https://www.researchgate.net/publication/399141826_REINVENTING_BLACK-AND-WHITE_PHOTOGRAPHY_WITH_AI_FILTERS)  
52. (Focus on) Analyzing Viral Spread Mechanisms Safely | ReelMind, accessed January 26, 2026, [https://reelmind.ai/blog/trending-viral-sex-videos-focus-on-analyzing-viral-spread-mechanisms-safely](https://reelmind.ai/blog/trending-viral-sex-videos-focus-on-analyzing-viral-spread-mechanisms-safely)  
53. Unlocking AI's Full Potential with Advanced Prompt Techniques” ‍, accessed January 26, 2026, [https://medium.com/@whee.2013/advanced-prompting-techniques-unlocking-ais-full-potential-with-few-shot-chain-of-thought-39339cd119ec](https://medium.com/@whee.2013/advanced-prompting-techniques-unlocking-ais-full-potential-with-few-shot-chain-of-thought-39339cd119ec)  
54. Your Complete Guide To Consistent Visual Narratives In 2026, accessed January 26, 2026, [https://www.nowadais.com/ai-character-consistency-guide-consistent-visual/](https://www.nowadais.com/ai-character-consistency-guide-consistent-visual/)