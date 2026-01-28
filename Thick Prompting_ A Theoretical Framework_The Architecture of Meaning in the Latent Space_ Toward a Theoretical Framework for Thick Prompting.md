# **The Architecture of Meaning in the Latent Space: Toward a Theoretical Framework for Thick Prompting**

## **Abstract**

The meteoric rise of generative artificial intelligence (GenAI) has precipitated a crisis in human-computer interaction (HCI). The dominant interface paradigm—the "thin" text box—reduces the complex, high-dimensional negotiation of semantic intent to a linear string of characters, giving rise to the ad-hoc discipline of "prompt engineering." This report argues that the engineering metaphor is insufficient for capturing the nuances of creative co-production with probabilistic models. We propose an alternative theoretical framework: **Thick Prompting**.

Synthesizing Clifford Geertz’s semiotic anthropology, Ludwig Wittgenstein’s picture theory of language, the oral-formulaic theory of Homeric composition, and the media theory of operative ekphrasis, we construct a robust ontology of the prompt not as a command, but as a "thick" cultural and logical artifact. We validate this framework through a detailed analysis of emerging "thick" interfaces, specifically Almeda et al.’s *Dreamsheets*, Lindley and Whitham’s *Prompt Craft*, and the ethnographic practices of Chang et al.’s *Prompt Artists*. We posit that the future of AI interaction lies in interfaces that support high "logical multiplicity," material engagement, and the visualization of the "web of significance" inherent in the model’s latent space.

## ---

**1\. Introduction: The Poverty of the Command Line**

### **1.1 The Regression to Text**

The history of computing is often narrated as a progression from the abstract to the concrete: from the punch card and the command line to the Graphical User Interface (GUI), the touch screen, and spatial computing. However, the advent of Large Language Models (LLMs) and Text-to-Image (TTI) models has triggered a startling regression. The primary interface for the most advanced intelligence humanity has ever built is, paradoxically, a blank text box.1

This return to the command line—what might be called "thin prompting"—presupposes that natural language is a sufficient instrument for controlling high-dimensional latent spaces. It assumes that the user’s intent can be perfectly encoded into a linear string of text and that the model’s output is a deterministic function of that string. The term "Prompt Engineering" codifies this assumption, implying that the interaction is a technical optimization problem where the correct sequence of keywords (the "spell") yields the desired result.2

### **1.2 The "Thick" Alternative**

However, empirical observation of expert users reveals a different reality. Interaction with GenAI is not a linear transmission of instructions but a messy, iterative loop of discovery, negotiation, and bricolage. Users do not merely "engineer" prompts; they inhabit them. They construct elaborate templates, manipulate parameters like faders on a mixing desk, and curate outputs like museum directors.4

To capture this complexity, we introduce the concept of **Thick Prompting**. Derived from Clifford Geertz’s distinction between "thin description" (surface observation) and "thick description" (contextual interpretation) 6, Thick Prompting posits that effective interaction with AI requires tools and theories that expose the "thick" layers of meaning—the cultural contexts, logical structures, and material constraints—that govern the generative process.

### **1.3 Report Structure**

This report is organized into three major sections.

* **Part I: Theoretical Foundations** constructs the philosophical scaffolding for Thick Prompting, drawing on Geertz (Anthropology), Wittgenstein (Logic), and Parry/Lord (Poetics).  
* **Part II: Interface Archaeologies** analyzes three distinct HCI interventions—*Dreamsheets*, *Prompt Craft*, and *Promptify*—that exemplify "thick" design principles.  
* **Part III: Ethnographies of Practice** examines the lived experience of "Prompt Artists" to understand how thickness manifests in human behavior.  
* **Part IV: Synthesis** integrates these strands into a unified taxonomy and offers design implications for the next generation of AI tools.

## ---

**2\. Theoretical Foundations I: The Anthropology of the Latent Space (Geertz)**

### **2.1 The Web of Significance**

Clifford Geertz famously defined culture as a "web of significance" spun by humanity, within which we are suspended. The analysis of culture, therefore, is "not an experimental science in search of law but an interpretive one in search of meaning".6

