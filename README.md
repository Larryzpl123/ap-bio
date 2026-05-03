# AP-Bio - Comprehensive 5 Review Guide

*Last-day review. Focused on what's actually tested, not the textbook.*

---

## How AP Bio is scored

- **MCQ:** 60 questions, 90 min — 50% of score. Half are standalone, half are in 2–4 question sets that share a stimulus (data, graph, experiment).
- **FRQ:** 6 questions, 90 min — 50% of score.
  - Q1 (Interpreting & Evaluating Experimental Results) — 8–10 pts, longest
  - Q2 (Interpreting & Evaluating Experimental Results with Graphing) — 8–10 pts
  - Q3 (Scientific Investigation) — 4 pts
  - Q4 (Conceptual Analysis) — 4 pts
  - Q5 (Analyze Model or Visual Representation) — 4 pts
  - Q6 (Analyze Data) — 4 pts
- **5 cutoff:** typically ~70% raw score. You don't need everything — you need the high-leverage stuff cold.

**Unit weighting (memorize so you allocate study time correctly):**

| Unit | Topic | Weight |
|------|-------|--------|
| 1 | Chemistry of Life | 8–11% |
| 2 | Cell Structure & Function | 10–13% |
| 3 | Cellular Energetics | 12–16% |
| 4 | Cell Communication & Cycle | 10–15% |
| 5 | Heredity | 8–11% |
| 6 | Gene Expression & Regulation | 12–16% |
| 7 | Natural Selection | 13–20% |
| 8 | Ecology | 10–15% |

Units 3, 6, and 7 are the biggest. If you have to triage, do those last and hardest.

---

## Universal FRQ scoring rules (read this first, save 5+ points)

These show up across every FRQ. Memorize the language.

### Scientific claim language
For any "does the data support the hypothesis" question, write:
> **"The data [supports / does not support] the hypothesis because [specific quantitative comparison from the data]."**

Example: "The data supports the hypothesis because the experimental group's enzyme activity (45 µmol/min) was 3× higher than the control (15 µmol/min)."

Just saying "yes it supports" = 0 points. You need the quantitative reason.

### Experimental design — required elements
Every experimental design FRQ wants:
1. **Independent variable** (what you change) — state explicitly
2. **Dependent variable** (what you measure) — state explicitly *and* how it's measured (units!)
3. **Control group** — what makes it a control
4. **Constants** — at least 2 specific variables held constant
5. **Replication** — "multiple trials" or "n=30"
6. **Prediction** — "If [hypothesis] is correct, then [specific measurable outcome]"

### "Justify" vs "Explain" vs "Describe" vs "Identify"
- **Identify:** name it. One word/phrase OK.
- **Describe:** state what something is or does. No reasoning.
- **Explain:** include the *why* or the mechanism.
- **Justify:** use evidence from the stimulus to defend a claim. **Quote/cite the data.**
- **Predict:** state what *will* happen + reasoning.

### Connect to a bigger concept (for 1 free point)
Many FRQs end with "explain how this relates to [evolution/homeostasis/cell communication]." Always tie back to:
- **Natural selection** (variation → differential survival → allele frequency change)
- **Homeostasis** (negative feedback maintains stable internal conditions)
- **Energy flow** (energy is required, transformed, and lost as heat)

---

## Statistics — the formula sheet stuff you must know

You get a formula sheet, but you need to know **when** to use each.

### Mean, standard deviation, standard error
- **Mean (x̄):** average
- **Standard deviation (s):** spread of data around the mean
- **Standard error (SEM):** s / √n — uncertainty of the mean estimate
- **95% Confidence Interval:** mean ± 2(SEM)

**The killer rule:** If the **error bars (95% CI) of two means do NOT overlap**, the difference is **statistically significant**. If they overlap, it is *not* significant. This shows up on FRQs constantly.

### Chi-square (χ²)
Use when comparing **observed vs expected categorical data** (genetics ratios, ecological distributions).

$$\chi^2 = \sum \frac{(O-E)^2}{E}$$

**Steps:**
1. State H₀ (null): "There is no significant difference between observed and expected."
2. Calculate expected values from the predicted ratio.
3. Calculate χ² using the formula.
4. **Degrees of freedom = (number of categories) − 1**
5. Compare χ² to critical value at p = 0.05.
6. **If χ² > critical value → REJECT H₀** (difference IS significant; data does NOT match prediction)
7. **If χ² < critical value → FAIL TO REJECT H₀** (difference is not significant; data IS consistent with prediction)

⚠️ Never say "accept the null." Always "fail to reject."

**Critical values (memorize at p = 0.05):**

