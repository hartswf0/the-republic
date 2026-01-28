# **THICK PROMPTING: REIMAGINING EKPHRASIS AND GEERTZIAN RITUAL FOR MULTIMODAL DESIGN**

## **1\. Introduction: The Interpretive Turn in Generative Computation**

The contemporary landscape of digital design is currently undergoing a seismic shift, precipitated by the rapid maturation of generative artificial intelligence. As we transition from the era of static command-line interfaces and direct manipulation tools into an age defined by probabilistic, multimodal systems, the fundamental nature of the interaction between human intent and machine output is being radically redefined. We stand at a juncture where the "prompt"—a string of natural language text—has become the primary instrument for invoking complex visual, spatial, and kinetic realities. However, the prevailing methodologies for engaging with these systems, colloquially and technically grouped under the banner of "prompt engineering," betray a mechanistic reductionism that fails to capture the true ontological weight of this new medium. This report introduces and rigorously develops the theoretical framework of "Thick Prompting," a concept situated at the intellectual intersection of Jay David Bolter’s media theory and Gaia Hartsoe’s research within the Digital Media program at the Georgia Institute of Technology.1

Thick Prompting is not merely a set of optimization techniques for extracting higher-fidelity images from diffusion models; it is a comprehensive methodological intervention that synthesizes two distinct yet complementary intellectual traditions: the literary and art-historical concept of **ekphrasis**—specifically the "operative ekphrasis" proposed by Hannes Bajohr 3—and the anthropological methodology of **thick description** pioneered by Clifford Geertz.4 By integrating these frameworks, Thick Prompting addresses the critical "thinness" of current AI outputs—characterized by high visual resolution but low semantic coherence—and proposes a new design ontology for the creation of inhabitable, multimodal fictions.

The urgency of this investigation is driven by the technological leap from "text-to-image" generation to "text-to-world" simulation. As evidenced by the emergence of "World Models" such as Google DeepMind’s Genie 3 5, World Labs’ Marble 7, and Runway’s GWM-1 8, we are moving toward systems where language does not simply retrieve a static picture but generates coherent, interactive 3D environments complete with physics, causality, and temporality. In this context, the prompt becomes a "Worldtext" 9, a performative utterance that remediates reality itself. If the prompts governing these worlds remain "thin"—lacking in cultural context, narrative depth, and ritualistic specificity—the resulting environments will be brittle, hallucinatory, and ultimately uninhabitable. Thus, Thick Prompting emerges not just as an aesthetic preference, but as a functional requirement for the stability and meaningfulness of the next generation of spatial computing.

This report will chart the genealogy of this concept, exploring how Bolter’s theories of remediation and reality media provide the historical scaffolding for understanding generative AI.11 It will delve into the mechanics of operative ekphrasis, examining how the collapse of the distinction between code and image necessitates a new form of literacy.3 It will analyze the anthropological dimensions of the human-AI loop, reframing the prompt as a ritualistic engagement with an "alien" intelligence.13 Finally, it will provide a detailed technical analysis of how "thickness" can be engineered into prompts through inception frameworks, JSON structuring, and latent space exploration.15

## ---

**2\. Theoretical Foundations: The Genealogy of Thickness**

To rigorously define Thick Prompting, one must first excavate the theoretical strata upon which it rests. This requires a deep engagement with the history of media theory, specifically the work emanating from the Georgia Tech School of Literature, Media, and Communication, where scholars like Jay David Bolter have long interrogated the relationship between writing, technology, and visual culture.1

### **2.1 From Remediation to Reality Media**

The intellectual lineage of this framework begins with the seminal concept of **Remediation**, articulated by Bolter and Richard Grusin in their 1999 text, *Remediation: Understanding New Media*.11 They argued that no medium is truly "new"; rather, all media achieve cultural significance by refashioning their predecessors. The World Wide Web remediated television, which remediated film, which remediated theater and photography. This process is governed by a double logic: **immediacy** (the desire for the medium to disappear, leaving the viewer in the presence of the represented object) and **hypermediacy** (the multiplication of signs and windows, making the viewer acutely aware of the medium itself).11

In the context of generative AI, we are witnessing a hyper-accelerated form of remediation. A model like DALL-E or Midjourney remediates the entire history of art and photography, digesting billions of images to reproduce their stylistic markers on command. However, the interaction with these systems introduces a new paradox. The interface—a simple text box—suggests ultimate immediacy; one types a word, and the thing appears. Yet, the output often reveals the deep hypermediacy of the system: artifacts, glitches, and the uncanny valley effects that remind us we are looking at a statistical probability, not a photograph.18

Bolter’s more recent work, *Reality Media* (2021), extends this analysis to Augmented Reality (AR) and Virtual Reality (VR).12 He argues that these technologies do not merely represent the world but seek to take their place alongside it, blurring the distinction between the virtual and the real. Generative AI fundamentally radicalizes this proposition. With "text-to-world" models, the "reality medium" is no longer captured via cameras or modeled by hand; it is synthesized from language. This shifts the site of remediation from the screen to the *latent space*—the multidimensional vector field where the model stores its "knowledge" of visual concepts. Thick Prompting, therefore, is the methodology for navigating this remediated reality. It acknowledges that to generate a "photograph" in AI is not to take a picture, but to *cite* the history of photography—to invoke the specific film stocks, lighting techniques, and cultural contexts that define "photographic" reality.18

### **2.2 Geertzian Deep Description: The Wink and the Twitch**

The metaphor of "thickness" is derived directly from the interpretive anthropology of Clifford Geertz, specifically his differentiation between a "thin description" and a "thick description," a concept he adapted from the philosopher Gilbert Ryle.4

