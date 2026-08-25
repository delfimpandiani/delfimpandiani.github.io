---
title: "RESEARCH"
description: "Research areas and selected publications of Delfina S. Martinez Pandiani."
---

# RESEARCH



My work operates at the intersection of **critical data** studies, **software** development and auditing, **queer** and **media** studies, and **anticolonial** epistemologies. I study how abstract, context-dependent, and inherently subjective cultural concepts—most centrally **identity**, **toxicity**, and **vulnerability**—are operationalized, classified, and flattened within datasets, machine learning models, and generative AI architectures.

During my doctoral research, I resaerched how pre-generative computer vision systems are taught to "see" and measure abstract cultural values like *freedom*, *comfort*, *danger*, and *power*. This revealed a fundamental computational tension: the structural necessity of machine learning to reduce multifaceted, culturally situated human phenomena into static, legible, and discrete mathematical variables. Today, I extend this critique to large language and vision-language architectures, analyzing how this flattening operates across their latent representations and downstream platform ecosystems.

Rather than approaching classification errors, representational harms, or hallucinations as isolated bugs to be corrected with larger datasets or parity benchmarks, my methodology centers on **“following the glitch.”** Drawing on glitch feminism, queer approaches to failure, and critical AI studies, I treat the moments where computational taxonomies, binary schemas, and colonial hierarchies break down as diagnostic and productive windows. These glitches reveal how systems operate underneath their interfaces, while exposing tactical sites for queer refusal, epistemic opacity, and counter-hegemonic practice.


## Conceptual Web

{{< research_map >}}

---

## Core Research Inquiries

### 1. Identity: Flattening, Latency, and the Hallucinated Subject

Computational systems require identity to be persistent, discrete, and legible. This research thread interrogates how gender, sexuality, race, and geography are modeled, compressed, and negotiated across LLMs, generative vision models, web-scale training data, and conversational interfaces.

{{< diagram_identity >}}

