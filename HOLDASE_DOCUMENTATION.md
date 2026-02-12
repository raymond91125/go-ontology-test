# Holdase Activity and Associated Biological Processes

## What is a Holdase?

Holdases are a functional class of molecular chaperones that prevent protein aggregation by binding to unfolded or partially folded proteins. Unlike foldases (such as GroEL/GroES or Hsp60), holdases do not actively promote or catalyze protein folding. Instead, they maintain proteins in a soluble, folding-competent state until conditions are favorable for refolding or until foldase chaperones become available.

## New GO Term

**GO:7770013 - protein holdase activity**

**Definition:** Binding to unfolded or partially folded proteins to prevent their aggregation and maintain them in a soluble, folding-competent state, without actively promoting the folding process.

**Key Characteristics:**
- Bind to exposed hydrophobic regions of unfolded proteins
- Prevent protein aggregation
- Do not actively promote folding (distinguishes them from foldases)
- Often ATP-independent
- Work in conjunction with ATP-dependent foldases

**Examples of Holdases:**
- Small heat shock proteins (sHsps) - e.g., Hsp26, Hsp42, αB-crystallin
- Some Hsp40/DnaJ family members (in holding mode)
- Some Hsp70/DnaK family members (when not actively folding)
- Trigger factor (TF) in bacteria

## Biological Processes Involving Holdases

### 1. Protein Quality Control (GO:0006515)

Holdases play a critical role in protein quality control by preventing the aggregation of misfolded proteins. They bind to proteins that have lost their native structure and keep them soluble until they can be either refolded by foldase chaperones or degraded by the proteasome.

**References:**
- PMID:8702519 - Buchner J. (1996) "Supervising the fold: functional principles of molecular chaperones"
- PMID:15142878 - Hartl FU, Hayer-Hartl M. (2002) "Molecular chaperones in the cytosol: from nascent chain to folded protein"
- PMID:20560768 - Balchin D, Hayer-Hartl M, Hartl FU. (2016) "In vivo aspects of protein folding and quality control"

### 2. Heat Shock and Stress Response (GO:0009408)

During heat shock and other cellular stress conditions, proteins denature and unfold. Holdases, particularly small heat shock proteins (sHsps), are upregulated and bind to these unfolded proteins to prevent irreversible aggregation. They act as a first line of defense, holding proteins until the stress is relieved and ATP-dependent foldases can refold them.

**Key Process:** Holdases prevent formation of toxic aggregates during stress

**References:**
- PMID:10330348 - Jakob U, Gaestel M, Engel K, Buchner J. (1993) "Small heat shock proteins are molecular chaperones"
- PMID:16336047 - Haslbeck M, Franzmann T, Weinfurtner D, Buchner J. (2005) "Some like it hot: the structure and function of small heat-shock proteins"
- PMID:19369943 - Basha E, O'Neill H, Vierling E. (2012) "Small heat shock proteins and α-crystallins: dynamic proteins with flexible functions"

### 3. Protein Refolding (GO:0042026)

Holdases are essential for protein refolding after stress or misfolding events. They maintain proteins in a folding-competent state and transfer them to ATP-dependent foldases (like Hsp70, Hsp90, or chaperonins) that actively promote refolding.

**Mechanism:** Holdase → Transfer → Foldase → Native protein

**References:**
- PMID:11283351 - Lee GJ, Roseman AM, Saibil HR, Vierling E. (1997) "A small heat shock protein cooperates with heat shock protein 70 systems to reactivate a heat-denatured protein"
- PMID:15632085 - Mogk A, Bukau B. (2004) "Molecular chaperones: structure of a protein disaggregase"

### 4. Protein Transport and Translocation (GO:0006886)

Holdases maintain proteins in an unfolded state during transport across membranes (e.g., into mitochondria, endoplasmic reticulum, or across bacterial membranes). They prevent premature folding or aggregation that would prevent translocation.

**Examples:**
- SecB in bacteria - holds preproteins for SecA-dependent translocation
- Hsp70 during mitochondrial import
- TOM/TIM complex-associated chaperones

**References:**
- PMID:8262938 - Hartl FU, Hlodan R, Langer T. (1994) "Molecular chaperones in protein folding: the art of avoiding sticky situations"
- PMID:12665801 - Young JC, Agashe VR, Siegers K, Hartl FU. (2004) "Pathways of chaperone-mediated protein folding in the cytosol"

### 5. Protein Degradation Pathways (GO:0006515)

Holdases can maintain misfolded proteins in a soluble state while they are being targeted for degradation by the ubiquitin-proteasome system or autophagy. This prevents formation of toxic aggregates and facilitates efficient degradation.

**Process:** Recognition of irreversibly damaged proteins → Holdase binding → Ubiquitination → Proteasomal degradation