Geertz illustrates this distinction with the example of a wink. Consider two boys rapidly contracting the eyelids of their right eyes. In a "thin description," these two acts are identical: a physiological contraction of the orbicularis oculi muscle. There is no difference between an involuntary twitch and a conspiratorial signal. However, in a "thick description," the difference is vast. The wink is a communicative act; it is deliberate, directed at someone, intended to impart a specific message, done according to a socially established code, and executed without the knowledge of the rest of the company.20

This anthropological distinction is the precise analogue for the crisis in generative AI prompting.

* **The Machine Twitch (Thinness):** When a user prompts a model with a generic instruction like "a cyberpunk city," the AI produces a "twitch." It identifies the statistical correlation between the token "cyberpunk" and certain visual features (neon, rain, darkness) and executes a generation. The result is often a hollow pastiche—visually recognizable but culturally empty. It lacks specific intent; it is a reflex of the training data.  
* **The Designed Wink (Thickness):** "Thick Prompting" attempts to force the model to "wink." It requires the user to input the "stratified hierarchy of meaningful structures" 22 that distinguishes a generic image from a meaningful artifact. A thick prompt does not just ask for "cyberpunk"; it asks for "the claustrophobic density of Kowloon Walled City, shot on 35mm Tungsten film, invoking the high-tech low-life ethos of William Gibson, with the architectural decay of post-Soviet brutalism."

By explicitly encoding the cultural, historical, and technical context, the user constrains the infinite variability of the latent space, forcing the model to generate an image that carries the specific "conspiratorial" weight of the intended reference. The model is no longer twitching; it is engaging in a complex cultural citation.23

### **2.3 The "Web of Significance" in Latent Space**

Geertz famously defined culture as the "webs of significance" that humanity has spun and in which we are suspended.4 In the era of Large Language Models (LLMs) and Large Multimodal Models (LMMs), these webs have been digitized, tokenized, and compressed into the weights of neural networks. The "latent space" of a model like GPT-4 or Stable Diffusion is, effectively, a mathematical map of human culture’s webs of significance.25

However, the model navigates these webs via vector proximity (cosine similarity) rather than semantic understanding. It knows that "king" is close to "queen," but it does not understand monarchy. "Thick Prompting" is the act of re-injecting the *human* understanding of these webs back into the *mathematical* navigation of them. It is an act of "interpretive anthropology" performed on a synthetic subject. The designer must "wallow in the microscopic scale" of the model’s capabilities, learning its specific dialect, biases, and "imaginative universe" to effectively communicate intent.4

## ---

**3\. Operative Ekphrasis: The Performative Text**

The mechanism by which Thick Prompting operates is best understood through the lens of **Operative Ekphrasis**, a concept developed by scholar Hannes Bajohr to describe the unique relationship between text and image in AI systems.3

### **3.1 The Collapse of Representation and Operation**

Classically, **ekphrasis** refers to the verbal description of a visual work of art. It is a rhetorical device found in antiquity (Homer’s description of the Shield of Achilles) and Romantic poetry (Keats’s *Ode on a Grecian Urn*).27 In traditional ekphrasis, there is a fundamental separation between the word and the image; the text *represents* the image, but it cannot *produce* it. This separation creates what W.J.T. Mitchell calls "ekphrastic hope" (the desire for language to make the image present) and "ekphrastic fear" (the anxiety that the distinction between the two might collapse).28

Bajohr argues that in multimodal AI, this distinction *has* collapsed. We have entered the age of **Operative Ekphrasis**.3 In a system like Midjourney or Genie, the text does not merely describe the image; it *executes* it. The relationship is performative and causal. The prompt is a "computational operation that correlates text and image".26 The text is the code that generates the visual reality.

### **3.2 Sequential vs. Connectionist Paradigms**

To understand why "thickness" is required, we must distinguish between the two paradigms of digital operation described by Bajohr:

1. **Sequential Paradigm (Classical Code):** In traditional programming, instructions are explicit and syntactic. draw\_line(x1, y1, x2, y2). The relationship between input and output is deterministic and "thin."  
2. **Connectionist Paradigm (Neural Networks):** In AI, instructions are implicit and semantic. The system is a "black box" of weighted connections. The input "draw a sad line" is processed through billions of parameters to produce a result based on statistical probability.3

In the connectionist paradigm, the "code" (the prompt) operates on a level of **artificial semantics**.3 The model "understands" concepts like "sadness" or "cyberpunk" as clusters of vectors. Because this understanding is probabilistic, a "thin" prompt (e.g., "a dog") results in the model reverting to the statistical mean—the most generic, average representation of a dog found in the training data. This is the "stereotype" inherent in the model.

**Thick Prompting** is the necessary methodology for controlling Operative Ekphrasis. Because the model operates on "artificial semantics" rather than explicit rules, the user must provide a "thick" input to steer the generation away from the statistical average. The user must manipulate the "operative" text to activate specific, less probable, but more culturally resonant regions of the latent space.

### **3.3 The Worldtext and the Textual Condition**

The rise of Operative Ekphrasis suggests that "everything is text".3 The image file is alphanumeric code; the generation process is mathematical text; the interface is natural language. This leads to the concept of the **Worldtext** 9, where the world itself becomes a legible and writable text.

In "text-to-world" systems, the prompt is the "Worldtext." It is the DNA of the simulation. A "thin" Worldtext results in a "thin" world—one that lacks physical consistency or narrative logic. A "thick" Worldtext encodes the complexity of the world into the linguistic interface. This confirms Bolter’s suspicion that we are moving toward a state where "all media exists in relation to new media" 11, but with a twist: all reality now exists in relation to the *textual* capabilities of the AI model.

## ---

**4\. The Architecture of the Thin: Analyzing the Current Crisis**

Before detailing the methodologies of Thick Prompting, it is essential to diagnose the limitations of current practices, often aggrandized as "Prompt Engineering."

### **4.1 The Semantic Void of "Prompt Engineering"**

