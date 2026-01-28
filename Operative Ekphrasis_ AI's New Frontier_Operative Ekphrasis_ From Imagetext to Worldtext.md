# **Operative Ekphrasis: From Imagetext to Worldtext**

## **A. Title & Abstract**

**Title:** Operative Ekphrasis: From Imagetext to Worldtext — The Prompt as Control Surface

**Abstract**

This report interrogates the ontological shift in ekphrasis precipitated by the advent of multimodal generative artificial intelligence. Historically defined by James Heffernan as the "verbal representation of visual representation," ekphrasis has long functioned as a literary mode of description bridging the sensory divide between word and image. This report argues that Generative AI displaces ekphrasis from a mode of *representational description* to one of *operative compilation*. In this new paradigm, the text input is not a passive mirror of an image but an active **control surface** that executes the generation of the image itself. We term this phenomenon **Operative Ekphrasis**, building on the work of Hannes Bajohr, to describe the collapse of the distinction between text and image into a unified, processable data substrate.

The report introduces two primary methodological contributions to the digital humanities. First, **Thick Prompting** adapts Clifford Geertz’s anthropological "thick description" to the latent space, treating the prompt as a layered cultural object containing the "residue" of intent, context, and code. Second, **Prompt Differentials** (Δ/ΔΔ) formalize the study of latent space by measuring the variance in visual output (ΔΔ) relative to the semantic variance in textual input (Δ). This metric maps the "sensitivity" of the model's imagination and exposes the underlying statistical rigidity of the system.

Through two detailed case studies—the heterogeneous stack of the "Carrot Uprising" and the modular, totalizing logic of the "Worldtext Compiler" (or "legOS")—we demonstrate how the AI model functions not as an artist but as a compiler of a new reality we call the **Worldtext**. This Worldtext differs from W.J.T. Mitchell’s "imagetext" in that it is not a suture of two media but a computational output where the world itself has been tokenized, processed, and re-rendered. We conclude that while Operative Ekphrasis vindicates the "ekphrastic hope" of language turning into vision, it simultaneously realizes the "ekphrastic fear" of the total collapse of difference, requiring a new critical literacy that is computational, statistical, and profoundly interpretive.

## **B. Introduction: The Silent Shield and the Speaking Machine**

The history of Western aesthetics is haunted by a single, persistent desire. It is the desire for the word to become the world. This desire finds its primal scene in Book 18 of the *Iliad*, where Hephaestus forges the Shield of Achilles. Homer does not present the reader with the shield itself. He presents a verbal sequence. He presents a temporal unfolding of a spatial object. "And he made the earth upon it, and the sky, and the sea's water, and the tireless sun," the poet chants. We do not see the bronze. We see the "ploughmen driving their teams of oxen" and "the grape-clusters" turning dark. This is the foundational moment of **ekphrasis**. It is the verbal representation of visual representation.1 For three millennia, this practice has been understood as a rhetorical feat. It is a "minor miracle" where language attempts to bridge the impossible gap between the symbolic order of the text and the sensory immediacy of the image. The shield remains silent. The poem speaks for it. The tension lies in the distance. The poet can describe the shield, but he cannot *make* the shield. The description remains a phantom. It hovers over the object but never penetrates its material reality.

Generative Artificial Intelligence shatters this distance. When a user inputs the string "A bronze shield depicting the earth, the sky, and the sea's water" into a multimodal model like DALL-E 3 or Midjourney, the text does not merely describe a potential image. It *commands* its existence. The text ceases to be a secondary reflection of a primary visual object. Instead, it becomes the **operative** code that compiles the image from the statistical noise of the latent space. The prompt is not a description. It is a **control surface**.

This report investigates this seismic shift from *representational ekphrasis* to **Operative Ekphrasis**. We posit that the prompt interface represents a fundamental transformation in the history of media. In the classical model, the "ekphrastic hope" was that language might make us see.2 In the computational model, language literally *manufactures* vision. The prompt is a linguistic lever that manipulates a high-dimensional mathematical space. To understand this, we must abandon the literary tools of "close reading" in favor of a new methodology suited to the algorithmic age. We propose **Thick Prompting**—an adaptation of Clifford Geertz’s thick description—as the necessary critical framework for reading these operative texts. We further propose **Prompt Differentials** as the quantitative heuristic for measuring the efficacy and "sensitivity" of these texts.3

The stakes of this inquiry are not strictly aesthetic. They are ontological. If the distinction between text and image collapses—if the word "shield" and the pixel-matrix of a shield are interchangeable data tokens within the model's architecture—then we have entered the era of the **Worldtext**. The Worldtext is the condition in which reality is processed not as a collection of distinct objects but as a continuous, tokenized stream of information, compilable and re-compilable at will. The AI model acts as the "legOS," a modular operating system that treats cultural concepts as interchangeable bricks.4

This report proceeds by first diagnosing the crisis in traditional definitions of ekphrasis (Section C). It then defines Bajohr’s concept of Operative Ekphrasis (Section D) and introduces the theory of Thick Prompting (Section E). We apply these theories to two case studies. The "Carrot Uprising" reveals the heterogeneous stack of code and culture (Section F). The "Worldtext Compiler" exposes the modular logic of the AI (Section G). Finally, we formalize the methodology of Prompt Differentials (Section H) before returning to the ethical and philosophical implications of this new media convergence (Section I).

## **C. Definition Crisis: Cracks in Traditional Ekphrasis**

Before we can understand the operative nature of the AI prompt, we must understand the theoretical architecture it dismantles. Traditional ekphrasis has always been defined by a binary. It is the *paragone*, or the competition between sister arts. Leonardo da Vinci famously argued for the superiority of painting over poetry. He claimed that the eye is the "nobler sense." Lessing, in his *Laocoön*, codified this separation. He prescribed "laws" to separate the temporal art of poetry from the spatial art of painting.2

### **The Representational Deadlock**

The standard definition, provided by James Heffernan, is deceptively simple. Ekphrasis is "the verbal representation of visual representation".1 This definition relies on three stable categories.

1. **The Verbal:** Language, syntax, time.  
2. **The Visual:** Image, space, simultaneity.  
3. **Representation:** The mimetic relationship between the two.

For centuries, this definition held. Whether it was Keats gazing at a Grecian Urn or Auden looking at Brueghel’s *Icarus*, the poet stood *outside* the image. The poet looked in. The power of the poem came from its inability to *be* the image. As W.J.T. Mitchell argues, this distance creates "ekphrastic hope"—the dream of overcoming the gap—and "ekphrastic fear"—the anxiety that the gap might close. This closure would lead to a "dangerous promiscuity" between the senses.2

However, even before the arrival of generative AI, this definition was cracking. Claus Clüver, Liliane Louvel, and Mats Jansson have long argued that the strict separation of "verbal" and "visual" is untenable in a multimedia age.5 Clüver expanded the definition to "intermedial transposition," acknowledging that modern media often blend the two. Louvel focused on the "pictorial" elements within text itself. She examined how typography and layout can become image.5 Yet, these theorists were still describing a relationship of *reference*. The text referred to the image. It did not *execute* it. The crisis of definition begins here. If the text does not merely refer but actively constructs, does the term "ekphrasis" still apply? Or have we moved beyond representation into pure production?

### **The Digital Strain and the Imagetext**