Generative AI models are, in a literal sense, crystallized webs of significance. Trained on petabytes of human cultural production, the "latent space" of a model like Stable Diffusion or GPT-4 is a high-dimensional map of human associations. It captures the statistical probability that "Victorian" creates a "foggy" atmosphere, or that "cyberpunk" implies "neon."

When a user prompts a model, they are navigating this frozen cultural web.

* **Thin Prompting:** Treating the prompt as a database query. "Show me a dog." This asks for a signifier.  
* **Thick Prompting:** Treating the prompt as an entry into a cultural context. "A loyal greyhound waiting in the rain on Baker Street, shot on 35mm film." This navigates the *relationships* between signifiers (dog, loyalty, London, noir, film grain).

### **2.2 The Twitch vs. The Wink**

Geertz illustrates "thick description" with the difference between a twitch and a wink. Physically (thinly), they are identical: a contraction of the eyelid. Culturally (thickly), they are worlds apart. The wink implies conspiracy, humor, or signal; it relies on a shared code between sender and receiver.6

In GenAI, the "thin" interface (the chat box) often fails to distinguish the twitch from the wink.

* **The Hallucination as Twitch:** When a model generates a six-fingered hand, a "thin" view sees a glitch—a mechanical failure of pixel prediction.  
* **The Glitch as Wink:** A "thick" view, adopted by the "Prompt Artists" described by Chang 5, sees the glitch as a revealing artifact of the model’s training data—a "wink" from the latent space that can be stylized and repurposed. "Thick Prompting" requires interfaces that allow users to perceive and manipulate these layers of intent. It moves beyond "correctness" (did I get a hand?) to "meaning" (what kind of hand does the model associate with 'labor' versus 'leisure'?).

### **2.3 Meaning is Not a Metric**

Recent scholarship in the Digital Humanities warns that "meaning is not a metric".7 The industry’s obsession with "thin" metrics—CLIP scores, perplexity, latency—obscures the "thick" reality of how users actually experience AI art. A prompt might have a high CLIP score (high alignment between text and image) but fail entirely to capture the *vibe* or *affect* the user intended. Thick Prompting prioritizes **semantic density** over statistical alignment. It asks: Does the interface allow the user to convey the *mood* of "loneliness" through lighting and texture, or just the *symbol* of a lonely person?

## ---

**3\. Theoretical Foundations II: The Logic of the Experimental Model (Wittgenstein)**

### **3.1 The Proposition as a Picture**

To understand the logical structure of a prompt, we turn to Ludwig Wittgenstein’s early masterpiece, the *Tractatus Logico-Philosophicus*. Wittgenstein famously developed the "picture theory of meaning" after seeing a scale model of a traffic accident in a Parisian courtroom.8 The model cars and dolls represented the real cars and people because they shared a "logical form"—a structural isomorphism—with the reality.

Wittgenstein wrote: *"In a proposition a world is as it were put together experimentally"*.9 This is the most precise philosophical definition of a generative prompt available. A prompt is not a command; it is an **experimental model** of a possible world. When a user types a prompt, they are constructing a logical picture in text, which the model then projects into pixels. The "experiment" is the generation process itself—probing whether the logical structure of the text holds together when instantiated in the visual plane.

### **3.2 Logical Multiplicity**

Wittgenstein introduced the concept of "logical multiplicity" (mathematical multiplicity). For a picture to adequately represent a fact, it must have the same degree of freedom—the same number of distinguishing parts—as the fact it represents.11

* *Critique of Thin Interfaces:* A single text string often suffers from **insufficient logical multiplicity**. If a user imagines a scene with specific lighting, camera angle, subject pose, and art style, compressing all these distinct dimensions into one linear sentence collapses the logical structure.  
* *The "Thick" Solution:* Interfaces like Almeda’s *Dreamsheets* 12 or Promptify’s *widgets* 1 restore logical multiplicity. By breaking the prompt into columns (Subject, Action, Context, Style) or sliders (Scale, CFG), the interface provides a "control manifold" that matches the complexity of the user’s mental model.

### **3.3 Dimensional Analysis and the Scale Model**

Susan Sterrett’s analysis of Wittgenstein connects his thought to the engineering practice of **dimensional analysis** and **scale modeling** prevalent in the early 20th century.9 Engineers use "dimensionless parameters" (like the Reynolds number) to ensure that a small-scale model behaves physically like the full-scale object. In Thick Prompting, the "modifiers" (e.g., "scale," "weight," "steps") act as these dimensionless parameters. They preserve the "similitude" between the user’s internal visualization and the external output.