The term "Prompt Engineering" borrows the prestige of engineering disciplines to describe what is often a chaotic, trial-and-error process. It implies a precise, deterministic science. However, researchers and practitioners increasingly recognize that this framing is misleading. Interacting with high-dimensional latent spaces is often more akin to **alchemy** or **magical thinking** than engineering.29

Users frequently employ "incantations"—specific keywords like "Unreal Engine," "4k," "trending on ArtStation," or "masterpiece"—without understanding why they work. They are treating the prompt as a magical spell; if the correct sequence of words is uttered, the desired result will manifest. This is "thin description" in action. The user observes that adding "4k" makes the image look better (the twitch) but does not understand *why* (the wink)—namely, that images tagged "4k" in the training dataset tend to be higher resolution and have better lighting.

This "cargo cult" approach to prompting limits the creative potential of the medium. It relies on "superstitious thinking" 30 rather than a deep understanding of the model’s internal culture. It leads to a homogenization of aesthetics, where every image looks like a "trending on ArtStation" digital painting because everyone is using the same "thin" incantations.

### **4.2 Biases and Representational Fidelity**

The "thinness" of current prompting practices also exacerbates the inherent biases of AI models. Research into **Representational Fidelity** 31 indicates that LLMs and image generators systematically amplify the perspectives of internet users (typically Western, educated, younger) while marginalizing non-users.

When a user provides a "thin" prompt like "a doctor," the model defaults to its statistical center: a white male. This is a failure of representation caused by a failure of description. To achieve "representational fidelity" for underrepresented groups, the prompt must be "thick." It must explicitly describe the race, gender, cultural context, and setting. A "thick" evaluation of AI systems reveals that they struggle with "cultural knowledge processing" unless explicitly guided by retrieval mechanisms or thick context.33

Thus, Thick Prompting is not just an aesthetic tool; it is an ethical imperative. It is the mechanism by which users resist the "thinning" of human diversity into algorithmic stereotypes.

## ---

**5\. Technical Frameworks: Engineering Thickness**

Thick Prompting is not merely a theoretical stance; it is implemented through specific technical frameworks that structure the interaction between human and machine. These frameworks transform the "thin" command line into a "thick" interface for cultural negotiation.

### **5.1 Inception Prompting and Role-Playing**

One of the most robust methods for achieving narrative and contextual thickness is **Inception Prompting**.15 This technique involves "priming" the AI with a specific persona, context, or scenario before the actual task begins.

* **Mechanism:** Instead of asking "Write a poem about a tree," the user creates a "thick" framing: "You are an 18th-century Romantic poet suffering from melancholia, sitting beneath an ancient oak tree in the Lake District. Write a poem that reflects your internal state and the sublime nature of the landscape."  
* **The CAMEL Framework:** Research into "Communicative Agents" (CAMEL) creates automated "role-playing" sessions where two AI agents interact.15 One adopts the role of the "User" (e.g., Stock Trader) and the other the "Assistant" (e.g., Python Programmer). They engage in a dialogue to solve a task. This "Inception Prompting" creates a self-sustaining "thick" context. The agents prompt each other, adding layers of detail and constraint that a single human user might omit.  
* **Impact:** This technique forces the model to access a specific "persona vector" in the latent space. It narrows the search space from "all possible text" to "text consistent with 18th-century Romanticism." This increases coherence and reduces hallucinations by establishing a narrative logic that the model must follow.

### **5.2 Structured "JSON" Prompting**

While Inception Prompting addresses *narrative* thickness, **JSON Prompting** addresses *structural* thickness.16 Natural language is often ambiguous. For complex design tasks, particularly in generating assets for games or films, ambiguity is fatal.

JSON (JavaScript Object Notation) allows users to encapsulate "thick" descriptions in a rigid, hierarchical format.

* **Key-Value Constraints:** Instead of a paragraph, the user inputs:  
  JSON  
  {  
    "Subject": "Cyberpunk Street Samurai",  
    "Environment": {  
      "Location": "Neo-Tokyo Slums",  
      "Weather": "Acid Rain",  
      "Lighting": "Neon Blue and Pink"  
    },  
    "Style": {  
      "Reference": "Blade Runner 2049",  
      "Medium": "Digital Painting",  
      "Artist": "Syd Mead"  
    },  
    "Technical": {  
      "Aspect\_Ratio": "16:9",  
      "Resolution": "8k"  
    }  
  }

* **Baking the Prompt:** This technique "bakes" the text into the image generation process.16 It acts as a contract between the user and the model. By separating "Content" from "Style" from "Technical Specs," the user provides a "thick" blueprint that prevents the model from conflating the subject with the style.  
* **Veo 3 and Video Generation:** In advanced video models like Google’s **Veo 3**, JSON prompting is essential for controlling temporal consistency.39 Users define "actors," "scene descriptions," and "camera movements" in separate JSON fields. This allows for "shot-by-shot" control, turning the prompt into a directorial script rather than a vague suggestion.

### **5.3 Latent Space Exploration (LSE) as Deep Description**

The most technical frontier of Thick Prompting involves the direct manipulation of the **latent space**—the n-dimensional vector space where the model stores its knowledge.17

* **SeedSelect and Interpolation:** Techniques like "SeedSelect" allow users to find the optimal "seed" (random noise starting point) for a specific concept.17 By interpolating between two seeds (e.g., blending the vector for "Victorian" with the vector for "Sci-Fi"), users can discover "hybrid" concepts that exist in the latent space but have no direct linguistic label.  
* **LatentPrompt:** This framework automates the optimization of prompts.40 It treats the prompt as a vector and "explores" the surrounding space to find a vector that yields better results on a specific task. This is "automated ethnography" of the model’s brain—using the machine to map its own "webs of significance."  
* **Meaning as Geometry:** These techniques reveal that in AI, meaning is geometric. "Thick Prompting" is the art of triangulation. It involves using multiple descriptors (vectors) to pinpoint a precise coordinate in the hypercube where the desired "wink" resides.