**References:**
- PMID:19520858 - Vembar SS, Brodsky JL. (2008) "One step at a time: endoplasmic reticulum-associated degradation"
- PMID:21483721 - Kettern N, Dreiseidler M, Tawo R, Höhfeld J. (2010) "Chaperone-assisted degradation: multiple paths to destruction"

### 6. Prevention of Protein Aggregation (Related to GO:0140455)

Holdases are key players in preventing the formation of toxic protein aggregates that are associated with neurodegenerative diseases (Alzheimer's, Parkinson's, Huntington's) and other protein misfolding disorders.

**Disease Relevance:**
- αB-crystallin prevents aggregation in the eye lens
- sHsps prevent aggregation of polyglutamine proteins
- Hsp70 prevents aggregation in various neurodegenerative diseases

**References:**
- PMID:17229683 - Horwitz J. (1992) "Alpha-crystallin can function as a molecular chaperone"
- PMID:19570034 - Muchowski PJ, Wacker JL. (2005) "Modulation of neurodegeneration by molecular chaperones"
- PMID:22020285 - Nillegoda NB, Bukau B. (2015) "Metazoan Hsp70-based protein disaggregases: emergence and mechanisms"

### 7. Cotranslational Protein Folding (GO:0006457)

Some holdases, like Trigger Factor (TF) in bacteria, bind to nascent polypeptide chains as they emerge from the ribosome, preventing premature folding or aggregation until the full polypeptide is synthesized.

**References:**
- PMID:10984529 - Deuerling E, Schulze-Specking A, Tomoyasu T, Mogk A, Bukau B. (1999) "Trigger factor and DnaK cooperate in folding of newly synthesized proteins"
- PMID:15766572 - Hoffmann A, Bukau B, Kramer G. (2010) "Structure and function of the molecular chaperone Trigger Factor"

### 8. Protein Maturation (GO:0051604)

Holdases contribute to protein maturation by maintaining newly synthesized or translocated proteins in appropriate states until post-translational modifications, cofactor binding, or assembly into complexes can occur.

## Summary Table

| Biological Process | Role of Holdase | Key Examples |
|-------------------|-----------------|--------------|
| Protein Quality Control | Prevent aggregation of misfolded proteins | sHsps, Hsp70 |
| Heat Shock Response | First-line defense against stress-induced unfolding | Hsp26, Hsp42, αB-crystallin |
| Protein Refolding | Maintain refoldable state for foldases | sHsps with Hsp70/Hsp104 |
| Protein Transport | Keep proteins unfolded during translocation | SecB, Hsp70 |
| Protein Degradation | Hold proteins for degradation machinery | Hsp70, CHIP |
| Aggregate Prevention | Prevent toxic aggregate formation | αB-crystallin, Hsp27 |
| Cotranslational Folding | Prevent premature folding of nascent chains | Trigger Factor, NAC |
| Protein Maturation | Maintain appropriate folding states | Various holdases |

## Distinction from Other Chaperone Activities

### Holdases vs. Foldases

- **Holdases**: Bind and hold unfolded proteins, ATP-independent (usually), prevent aggregation only
- **Foldases**: Actively promote folding, ATP-dependent (usually), catalyze conformational changes

### Holdases vs. Unfoldases/Disaggregases

- **Holdases**: Prevent aggregation of already unfolded proteins
- **Unfoldases/Disaggregases**: Break apart existing aggregates or unfold misfolded proteins (e.g., Hsp104/ClpB, Hsp70 with Hsp40)

## Relationship to Existing GO Terms

The new holdase term (GO:7770013) is related to but distinct from:
- **GO:0044183** (protein folding chaperone) - broader term that includes both holdases and foldases
- **GO:0051082** (unfolded protein binding) - molecular function that is part of holdase activity
- **GO:0006457** (protein folding) - biological process that holdases contribute to
- **GO:0051787** (misfolded protein binding) - related binding activity
- **GO:0042026** (protein refolding) - biological process involving holdases

## References

Key review articles on holdases and chaperone function:

1. **PMID:8702519** - Buchner J. Supervising the fold: functional principles of molecular chaperones. FASEB J. 1996
2. **PMID:15142878** - Hartl FU, Hayer-Hartl M. Molecular chaperones in the cytosol: from nascent chain to folded protein. Science. 2002
3. **PMID:20560768** - Balchin D, Hayer-Hartl M, Hartl FU. In vivo aspects of protein folding and quality control. Science. 2016
4. **PMID:16336047** - Haslbeck M, Franzmann T, Weinfurtner D, Buchner J. Some like it hot: the structure and function of small heat-shock proteins. Nat Struct Mol Biol. 2005
5. **PMID:19369943** - Basha E, O'Neill H, Vierling E. Small heat shock proteins and α-crystallins: dynamic proteins with flexible functions. Trends Biochem Sci. 2012

---

*Documentation created by @dragon-ai-agent for GO ontology issue regarding holdase activity*
*Date: 2026-02-12*