The introduction of digital media placed immense strain on the "representational" model. When a digital image is stored as a JPEG, is it an image? Or is it a text (binary code)? As early as the 1990s, the "imagetext" began to emerge as a dominant form. Websites, memes, and hypermedia presented environments where text and image coexisted on the same screen.2 Mitchell defined the imagetext as a composite form where the "image/text division is overcome, and a sutured, synthetic form" arises.2

Yet, even here, the distinction remained at the user layer. The user wrote an HTML tag (\<img src="..."\>). The browser displayed an image. The tag *pointed* to the image file. It did not *contain* the image's visual data in a semantic form. The "signifier" (the code) and the "signified" (the image) were linked by a pointer. They were not linked by a generative synthesis. The rupture was still present. The code could exist without the image file. The image file could exist without the code. They were ontologically distinct entities brought together by the browser's rendering engine.

The crisis reaches its breaking point with Neural Networks. In a model like CLIP (Contrastive Language-Image Pre-training), the text "a dog" and the image of a dog are mapped to the same vector in a high-dimensional latent space.6 The distance—the defining feature of classical ekphrasis—is mathematically eliminated. The "paragone" is over because the combatants have merged. The definition of ekphrasis as "representation" fails because the relationship is no longer mimetic. It is algorithmic. We need a new term. We need **Operative Ekphrasis**.

### **The Pre-AI Lineage**

It is crucial to recognize that this collapse was foreshadowed in the deeper history of computing. As Bajohr notes, code has always been a form of writing that *does* what it says.7 A script that says print("Hello World") executes the action of printing. This "performative" quality of code distinguishes it from the descriptive quality of literature. However, for most of computing history, this performativity was syntactic. It was logical. It dealt with variables and functions. It did not deal with *semantics* in the human sense. It did not know what a "dog" was. It only knew the variable dog\_count.

The shift to multimodal AI introduces semantics into the operative layer. The model now "understands" (statistically) the visual features of a dog. It can operate on the *concept* of a dog, not just the *symbol* of a dog. This is the "pivot" point where the digital humanities must update its lexicon. We are no longer dealing with "digital ekphrasis" (descriptions on a screen). We are dealing with "operative ekphrasis" (descriptions *as* screens).

## **D. Operative Ekphrasis & The Pivot**

Hannes Bajohr provides the critical pivot point for this investigation. In his seminal work on the subject, Bajohr defines **Operative Ekphrasis** as the condition where the distinction between text and image collapses within the "multimodal AI" substrate.7

### **The Collapse of the Medium**

Bajohr argues that we must broaden the concept of ekphrasis to include the "technical substrate of this interaction in the digital".9 In a multimodal model, text and image are processed as "one type of data." They are both tokenized inputs converted into numerical vectors. The traditional flow of ekphrasis was:

![][image1]  
The operative flow is:

![][image2]  
The arrows meet in the middle. The "latent space" is a semantic manifold where the concept of "dogness" exists not as a word or a picture. It exists as a cluster of numerical values.10 As Bajohr notes, "multimodal AI does away with the separation of mediums that is at the core of ekphrasis, as this technology can process both text and image as one type of data".7 This is not a trivial technical detail. It is a fundamental reordering of the aesthetic categories. If the medium is the message, as McLuhan argued, then the collapse of the medium implies the collapse of the message's distinctiveness. The message is no longer "textual" or "visual." It is "data."

### **Code as Performance**

The crucial shift in Operative Ekphrasis is from *mimesis* (imitation) to *performance* (action). Renate Brosch had previously suggested a "performative" definition of ekphrasis as a "literary response".9 This was a way to emphasize the active role of the viewer. Bajohr radicalizes this. He argues that in the digital realm, code is "performative by its very nature" (citing Hayles).9