### **5.4 Chain-of-Thought (CoT) and Reflexivity**

**Chain-of-Thought** prompting encourages the model to "show its reasoning" before generating a final answer.41 This adds "thickness" to the *process* of generation.

* **Mechanism:** "Think step-by-step. First, analyze the historical context of the request. Second, identify key visual signifiers. Third, generate the image description."  
* **Reflexivity:** This parallels the "reflexivity" required in ethnographic research. The researcher (or AI) must account for their own interpretive process. By forcing the AI to verbalize its logic, CoT transforms the generation from a black-box reflex (twitch) into a transparent, interpretive act (wink). This has been shown to significantly improve performance on complex reasoning tasks and code generation.42

## ---

**6\. From Text-to-Image to Text-to-World**

The application of Thick Prompting reaches its zenith in the domain of **Text-to-World** generation. As AI models evolve to generate 3D environments, the prompt becomes the "physics engine" and the "architect" of the simulation.

### **6.1 The Rise of World Models**

We are witnessing the emergence of "World Models" that simulate reality.

* **Genie 3 (Google DeepMind):** A foundation world model capable of generating fully controllable, interactive 3D environments from text and image prompts.5 It operates at 24fps and 720p resolution, learning physics and causal dynamics from video data. A "thin" prompt here ("a game") fails to leverage the model's capacity. A "thick" prompt must describe the *mechanics* ("a platformer with low gravity and bouncy terrain").  
* **Marble (World Labs):** Focuses on creating static, persistent 3D worlds from text. It allows for "iterative editing," where the user can refine the world through dialogue.7  
* **GWM-1 (Runway):** A general world model that allows for "action-conditioned" generation. The user prompts not just the scene, but the *agent's interaction* with it.8

### **6.2 Spatial Narrative and Vocabulary**

Generating a world requires **Spatial Narrative**.45 The prompt must generate a "spatial syntax"—a logical arrangement of space that tells a story.

* **Spatial Vocabularies:** Research in architectural AI suggests that users need to develop "spatial vocabularies" to effectively prompt 3D models.45 A prompt like "a spooky house" is insufficient. A thick prompt must describe the "spatial grammar": "A Victorian hallway (Structure) connecting to a dimly lit library (adjacency), creating a sense of foreboding through narrow corridors and high ceilings (Atmosphere)."  
* **Holodeck:** The **Holodeck** system 47 generates 3D environments by first using an LLM to generate a "layout" (a thick structural description) and then populating it with assets. This intermediate step—translating text to layout—is the essence of Thick Prompting. It translates the "fiction" of the text into the "habitation" of the world.

### **6.3 Inhabitable Fictions**

The concept of "Inhabitable Fictions" 48 suggests that the goal of spatial design is to transform volumes of space into immersive environments. In AI world generation, the prompt is the script for this transformation.

* **Skybox AI (Blockade Labs):** This tool generates 360-degree panoramas.49 The prompting guide explicitly advises users to build "thick" descriptions involving "indoors/outdoors," "camera POV," and "negative text" to construct a coherent space.  
* **Atmosphere as Physics:** In world models, descriptive adjectives act as physical constraints. Describing a world as "dreamlike" might alter the consistency of objects (morphing, floating). Describing it as "realistic" enforces rigid body dynamics. The "adjective" becomes a "variable" in the simulation.

### **6.4 Table: Comparative Analysis of Text-to-World Models**

| Model | Developer | Primary Output | "Thickness" Requirement | Interaction Methodology |
| :---- | :---- | :---- | :---- | :---- |
| **Genie 3** | Google DeepMind | Interactive 3D Worlds (24fps) | **High:** Requires description of mechanics, physics, and agent actions. | Real-time control, learned physics simulation.5 |
| **Marble** | World Labs | Static 3D Environments | **Medium:** Focus on visual detail, lighting, and spatial layout. | Iterative editing, "Chisel" tools, multi-modal input.7 |
| **GWM-1** | Runway | Action-Conditioned Video/World | **High:** Prompts must define agent behavior and camera movement. | Autoregressive video generation, camera pose control.8 |
| **Skybox AI** | Blockade Labs | 360° Panoramas | **Medium:** Focus on horizon lines, POV, and style coherence. | "Remixing" worlds, negative prompting, style presets.49 |
| **Holodeck** | UPenn / AI2 | 3D Scene Layouts (Obj/JSON) | **Very High:** Requires explicit object relations and spatial constraints. | Procedural generation via LLM-defined constraints.47 |

## ---

**7\. Ritual and Performance: The Human-AI Loop**

The framework of Thick Prompting extends beyond the technical into the performative. The interaction with generative AI is increasingly viewed as a form of **ritual**—a structured, repetitive performance that mediates the relationship between the human and the "alien" intelligence of the machine.

### **7.1 AI as Ritual and Divination**

Anthropological research into "AI as Ritual" 14 suggests that users engage with these systems in ways that parallel divination or augury.52 The interface is the "magic circle"; the prompt is the "incantation"; the generation is the "oracle."

* **The Black Box as Mystery:** Because the internal logic of a deep neural network is opaque (the "Black Box problem"), the user cannot fully "know" the system. They must "feel" it out through ritualistic trial and error. Thick Prompting formalizes this ritual. It transforms the incantation from a superstitious act (using "magic words" without understanding) into a deliberate design practice based on a deep knowledge of the system's "spirits" (weights and biases).29  
* **Collaborative Rituals:** Projects like *Humane Methods* or *Corpus Nil* 13 stage this ritual explicitly. In *Corpus Nil*, a dancer performs a "ritualistic interaction" with an AI system. The dancer's body provides the "thick prompt" (muscular tension, sweat, movement), and the AI interprets this to generate sound and light. This suggests a future of **Gestural Thick Prompting**, where the body itself becomes the instrument of operative ekphrasis.