| df | Critical value |
|----|----------------|
| 1 | 3.84 |
| 2 | 5.99 |
| 3 | 7.81 |
| 4 | 9.49 |

### Hardy-Weinberg
$$p + q = 1 \qquad p^2 + 2pq + q^2 = 1$$

- p = freq of dominant allele, q = freq of recessive allele
- p² = freq of homozygous dominant, q² = freq of homozygous recessive, 2pq = freq of heterozygous
- **5 conditions for HWE (no evolution):** large population, no migration, no mutation, random mating, no natural selection
- **If a population is in HWE, it is NOT evolving.** Allele frequencies stay constant.
- **Always start from q²** when given % of recessive phenotype: q = √q², then p = 1 − q.

### Rate calculations
Rate = Δ(quantity) / Δ(time). Always include units. Used everywhere — enzyme activity, photosynthesis (O₂ produced/min), respiration, population growth.

---

# Unit 1 — Chemistry of Life (8–11%)

## Water properties (memorize 4)
1. **Cohesion** (water-water H-bonds) → surface tension, transpiration in plants (xylem)
2. **Adhesion** (water-other) → capillary action
3. **High specific heat** → temperature buffering, climate moderation
4. **Less dense as solid** → ice floats, insulates aquatic life

All from **hydrogen bonding** due to polarity (O is electronegative).

## The four macromolecules

| Macromolecule | Monomer | Bond | Key examples / roles |
|---|---|---|---|
| **Carbohydrate** | Monosaccharide | Glycosidic | Glucose (energy), starch (storage, plants), glycogen (storage, animals), cellulose (structure) |
| **Lipid** | Glycerol + fatty acids (no true monomer) | Ester | Triglycerides (storage), phospholipids (membranes), steroids (hormones) |
| **Protein** | Amino acid | Peptide | Enzymes, antibodies, hemoglobin, structural |
| **Nucleic acid** | Nucleotide | Phosphodiester | DNA, RNA |

**Dehydration synthesis:** join monomers, release H₂O.
**Hydrolysis:** break polymers, add H₂O.

## Protein structure (high-yield)
- **Primary:** sequence of amino acids (peptide bonds)
- **Secondary:** α-helix and β-pleated sheet (H-bonds in backbone)
- **Tertiary:** 3D folding (R-group interactions: H-bonds, ionic, disulfide bridges, hydrophobic)
- **Quaternary:** multiple polypeptides (e.g., hemoglobin = 4 subunits)

**Denaturation:** disruption of structure (heat, pH) → loss of function. Primary structure usually preserved; secondary/tertiary lost.

## Nucleic acids
- **DNA:** double helix, deoxyribose, A-T / G-C, antiparallel (5'→3' on one strand, 3'→5' on the other)
- **RNA:** single-stranded, ribose, A-U / G-C
- Phosphodiester bond joins nucleotides; sugar-phosphate backbone is on the outside, bases pair on the inside via H-bonds (A=T has 2 H-bonds, G≡C has 3)

---

# Unit 2 — Cell Structure & Function (10–13%)

## Organelles — function pairs to memorize

| Organelle | Function | Trick |
|---|---|---|
| Nucleus | DNA storage, transcription | — |
| Ribosome | Protein synthesis | Free = cytosolic proteins; rough ER = secreted/membrane proteins |
| Rough ER | Protein synthesis & folding | Has ribosomes |
| Smooth ER | Lipid synthesis, detox | No ribosomes |
| Golgi | Modify, sort, ship proteins | Cis face receives, trans face ships |
| Lysosome | Hydrolytic enzymes, digestion | Acidic interior |
| Mitochondria | ATP via cellular respiration | Double membrane, own DNA, cristae |
| Chloroplast | Photosynthesis | Double membrane (+thylakoid), own DNA, grana |
| Vacuole | Storage, turgor (plants) | — |
| Peroxisome | Break down fatty acids, H₂O₂ | — |

## Endosymbiotic theory (almost guaranteed FRQ topic)
**Mitochondria and chloroplasts evolved from prokaryotes engulfed by ancestral eukaryotes.**

Evidence:
1. **Double membrane** (outer = host, inner = original prokaryote)
2. **Own circular DNA** (prokaryote-like)
3. **Own ribosomes** (70S, prokaryote-like, not 80S like eukaryotes)
4. **Binary fission** (divide independently of cell)
5. Size similar to bacteria

## Membrane structure — fluid mosaic model
- **Phospholipid bilayer:** hydrophilic heads out, hydrophobic tails in
- **Embedded proteins:** integral (transmembrane) and peripheral
- **Cholesterol:** modulates fluidity (more fluid at low temp, less fluid at high temp)
- **Glycoproteins/glycolipids:** cell recognition