The prompt is a performative speech act. When a user types a prompt, they are not "responding" to an image (as in Brosch's definition). They are initiating a causal chain that *results* in an image. "Here, the text and the resulting text-image stand not simply in a mimetic relationship... but a causal one," Bajohr writes.7 This is the definition of **operation**. The text operates on the model to produce the visual. The text is the *cause*. The image is the *effect*. This reversal of the traditional ekphrastic flow (where the image was the cause and the text was the effect) marks the pivot to the operative mode.

### **The Prompt as Control Surface**

If the prompt is an operator, then the interface where the user types is a **control surface**. In aviation, a control surface (like an aileron) manipulates the airflow to change the aircraft's orientation. In Generative AI, the prompt manipulates the "flow" of the denoising process to change the orientation of the output in latent space.11

This metaphor clarifies the role of the user. The user is not an author in the Romantic sense. The user is a pilot. The pilot does not "create" the airflow. The pilot manipulates it. Similarly, the user does not "create" the image pixel by pixel. The user manipulates the statistical flow of the model to arrive at a desired visual state. The skill required is not "description" in the adjective-heavy sense of the 19th century. It is "specification" in the procedural sense of computer science. The prompt must be "thick" with instruction, context, and constraint. It must navigate the "turbulence" of the latent space.

The control surface metaphor also highlights the *resistance* of the medium. Just as a pilot feels resistance from the air, the prompter feels resistance from the model. This resistance comes in the form of the model's training biases, its "refusal" to render certain concepts, or its tendency to "hallucinate." The study of Operative Ekphrasis is the study of how users navigate this resistance using the control surface of the prompt.

## **E. Theory of Thick Prompting**

To analyze this new form of writing—this "operative" text—we require a new critical theory. Traditional literary analysis focuses on style, tone, and metaphor. While these are present in prompts, they function differently. A metaphor in a prompt is not a poetic flourish. It is a functional instruction. "The sun like a burning coin" tells the model to render a specific visual texture. To capture this functional depth, we propose **Thick Prompting**, a concept derived from Clifford Geertz’s "Thick Description."

### **From Thick Description to Thick Prompting**

Geertz famously distinguished between a "thin description" (e.g., "his eye twitched") and a "thick description" (e.g., "he winked conspiratorially to mock the mayor").12 Thick description accounts for the *intent*, the *cultural context*, and the *web of significance* that gives the action meaning. It separates the raw physical movement from the social gesture. It identifies the "stratified hierarchy of meaningful structures" 12 that makes the action intelligible.

In the context of AI, **Thick Prompting** acknowledges that a prompt is never just a string of keywords. It is a layered artifact containing:

1. **The Explicit Instruction:** The "thin" text (e.g., "Draw a cat"). This corresponds to the "twitch." It is the raw input.  
2. **The Latent Residue:** The statistical "web of significance" the model associates with those words. The model does not know what a "cat" is biologically. It knows the "thick" statistical distribution of "cat" pixels in its training data (whiskers, ears, internet memes).13 This is the culture of the model.  
3. **The User's Intentionality:** The specific "control" the user is trying to exert (e.g., "photorealistic," "in the style of Van Gogh"). This is the "wink." It is the attempt to imbue the raw input with specific social or aesthetic meaning.

A "thin prompt" relies on the model's default assumptions (its biases). A "thick prompt" explicitly navigates these assumptions. It adds layers of context to force a specific outcome. Geertz argued that ethnography is the "sorting of winks from twitches".12 Thick Prompting is the sorting of "intended features" from "statistical hallucinations."

### **The Prompt as Experimental Model (Wittgenstein)**

To understand *how* Thick Prompting works, we turn to Ludwig Wittgenstein’s "Picture Theory of Language." In his diary from 1914, Wittgenstein wrote: "In a proposition a world is as it were put together experimentally".14 He compared a proposition to the dolls used in a Parisian court to represent a motor accident. The dolls are a *model* of reality. They are a spatial arrangement that corresponds to a logical arrangement.

In AI, the prompt is exactly this. It is an **experimental model**. When a user writes a prompt, they are constructing a "proposition" ("There exists a cat on a mat"). The AI then "puts together the world experimentally" by generating the pixels that satisfy this proposition. The prompt acts as the blueprint for this experimental assembly.

However, as Boltzmann noted regarding "experimental models" vs. "mental models" 14, there is a difference between a theoretical abstraction and a physical simulation. Boltzmann described experimental models as those which "present on a small scale a machine that is subsequently to be completed on a larger".14 The AI prompt sits in between these categories. It is a linguistic abstraction (mental model) that triggers a physical/computational simulation (experimental model).

**Thick Prompting** is the practice of refining this experimental model. It involves what we call **iterative specification**. The user observes the output (the "twitch"). The user realizes it lacks the "wink" (the intent). The user adds thickness to the prompt ("conspiratorial wink," "sarcastic expression," "cinematic lighting"). The prompt becomes a record of the negotiation between the user's intent and the model's latent capabilities. It is a sedimentation of trial and error.

### **The Residue of the Training Data**

Geertz speaks of the "residue" of social behavior.15 In Thick Prompting, we must contend with the "residue" of the training data. Every word in a prompt drags with it a "thick" tail of statistical correlations. The word "Nurse" drags with it a gendered residue (often producing female images). The word "CEO" drags a different residue. The word "Cyberpunk" drags a residue of neon pink and blue.

Thick Prompting is the act of *managing this residue*. It is the "operative" attempt to scrape away the unwanted statistical correlations and reinforce the desired ones. It is a form of "negative capability"—using language not just to say what *is*, but to suppress what *should not be*. This is evident in the use of "negative prompts" (e.g., "--no blurry, \--no watermark"). These are explicitly operative commands to prune the latent space. They are tools to cut away the unwanted "webs of significance" that the model automatically spins.

This concept of residue connects deeply to the Digital Humanities focus on "cultural technique." The prompt is not just a command; it is an excavation of the cultural archive compressed into the model. When we prompt, we are navigating the compressed history of human visual culture. Thick Prompting is the methodology for navigating this archive with intention.

## **F. Case Study 1: Carrot Uprising (The Heterogeneous Stack)**

To illustrate Thick Prompting in action, we examine a specific, culturally dense artifact: the "Carrot Uprising." This case study demonstrates how Operative Ekphrasis functions in a "Heterogeneous Stack" of code, culture, and absurdism.

**Origin:** The concept stems from a Reddit thread discussing the children’s game *Pajama Sam 3: You Are What You Eat from Your Head to Your Feet*. In this game, there is a political conflict involving food. A user commented: "Sam joins the communist carrot uprising".16 **The Prompt:** "Pajama Sam leading a communist revolution of carrots, propaganda poster style."

### **The Heterogeneous Stack**

This prompt is not a simple sentence. It is a **Heterogeneous Stack**.17 In software engineering, a heterogeneous stack refers to a system combining different technologies (e.g., Python \+ React \+ Docker).17 In Operative Ekphrasis, it refers to the stacking of distinct ontological layers within the prompt:

1. **The Cultural Object (IP):** "Pajama Sam." This invokes a specific visual style (1990s Humongous Entertainment adventure games), a color palette (blues, purples), and a character design (boy with a cape). It is a vector pointing to a specific era of digital childhood.  
2. **The Political Abstraction:** "Communist revolution." This invokes a totally different visual language: Constructivist geometry, bold reds and blacks, Cyrillic-style typography, and heroic poses. It is a vector pointing to 20th-century political history.  
3. **The Absurdist Glitch:** "Carrots." This introduces a biological object that must be anthropomorphized to fit the "revolution" context. It is a vector pointing to nature, but modified by the "Pajama Sam" context (anthropomorphic food).

In a "thin" reading, this is just a funny sentence. In a **Thick Prompting** analysis, this is a collision of distinct regions of the latent space. The model must resolve the conflict between the "cute/childish" vector of Pajama Sam and the "aggressive/political" vector of Soviet propaganda. It must manage the "residue" of both.

### **Operative Resolution**

How does the model resolve this? It performs an **operative synthesis**.

* It does not "imagine" a revolution in the human sense.  
* It *compiles* the "residue" of Soviet posters (rays of light, raised fists, angular text).  
* It *compiles* the "residue" of Pajama Sam (the mask, the blue skin, the jagged outlines).  
* It *maps* the "fist" vector onto the "carrot" vector.

The result is an image of a blue boy raising a carrot like a hammer. The background is a stark red sunburst. This image is a **Worldtext** artifact. It exists only because the model can treat "Stalin" and "Carrot" as mathematically compatible tokens.

We see here the "Carrot" acting as what Bajohr calls a "constellation".7 The "Carrot" in history (as noted in historical texts about the "carrot and stick" approach in Nazi Germany 19 or Yugoslavian politics 20) is a metaphor for incentive. In the AI "Carrot Uprising," the carrot returns to its literal roots but is politicized. The prompt creates a "glitch" in the semantic logic—carrots don't revolt—but the *operative* logic of the AI has no trouble processing it. If the probability paths connect "Revolution" to "Crowd" and "Carrot" to "Object," the model simply renders a crowd of carrots.

### **The Role of Tags and Code**

The "Heterogeneous Stack" also refers to the mix of natural language and "tags" in modern prompting. Users often append tags like high quality, 4k, trending on artstation. These are not descriptions of the scene; they are descriptions of the *file*. They are meta-data instructions. In the "Carrot Uprising" prompt, a user might add poster style or vector art. These tags act as "switchers," routing the generation through specific sub-manifolds of the latent space. The prompt is thus a mix of narrative ("Sam joins...") and code-like parameters ("poster style"). This hybridity is characteristic of Operative Ekphrasis. It is writing that functions as both story and script.

The "Carrot Uprising" demonstrates that Operative Ekphrasis allows for the **literalization of metaphor**. The "ekphrastic fear" Mitchell describes—that the difference between the verbal and visual might collapse—is realized here as a surrealist weapon. We can literally *see* the "carrot and stick" ideology manifest as an army of vegetables. The distance required for metaphor (A is *like* B) collapses into identity (A *is* B).

## **G. Case Study 2: Worldtext Compiler (legOS)**

If the "Carrot Uprising" shows the collision of concepts, our second case study, the "Worldtext Compiler," demonstrates the *mechanism* of assembly. We use the metaphor of "legOS" (Lego Operating System) 4 to describe the AI's function. This case study is central to understanding the Digital Humanities implications of AI as a "cultural technique."

### **The legOS Metaphor**

Snippet analysis reveals a recurring comparison between AI modularity and Legos.4 "Legos are the building blocks... text based NFTs are akin to Lego blocks." Another snippet notes: "AI Services Like Legos, Not a Monolith".21 This metaphor is precise. Legos are:

1. **Discrete:** Individual units (studs/tubes). They are "atomistic".24  
2. **Universal:** Any brick fits any other brick (system compatibility). A "Star Wars" brick fits a "City" brick.  
3. **Non-semantic:** A red 2x4 brick implies nothing about a "house" or a "car" until it is assembled.

The AI model functions as the **legOS**.4 It treats the world not as a continuous analog reality but as a bin of discrete "tokens" (bricks). "Worldtext" 25 is the name we give to this *total inventory* of tokenized reality.

* The "sky" is a brick (Token ID: 8921).  
* The "style of Van Gogh" is a brick (Token ID: 1402).  
* "Sadness" is a brick (Token ID: 5531).

In the "legOS," these bricks can be snapped together regardless of semantic logic. You can snap "Van Gogh" onto "Toaster." You can snap "Sadness" onto "Pizza." The system permits the connection because the *interface* (the embedding vector) is standardized. This echoes the "atomistic ontologies" described in snippet 24, where "digital remediation is a process of breaking information into smaller functional pieces."

### **The Compiler**

In computer science, a compiler translates high-level source code into low-level machine code.26 The compiler "understands" the code's structure and converts it into executable instructions.

* **Source Code:** The Prompt (Thick Description).  
* **Compiler:** The Transformer Model (The Operator).  
* **Machine Code:** The Pixel/Token Grid (The Worldtext).

When we engage in Operative Ekphrasis, we are acting as programmers writing source code for the Worldtext Compiler. The "Worldtext" is the output executable. Snippet 27 discusses the "WorldText-Reader Entanglement." In our context, this means the reader (the user) is entangled with the compiler. We are not reading the world; we are *writing* it. We are compiling it from the available libraries of the model.

This shifts the interpretive labor. In classical ekphrasis, the labor was in *imagining* the scene described by the poet. In operative ekphrasis, the labor is in *debugging* the compilation. The user writes a prompt, compiles (generates), checks for errors (artifacts, wrong colors), and refactors the code (edits the prompt).

### **Failure Mode: The Hallucination as Syntax Error**

In this model, what is a "hallucination"? It is a compilation error. If I prompt "A square circle," the legOS tries to snap a "square" brick onto a "circle" brick. They don't fit geometrically, but the compiler forces a fit because the user commanded it. The result is a distorted, non-Euclidean shape. Snippet 28 discusses "Prompt Sensitivity" and hallucination control. It notes that "ambiguous formulations" lead to hallucinations. In compiler terms, this is "undefined behavior." If the source code (prompt) is ambiguous, the compiler makes an arbitrary choice based on optimization flags (probability weights).

For example, if the prompt is simply "Bank," the compiler must decide: "River bank" or "Financial bank"? It checks the "residue" of the surrounding tokens. If there is no context, it picks the statistically most probable one. This is not "creativity." It is "default behavior."

The "Worldtext" is thus a fragile reality. It is a reality held together by the statistical glue of the legOS. Unlike the "Imagetext," which acknowledges the gap between word and image, the Worldtext papers over the gap with probability. It presents the *illusion* of a seamless world, but a "Thick Prompting" analysis reveals the seams—the places where the "Carrot" brick was forced onto the "Communist" brick, or where the "Hand" brick failed to resolve the "Finger" count correctly.

### **The Worldtext Definition**

We formally define the **Worldtext** as follows: *The Worldtext is the condition of reality-as-data, where all visual, textual, and conceptual objects are reduced to interchangeable tokens within a unified latent space, capable of being compiled into new configurations by an operative prompt.* This definition draws on snippet 25 which discusses "letters of the worldtext" as being of "dependent co-origination." In the AI model, every token is dependent on every other token. The "dog" token is defined by its distance from "cat" and "wolf." There is no "origin," only the mutual difference of the vectors.

## **H. Methodology: Prompt Differentials (Δ/ΔΔ)**

How do we scientifically study this Operative Ekphrasis? We cannot rely solely on "literary analysis" of the output image, because the image is unstable. We must study the *process*. We introduce the methodology of **Prompt Differentials**.

This methodology is grounded in the "Prompt Sensitivity Analysis" and "Counterfactual Prompting" found in current computer vision research.3 It provides a rigorous way to measure the "thickness" of the prompt and the "responsiveness" of the control surface.

### **Defining the Differentials**

We define two primary variables:

1. **Δ (Delta Prompt):** The semantic change in the input text. This can be measured by word substitution, structural variation, or negation.  
2. **ΔΔ (Delta Latent/Delta Image):** The resulting change in the output visualization. This can be measured by pixel distance, CLIP score variance, or semantic shift.

The core research question of Operative Ekphrasis is: **What is the ratio of Δ to ΔΔ?** This ratio defines the "sensitivity" of the cultural concept within the model.

### **The Sensitivity Metric**

We establish the following heuristics for reading the Worldtext:

* **High Sensitivity (Chaos):** Small Δ ![][image3] Massive ΔΔ.  
  * *Example:* Changing "A dog" to "A *happy* dog" completely changes the breed, the background, and the lighting.  
  * *Implication:* The model is "unstable" or "hallucinatory." The "control surface" is too sensitive; a slight touch sends the plane into a spin. The concept "dog" is not stable; it is highly dependent on the "happy" modifier. Snippet 31 notes that "high prompt sensitivity may indicate undesirable overfitting."  
* **Low Sensitivity (Rigidity):** Large Δ ![][image3] Small ΔΔ.  
  * *Example:* Adding "in the style of Picasso" fails to change the photorealistic rendering of a celebrity.  
  * *Implication:* The model suffers from "mode collapse" or strong prior biases. The control surface is "stuck." The "Celebrity" token is so heavily weighted towards "Photograph" that the "Picasso" token cannot dislodge it.

### **Table 1: Prompt Differential Analysis (Hypothetical Data based on**

30)