* **The Prompt as Scale Model:** The prompt is a low-fidelity scale model of the high-fidelity image. The "Prompt Craft" practice of adjusting weights (e.g., (fog:1.2)) is an act of tuning these dimensional parameters to maintain structural integrity during the "scale-up" from text to image.4

## ---

**4\. Theoretical Foundations III: The Poetics of Code (Homer & Ekphrasis)**

### **4.1 The Parry-Lord Thesis: AI as Oral Bard**

How do we compose these "experimental models" in the age of AI? We look to the oldest tradition of generative composition: the **Homeric Epic**. Milman Parry and Albert Lord demonstrated that the *Iliad* and *Odyssey* were not written word-by-word by a modern author, but composed orally using a system of **formulas** (epithets like "swift-footed Achilles" or "wine-dark sea") to "fill up the line" of the hexameter.14

Generative AI is a digital oral-formulaic system.

* **The Bard:** The LLM is the bard, trained on the "tradition" of the internet.  
* **The Formula:** Prompt "modifiers" identified by Oppenlaender 16—terms like "4k," "unreal engine," "trending on artstation," "highly detailed"—are the digital epithets. They are used not just for meaning, but for function: to "fill up the context" and stabilize the generation. Just as "swift-footed" is attached to Achilles regardless of whether he is running, "4k" is attached to an AI image regardless of its resolution, to invoke a specific *quality* of "high-definition-ness" in the latent space.16  
* **Thick Prompting as Rhapsodic Performance:** The expert user (the "Prompt Artist") does not write *ex nihilo*. They stitch together pre-existing formulas (templates) to invoke a theme. Thick Prompting acknowledges this "bricolage" nature of the craft. It does not demand originality in syntax; it demands mastery of the formulaic registry.5

### **4.2 Operative Ekphrasis**

The relationship between the text prompt and the visual output is best described by the media theory of **Operative Ekphrasis**, developed by Hannes Bajohr.17

* **Classical Ekphrasis:** A literary description of a visual object (e.g., Homer describing the Shield of Achilles). It is representational and distinct from the object.  
* **Operative Ekphrasis:** In Generative AI, the description is **performative**. The text *causes* the image to exist. The text is the code; the description is the operation.

This collapse of the distinction between word and image 18 is central to Thick Prompting. If the prompt is "operative," then the interface must allow the user to operate on it *as* a functional object, not just a linguistic one.

* **Implication:** A "thick" prompt is executable code. Users need tools to debug, trace, and refactor this code. This explains the emergence of tools like *Dreamsheets*, where prompts are treated as formulas in a spreadsheet, allowing for the systematic debugging of the "ekphrasis".12

## ---

**5\. HCI Archaeology I: The Tabular Epistemology (Dreamsheets)**

### **5.1 The Interface of Discovery**

Almeda et al.’s *Dreamsheets* 12 represents a radical departure from the chat interface, moving from a "conversational" epistemology to a "tabular" one. By embedding Stable Diffusion into a Google Sheet, the interface transforms the prompt from a fleeting utterance into a structured, persistent data object.

### **5.2 Mechanics of Thickness**

The "thickness" of *Dreamsheets* derives from its ability to handle **combinatorial complexity**.

* **Decomposition:** The user does not write a sentence. They populate columns: *Subject*, *Action*, *Style*, *Artist*, *Camera*. The interface (via the tti function) concatenates these into a prompt.19  
* **Permutation:** The "grid" structure allows the user to generate rows of variations. Row 1 might use "Oil Painting," Row 2 "Watercolor," Row 3 "Cyberpunk."  
* **LLM Augmentation:** The function gpt\_list(prompt, length) acts as a generative amplifier.19 The user can ask the LLM to "generate 10 synonyms for 'gloomy'," and the spreadsheet automatically populates the cells, creating 10 variations of the final image. This automates the "experimental modeling" process, allowing the user to survey the boundaries of the latent space.

### **5.3 The Hyperparameter Slider**