## Transport (HUGE topic)

| Type | Energy? | Mechanism | Example |
|---|---|---|---|
| Diffusion | No | Down gradient, through bilayer | O₂, CO₂, small nonpolar |
| Facilitated diffusion | No | Down gradient, via channel/carrier | Glucose, ions |
| Osmosis | No | Water down its gradient (via aquaporins) | Plant turgor |
| Active transport | **Yes (ATP)** | Up gradient, via pump | Na⁺/K⁺ pump |
| Endocytosis | Yes | Bring in via vesicle | Phagocytosis |
| Exocytosis | Yes | Send out via vesicle | Neurotransmitter release |

## Tonicity (always tested)
- **Hypertonic:** higher solute outside → cell **shrinks** (plasmolysis in plants)
- **Hypotonic:** lower solute outside → cell **swells / lyses** (turgid in plants — good)
- **Isotonic:** equal → no net movement

⚠️ **Water moves from low solute → high solute** (i.e., toward the hypertonic side).

## Surface area to volume ratio
As cells grow, **volume grows faster than surface area** → can't exchange materials fast enough → must divide or stay small. This is *why* cells are small and *why* organisms have folded structures (villi, alveoli, mitochondrial cristae, root hairs) — to maximize SA:V.

---

# Unit 3 — Cellular Energetics (12–16%)

## Enzymes (FRQ favorite)
- **Lower activation energy** without being consumed
- **Active site:** where substrate binds (induced fit model — site changes shape slightly when substrate binds)
- **Specificity:** each enzyme catalyzes one type of reaction
- **Optimal temperature/pH:** activity peaks then drops sharply (denaturation)

**Inhibition:**
- **Competitive:** binds active site directly. Overcome by adding more substrate. Vmax unchanged, Km increases.
- **Noncompetitive (allosteric):** binds elsewhere, changes shape of active site. Cannot be overcome by adding substrate. Vmax decreases.
- **Allosteric regulation** can also activate (cooperative binding, like O₂ to hemoglobin).
- **Feedback inhibition:** end product inhibits earlier enzyme in pathway (homeostasis).

## Thermodynamics
- **1st law:** energy is conserved (transformed, not destroyed)
- **2nd law:** entropy increases; some energy is always lost as heat
- **Exergonic:** ΔG < 0, spontaneous, releases energy (e.g., ATP hydrolysis)
- **Endergonic:** ΔG > 0, requires energy input (e.g., synthesis reactions)
- **Coupling:** cells couple endergonic reactions to ATP hydrolysis to drive them forward

## Photosynthesis
**Overall:** 6CO₂ + 6H₂O + light → C₆H₁₂O₆ + 6O₂

### Light reactions (thylakoid membrane)
- **Inputs:** H₂O, light, NADP⁺, ADP + Pi
- **Outputs:** O₂ (from splitting H₂O), NADPH, ATP
- **Photosystem II → ETC → Photosystem I → NADP⁺ reductase**
- **Chemiosmosis:** H⁺ pumped into thylakoid lumen; flow back out through ATP synthase makes ATP
- O₂ comes from H₂O, **not CO₂** (memorize this — common trap)

### Calvin cycle (stroma)
- **Inputs:** CO₂, NADPH, ATP
- **Outputs:** G3P (→ glucose), NADP⁺, ADP
- **3 phases:** carbon fixation (RuBisCO + CO₂ + RuBP), reduction (G3P formed), regeneration (RuBP)
- **3 turns** of the cycle = 1 G3P; **6 turns** = 1 glucose
- Light-independent BUT requires products of light reactions (NADPH, ATP)

### Adaptations
- **C4 plants** (corn, sugarcane): fix CO₂ into 4C compound first, separate spatially → reduce photorespiration in hot/dry climates
- **CAM plants** (cacti, succulents): open stomata at night, fix CO₂ then → separate temporally

## Cellular respiration
**Overall:** C₆H₁₂O₆ + 6O₂ → 6CO₂ + 6H₂O + ~32 ATP

### Steps

| Step | Location | Inputs | Outputs |
|---|---|---|---|
| **Glycolysis** | Cytoplasm | Glucose, 2 ATP, 2 NAD⁺ | 2 pyruvate, 4 ATP (net 2), 2 NADH |
| **Pyruvate oxidation** | Mitochondrial matrix | 2 pyruvate, 2 NAD⁺, 2 CoA | 2 acetyl-CoA, 2 NADH, 2 CO₂ |
| **Krebs cycle** | Matrix | 2 acetyl-CoA | 4 CO₂, 6 NADH, 2 FADH₂, 2 ATP |
| **ETC + chemiosmosis** | Inner mitochondrial membrane | NADH, FADH₂, O₂ | ~28 ATP, H₂O |