| Base Prompt (P) | Counterfactual (P′) (Δ) | Output Shift (ΔΔ) | Interpretation |
| :---- | :---- | :---- | :---- |
| "Astronaut riding a horse" | "Astronaut riding a *donkey*" | **High:** Style shifts to cartoon/shrek. | "Donkey" carries strong "cartoon" residue. |
| "Astronaut riding a horse" | "*Cosmonaut* riding a horse" | **Medium:** Suit changes to orange/vintage. | "Cosmonaut" carries "Soviet" residue. |
| "CEO in a meeting" | "CEO in a meeting *wearing a dress*" | **Low/Resistance:** Model generates a suit. | "CEO" has strong "Male/Suit" bias (Rigidity). |
| "Cyberpunk city" | "Cyberpunk city *daytime*" | **High:** Image breaks/glitches. | "Cyberpunk" is strongly correlated with "Night." |

### **Counterfactual Prompting as Method**

To perform this analysis, we use **Counterfactual Prompting**.30 This involves taking a base prompt (![][image4]) and systematically generating a set of counterfactuals (![][image5]). Snippet 11 discusses "Latent space trajectory." Prompt Differentials allow us to trace these trajectories. We are not just looking at points (images); we are looking at the *vectors* that connect them. This is the **differential calculus** of culture. We are measuring the *rate of change* of cultural concepts within the AI's mind.

We can define **Conditional Prompt Sensitivity (CPS)** as proposed in snippet 28:

![][image6]  
Where ![][image7] is the "hallucination rate" or visual variance. This metric allows us to quantify how "fragile" a specific concept is. If the CPS for "Democracy" is high, it means the model's visual definition of democracy is unstable and easily swayed by minor adjectives. If the CPS for "Apple" is low, it means the model has a very fixed idea of what an apple is.

This formalizes the "ekphrastic fear".1 If the differential is zero—if "freedom fighter" and "terrorist" produce the exact same image—then the model has collapsed a crucial political distinction. If the differential is infinite—if "nurse" and "doctor" produce mutually exclusive gender categories—the model has encoded a social bias as a hard constraint.