Crucially, *Dreamsheets* incorporates "hyperparameter sliders" directly into the grid (e.g., Columns G and H for cfg guidance scale).19 This allows the user to see the causal relationship between a numerical parameter and the visual output across a series of images. In a chat interface, this relationship is opaque; in the spreadsheet, it is explicit and graphable. The user is no longer guessing; they are performing "sensitivity analysis" on the cultural web of the model.

### **5.4 Case Study: The Concept Art Workflow**

In Almeda’s study, participants used the tool for "concept art," generating three distinct images to tell a story.19 The "think-aloud" protocols revealed that the spreadsheet structure encouraged users to "branch" their thinking—keeping a successful "seed" constant while iterating on the "style" column. This is "Thick Prompting" in action: holding one dimension of the "experimental model" fixed while varying another to probe the "logical multiplicity" of the system.

## ---

**6\. HCI Archaeology II: Materiality and Craft (Prompt Craft)**

### **6.1 Beyond Engineering: The Craft Metaphor**

Lindley and Whitham critique the "engineering" metaphor for its focus on efficiency and separation of design/execution. They propose **Prompt Craft**, which emphasizes ongoing, material engagement with the AI.2 "Craft" implies a respect for the "grain" of the material—the specific resistances and affordances of the latent space.

### **6.2 The Mixer Metaphor: PromptJ**

The **PromptJ** interface described by Lindley reimagines the prompt not as a sentence, but as a **mix**. Drawing on the metaphor of the audio mixing desk, the interface assigns "faders" to different prompt components.4

* **The Mechanism:** Instead of deleting the word "fog," the user lowers the "fog fader" from 100% to 20%.  
* **Thick Interaction:** This introduces **continuous control** to a domain previously dominated by discrete control (words). The user can "fade in" a style or "cross-fade" between two subjects. This aligns with Wittgenstein’s "logical multiplicity"—the interface now matches the continuous nature of the vector space it controls.

### **6.3 Tangible Thickness: Shadowplay and Cardshark**

Lindley extends "thickness" into the physical world with **Light Prompting** (*Shadowplay*) and **Tangible Prompting** (*Cardshark*).4

* **Shadowplay:** The input is multimodal. A camera captures the user’s shadow, which acts as a "constraining mask" for the diffusion model. The user "performs" the prompt with their body. Large movements increase the "diffusion amount" (AI hallucination), while stillness grounds the image in the physical shadow.4 This is "operative ekphrasis" made flesh—the body itself becomes the code.  
* **Cardshark:** Users place physical "Prompt Fragment Cards" (representing subjects or styles) into a lightbox. The position of the card determines its weight in the prompt. This "tangible user interface" (TUI) makes the abstract "weights" of the attention mechanism physically graspable. It turns "prompt engineering" into a tabletop game of arrangement and juxtaposition.4

## ---

**7\. HCI Archaeology III: The Visual Canvas (Promptify)**

### **7.1 Visualizing the Latent Space**

While *Dreamsheets* is tabular and *Prompt Craft* is tangible, **Promptify** (Brade et al.) offers a **spatial-visual** approach to Thick Prompting.1

* **The Infinite Canvas:** The interface abandons the linear feed for a zoomable 2D canvas. Users can organize "nodes" of prompts and images spatially.  
* **Logical Clustering:** The tool uses an "image layout and clustering" algorithm. It positions generated images on the canvas based on visual similarity.20 This allows the user to see "clusters" of style or subject—literally mapping the topography of the latent space.  
* **The Scale Slider:** A specific "scale slider" feature allows users to spread images apart to avoid overlap, managing the density of visual information.20

### **7.2 Structured Exploration**

Promptify includes "control widgets" for specific parameters, allowing users to "lock" a seed or "steer" a prompt suggestion.1 This supports **structured exploration**. The user creates a "visual genealogy" of their idea, tracing the lineage from an initial "thin" prompt to a final "thick" creation. This visual history is crucial for "sense-making"—it serves as the "thick description" of the creative process itself.

## ---

**8\. Ethnography of Practice: The Prompt Artist (Chang)**

### **8.1 The Rise of the Template**

Chang et al.’s study of **Prompt Artists** reveals that expert users have already intuited the principles of Thick Prompting.5