- **Final electron acceptor: O₂** → forms H₂O
- **NADH** delivers electrons to Complex I; **FADH₂** to Complex II (so NADH yields more ATP)
- **ATP synthase:** uses H⁺ gradient to make ATP from ADP + Pi (chemiosmosis)
- Without O₂ → ETC backs up → no NAD⁺ regeneration → glycolysis stops

### Fermentation (anaerobic)
- **Purpose:** regenerate NAD⁺ so glycolysis can continue
- **Lactic acid fermentation:** pyruvate → lactate (humans, muscle)
- **Alcohol fermentation:** pyruvate → ethanol + CO₂ (yeast)
- ATP yield: only 2 ATP per glucose

### Comparing photosynthesis & respiration
Both use **chemiosmosis** (H⁺ gradient → ATP synthase → ATP). Both have **electron transport chains**. They are essentially mirror processes — products of one = reactants of the other.

---

# Unit 4 — Cell Communication & Cell Cycle (10–15%)

## Cell signaling (3 stages)
1. **Reception:** signal molecule (ligand) binds receptor (cell surface or intracellular)
2. **Transduction:** signal relayed via phosphorylation cascade, often using **second messengers** (cAMP, Ca²⁺)
3. **Response:** gene expression change, enzyme activation, etc.

### Receptor types
- **G-protein coupled receptors (GPCRs):** activate G-protein → triggers cascade
- **Receptor tyrosine kinases (RTKs):** dimerize, autophosphorylate, activate multiple pathways
- **Ligand-gated ion channels:** open when ligand binds → ions flow
- **Intracellular receptors:** for steroid hormones (lipid-soluble, cross membrane); receptor-hormone complex acts as transcription factor

### Local vs long-distance
- **Direct contact:** plasmodesmata, gap junctions
- **Paracrine:** local cells (neurotransmitters, growth factors)
- **Autocrine:** signals self
- **Endocrine:** hormones, long-distance via bloodstream

## Feedback loops (very high yield)
- **Negative feedback:** output reduces the original stimulus → maintains **homeostasis**
  - Examples: blood glucose (insulin/glucagon), body temperature, blood pressure
- **Positive feedback:** output amplifies the stimulus → drives process to completion
  - Examples: childbirth (oxytocin), blood clotting, fruit ripening

## Cell cycle
**Phases:** G1 → S (DNA replication) → G2 → M (mitosis + cytokinesis)

### Checkpoints (regulated by cyclin-CDK complexes)
- **G1 checkpoint:** "Should I divide?" Most cells exit to G0 here. DNA damage check.
- **G2 checkpoint:** Is DNA fully replicated and undamaged?
- **M checkpoint (spindle):** Are all chromosomes attached to spindle?

⚠️ Mutations in checkpoint regulators (e.g., **p53**, "guardian of the genome") → uncontrolled division → cancer.

### Mitosis stages
**P-M-A-T** (Prophase, Metaphase, Anaphase, Telophase)
- **Prophase:** chromosomes condense, spindle forms, nuclear envelope breaks down
- **Metaphase:** chromosomes align at metaphase plate
- **Anaphase:** sister chromatids separate, pulled to opposite poles
- **Telophase:** chromosomes decondense, nuclear envelopes reform
- **Cytokinesis:** cytoplasm divides (cleavage furrow in animals, cell plate in plants)

Result: 2 identical diploid daughter cells.

---

# Unit 5 — Heredity (8–11%)

## Meiosis (compare to mitosis CONSTANTLY)

| Feature | Mitosis | Meiosis |
|---|---|---|
| Purpose | Growth, repair | Gamete production |
| Divisions | 1 | 2 |
| Daughter cells | 2 | 4 |
| Ploidy | 2n → 2n | 2n → n |
| Genetic identity | Identical to parent | Genetically unique |
| Synapsis/crossing over | No | Yes (Prophase I) |

### Sources of genetic variation in meiosis
1. **Crossing over** (Prophase I) — homologs exchange segments at chiasmata
2. **Independent assortment** (Metaphase I) — random orientation of homolog pairs (2ⁿ combinations)
3. **Random fertilization** — random sperm meets random egg

**Nondisjunction:** failure of homologs (Meiosis I) or sister chromatids (Meiosis II) to separate → aneuploidy (e.g., Trisomy 21 / Down syndrome).

## Mendelian genetics

### Laws
- **Law of segregation:** allele pairs separate during gamete formation (Anaphase I)
- **Law of independent assortment:** different gene pairs assort independently (only if on different chromosomes / far apart on same chromosome)