### **7.2 The Dialogic of Adaptation**

The interaction is not one-way. It is a "dialogic of adaptation".54 The user prompts the AI; the AI generates a "twitch" or a "wink"; the user interprets this signal and refines the prompt. This feedback loop is the essence of the design process.

* **Beyond Fidelity:** Traditional adaptation studies focus on "fidelity" to the source text. In Thick Prompting, fidelity is secondary to **expressivity**.55 The goal is not to perfectly reproduce the user's mental image (which is impossible) but to engage in a "jazz-like" improvisation with the model to discover a new, shared reality.  
* **The AI as Actor:** In this ritual, the AI is not a tool but an "actor" or "partner".13 It has agency (or at least, complex reactivity). Thick Prompting acknowledges this agency. It treats the AI as a collaborator that must be "persuaded" or "guided" rather than "commanded."

### **7.3 Affective Computing and Expressive Metrics**

To evaluate the success of these rituals, we need new metrics. Standard metrics like "accuracy" or "latency" are "thin." We need **Expressive Metrics** 57 that measure emotional intensity, style transfer, and cultural resonance.

* **EmoSphere-TTS:** Research into expressive text-to-speech (TTS) utilizes a "spherical emotion vector" to control the intensity and style of speech.57 This is a form of Thick Prompting for audio. The user does not just input text; they input a coordinate in the "emotion sphere," defining the "thickness" of the delivery (e.g., "sadness with a hint of anger").  
* **Våken:** The *Våken* system uses biosignals to facilitate "ritualistic interaction" corresponding to basic emotions.59 Here, the "prompt" is the user's biological state, interpreted through a "thick" layer of emotional analysis.

## ---

**8\. The Future of Design: The Ethnographer-Engineer**

The rise of Thick Prompting signals a fundamental shift in the required skillset for the designer of the future. We are moving away from the "Prompt Engineer" (who optimizes syntax) toward the **Prompt Ethnographer** or **Latent Space Curator**.

### **8.1 The Ethnographer's Toolkit**

The effective designer must possess an "ethnographic" understanding of the model. They must be able to:

1. **Map the Culture of the Model:** Understand the biases, stereotypes, and aesthetic tendencies embedded in the training data (e.g., knowing that the model associates "cyberpunk" with "rain" and "neon").  
2. **Employ Cultural Literacy:** Use "thick" cultural codes (art history references, cinematic tropes, literary styles) to guide the model. A prompt referencing "Chiaroscuro" is thicker than one saying "high contrast".12  
3. **Perform Rituals of Verification:** Use techniques like "Inception" and "Chain-of-Thought" to verify the model's reasoning and ensure "representational fidelity".31

### **8.2 The Worldtext and the End of Distinction**

As "Text-to-World" models mature, the concept of the **Worldtext** becomes central.9 The world itself becomes a text that is written and read. The distinction between "authoring" a story and "building" a level dissolves.

* **Implication:** Literacy becomes the primary mode of world-building. The ability to write "thick," nuanced, and structurally sound prompts becomes the ability to shape reality.  
* **The Risk of the Thin:** If we lose the ability to "thickly" describe our world—if we rely on "thin" auto-completes and default settings—we risk living in a "thin" reality, defined by corporate algorithms and statistical averages. Thick Prompting is a defense of human nuance against the smoothing effects of the algorithm.

### **8.3 Conclusion: The Wink of the Machine**

The framework of **Thick Prompting** provides a necessary roadmap for the future of multimodal design. It asserts that the "prompt" is not a command line, but a site of profound cultural negotiation. By integrating **Operative Ekphrasis** (the recognition of text’s performative power) with **Geertzian Thick Description** (the requirement for interpretive context), we can move beyond the "twitch" of the glitch and achieve the "wink" of meaningful communication.

As AI systems evolve into "World Models" capable of simulating consistent realities, the thickness of our prompts will determine the depth of the worlds we inhabit. The designer must learn to become an ethnographer of the latent space, crafting inhabitable fictions that resonate with the complexity, ambiguity, and richness of the real.

## ---

**9\. Selected References and Data Clusters**

### **9.1 Theoretical Frameworks**

* **Thick Description:** Geertz.4  
* **Remediation & Reality Media:** Bolter & Grusin.11  
* **Ekphrasis (Classical/Operative):** Mitchell 27; Bajohr.3  
* **Ritual & Magic:**.13

### **9.2 Technical Architectures**

* **Text-to-World Models:** Genie 3 5; Marble 7; GWM-1 8; Skybox.49  
* **Prompting Techniques:** Inception/Role-Playing 15; JSON 16; Latent Space Exploration.17  
* **Evaluation Metrics:** Representational Fidelity 31; Expressivity 57; Text2World Benchmarks.63

### **9.3 Case Studies**

* **Humane Methods / Corpus Nil:**.13  
* **Inhabitable Fictions:**.48  
* **Text2World Benchmark:**.63  
* **Space/Architecture:** Holodeck 47; SceneTeller.64

#### **Works cited**