* **The Template as Artifact:** Prompt Artists do not just create images; they create **Templates**. A template is a "meta-prompt" with slots (e.g., in a \[Context\]). These templates are traded and sold as valuable commodities.  
* **Thick Validity:** The template is a "thick" artifact because it encapsulates *reliability*. It is a tested formula (in the Homeric sense) that guarantees a certain quality of output. The "Prompt Artist" is a tool-builder, crafting the "operative ekphrasis" that others will perform.

### **8.2 Glitch Hunting as Style**

Chang notes a fascinating behavior: **Glitch Hunting**. Artists deliberately seek out "glitches" (e.g., the way a model mis-renders mirrors or hands) and stabilize them into a consistent style.5

* **Theoretical Implication:** In "thin" engineering, a glitch is noise. In "thick" craft, a glitch is **texture**. By stabilizing the glitch, the artist turns a "twitch" into a "wink." They transform a technical failure into a cultural signal of "AI-ness" or "surrealism." This requires a deep, "thick" knowledge of the model’s quirks—a form of "latent space literacy."

### **8.3 Validation Rituals**

Prompt Artists engage in "validity testing" by reverse-image searching their own outputs.5 They want to ensure their prompt has generated something novel, not just retrieved a training image. This is a navigation of the "web of significance"—checking the coordinates of the output against the known map of human culture to assert originality.

## ---

**9\. Synthesis: The Framework of Thick Prompting**

We can now formalize the **Thick Prompting** framework through three constitutive dimensions.

### **9.1 Dimension 1: Semantic Density (The "What")**

* **Definition:** The richness of the cultural, historical, and aesthetic codes activated by the prompt.  
* **Theoretical Basis:** Geertz (Web of Significance) 6 \+ Homer (Oral Formula).14  
* **Manifestation:** The use of "boosters," "modifiers," and "negative prompts" to saturate the context window.  
* **Thick Practice:** Moving from identifying a *subject* ("a cat") to invoking a *world* ("a cat, 35mm, Wong Kar-Wai style, neon, rain, melancholic"). The prompt acts as a "dense" cultural pointer.

### **9.2 Dimension 2: Operative Multiplicity (The "How")**

* **Definition:** The degree of structural control and logical complexity afforded by the interface.  
* **Theoretical Basis:** Wittgenstein (Logical Multiplicity) 11 \+ Bajohr (Operative Ekphrasis).18  
* **Manifestation:** The shift from text strings to **spreadsheets** (*Dreamsheets*), **canvases** (*Promptify*), and **mixers** (*PromptJ*).  
* **Thick Practice:** Decomposing the prompt into independent variables; using sliders, weights, and logic gates to model the complexity of the mental image.

### **9.3 Dimension 3: Material Engagement (The "Feel")**

* **Definition:** The tactile, temporal, and embodied quality of the interaction.  
* **Theoretical Basis:** Lindley (Craft/Materiality) 4 \+ Sterrett (Scale Modeling).9  
* **Manifestation:** Real-time feedback loops, tangible inputs (*Cardshark*), embodied controls (*Shadowplay*).  
* **Thick Practice:** "Playing" the latent space like an instrument; treating the generative process as a continuous flow rather than a discrete transaction; accepting and stylizing "glitches" as material texture.

### **9.4 Comparative Taxonomy**

| Dimension | Thin Prompting (Engineering) | Thick Prompting (Craft/Theory) |
| :---- | :---- | :---- |
| **Goal** | Optimization, Efficiency, Accuracy | Exploration, Expressivity, Meaning |
| **Ontology** | Command / Query | Experimental Model / Performance |
| **Logic** | Deterministic (Input \-\> Output) | Probabilistic (Negotiation / Bricolage) |
| **Interface** | Text Box (Chat) | Mixer / Spreadsheet / Canvas / TUI |
| **Feedback** | Discrete (Turn-taking) | Continuous (Real-time / Slider) |
| **Culture** | Retrieval (Finding the data) | Navigation (Tracing the web of significance) |
| **Error** | Glitch (Failure) | Texture (Style / Materiality) 5 |

## ---

**10\. Design Implications and Future Directions**

The theory of Thick Prompting demands a fundamental rethinking of AI interface design. The "Chat" paradigm, while accessible, is a "thin" bottleneck that strangles the creative potential of "thick" models.