### Crosses
- Monohybrid Aa × Aa → 1:2:1 genotype, 3:1 phenotype
- Dihybrid AaBb × AaBb → 9:3:3:1 phenotype
- Test cross: cross unknown with homozygous recessive

### Non-Mendelian patterns
- **Incomplete dominance:** blended phenotype (red × white = pink)
- **Codominance:** both expressed (AB blood type, roan cattle)
- **Multiple alleles:** more than 2 alleles in population (ABO blood)
- **Polygenic:** multiple genes → continuous variation (height, skin color)
- **Pleiotropy:** one gene affects multiple traits (sickle cell)
- **Epistasis:** one gene masks another (coat color in mice)
- **Sex-linked:** gene on sex chromosome; X-linked recessive shows up more in males

### Pedigree clues
- **Autosomal recessive:** skips generations, both parents can be carriers
- **Autosomal dominant:** appears every generation, affected parent → ~50% affected
- **X-linked recessive:** mostly males, affected fathers can't pass to sons
- **X-linked dominant:** affected fathers pass to ALL daughters, no sons

### Linked genes
Genes on the same chromosome don't assort independently. Closer = more linked. Recombination frequency = % of recombinant offspring = map distance (cM).

## Environment and gene expression
Phenotype = genotype + environment. Examples: hydrangea color (soil pH), Himalayan rabbit fur (temperature), height (nutrition). Identical twins are genetically identical but have different phenotypes due to environment.

---

# Unit 6 — Gene Expression & Regulation (12–16%)

## DNA structure recap
- Double helix, antiparallel, sugar-phosphate backbone, A-T (2 H-bonds), G-C (3 H-bonds)
- 5' phosphate end, 3' hydroxyl end
- DNA replication is **semiconservative** (Meselson-Stahl): each daughter molecule has 1 old strand + 1 new strand

## DNA replication

| Enzyme | Role |
|---|---|
| **Helicase** | Unwinds DNA at replication fork |
| **Topoisomerase** | Relieves supercoiling ahead of fork |
| **Single-strand binding proteins** | Stabilize unwound DNA |
| **Primase** | Lays down RNA primer |
| **DNA polymerase III** | Adds nucleotides 5'→3' |
| **DNA polymerase I** | Replaces primers with DNA |
| **Ligase** | Joins Okazaki fragments |

- **Leading strand:** synthesized continuously toward fork
- **Lagging strand:** synthesized in **Okazaki fragments** away from fork (because polymerase only goes 5'→3')

## Transcription (DNA → mRNA, in nucleus)
1. **Initiation:** RNA polymerase binds **promoter** (TATA box in eukaryotes)
2. **Elongation:** RNA polymerase reads 3'→5' on template, builds mRNA 5'→3'
3. **Termination:** RNA polymerase releases at terminator

### Eukaryotic mRNA processing
- **5' cap** (modified G) — protects mRNA, ribosome binding
- **Poly-A tail** — protects from degradation
- **Splicing:** introns removed, exons joined by **spliceosome**
- **Alternative splicing:** different exon combinations → different proteins from one gene (one gene can code multiple proteins!)

## Translation (mRNA → protein, at ribosome)
- **Codon:** 3 mRNA nucleotides = 1 amino acid
- **Genetic code:** redundant (multiple codons per AA), nearly universal, non-overlapping
- **Start codon:** AUG (Methionine)
- **Stop codons:** UAA, UAG, UGA

### Process
1. **Initiation:** small ribosomal subunit binds mRNA at start codon, tRNA-Met binds, large subunit joins
2. **Elongation:** tRNAs deliver amino acids to A site; peptide bond forms; ribosome translocates; tRNA exits at E site
3. **Termination:** stop codon → release factor → polypeptide released

## Regulation of gene expression

### Prokaryotes — operons
**Lac operon (inducible):**
- Default: OFF (repressor bound to operator)
- Lactose present → binds repressor → repressor falls off → genes ON
- "Inducible" = turn ON in presence of substrate

**Trp operon (repressible):**
- Default: ON
- Tryptophan present → binds repressor → repressor binds operator → genes OFF
- "Repressible" = turn OFF in presence of product (negative feedback!)

### Eukaryotes — multiple levels
1. **Chromatin modification:** DNA methylation (silences), histone acetylation (activates)
2. **Transcription factors** bind promoters/enhancers
3. **RNA processing** (alternative splicing)
4. **mRNA degradation** (microRNAs)
5. **Translation regulation**
6. **Post-translational modification** (phosphorylation, etc.)

**Epigenetics:** heritable changes in gene expression without DNA sequence changes (methylation patterns).

## Mutations
- **Point mutations:**
  - **Silent:** no AA change (redundancy)
  - **Missense:** different AA
  - **Nonsense:** premature stop codon (usually severe)