1. PhD in Digital Media, accessed January 26, 2026, [https://dm.lmc.gatech.edu/program/phd-program/](https://dm.lmc.gatech.edu/program/phd-program/)  
2. Jay David Bolter: Augmented and Virtual Reality \- YouTube, accessed January 26, 2026, [https://www.youtube.com/watch?v=hkXNz5d6hg8](https://www.youtube.com/watch?v=hkXNz5d6hg8)  
3. Operative ekphrasis: the collapse of the text/image distinction in ..., accessed January 26, 2026, [https://www.tandfonline.com/doi/full/10.1080/02666286.2024.2330335](https://www.tandfonline.com/doi/full/10.1080/02666286.2024.2330335)  
4. Clifford Geertz's “Thick Description” \- A Travelogue of Literary Arts, accessed January 26, 2026, [https://mylitjourney.wordpress.com/2019/09/13/clifford-geertzs-thick-description/](https://mylitjourney.wordpress.com/2019/09/13/clifford-geertzs-thick-description/)  
5. World Models: The Next Leap Beyond LLMs | by Graison Thomas, accessed January 26, 2026, [https://medium.com/@graison/world-models-the-next-leap-beyond-llms-012504a9c1e7](https://medium.com/@graison/world-models-the-next-leap-beyond-llms-012504a9c1e7)  
6. Google's Genie 3: The Future of AI-Generated Interactive Worlds, accessed January 26, 2026, [https://www.imagine.art/blogs/google-genie-3-overview](https://www.imagine.art/blogs/google-genie-3-overview)  
7. Marble: A Multimodal World Model \- World Labs, accessed January 26, 2026, [https://www.worldlabs.ai/blog/marble-world-model](https://www.worldlabs.ai/blog/marble-world-model)  
8. Best AI World Models \[2026\]: Where to Play Immersive Text-to-World ..., accessed January 26, 2026, [https://worldsimulator.ai/blog/articles/best-ai-world-models](https://worldsimulator.ai/blog/articles/best-ai-world-models)  
9. Diffractive Reading: New Materialism, Theory, Critique 1786613964 ..., accessed January 26, 2026, [https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html](https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html)  
10. Language in the Buddhist Tantra of Japan: Indic Roots of Mantra ..., accessed January 26, 2026, [https://dokumen.pub/language-in-the-buddhist-tantra-of-japan-indic-roots-of-mantra-9781350037267-9781350038110-9781350037274.html](https://dokumen.pub/language-in-the-buddhist-tantra-of-japan-indic-roots-of-mantra-9781350037267-9781350038110-9781350037274.html)  
11. After Class Writing: Bolter and Grusin's “Remediation”, accessed January 26, 2026, [https://openlab.citytech.cuny.edu/elliseng1710sp2018/2018/03/22/after-class-writing-bolter-and-grusins-remediation/](https://openlab.citytech.cuny.edu/elliseng1710sp2018/2018/03/22/after-class-writing-bolter-and-grusins-remediation/)  
12. Reality Media: Augmented and Virtual Reality by Jay David Bolter, accessed January 26, 2026, [https://www.goodreads.com/book/show/56903760-reality-media](https://www.goodreads.com/book/show/56903760-reality-media)  
13. Artificial Intelligence in Music and Performance: A Subjective Art ..., accessed January 26, 2026, [https://arxiv.org/pdf/2007.15843](https://arxiv.org/pdf/2007.15843)  
14. AI as intermediary in modern-day ritual: An immersive, interactive ..., accessed January 26, 2026, [https://arxiv.org/html/2511.06195v1](https://arxiv.org/html/2511.06195v1)  
15. CAMEL: Communicative Agents for “Mind” Exploration of Large ..., accessed January 26, 2026, [https://proceedings.neurips.cc/paper\_files/paper/2023/file/a3621ee907def47c1b952ade25c67698-Paper-Conference.pdf](https://proceedings.neurips.cc/paper_files/paper/2023/file/a3621ee907def47c1b952ade25c67698-Paper-Conference.pdf)  
16. The JSON Art Director. Vibe Rendering \- Leon Nicholls, accessed January 26, 2026, [https://leonnicholls.medium.com/the-json-art-director-f826c507dd2d](https://leonnicholls.medium.com/the-json-art-director-f826c507dd2d)  
17. Norm-guided latent space exploration for text-to-image generation, accessed January 26, 2026, [https://papers.nips.cc/paper\_files/paper/2023/file/b49213694c3e752252d62ca360b72a36-Paper-Conference.pdf](https://papers.nips.cc/paper_files/paper/2023/file/b49213694c3e752252d62ca360b72a36-Paper-Conference.pdf)  
18. Jay David Bolter and Richard Grusin, Remediation Understanding ..., accessed January 26, 2026, [https://www.scribd.com/document/539659524/Jay-David-Bolter-and-Richard-Grusin-Remediation-Understanding-New-Media](https://www.scribd.com/document/539659524/Jay-David-Bolter-and-Richard-Grusin-Remediation-Understanding-New-Media)  
19. Remediation: Understanding New Media by Jay David Bolter, accessed January 26, 2026, [https://www.goodreads.com/book/show/126280.Remediation](https://www.goodreads.com/book/show/126280.Remediation)  
20. Thick Description: \- Toward an Interpretive Theory of Culture 1973, accessed January 26, 2026, [https://people.ucsc.edu/\~ktellez/geertz1973.pdf](https://people.ucsc.edu/~ktellez/geertz1973.pdf)  
21. Thick description \- Grokipedia, accessed January 26, 2026, [https://grokipedia.com/page/Thick\_description](https://grokipedia.com/page/Thick_description)  
22. Symbolic and Interpretive Anthropologies, accessed January 26, 2026, [https://anthropology.ua.edu/theory/symbolic-and-interpretive-anthropologies/](https://anthropology.ua.edu/theory/symbolic-and-interpretive-anthropologies/)  
23. accessed January 26, 2026, [https://arxiv.org/html/2503.19075v1\#:\~:text=Ryle's%20classic%20example%20of%20a,as%20a%20signal%20to%20interlocutors.](https://arxiv.org/html/2503.19075v1#:~:text=Ryle's%20classic%20example%20of%20a,as%20a%20signal%20to%20interlocutors.)  
24. Wink or Twitch: The Case for Ethnography in Communications, accessed January 26, 2026, [https://www.neboagency.com/blog/wink-or-twitch-the-case-for-ethnography-in-communications/](https://www.neboagency.com/blog/wink-or-twitch-the-case-for-ethnography-in-communications/)  
25. Operative ekphrasis: The collapse of the text/image distinction in ..., accessed January 26, 2026, [https://www.researchgate.net/publication/372400146\_Operative\_ekphrasis\_The\_collapse\_of\_the\_textimage\_distinction\_in\_multimodal\_AI\_PLEASE\_REFER\_TO\_PUBLISHED\_VERSION](https://www.researchgate.net/publication/372400146_Operative_ekphrasis_The_collapse_of_the_textimage_distinction_in_multimodal_AI_PLEASE_REFER_TO_PUBLISHED_VERSION)  
26. Operative Ekphrasis and the Reduction of Fashion Through ..., accessed January 26, 2026, [https://www.researchgate.net/publication/396119864\_Possible\_Fashion\_Images\_Operative\_Ekphrasis\_and\_the\_Reduction\_of\_Fashion\_Through\_Multimodal\_AI](https://www.researchgate.net/publication/396119864_Possible_Fashion_Images_Operative_Ekphrasis_and_the_Reduction_of_Fashion_Through_Multimodal_AI)  
27. Ekphrasis/exscription: Jean-Luc Nancy on thinking and touching art, accessed January 26, 2026, [https://www.manchesterhive.com/display/9781526125804/9781526125804.00020.pdf](https://www.manchesterhive.com/display/9781526125804/9781526125804.00020.pdf)  
28. Ekphrasis and the Other \- Centre for Comparative Literature, accessed January 26, 2026, [https://complit.utoronto.ca/wp-content/uploads/COL1000-Week11-Nov25\_WJT\_Mitchell.pdf](https://complit.utoronto.ca/wp-content/uploads/COL1000-Week11-Nov25_WJT_Mitchell.pdf)  
29. Magical thinking and textual skeuomorphism: prompt engineering ..., accessed January 26, 2026, [https://medium.com/@mikekuniavsky/magical-thinking-and-textual-skeuomorphism-prompt-engineering-incantations-is-terrible-ux-40cbc80a0c94](https://medium.com/@mikekuniavsky/magical-thinking-and-textual-skeuomorphism-prompt-engineering-incantations-is-terrible-ux-40cbc80a0c94)  
30. Nobody, Prompt engineers: : r/OpenAI \- Reddit, accessed January 26, 2026, [https://www.reddit.com/r/OpenAI/comments/1ac7l5l/nobody\_prompt\_engineers/](https://www.reddit.com/r/OpenAI/comments/1ac7l5l/nobody_prompt_engineers/)  
31. Implicit bias in digital health: systematic biases in large language ..., accessed January 26, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12698530/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12698530/)  
32. (PDF) How representational fidelity affects sociability and cyberself ..., accessed January 26, 2026, [https://www.researchgate.net/publication/383455954\_How\_representational\_fidelity\_affects\_sociability\_and\_cyberself\_engagement\_in\_the\_Metaverse/download](https://www.researchgate.net/publication/383455954_How_representational_fidelity_affects_sociability_and_cyberself_engagement_in_the_Metaverse/download)  
33. Evaluating cultural knowledge processing in large language models, accessed January 26, 2026, [https://www.emerald.com/el/article/doi/10.1108/EL-04-2025-0136/1318075/Evaluating-cultural-knowledge-processing-in-large](https://www.emerald.com/el/article/doi/10.1108/EL-04-2025-0136/1318075/Evaluating-cultural-knowledge-processing-in-large)  
34. Prompt Priming with Practical Examples, accessed January 26, 2026, [https://learnprompting.org/docs/basics/priming\_prompt](https://learnprompting.org/docs/basics/priming_prompt)  
35. CAMEL: Communicative Agents for "Mind" Exploration of Large ..., accessed January 26, 2026, [https://repository.kaust.edu.sa/items/24934d20-9e08-4b05-8ca6-01f55576e195](https://repository.kaust.edu.sa/items/24934d20-9e08-4b05-8ca6-01f55576e195)  
36. arXiv:2303.17760v2 \[cs.AI\] 2 Nov 2023, accessed January 26, 2026, [https://3dvar.com/Li2023CAMEL.pdf](https://3dvar.com/Li2023CAMEL.pdf)  
37. JSON Prompting for AI Video Generation | ImagineArt, accessed January 26, 2026, [https://www.imagine.art/blogs/json-prompting-for-ai-video-generation](https://www.imagine.art/blogs/json-prompting-for-ai-video-generation)  
38. Directing AI like a Pro with JSON Prompts (Guide and 10 ... \- Reddit, accessed January 26, 2026, [https://www.reddit.com/r/PromptEngineering/comments/1n002n3/start\_directing\_ai\_like\_a\_pro\_with\_json\_prompts/](https://www.reddit.com/r/PromptEngineering/comments/1n002n3/start_directing_ai_like_a_pro_with_json_prompts/)  
39. Veo 3 JSON Prompt Guide | Professional Video Production with AI, accessed January 26, 2026, [https://ademyuce.tr/en/veo-3-json-prompt-guide/](https://ademyuce.tr/en/veo-3-json-prompt-guide/)  
40. LatentPrompt: Optimizing Promts in Latent Space \- arXiv, accessed January 26, 2026, [https://arxiv.org/html/2508.02452v1](https://arxiv.org/html/2508.02452v1)  
41. Chapter 3: Architectures for Building Agentic AI \- arXiv, accessed January 26, 2026, [https://arxiv.org/html/2512.09458v1](https://arxiv.org/html/2512.09458v1)  
42. Advanced Smart Contract Vulnerability Detection via LLM-Powered ..., accessed January 26, 2026, [https://www.computer.org/csdl/journal/ts/2025/10/11121619/2965TdCMd9u](https://www.computer.org/csdl/journal/ts/2025/10/11121619/2965TdCMd9u)  
43. Genie 3: AI-Powered World Models and Interactive Environments, accessed January 26, 2026, [https://www.flowhunt.io/blog/genie-3-ai-powered-world-models/](https://www.flowhunt.io/blog/genie-3-ai-powered-world-models/)  
44. The World Model Inflection: 2025 Made It Real | by Graison Thomas, accessed January 26, 2026, [https://medium.com/@graison/the-world-model-inflection-2025-made-it-real-f5a9c31475d4](https://medium.com/@graison/the-world-model-inflection-2025-made-it-real-f5a9c31475d4)  
45. AI Diffusion as Design Vocabulary \- CumInCAD, accessed January 26, 2026, [https://papers.cumincad.org/data/works/att/ecaade2023\_436.pdf](https://papers.cumincad.org/data/works/att/ecaade2023_436.pdf)  
46. Spatial Narrative Optimization in Digitally Gamified Architectural ..., accessed January 26, 2026, [https://www.mdpi.com/2075-5309/15/15/2597](https://www.mdpi.com/2075-5309/15/15/2597)  
47. Language Guided Generation of 3D Embodied AI Environments, accessed January 26, 2026, [https://yueyang1996.github.io/papers/holodeck.pdf](https://yueyang1996.github.io/papers/holodeck.pdf)  
48. Inhabitable Fictions, accessed January 26, 2026, [https://www.msa.ac.uk/media/msaacuk/documents/research/portfolios/Huneck-Karsten--Inhabitable-Fictions.pdf](https://www.msa.ac.uk/media/msaacuk/documents/research/portfolios/Huneck-Karsten--Inhabitable-Fictions.pdf)  
49. Skybox AI Review: Features, Pros, Cons & Alternatives \- Zegashop, accessed January 26, 2026, [https://www.zegashop.com/web/ai-tools/skybox-ai/](https://www.zegashop.com/web/ai-tools/skybox-ai/)  
50. Skybox AI Prompting Guide, accessed January 26, 2026, [https://skybox.blockadelabs.com/prompting-guide](https://skybox.blockadelabs.com/prompting-guide)  
51. Postdigital Cultures, Aesthetics and Politics \- publisherspanel.com, accessed January 26, 2026, [https://publisherspanel.com/api/files/view/2630114.pdf](https://publisherspanel.com/api/files/view/2630114.pdf)  
52. Bai (Boyce) Liu | Edinburgh College of Art Graduate Show 2024, accessed January 26, 2026, [https://www.2024.graduateshow.eca.ed.ac.uk/portfolio/bai-boyce-liu](https://www.2024.graduateshow.eca.ed.ac.uk/portfolio/bai-boyce-liu)  
53. From Alchemy to AI: How Occulture is Shaping the Conversation ..., accessed January 26, 2026, [https://www.soulcruzer.com/from-alchemy-to-ai-how-occulture-is-shaping-the-conversation-around-technology/](https://www.soulcruzer.com/from-alchemy-to-ai-how-occulture-is-shaping-the-conversation-around-technology/)  
54. UC Irvine Electronic Theses and Dissertations \- eScholarship.org, accessed January 26, 2026, [https://escholarship.org/content/qt2jm9q0dv/qt2jm9q0dv.pdf](https://escholarship.org/content/qt2jm9q0dv/qt2jm9q0dv.pdf)  
55. Towards Automatic Evaluation for Image Transcreation \- arXiv, accessed January 26, 2026, [https://arxiv.org/html/2412.13717v3](https://arxiv.org/html/2412.13717v3)  
56. SCEditor-Web: Bridging Model-Driven Engineering and Generative ..., accessed January 26, 2026, [https://www.mdpi.com/2078-2489/16/10/870](https://www.mdpi.com/2078-2489/16/10/870)  
57. EmoSphere++: Emotion-Controllable Zero-Shot Text-to-Speech Via ..., accessed January 26, 2026, [https://ieeexplore.ieee.org/iel8/5165369/11152495/10965917.pdf](https://ieeexplore.ieee.org/iel8/5165369/11152495/10965917.pdf)  
58. EmoSphere-TTS: Emotional Style and Intensity Modeling via ..., accessed January 26, 2026, [https://www.isca-archive.org/interspeech\_2024/cho24\_interspeech.pdf](https://www.isca-archive.org/interspeech_2024/cho24_interspeech.pdf)  
59. A design toolkit for user acceptance and adoption, accessed January 26, 2026, [https://re.public.polimi.it/retrieve/391c41bf-fce1-4347-9e6c-1eb179d2c4f3/s10209-025-01286-4.pdf](https://re.public.polimi.it/retrieve/391c41bf-fce1-4347-9e6c-1eb179d2c4f3/s10209-025-01286-4.pdf)  
60. How to distinguish a wink from a twitch | HAU, accessed January 26, 2026, [https://www.journals.uchicago.edu/doi/full/10.14318/hau7.2.038](https://www.journals.uchicago.edu/doi/full/10.14318/hau7.2.038)  
61. AI Generative Art as Algorithmic Remediation \- media/rep, accessed January 26, 2026, [https://mediarep.org/bitstreams/db11c2d8-a3c1-427d-911e-7bd788e5facd/download](https://mediarep.org/bitstreams/db11c2d8-a3c1-427d-911e-7bd788e5facd/download)  
62. Daily Papers \- Hugging Face, accessed January 26, 2026, [https://huggingface.co/papers?q=latent-space%20planners](https://huggingface.co/papers?q=latent-space+planners)  
63. TEXT2WORLD: Benchmarking Large Language Models for, accessed January 26, 2026, [https://aclanthology.org/2025.findings-acl.1337.pdf](https://aclanthology.org/2025.findings-acl.1337.pdf)  
64. SceneTeller: Language-to-3D Scene Generation, accessed January 26, 2026, [https://www.ecva.net/papers/eccv\_2024/papers\_ECCV/papers/11481.pdf](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/11481.pdf)