### **10.1 The "Thick" OS**

We envision a future "Thick OS" for generative creativity that integrates:

1. **The Mixer:** A universal control surface where semantic concepts (Style, Mood, Lighting) are assigned to faders.  
2. **The Loom:** A template-management system (based on the Homeric/Chang insight) that allows users to weave "formulas" into new prompts.  
3. **The Map:** A spatial visualization (like Promptify) that places the user’s current generation within the broader topography of the latent space, showing "nearby" concepts and "cultural clusters."

### **10.2 Conclusion**

"Thick Prompting" is not just a technique; it is a recognition of the new ontological status of the human-AI relationship. We are not masters commanding slaves; we are anthropologists navigating a vast, alien culture of our own making. We are rhapsodes singing with a digital chorus. We are logicians building experimental models of worlds we have not yet seen.

To prompt "thickly" is to accept the complexity of this entanglement. It is to move beyond the engineering of outputs and engage in the crafting of meaning. As we stand at the threshold of the generative age, our tools must rise to the dignity of this task—replacing the thin silence of the text box with the thick, resonant interface of the mixer, the canvas, and the loom.

---

**Citations used:**.1

#### **Works cited**

1. Composable Prompting Workspaces Using Dynamic Widgets ... \- arXiv, accessed January 26, 2026, [https://arxiv.org/html/2506.03741v1](https://arxiv.org/html/2506.03741v1)  
2. \[PDF\] From Prompt Engineering to Prompt Craft \- Semantic Scholar, accessed January 26, 2026, [https://www.semanticscholar.org/paper/daaafaafaf0e7c238f45802bcea37ba56dfb203e](https://www.semanticscholar.org/paper/daaafaafaf0e7c238f45802bcea37ba56dfb203e)  
3. Reflexive Prompt Engineering | PDF | Artificial Intelligence \- Scribd, accessed January 26, 2026, [https://www.scribd.com/document/860434008/Reflexive-Prompt-Engineering](https://www.scribd.com/document/860434008/Reflexive-Prompt-Engineering)  
4. (PDF) From Prompt Engineering to Prompt Craft \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/publication/386014125\_From\_Prompt\_Engineering\_to\_Prompt\_Craft](https://www.researchgate.net/publication/386014125_From_Prompt_Engineering_to_Prompt_Craft)  
5. The Prompt Artists \- UCSB MAT, accessed January 26, 2026, [https://www.mat.ucsb.edu/\~g.legrady/academic/courses/24f255/promptArtists.pdf](https://www.mat.ucsb.edu/~g.legrady/academic/courses/24f255/promptArtists.pdf)  
6. Digital Ethnography: A Systematic Literature Review \- ResearchGate, accessed January 26, 2026, [https://www.researchgate.net/publication/371970923\_Digital\_Ethnography\_A\_Systematic\_Literature\_Review](https://www.researchgate.net/publication/371970923_Digital_Ethnography_A_Systematic_Literature_Review)  
7. Using LLMs to make cultural context legible at scale \- OpenReview, accessed January 26, 2026, [https://openreview.net/pdf?id=kJfpS7lCVT](https://openreview.net/pdf?id=kJfpS7lCVT)  
8. (PDF) PICTURES, MODELS, AND MEASURES \- Academia.edu, accessed January 26, 2026, [https://www.academia.edu/36117971/PICTURES\_MODELS\_AND\_MEASURES](https://www.academia.edu/36117971/PICTURES_MODELS_AND_MEASURES)  
9. Engineering Models Circa 1914 and in Wittgenstein's Tractatus, accessed January 26, 2026, [https://soar.wichita.edu/bitstreams/b5106b9e-dfe7-4a3f-9b93-2620e276c7d7/download](https://soar.wichita.edu/bitstreams/b5106b9e-dfe7-4a3f-9b93-2620e276c7d7/download)  
10. Engineering models circa 1914 and in Wittgenstein's "Tractatus", accessed January 26, 2026, [https://scispace.com/pdf/physical-pictures-engineering-models-circa-1914-and-in-46lu91kztk.pdf](https://scispace.com/pdf/physical-pictures-engineering-models-circa-1914-and-in-46lu91kztk.pdf)  
11. WITTGENSTEINIAN (adj.): Looking at the World from the Viewpoint ..., accessed January 26, 2026, [https://dokumen.pub/wittgensteinian-adj-looking-at-the-world-from-the-viewpoint-of-wittgensteins-philosophy-1st-ed-2020-978-3-030-27568-6-978-3-030-27569-3.html](https://dokumen.pub/wittgensteinian-adj-looking-at-the-world-from-the-viewpoint-of-wittgensteins-philosophy-1st-ed-2020-978-3-030-27568-6-978-3-030-27569-3.html)  
12. AIdeation: Designing a Human-AI Collaborative Ideation System for ..., accessed January 26, 2026, [https://arxiv.org/html/2502.14747v1](https://arxiv.org/html/2502.14747v1)  
13. Prompt Engineering For Text-Based Generative Art | PDF \- Scribd, accessed January 26, 2026, [https://www.scribd.com/document/927770939/Prompt-Engineering-for-Text-Based-Generative-Art](https://www.scribd.com/document/927770939/Prompt-Engineering-for-Text-Based-Generative-Art)  
14. An Annotated Reading of 'The Singer of Tales' in the LLM Era \- arXiv, accessed January 26, 2026, [https://arxiv.org/pdf/2502.05148](https://arxiv.org/pdf/2502.05148)  
15. Which Contributions Deserve Credit? Perceptions of Attribution in ..., accessed January 26, 2026, [https://www.researchgate.net/publication/391269935\_Which\_Contributions\_Deserve\_Credit\_Perceptions\_of\_Attribution\_in\_Human-AI\_Co-Creation](https://www.researchgate.net/publication/391269935_Which_Contributions_Deserve_Credit_Perceptions_of_Attribution_in_Human-AI_Co-Creation)  
16. A Taxonomy of Prompt Modifiers for Text-To-Image Generation \- arXiv, accessed January 26, 2026, [https://arxiv.org/pdf/2204.13988](https://arxiv.org/pdf/2204.13988)  
17. Operative ekphrasis: the collapse of the text/image distinction in ..., accessed January 26, 2026, [https://www.tandfonline.com/doi/full/10.1080/02666286.2024.2330335](https://www.tandfonline.com/doi/full/10.1080/02666286.2024.2330335)  
18. Operative ekphrasis: The collapse of the text/image distinction in ..., accessed January 26, 2026, [https://www.researchgate.net/publication/372400146\_Operative\_ekphrasis\_The\_collapse\_of\_the\_textimage\_distinction\_in\_multimodal\_AI\_PLEASE\_REFER\_TO\_PUBLISHED\_VERSION](https://www.researchgate.net/publication/372400146_Operative_ekphrasis_The_collapse_of_the_textimage_distinction_in_multimodal_AI_PLEASE_REFER_TO_PUBLISHED_VERSION)  
19. Flexible Sense-Making for AI Art-Making with DreamSheets \- arXiv, accessed January 26, 2026, [https://arxiv.org/html/2310.09985v2](https://arxiv.org/html/2310.09985v2)  
20. Promptify: Text-to-Image Generation through Interactive Prompt ..., accessed January 26, 2026, [https://www.dgp.toronto.edu/\~bryanw/pdf/promptify.pdf](https://www.dgp.toronto.edu/~bryanw/pdf/promptify.pdf)  
21. AI-Assisted Causal Pathway Diagram for Human-Centered Design, accessed January 26, 2026, [https://faculty.washington.edu/garyhs/docs/zhong-CHI2024-CPD.pdf](https://faculty.washington.edu/garyhs/docs/zhong-CHI2024-CPD.pdf)  
22. A taxonomy of prompt modifiers for text-to-image generation, accessed January 26, 2026, [https://www.tandfonline.com/doi/full/10.1080/0144929X.2023.2286532](https://www.tandfonline.com/doi/full/10.1080/0144929X.2023.2286532)  
23. (PDF) A Spreadsheet Approach to Information Visualization, accessed January 26, 2026, [https://www.researchgate.net/publication/2408972\_A\_Spreadsheet\_Approach\_to\_Information\_Visualization](https://www.researchgate.net/publication/2408972_A_Spreadsheet_Approach_to_Information_Visualization)