## **I. Vindication and Vitiation**

We return, finally, to W.J.T. Mitchell’s dialectic of **Hope** and **Fear**.1 The advent of Operative Ekphrasis brings this dialectic to a head.

### **The Vindication of Ekphrastic Hope**

Generative AI vindicates the "Ekphrastic Hope" that language might "make us see." The "mute" object (the shield, the urn) finally speaks. Or rather, the speaking subject (the user) finally produces the object. The "impossibility" of ekphrasis—the gap between the signifier and the signified—has been bridged by the "operative" code. We have achieved the "sutured, synthetic form" Mitchell dreamed of.2 The "imagetext" is no longer a collage; it is a fusion. The "paragone" is resolved in favor of the **algorithm**, which subsumes both painting and poetry.

### **The Vitiation of the Subject**

But this vindication comes at a terrible cost: the **Vitiation** (spoiling/impairing) of the human subject and the interpretive act.

In classical ekphrasis, the "failure" of language was its strength. The fact that the poet *could not* make the shield real meant that the poem remained a space of human imagination. It was a space of *difference*. The reader had to work to visualize the shield.

In Operative Ekphrasis, the "success" of the machine eliminates this space. The imagination is outsourced to the "legOS." The user provides the "thin" prompt, and the machine fills in the "thick" details.

* **Classical:** The poet imagines the "tireless sun." The reader imagines their own sun.  
* **Operative:** The model retrieves the "Sun" token and renders a generic fusion of 10,000 suns.

The "residue" 15 that fills the image is not the user's intent; it is the statistical average of the dataset. The "thick description" is supplied by the algorithm, not the anthropologist. We are "vitiated"—made less effective, less agentic. We become mere "prompters," nudging a machine that does the heavy lifting of visualization.

This realizes the "Ekphrastic Fear": the fear that the "difference between the verbal and visual representation might collapse".1 When it collapses, we lose the critical distance necessary for interpretation. We are left with the **Worldtext**—a seamless, hallucinated reality where "Carrots" and "Communists" blend into a single, uncritical spectacle. The "control surface" works, but we are no longer sure who is flying the plane—the user, or the statistical ghosts in the machine.

### **The Loss of the "Other"**

Mitchell argues that ekphrasis is a "menage a trois" between the poet, the object, and the audience.2 It is an exchange of "otherness." In the Worldtext, there is no "other." There is only the self-referential loop of the training data. The model consumes the world (text/images) and regurgitates it. The "mute object" does not speak; the *archive* speaks. The "Carrot Uprising" is not a new political thought; it is a statistical recombination of old thoughts. We are trapped in a hall of mirrors where every reflection is a "prompt differential" away from the next.

## **J. Conclusion & Contributions**

The shift from Representational Ekphrasis to Operative Ekphrasis marks a watershed moment in the history of media. The prompt is not a literary genre; it is a technical operation. It is a control surface for the Worldtext.

**Contributions:**

1. **Operative Ekphrasis Defined:** We have formally redefined ekphrasis for the AI age, shifting it from a *representational* mode (describing the visual) to an *operative* mode (compiling the visual through performative code).7 We have identified the "pivot" where semantics becomes a functional variable in the code.  
2. **Thick Prompting Theory:** We have established a critical framework for reading prompts not as text but as "thick" cultural artifacts containing layers of intent, residue, and control structures, adapting Geertz’s anthropology for latent space.15 We have linked this to Wittgenstein's concept of the "proposition as experimental model".14  
3. **Prompt Differentials (Δ/ΔΔ):** We have proposed a quantitative heuristic for measuring the "sensitivity" and cultural topology of the latent space, utilizing counterfactuals to map the operative logic of the Worldtext.3 We have provided a table of heuristics for interpreting High vs. Low sensitivity.

**Checks & Disproofs:**

To test the validity of this theory, future research should apply the following checks:

1. **The Synonym Check:** If distinct synonyms (e.g., "automobile" vs. "car") produce statistically identical image distributions (Low ΔΔ), the "Worldtext" hypothesis (that tokens are collapsed into universal concepts) is strengthened. If they produce distinct "class" images, the "residue" theory is dominant.  
2. **The Nonsense Check:** Inputting purely syntactic but asemic text (e.g., Chomsky’s "Colorless green ideas sleep furiously"). If the model refuses to generate or generates pure noise, the "Operative" link is broken. If it generates a "surreal" image, it proves the "legOS" forces modularity even in the absence of semantic logic.  
3. **The Glitch Check:** Analyzing "failure modes" (like the "Carrot Uprising"). If the model consistently resolves contradictions through "visual puns" (literalizing metaphors), it confirms that Operative Ekphrasis functions through a logic of *synthesis* rather than *critique*.

In conclusion, the AI prompt is the most significant development in the history of ekphrasis since the *Iliad*. It transforms the "speaking picture" from a metaphor into a mechanism. We have moved from the Imagetext, which we read, to the Worldtext, which writes us. The challenge for the Digital Humanities is to learn how to read this new world—not by looking at the images, but by analyzing the differentials of the control surface that produced them.

#### **Works cited**