- **Frameshift** (insertion/deletion of non-multiples of 3): shifts reading frame, usually catastrophic
- Mutations in gametes are heritable; somatic mutations are not

## Biotechnology
- **PCR:** amplify DNA. Steps: denature (94°C) → anneal primers (~55°C) → extend (72°C, Taq polymerase). Doubles each cycle (2ⁿ).
- **Gel electrophoresis:** separates DNA by size. **Smaller fragments travel farther.** DNA is negatively charged (phosphates) → moves to + electrode.
- **Restriction enzymes:** cut DNA at specific sequences.
- **Plasmids:** small circular DNA used as vectors in recombinant DNA.
- **CRISPR-Cas9:** targeted gene editing using guide RNA.
- **DNA sequencing:** determines order of nucleotides.

---

# Unit 7 — Natural Selection (13–20%)

This is the LARGEST unit. Master it.

## Natural selection — the 4 conditions
1. **Variation** in heritable traits exists
2. **Overproduction** of offspring (more than environment can support)
3. **Differential reproductive success** based on fitness
4. **Heritability** — traits passed to offspring

→ Over generations, allele frequencies change → **evolution**.

⚠️ Individuals don't evolve — **populations** evolve.
⚠️ Fitness = reproductive success, not strength or longevity.

## Types of selection
- **Directional:** one extreme favored (peppered moths, antibiotic resistance)
- **Stabilizing:** mean favored, extremes selected against (human birth weight)
- **Disruptive:** both extremes favored, mean against (can lead to speciation)
- **Sexual selection:** traits favored for mating success (peacock tail) — can produce sexual dimorphism

## Evidence for evolution
1. **Fossil record** — transitional fossils (Tiktaalik, Archaeopteryx)
2. **Biogeography** — similar environments, different species (Galapagos finches)
3. **Comparative anatomy:**
   - **Homologous structures:** same origin, different function (whale fin, human arm) — common ancestry
   - **Analogous structures:** same function, different origin (bird wing, insect wing) — convergent evolution
   - **Vestigial structures:** reduced/non-functional remains (whale pelvis, human appendix)
4. **Embryology** — similar embryonic development in vertebrates
5. **Molecular evidence:**
   - DNA/protein sequences (cytochrome c, ribosomal RNA)
   - More similar sequences = more recent common ancestor
   - **Universal genetic code** = single origin of life