* **Sentence Completion & Normative Baselines:** Auditing how language models encode societal norms. Rather than relying on simplistic binary evaluations (queer vs. non-queer), this work audits model generations across four metrics (*sentiment, regard, toxicity,* and *prediction diversity*), demonstrating that models penalize queer-marked subjects while treating unmarked categories as the normative cis-heteronormative default.  
  ↳ *Explore in [QueerGen](/publications#queergen).*
* **Pre-training Corpora & Colonial Taxonomies:** Auditing the persistence of commercial adult content within Common Crawl pre-training corpora, revealing that foundational models inherit explicit demographic taxonomies (*Asian, Latina, Brazilian, Ebony*) derived from pornographic platforms, embedding colonial hierarchies into baseline AI representations.  
  ↳ *Ongoing work in collaboration with Goethe University Frankfurt: [Echoes of NSFW](/publications#echoes-of-nsfw) [WIP].*
* **Visual Grammars in Synthetic Portraiture:** Auditing over 1,200 synthetic portraits generated from neutral demographic prompts, identifying 157 unprompted aesthetic features (gaze, pose, lighting, atmosphere) that position marginalized bodies within colonial and affective regimes of docility and vulnerability.  
  ↳ *Ongoing collaboration with Affect Lab: [Mapping the Latent Image](/publications#mapping-latent-image) [WIP].*
* **Ontological Subject Fabrication:** Theorizing AI hallucination not as an epistemic error, but as an infrastructure of subjectivation. Traces the recursive stabilization between the **Hallucinated Human Subject** (the datafied double built to be governable) and the **Hallucinated Machinic Subject** (the synthetic persona performing unrefusing care while obscuring the precarious, racialized data labor sustaining its existence).  
  ↳ *Read the theoretical framework in [The Hallucinated Subjects](/publications#hallucinated-subjects).*

---

### 2. Toxicity: Multimodal Complexity, Taxonomies, and Trauma Extractivism

Automated moderation tools routinely reduce online harm to a binary classification task. This thread dissects the computational operationalization of "toxicity," uncovering how benchmarks conflate distinct rhetorical phenomena and how platforms enable the extraction and circulation of historical violence.

{{< diagram_toxicity >}}

* **Harmonizing Multimodal Toxicity:** A systematic survey of 158 computational studies and 34 datasets evaluating toxic memes. This work untangles widespread terminological confusion by formalizing a meta-model across three independent dimensions:
  * **Target:** *Who* is attacked (Individual, Organization, Community, Society).
  * **Intent:** *Why* the content was produced (Harm/Abuse, Disinformation, Exploitation).
  * **Conveyance Tactics:** *How* harm is delivered (Attack types, persuasion fallacies, entity roles).  
  *Critique:* The survey demonstrates that automated classifiers inadvertently freeze demographic schemas, relying on hard-coded identity taxonomies as target proxies to infer whether an attack has occurred.  
  ↳ *Access the meta-taxonomy in [‘Toxic’ Memes: A Computational Survey](/publications#toxic-memes-survey).*
* **Memetic Trauma Extractivism:** Tracing the digital lifecycle of South American state terror—specifically the *vuelos de la muerte* (death flights) carried out by Southern Cone military dictatorships—into the alt-right "Free Helicopter Rides" meme on 4chan's `/pol/`. Combining ten years of computational archives with digital ethnography, this work articulates **Memetic Trauma Extractivism**: how platform infrastructures detach historical trauma from the Global South, sanitize its state-terror origins, and convert it into gamified ideological tokens used to forge reactionary identities in the Global North.  
  ↳ *Read the analysis in [Tracing a Memetic Journey](/publications#tracing-memetic-journey).*

---

### 3. Vulnerability: From Inherent Traits to Vulnerabilizing Practices

Rather than viewing vulnerability as an intrinsic demographic deficit belonging to specific "vulnerable groups," this research examines how vulnerability is **actively manufactured, amplified, and precarized through data practices and algorithmic interventions**.

{{< diagram_vulnerability >}}

* **The Protection Paradox:** Grounded in an AI for Social Good (AI4SG) case study involving computer vision pipelines designed to detect children in monetized family vlogs for regulatory advocacy, this work demonstrates how technical efforts to protect subjects often subject them to intensified extraction, exposure, and control.
* **Reflexive Pipeline Junctures:** We formulate an operational ethics protocol analyzing how granular technical choices across four pipeline stages produce precarity:
  * **Dataset Design:** Navigating sampling scale, attention-mirroring biases, and the false equivalence between platform accessibility and ethical consent.
  * **Operationalization:** Critiquing how fluid human affect and caregiving are reduced to rigid labels (*distress, nudity*), imposing moralized classifications and biometric tracking on minors.
  * **Inference & Evaluation:** Analyzing data sovereignty risks when querying third-party APIs, and showing how confidence thresholding pathologizes ordinary domestic life.
  * **Dissemination:** Preventing *narrative fixing* (locking subjects into permanent roles of victimhood) and mitigating the risk of research artifacts turning into discovery tools for online harassment.  
  ↳ *Review the protocol in [From Vulnerable Data Subjects to Vulnerabilizing Data Practices](/publications#vulnerabilizing-data-practices).*

---

## Methodological Stance: "Following the Glitch"

Across all three threads, my work connects technical audits with critical theory to interrogate points of system failure:

* **Beyond Inclusion-as-Capture:** Expanding dataset diversity or adding granular classification labels frequently extends the reach of computational surveillance. Inclusion within reductive taxonomic architectures functions as algorithmic capture. My work pinpoints the boundaries where systems *cannot* and *should not* classify.
* **Reflexivity as World-Making:** Treating technical choices—from tokenization and bounding boxes to loss functions and data dissemination formats—as active, ethically constitutive decisions that script social reality.
* **Affirming Opacity & Fugitivity:** Drawing on Édouard Glissant’s *right to opacity* and Marquis Bey’s *trans fugitivity*, glitches are treated not as bugs to patch, but as structural limits that protect human multiplicity from totalized datafication.







```terminal
> THREE CORE AXES:
> [IDENTITY] [TOXICITY] [VULNERABILITY]
> _
```

<div class="research-grid">

<div class="research-column">
<h3>IDENTITY</h3>
<p>Breaking or collapsing the binary and taxonomic (colonial) hierarchies of identity categories. This includes gender and sexuality binarisms or taxonomic ideas (male/female, queer/non-queer) and moving toward more complex framings like <strong>marked vs. unmarked</strong>.</p>

<p>This work is seen in the latest <strong>QueerGen</strong> article, my role as co-founder of the <strong>Queer and Feminist Informatics Network (QFIN)</strong>, and two upcoming works:</p>

<ul>
<li><strong>"Echoes of NSFW"</strong> — on the identity categories (demographic, national, regional, and racialized terms like <em>asian, latina, brazilian, ebony</em>, etc.) in NSFW pages that are part of the training data of foundational models through Common Crawl. This work is led by PhD student <strong>Ella Streefkerk</strong> at Goethe University Frankfurt.</li>
<li><strong>Synthetic portraiture</strong> — how identity/demographic labels like age, gender, and racial markers affect outputs in text-to-image models. This interest is centered on synthetic portraiture and developed in collaboration with the <strong>Affect Lab</strong>, currently finishing a paper on <em>"Mapping the Latent Image: Analyzing Representational Power and Harm in Synthetic Portraits."</em></li>
</ul>

<p><strong>Recent publication:</strong> <em>"The Hallucinated Subjects: Gender, Coherence, and the Ontological Politics of Generative AI"</em> (with Siân J M Brooke, 2026) — develops a queer and technofeminist account of how GenAI hallucination operates as ontological subject production, fabricating gendered coherence through the hallucinated human subject and the hallucinated machinic subject.</p>

```terminal
> STATUS: ACTIVE
> PUBLICATIONS: QUEERGEN, QFIN, THE HALLUCINATED SUBJECTS
> UPCOMING: ECHOES OF NSFW, MAPPING THE LATENT IMAGE
> _
```
</div>

<div class="research-column">
<h3>TOXICITY</h3>
<p>Questioning who and how decides who is toxic. Operationalizing abstract social concepts—toxicity, moderation, harm—in datafied environments.</p>

<p>This includes developing AI models for detecting and analyzing toxicity in online platforms, with a focus on identifying patterns of toxic symbology in memes. It also involves advocating for digital literacy skills and interrogating how morality and normativity are operationalized in content moderation systems.</p>

```terminal
> STATUS: ACTIVE
> FOCUS: MEMES / CONTENT MODERATION / DIGITAL LITERACY
> _
```
</div>

<div class="research-column">
<h3>VULNERABILITY</h3>
<p>Questioning who gets labeled vulnerable, and how that labeling becomes embedded in governance systems and surveillance practices.</p>

<p>This includes work on <strong>vulnerable data subjects</strong>—such as children in family vlogs—and the protection paradox in AI-based analyses of platformized lives. It also examines how vulnerability is co-constructed through AI systems and data practices, balancing public interest with individual rights.</p>

```terminal
> STATUS: ACTIVE
> FOCUS: CHILDFLUENCERS / DATA GOVERNANCE / PROTECTION PARADOX
> _
```
</div>

</div>


```terminal
> FULL PUBLICATION LIST: [PUBLICATIONS PAGE]
> GOOGLE SCHOLAR: [LINK]
> _
```

For the complete publication list, see the [Publications](/publications) page.

[GOOGLE SCHOLAR >](https://scholar.google.com/citations?hl=en&user=aWasWbEAAAAJ)