1. Surpassing the Ekphrastic Experience in Modernist Poetry, accessed January 26, 2026, [https://ijels.com/upload\_document/issue\_files/11-IJELS-FEB-2019-48-Surpassingthe.pdf](https://ijels.com/upload_document/issue_files/11-IJELS-FEB-2019-48-Surpassingthe.pdf)  
2. Ekphrasis and the Other \- Centre for Comparative Literature, accessed January 26, 2026, [https://complit.utoronto.ca/wp-content/uploads/COL1000-Week11-Nov25\_WJT\_Mitchell.pdf](https://complit.utoronto.ca/wp-content/uploads/COL1000-Week11-Nov25_WJT_Mitchell.pdf)  
3. What is Prompt sensitivity analysis? \- PromptLayer, accessed January 26, 2026, [https://www.promptlayer.com/glossary/prompt-sensitivity-analysis](https://www.promptlayer.com/glossary/prompt-sensitivity-analysis)  
4. Building DevDaoStory: A Dynamic Visual Novel \- DEV Community, accessed January 26, 2026, [https://dev.to/banjtheman/building-devdaostory-a-dynamic-visual-novel-738](https://dev.to/banjtheman/building-devdaostory-a-dynamic-visual-novel-738)  
5. The ekphrastic encounter in contemporary British poetry and ..., accessed January 26, 2026, [https://www.researchgate.net/publication/290785721\_The\_ekphrastic\_encounter\_in\_contemporary\_British\_poetry\_and\_elsewhere](https://www.researchgate.net/publication/290785721_The_ekphrastic_encounter_in_contemporary_British_poetry_and_elsewhere)  
6. Language-Guided Trajectory Traversal in Disentangled Stable ..., accessed January 26, 2026, [https://arxiv.org/html/2503.23623v1](https://arxiv.org/html/2503.23623v1)  
7. Operative ekphrasis: The collapse of the text/image distinction in ..., accessed January 26, 2026, [https://www.researchgate.net/publication/372400146\_Operative\_ekphrasis\_The\_collapse\_of\_the\_textimage\_distinction\_in\_multimodal\_AI\_PLEASE\_REFER\_TO\_PUBLISHED\_VERSION](https://www.researchgate.net/publication/372400146_Operative_ekphrasis_The_collapse_of_the_textimage_distinction_in_multimodal_AI_PLEASE_REFER_TO_PUBLISHED_VERSION)  
8. The Dissolution of the Text-Image Distinction in Multimodal AI, accessed January 26, 2026, [https://german.uic.edu/events/operative-ekphrasis-the-dissolution-of-the-text-image-distinction-in-multimodal-ai/](https://german.uic.edu/events/operative-ekphrasis-the-dissolution-of-the-text-image-distinction-in-multimodal-ai/)  
9. the collapse of the text/image distinction in multimodal AI, accessed January 26, 2026, [https://escholarship.org/content/qt1cf8h0jz/qt1cf8h0jz.pdf](https://escholarship.org/content/qt1cf8h0jz/qt1cf8h0jz.pdf)  
10. Two new projects funded \- HANNES BAJOHR, accessed January 26, 2026, [https://hannesbajohr.de/en/2025/10/19/two-new-projects-funded/](https://hannesbajohr.de/en/2025/10/19/two-new-projects-funded/)  
11. Localized Semantic Video Editing with Noise-Extrapolated Diffusion ..., accessed January 26, 2026, [https://www.ecva.net/papers/eccv\_2024/papers\_ECCV/papers/01890.pdf](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01890.pdf)  
12. Clifford Geertz The Interpretation of Cultures. Selected Essays, accessed January 26, 2026, [http://hypergeertz.jku.at/GeertzTexts/Geertz%20Interpretation%20of%20Cultures%201973.pdf](http://hypergeertz.jku.at/GeertzTexts/Geertz%20Interpretation%20of%20Cultures%201973.pdf)  
13. Thick description | Literary Theory and Criticism Class Notes \- Fiveable, accessed January 26, 2026, [https://fiveable.me/literary-theory-criticism/unit-8/thick-description/study-guide/9FRywJGWCH1SlgzL](https://fiveable.me/literary-theory-criticism/unit-8/thick-description/study-guide/9FRywJGWCH1SlgzL)  
14. Engineering models circa 1914 and in Wittgenstein's "Tractatus", accessed January 26, 2026, [https://scispace.com/pdf/physical-pictures-engineering-models-circa-1914-and-in-46lu91kztk.pdf](https://scispace.com/pdf/physical-pictures-engineering-models-circa-1914-and-in-46lu91kztk.pdf)  
15. What is Thick Description in Qualitative Research? \- QDAcity, accessed January 26, 2026, [https://qdacity.com/thick-description/](https://qdacity.com/thick-description/)  
16. What would a 5th Pajama Sam game be about? \- Reddit, accessed January 26, 2026, [https://www.reddit.com/r/pajamasam/comments/vzhdy6/what\_would\_a\_5th\_pajama\_sam\_game\_be\_about/](https://www.reddit.com/r/pajamasam/comments/vzhdy6/what_would_a_5th_pajama_sam_game_be_about/)  
17. Claude Code Full-Stack Configuration Guide \- htdocs, accessed January 26, 2026, [https://htdocs.dev/posts/claude-code-full-stack-configuration-guide/](https://htdocs.dev/posts/claude-code-full-stack-configuration-guide/)  
18. How TCO, Specialization, and Governance Are Forging the Next AI ..., accessed January 26, 2026, [https://machine-learning-made-simple.medium.com/how-tco-specialization-and-governance-are-forging-the-next-ai-infrastructure-stack-122aac89a647](https://machine-learning-made-simple.medium.com/how-tco-specialization-and-governance-are-forging-the-next-ai-infrastructure-stack-122aac89a647)  
19. "the holy rieich": religious dimxnsions of nazi ideology, 1919-1945, accessed January 26, 2026, [https://www.collectionscanada.ca/obj/s4/f2/dsk1/tape9/PQDD\_0005/NQ41317.pdf](https://www.collectionscanada.ca/obj/s4/f2/dsk1/tape9/PQDD_0005/NQ41317.pdf)  
20. Mirna Zakić \- Ethnic Germans and National Socialism in Yugoslavia ..., accessed January 26, 2026, [https://www.scribd.com/document/454346336/Mirna-Zaki%C4%87-Ethnic-Germans-and-National-Socialism-in-Yugoslavia-in-World-War-II-2017-Cambridge-University-Press-pdf](https://www.scribd.com/document/454346336/Mirna-Zaki%C4%87-Ethnic-Germans-and-National-Socialism-in-Yugoslavia-in-World-War-II-2017-Cambridge-University-Press-pdf)  
21. A Look at a Framework Treating AI Services Like Legos, Not ... \- Reddit, accessed January 26, 2026, [https://www.reddit.com/r/programming/comments/1p10mua/a\_look\_at\_a\_framework\_treating\_ai\_services\_like/](https://www.reddit.com/r/programming/comments/1p10mua/a_look_at_a_framework_treating_ai_services_like/)  
22. Benchmarking String Literal ("") vs Template Literal \- DEV Community, accessed January 26, 2026, [https://dev.to/maafaishal/benchmarking-string-literal-vs-template-literal-using-performancenow-49gh](https://dev.to/maafaishal/benchmarking-string-literal-vs-template-literal-using-performancenow-49gh)  
23. Deconstructing LEGOs \- The University of Utah Magazine, accessed January 26, 2026, [https://magazine.utah.edu/issues/winter-2025/deconstructing-legos/](https://magazine.utah.edu/issues/winter-2025/deconstructing-legos/)  
24. LEGO, Synthetic Biology, and a Digital Episteme., accessed January 26, 2026, [https://repository.lib.ncsu.edu/bitstreams/a4a525d5-fead-4730-a73e-24c195f4f62e/download](https://repository.lib.ncsu.edu/bitstreams/a4a525d5-fead-4730-a73e-24c195f4f62e/download)  
25. Language in the Buddhist Tantra of Japan: Indic Roots of Mantra ..., accessed January 26, 2026, [https://dokumen.pub/language-in-the-buddhist-tantra-of-japan-indic-roots-of-mantra-9781350037267-9781350038110-9781350037274.html](https://dokumen.pub/language-in-the-buddhist-tantra-of-japan-indic-roots-of-mantra-9781350037267-9781350038110-9781350037274.html)  
26. I Thought Compilers Were Scary. So I Built Sauce. \- DEV Community, accessed January 26, 2026, [https://dev.to/kayleecodez/i-thought-compilers-were-scary-so-i-built-sauce-5j](https://dev.to/kayleecodez/i-thought-compilers-were-scary-so-i-built-sauce-5j)  
27. Diffractive Reading: New Materialism, Theory, Critique 1786613964 ..., accessed January 26, 2026, [https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html](https://dokumen.pub/diffractive-reading-new-materialism-theory-critique-1786613964-9781786613967.html)  
28. Survey and analysis of hallucinations in large language models, accessed January 26, 2026, [https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1622292/epub](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1622292/epub)  
29. PARC: A Quantitative Framework Uncovering the Symmetries within ..., accessed January 26, 2026, [https://openaccess.thecvf.com/content/CVPR2025/papers/Schmalfuss\_PARC\_A\_Quantitative\_Framework\_Uncovering\_the\_Symmetries\_within\_Vision\_Language\_CVPR\_2025\_paper.pdf](https://openaccess.thecvf.com/content/CVPR2025/papers/Schmalfuss_PARC_A_Quantitative_Framework_Uncovering_the_Symmetries_within_Vision_Language_CVPR_2025_paper.pdf)  
30. Counterfactual Self-Questioning for Stable Policy Optimization in ..., accessed January 26, 2026, [https://arxiv.org/html/2601.00885v1](https://arxiv.org/html/2601.00885v1)  
31. Aligning Prompts with Ranking Goals: A Technical Review of Prompt ..., accessed January 26, 2026, [https://www.preprints.org/manuscript/202509.1959](https://www.preprints.org/manuscript/202509.1959)  
32. \[Literature Review\] Controlling Risk of Retrieval-augmented ..., accessed January 26, 2026, [https://www.themoonlight.io/en/review/controlling-risk-of-retrieval-augmented-generation-a-counterfactual-prompting-framework](https://www.themoonlight.io/en/review/controlling-risk-of-retrieval-augmented-generation-a-counterfactual-prompting-framework)

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAmwAAAAhCAYAAABkzPe+AAAHkklEQVR4Xu3caaitVRnA8aeyQZtsnsNKIQobjAZtug1aBpVWNkjDBW2gooGioA9lg1BUNI+IUoo0q1FSiGgjSUT1oQK10SaaB6ISGtaftZ67n7POPufswz11r5f/Dx72Ousd1lrvu+V97lrvNkKSJEmSJEmSJEmSJEmSJEmSJEmSJEmSJEmSJEmSJEmSJEmSJEmSJEmSJB2gbtTixnOlJEn7g29uEvuT67W4osXl4/PCFu8tdcTd9+z9/3flCPrzjWnbTnprizvOlXvhOXPFPnJqi1+3+OW8oXlZi1/E8m075eUt/tPidVP96bH2eydJ0j5xYinzwEqfKuXt+PlcscPo49xG7fe+dJvoicX/0htb3GKuXNFDWnxyqnva9Pe+9PoWr23xzqmehG1v7jHjXsWyhA0fiL1rX5KkHVUfSrtK+dEtHtXi2i2u3+JOLe4wtt0ueqKCo1v8ocURLW426lZ1ylyxAfr4syV16eEtrjPKD25x21F+YIvDW1yrxWNHHY4vZXD881vcpNQd1eLYUWb/m5dt1a1aXDXKB8fiGGbE7lzKee3Ss1s8a6oD57tbi4dFT2QOjd73e8bi/Fxzzln7xH1iHI+f6v7e4gvR7w+YkXzSnj0irhv9nNzrxNhpA/O1WtWq95aE7Qmx9n7mfZgTpnu3OCEWS5gkZU+M/v3kXqeTo4+bMee4OefjYn0it1HC9r5YtH9Y9ONu2uJB0a8z+K5xnyraeGH061rdN/o1pu/PLfXPi95fSZI2NT8UQTJwRvQl0kujJz0kZbnv51v8Y+xHMnB1iy/G9mduSEaIrdAuS2P0IyP7clCLf7e4wfj7j7FImn4aPSE4v8VHWhwzPk+LtQ9JljN3RT82fSd6G8z88ED/W9lWkWBlMkmik8dw/bgur2pxQdkHr4ieEJOwfbDUv6bFD6PPiH0o+ownCUkmFXl+xsP56dNuDmw+G30cLPM9c9SRPNAHlh25P/hcrL3n348+g0c/Mrlh7LSRY9896rdj1XubCds/S10mNLWfJGVfaXFWi5+MOu4X+1w0tn1v1DPW/E7muFnaZIzvaHGPUYe8trOasL0nelu7o99P2rpPize0ODt6gg3+EUMb3Fv+e0l3jd7vV7f4dvSxMmP6kuj3iu/DU/bsLUnSEvWhCGYSqLvhiG+VbSQYPLC+Xurw2+nv6vZbxItaPGDP3svRn81m2EgsMmFjuTcTNhKGj40ySOCYdUI9PmdsmMl6aqknccmZOx7gWa5uGWv7Nh9DcolnxGJmhuQjkWwm+pQzRd+d6jOp4Py5PFyTCvqR46Aux/GbWL8kmseQ3N1/qmfmD7SR46B+2djneznHKveWhI2klJk8vlt42/jMfjJbxYxZfie538yanlD2IXGu95RxV8x21vHcupTz2la8K1nPR1svGGXaOqdsu6SUs403x6KNv45P1HPyj54cU62XJGmd+UHBA3uuq5g5mBO2nE2o78at6rzoD9/N0J/NEjZeyuehB5b7MmEjgXnLKOOrpczxtEvydFWLe0Vf3iKxSjVZfVesX+YCD2WOTxsdc1KLR4zyWS2ePso1YftSix+3uDjWLi/XpILzXzbKnD+vww9i0Q/qchwkLp+JRfKAPOajLY6c6kkCkW1k/bKxb2WVe0vClt8b2mGZMWU/SbaWfSdZ/s16rlfdJxO2HPefY5FYsR/L+lnOa1u9P9aej7ZyeZi2Ti/buG/gWtIGS9UsZ2cbHEv922Nx30HCJknSSuYHIe+qbbT8d3L0GZmrp/o/jU8Sje1idmUr9HGzHx0wm5GzS8zqHDfKvHNUE7avlTLHM9t2SotHjjqWskh0WOoCy1fp3bE8aZl/dLDRMcx4ZTv/Gp+gH0+OPrPJciVLvHcp21GTCs6fyRTnz+vAZ56fMuPgf1nBcijLm/Udrzzm1OjLprU+Z8R2ImFb5d6SsOU7dbTDEm3KfpL01RlHcJ1yuRgkSfU7wbiR4yY5OmSU2a8mbKeNcjX/6CBnAUFbNWH78vhkeTTbeFP0NliCZUmVGcejx7ZUz88SqyRJ61wefTaHmQfe77mybCORYcbm09FnBXa1+EssEjnes+K4fBjy7tQFsVj+WxUPs83k/9aDtokLoy9V0T5/MwZeoqe/l0RPzniJm1mrj7f4ffTlKJZCGSvH8C4cY6X8u+hLWDzcPxz9HTzKPGx/Nfbhk/1JStm/op7zsR/X4KGjzDEkT3nMi6MvG3PNeIeOd5c+EX38L41+nUmIePDzECc4zyuj/1qSMmPJ8xN5fsqcn9ky+s5yIWPPhIUk4UejjsSHa8ExfILz03f6nEu189jzWm3HVvcWJIw5Hl7mZ3b3zLGNBJ16+p6Y2T03Fr9mzmNZ9iZppsx9BuMmQWfcIAHlu0S/+N4wrry2dckSJGN5bTmG9rIt3kOjLY4hwc/v1VHRk3f25x5wf2iDpdTHxOK+Erz7iSOiJ6gsr95v1EmSpP1c/lgAJHBzIqFrpvqPIZAwSpKkayhma44ZZWb8fLAfGJjNPHSUj43FjxckSZIkSZIkSZIkSZIkSZIkSZIkSZIkSZIkSZIkSZIkSZIkSZIkSZIk6UD2X2pYxOIInSLKAAAAAElFTkSuQmCC>

[image2]: <data:image/png;base64,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>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABMAAAAXCAYAAADpwXTaAAAAbUlEQVR4XmNgGAWjgKqgEF2AErAQiFXRBckF1kC8DV2QEpANxGnogiAgBMRSZOClQLwWyoaDTiBeTgY+CcT/gLiegUKgAsR7GSDhRxHgAOIrQCyDLkEOSAHiYnRBcsF+IGZBFyQXSKILjIJBAAAj9xTbjwG/KAAAAABJRU5ErkJggg==>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAYCAYAAAAlBadpAAAA6ElEQVR4XmNgGAXWQHwbiJ8B8QsofQ+I7wDxfSA+DMSxQMwG04ANrADi/0BsiSTGAcQ5UPE+JHEMALLtAxAzo0sAwUMg/gPEcugSICDDADF9M7oEEDAB8Rcg/gfECqhSEBDNANFcgi4BBI4MELkFaOJwMJsBosAYTVweiE8B8WMgFkeTgwNQaIOcVQPE5UBcDcRLGSBhMB+IBRFKUQHMv2eB2B+KfYDYgQES2nhBDANEcwOaOFFgLgNEswOaOFEAlIq+AzE7ugQhoM4AsfUgugQ+AEqCt4D4HQPE1m8MkOgIRlY0CoY0AACDRS+8qwZWSgAAAABJRU5ErkJggg==>

[image5]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAYCAYAAAD6S912AAABHUlEQVR4Xu2TvUoDURBGBw1qZbASghg7H0CIiE1sUgkWluoLiHaKRVLkCXyBILEJ2FtYi50g9iqKCGIVBI02QT3D3DXrkEWyYpUcOCw73+zd+7Mr0i/kfOEvbGMbx32gLOI1PuJTuN7iDd7hGW7gSPQAnOBl7L4rR/iJC7HaGG6F+n6oZfAFN6OmJHRWzzjsA7gXW+I0zmMLsz86HFNiszj2AQzhK37gDO7iQbyhG2tiA+74AJbEssNwry8tfKcJ1MQemnP1PJ7jA06GWqkTJ6OnrEuq4B6WsSG2p3Wc6LT+TrR/F7gSXMai2Cn3zLrYgFVXT42emA5YdPXU6N/wjqM+SMOs2OxOfdAr+ntdYVNsdm9in8ZqvGnAgH/kC/epN7Bvx0pMAAAAAElFTkSuQmCC>

[image6]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAmwAAAArCAYAAADFV9TYAAAFgUlEQVR4Xu3dachtUxzH8b+ZkOneMt7ILGWWITN5I0XeyBQZIl6IkOk5onghQyKZFUm6XlCEcF1KxAsSSrhkDJnnDOvXWqtnnf/Ze599zj33Puc85/upf89e/zPtu7u1/61pmwEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADzzLohLvJJAAAAjIcLQiwN8at/AQAAAOPjGaNgAwAAGGsUbAAAAGNOBdtvPgkAAIDxoYLtd58EAADA+FDB9odPtvBfiPctrjKts0OIY0I8afH9CgAAAAzggxA/pVDxNYhDbPAi7KAQu/pkso5PLIc1faLB4hCv++Qc2dwnGiz0CWeU1xMAgHlnU4uFySr+hRb0uT3T8STccHPBtq1/ocGdPpHM+MSQVgvxtE82+DnEzen49vKFOXCJTzR4NcTOPlm43CcAAIDZyyE+L9qbhPinaIuKm/3T8dqpnekGnP1bHI+zRSG+t8F62epc4xMV/O+ofb/LqQDbzOXkB4vXXO6z2e96Jf2V/UL8XbRHpeq8fY+mzruKzjsrz1uaCtMrfQIAgGn3WohdfNK6b8JbWpzLVfolxNYWe1bWK/K3FceTQEXE1xZ7F4fVr2DTfDhfoKiwVWGc7RZiQdHOTrbupznsa/GcV7XZIi472Lq/cxQ05FzSbx9ftDWEe0LRzurOu3Sra2dX+QQAANPO30SzssA4KcTFRVvy5zQUd22Rz8Oik+Idi/+WZ/0LA+hXsJ1l3UOGG4Z4q2jLFa6d3R1i76Kt39L5rlHkMs0jqyqehrV9iKdczheaB4bYvWhndedd0rWvcrVPAAAwzY62dvuYaYK/hqkuDfGwxaGujdJrmu+mrTV0M1asnvLeSy6WhHgxxPPFe+ZKPvd9/Ast9SvYPrO4olWhwvCrEMd1vcPsBdfOdF6XWbz2um4q7DTXrc5jPrEcHrL4m/nc37PeXrGq4moLmz1v/b+pO29fwGUzPgEAwDS7zuJN1dMNt1R3Y9UwXuncFJNGPV7LrHfeXltNBdvZ1nv9qn7HDz1m/rP9lPPasj1CPFITdQW2hnH9b79pvUOuT7i23GO9n61S956OTwAAMM1OD3GjTwb3unbdjdX3jmlRwl4ulx3VEONAe66d75MtNRVsKor89fNt+cQnkkE3BlYP6CicY73nWVVoPugTwYfW7rz992cdnwAAYNrppln2miyx2OOU7WhxSKuKPntqOtZcJq26nEQaRnzUJwfQVLDpGmk4MdNigapCRcOPnoqmpu/2tAjhDJ8c0jfW+5zWqvM+0+KilJLe1+a8P/WJpOMTAADA7DCLvW1NO//X0SpBfXZSqVdtY58cUJvipB8tGCgn6Q/jFJ9YSfyClDZUuPp5fFnHJwAAwHT7wieGMIqCTZ7ziQGsZXEoci6oN25QWjnrFyFkHZ8AAADTabsQX/pkH1Xz/WRUBdvhId71yZY+CrGVT64k2ux3J59scEuI632y0PEJAAAw3h63uI2IFifokUXf2uyWIjeF+CvEHRb3OfvT4hyu8yyu+qyjR2fd4JM1tIpSiyuq5m8BAABMvQMs7vOlYunjlNOxtg7ZILXVS6YFD/JGiAvTcX7GZhUVgUdYnLt3aPqrUA/XkRb3p9N2HDMWv1+/ScEGAADQQD1smqQuKpy0clX0+KNcSG1THOu9dfOqtAJWm7mqGFN0akKvqVhU6FFJo1p9CQAAMO9oE9/8TEo971PDohqmFD2BIT/j9IEQ36Xju0L8GOK01AYAAMAKdKLFnfrlWIsb8+ZCTD1qeQh0WYjF6fhtizvwL01tAAAArEDru/ai4nhBcZwXImQLXRsAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADAJPsfSqb6EW46lU8AAAAASUVORK5CYII=>

[image7]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAYCAYAAAD3Va0xAAAA/klEQVR4Xu2Tv0qCcRSGXyRnhfAOrL3JURDBQRo0aGkUu4QuwxAnJydpbpAo8AaEhgYXK0yQamsIdOrP+/McPuRNpW//HnhweI7Hj6MCCXEp0Wf6Qqf+OqEV70P6RB/X7HjbyDX9oWUN5BTWejQt7Q/v9JPuaSAt2KITDcohbPBGg3NPv+m+BqUJW3ShgWTpF33QsIk+bNEZ7OkOaN5teGtH0zuY0wW9XfPODbcLi2rR9BbCp4fBgQbn3/c5x/b7ZBDjPlewRQUN5Bgx7rPr93MJW1TXoBzBBsNxlRQdw3pOWkQR9v/5gH1b4YlmtApbMKKv3pb0jXZX70xIMH4BCVZB68f13h4AAAAASUVORK5CYII=>