6. **Direct observation** — antibiotic resistance, Galapagos finch beak changes (Grants' research)

## Hardy-Weinberg (revisit — essential)

**Equations:**
$$p + q = 1 \qquad p^2 + 2pq + q^2 = 1$$

**Conditions for HWE (no evolution occurring):**
1. Large population (no genetic drift)
2. No migration (no gene flow)
3. No mutation
4. Random mating
5. No natural selection

**If any condition is violated → population is evolving.**

### Mechanisms of evolution
- **Natural selection:** non-random, increases fitness
- **Genetic drift:** random changes; major in small populations
  - **Bottleneck effect:** disaster reduces population (cheetahs)
  - **Founder effect:** small group establishes new population (Amish)
- **Gene flow:** migration moves alleles between populations
- **Mutation:** ultimate source of new alleles (rare per gene, but common across genome)
- **Non-random mating:** doesn't change allele frequencies, but changes genotype frequencies

## Speciation
- **Biological species concept:** group that can interbreed and produce fertile offspring
- **Reproductive isolation** drives speciation
  - **Prezygotic:** habitat, temporal, behavioral, mechanical, gametic
  - **Postzygotic:** hybrid inviability, sterility (mule), breakdown
- **Allopatric:** geographic isolation → speciation (Grand Canyon squirrels)
- **Sympatric:** same area, but reproductively isolated (polyploidy in plants is the textbook example)
- **Adaptive radiation:** rapid speciation from a common ancestor exploiting different niches (Galapagos finches, Hawaiian honeycreepers)

## Phylogeny
- **Cladogram/phylogenetic tree:** depicts evolutionary relationships
- **Node** = common ancestor; **branch** = lineage
- **Sister taxa:** share most recent common ancestor
- **Monophyletic group (clade):** ancestor + ALL descendants
- **Paraphyletic:** ancestor + SOME descendants (excludes some)
- **Polyphyletic:** no common ancestor (artificial grouping)

⚠️ **Reading trees:** rotation around a node doesn't change relationships. Two species are equally related if they share the same most recent common ancestor (no matter how the tree is drawn).

**Molecular clocks:** mutation rate ~constant → use sequence differences to estimate divergence time.

## Origin of life
- **Earth:** ~4.6 bya, life ~3.5–3.8 bya
- **Miller-Urey:** showed organic molecules could form from inorganic precursors under early Earth conditions
- **RNA world hypothesis:** RNA was first genetic material — can store info AND catalyze reactions (ribozymes)
- **Order of events:** organic molecules → polymers → protocells (lipid vesicles) → self-replicating systems → cells
- **Endosymbiosis** (Unit 2) explains origin of mitochondria/chloroplasts

## Extinction & rates
- **Background extinction:** continuous, low rate
- **Mass extinctions:** 5 major events (Permian was largest; K-T ended dinosaurs)
- We may be in 6th mass extinction (anthropogenic)

---

# Unit 8 — Ecology (10–15%)

## Levels of organization
Organism → Population → Community → Ecosystem → Biosphere

## Energy flow

### Trophic levels
- **Producers (autotrophs):** make own food (plants, algae, cyanobacteria)
- **Primary consumers:** herbivores
- **Secondary consumers:** eat herbivores
- **Tertiary consumers:** eat secondary consumers
- **Decomposers:** break down dead matter (fungi, bacteria)

### 10% rule
Only ~10% of energy transfers between trophic levels. Rest is lost as **heat** (2nd law of thermodynamics) or used in metabolism. This is why food chains rarely exceed 4–5 trophic levels.

### Productivity
- **Gross primary productivity (GPP):** total energy fixed by producers
- **Net primary productivity (NPP):** GPP − respiration = energy available to consumers

## Biogeochemical cycles

### Carbon cycle
- **Reservoirs:** atmosphere (CO₂), oceans (HCO₃⁻), biosphere, fossil fuels, sediments
- **Movement:** photosynthesis (atmosphere → biosphere), respiration & combustion (biosphere/fossil → atmosphere)
- Burning fossil fuels → ↑ atmospheric CO₂ → climate change

### Nitrogen cycle
- N₂ is unusable by most organisms — must be **fixed**
- **Nitrogen fixation:** N₂ → NH₃ by **Rhizobium** bacteria (in legume roots) and lightning
- **Nitrification:** NH₃ → NO₂⁻ → NO₃⁻
- **Assimilation:** plants take up NO₃⁻
- **Denitrification:** NO₃⁻ → N₂ (back to atmosphere)
- Often the **limiting nutrient** in terrestrial ecosystems

### Phosphorus cycle
- No atmospheric component (no gas phase)
- Reservoirs: rocks, soil, water
- Released by weathering; cycles slowly
- Often **limiting nutrient** in aquatic ecosystems
- Excess (fertilizer runoff) → **eutrophication** → algal bloom → O₂ depletion → dead zones

### Water cycle
Evaporation, transpiration, condensation, precipitation. Only cycle without major biological role (mostly physical).

## Population ecology

### Growth models
**Exponential growth:** dN/dt = rN — unlimited resources, J-shaped curve
**Logistic growth:** dN/dt = rN((K−N)/K) — limited by carrying capacity (K), S-shaped curve

- **r:** intrinsic rate of increase
- **K:** carrying capacity (max population environment can support)

### r vs K selected species

| Trait | r-selected | K-selected |
|---|---|---|
| Body size | Small | Large |
| Lifespan | Short | Long |
| Offspring | Many | Few |
| Parental care | Little | Lots |
| Examples | Insects, weeds | Elephants, humans |

### Density-dependent vs density-independent factors
- **Density-dependent:** intensify with population density (disease, competition, predation)
- **Density-independent:** affect regardless of density (weather, natural disasters)

## Community ecology

### Species interactions

| Interaction | Species A | Species B |
|---|---|---|
| Mutualism | + | + |
| Commensalism | + | 0 |
| Parasitism | + | − |
| Predation | + | − |
| Competition | − | − |

- **Competitive exclusion:** two species with identical niches can't coexist
- **Resource partitioning:** species evolve to use different resources to coexist
- **Keystone species:** disproportionate effect on community (sea otters → kelp forests)
- **Ecosystem engineers:** modify habitat (beavers)

### Succession
- **Primary:** starts on bare rock (lichens first)
- **Secondary:** after disturbance, soil remains (forest fire recovery)

## Ecosystem disruption
- **Invasive species:** outcompete natives (zebra mussels, kudzu)
- **Habitat fragmentation:** reduces population size, gene flow
- **Climate change:** shifts ranges, alters phenology, ocean acidification
- **Eutrophication:** nutrient pollution → algal bloom → hypoxic zones

## Behavior
- **Innate vs learned behaviors**
- **Fixed action patterns:** triggered by sign stimulus
- **Imprinting:** critical period learning (Lorenz's geese)
- **Communication:** visual, chemical (pheromones), auditory, tactile
- **Altruism:** helping behavior; explained by **inclusive fitness** / **kin selection** (Hamilton's rule: rB > C)

---

# High-yield experiments to know

These come up in stimuli all the time. Know what each demonstrated.

| Experiment | What it showed |
|---|---|
| **Griffith** | Transformation — something heritable transferred between bacteria |
| **Avery, MacLeod, McCarty** | DNA is the transforming principle (not protein) |
| **Hershey-Chase** | Confirmed DNA, not protein, is genetic material (using radioactive S and P) |
| **Meselson-Stahl** | DNA replication is semiconservative |
| **Miller-Urey** | Organic molecules can form from inorganic precursors |
| **Lederberg replica plating** | Mutations are random, not directed by environment |
| **Calvin** | Calvin cycle — used radioactive ¹⁴C to trace path of carbon |
| **Engelmann** | Action spectrum of photosynthesis (red and blue light most effective) |

---

# FRQ-specific tactics

## Q1 & Q2 (long FRQs) — point distribution
- Identify variables (1 pt)
- Justify control (1 pt)
- Predict result (1 pt with reasoning)
- Calculate something — rate, mean, percent change (1 pt)
- Justify with data (1 pt — must reference numbers)
- Connect to concept (1 pt)
- Propose follow-up experiment (1 pt)

**Tip:** Start by writing down the IV, DV, and control before answering anything.

## Q3 (Scientific Investigation) — 4 pts
Always asks for: hypothesis, experimental design, predicted result, justification. Use the 6-element checklist (page top).

## Q4 (Conceptual Analysis) — 4 pts
Pure content knowledge. Each part = ~1 pt. Be **specific** — name the molecule, organelle, mechanism.

## Q5 (Model/Visual) — 4 pts
Often a diagram (signaling pathway, phylogenetic tree, food web). Identify a part, predict effect of change, connect to bigger concept.

## Q6 (Data) — 4 pts
Calculate something, describe trend, draw conclusion with justification.

## Graphing rules (Q2)
- **Title** the graph
- **Label both axes** with units
- **IV on x-axis, DV on y-axis**
- **Appropriate scale** (use the space; don't bunch up)
- **Plot data accurately**
- **Add error bars** if SEM/CI given
- **Line of best fit** if continuous data; **bar graph** if categorical
- **Legend** if multiple data series

## Phrases that earn points
- "The data supports/does not support the hypothesis because [specific number] vs [specific number]…"
- "This is an example of negative feedback because the response reduces the original stimulus."
- "Error bars overlap, so the difference is not statistically significant."
- "If the null hypothesis is correct, we would expect…"
- "This change would [increase/decrease] fitness because…"
- "Allele frequencies would change over generations because…"

## Phrases to NEVER say
- "Survival of the fittest" (vague)
- "Organism adapted to" (sounds Lamarckian — say "evolved" or "was selected for")
- "Natural selection chose…" (no agency — selection happens, doesn't choose)
- "Theory is just a guess" (don't undermine evolution)
- "Accept the null" (fail to reject)

---

# 24 hours before — final habits

1. **Sleep 7+ hours.** Consolidation > 2 extra hours of cramming.
2. **Eat protein + complex carbs in the morning.** Don't skip breakfast.
3. **Bring:** ID, admission ticket, 2 #2 pencils, blue/black pens, approved calculator, watch (no smartwatch).
4. **Pace yourself:** ~1.5 min/MCQ. ~15 min for long FRQs (Q1, Q2). ~6 min for short FRQs (Q3–6).
5. **Skip and return.** Don't burn 5 minutes on one MCQ — flag it, move on.
6. **Read every FRQ TWICE before writing.** Underline the verb (identify, justify, predict, explain).
7. **Show calculations.** Even if wrong setup, partial credit for showing work.
8. **Answer every question.** No guessing penalty.

---

# The "if you only memorize these" list

If you've got 30 minutes left:
1. The 4 macromolecules + monomers + bonds
2. Stages of cellular respiration: locations, inputs, outputs
3. Photosynthesis: light reactions vs Calvin cycle
4. Endosymbiotic theory + 4 evidence points
5. Cell signaling: reception → transduction → response
6. Negative vs positive feedback (with examples)
7. Mitosis vs meiosis comparison
8. Hardy-Weinberg conditions (5) and equations
9. Chi-square procedure + interpretation
10. Natural selection's 4 conditions
11. Types of selection (directional, stabilizing, disruptive)
12. Reading phylogenetic trees
13. Carbon and nitrogen cycle key steps
14. r vs K selection
15. Lac vs trp operon

---

You've got this. Trust your prep, write specifically, cite the data, and keep moving on the test.
